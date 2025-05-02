# HttpWebRequest

**Namespace:** `System.Net`


## Fields

- `Uri requestUri`

- `Uri actualUri`

- `Boolean hostChanged`

- `Boolean allowAutoRedirect`

- `Boolean allowBuffering`

- `X509CertificateCollection certificates`

- `String connectionGroup`

- `Boolean haveContentLength`

- `Int64 contentLength`

- `HttpContinueDelegate continueDelegate`

- `CookieContainer cookieContainer`

- `ICredentials credentials`

- `Boolean haveResponse`

- `Boolean requestSent`

- `WebHeaderCollection webHeaders`

- `Boolean keepAlive`

- `Int32 maxAutoRedirect`

- `String mediaType`

- `String method`

- `String initialMethod`

- `Boolean pipelined`

- `Boolean preAuthenticate`

- `Boolean usedPreAuth`

- `Version version`

- `Boolean force_version`

- `Version actualVersion`

- `IWebProxy proxy`

- `Boolean sendChunked`

- `ServicePoint servicePoint`

- `Int32 timeout`

- `Int32 continueTimeout`

- `WebRequestStream writeStream`

- `HttpWebResponse webResponse`

- `WebCompletionSource responseTask`

- `WebOperation currentOperation`

- `Int32 aborted`

- `Boolean gotRequestStream`

- `Int32 redirects`

- `Boolean expectContinue`

- `Boolean getResponseCalled`

- `Object locker`

- `Boolean finished_reading`

- `DecompressionMethods auto_decomp`

- `Int32 readWriteTimeout`

- `MobileTlsProvider tlsProvider`

- `MonoTlsSettings tlsSettings`

- `ServerCertValidationCallback certValidationCallback`

- `Boolean hostHasPort`

- `Uri hostUri`

- `AuthorizationState auth_state`

- `AuthorizationState proxy_auth_state`

- `Boolean <ThrowOnError>k__BackingField`

- `Boolean unsafe_auth_blah`


## Properties

- `String Accept`

- `Uri Address`

- `DecompressionMethods AutomaticDecompression`

- `Boolean MethodWithBuffer`

- `X509CertificateCollection ClientCertificates`

- `String Connection`

- `String Expect`

- `String Host`

- `Boolean KeepAlive`

- `Int32 ReadWriteTimeout`

- `Version ProtocolVersion`

- `String Referer`

- `Boolean SendChunked`

- `ServicePoint ServicePoint`

- `String TransferEncoding`

- `String UserAgent`

- `Boolean UnsafeAuthenticatedConnectionSharing`

- `RemoteCertificateValidationCallback ServerCertificateValidationCallback`


## Methods

- `Void ResetAuthorization()`

- `Void SetSpecialHeaders(String, String)`

- `Void set_Accept(String)`

- `Uri get_Address()`

- `DecompressionMethods get_AutomaticDecompression()`

- `Boolean get_MethodWithBuffer()`

- `X509CertificateCollection get_ClientCertificates()`

- `Void set_Connection(String)`

- `Void set_Expect(String)`

- `String get_Host()`

- `Void set_Host(String)`

- `Boolean TryGetHostUri(String, out)`

- `Boolean get_KeepAlive()`

- `Int32 get_ReadWriteTimeout()`

- `Version get_ProtocolVersion()`

- `Void set_Referer(String)`

- `Boolean get_SendChunked()`

- `ServicePoint get_ServicePoint()`

- `String get_TransferEncoding()`

- `Void set_UserAgent(String)`

- `Boolean get_UnsafeAuthenticatedConnectionSharing()`

- `RemoteCertificateValidationCallback get_ServerCertificateValidationCallback()`

- `WebOperation SendRequest(Boolean, BufferOffsetSize, CancellationToken)`

- `WebException GetWebException(Exception)`

- `Void CheckRequestStarted()`

- `Void RewriteRedirectToGet()`

- `Boolean Redirect(HttpStatusCode, WebResponse)`

- `String GetHeaders()`

- `Void DoPreAuthenticate()`

- `Boolean CheckAuthorization(WebResponse, HttpStatusCode)`

- `Boolean <RunWithTimeout>b__242_0()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class HttpWebRequest : WebRequest, ISerializable
{
	private Uri requestUri; // 0x38
	private Uri actualUri; // 0x40
	private Boolean hostChanged; // 0x48
	private Boolean allowAutoRedirect; // 0x49
	private Boolean allowBuffering; // 0x4a
	private X509CertificateCollection certificates; // 0x50
	private String connectionGroup; // 0x58
	private Boolean haveContentLength; // 0x60
	private Int64 contentLength; // 0x68
	private HttpContinueDelegate continueDelegate; // 0x70
	private CookieContainer cookieContainer; // 0x78
	private ICredentials credentials; // 0x80
	private Boolean haveResponse; // 0x88
	private Boolean requestSent; // 0x89
	private WebHeaderCollection webHeaders; // 0x90
	private Boolean keepAlive; // 0x98
	private Int32 maxAutoRedirect; // 0x9c
	private String mediaType; // 0xa0
	private String method; // 0xa8
	private String initialMethod; // 0xb0
	private Boolean pipelined; // 0xb8
	private Boolean preAuthenticate; // 0xb9
	private Boolean usedPreAuth; // 0xba
	private Version version; // 0xc0
	private Boolean force_version; // 0xc8
	private Version actualVersion; // 0xd0
	private IWebProxy proxy; // 0xd8
	private Boolean sendChunked; // 0xe0
	private ServicePoint servicePoint; // 0xe8
	private Int32 timeout; // 0xf0
	private Int32 continueTimeout; // 0xf4
	private WebRequestStream writeStream; // 0xf8
	private HttpWebResponse webResponse; // 0x100
	private WebCompletionSource responseTask; // 0x108
	private WebOperation currentOperation; // 0x110
	private Int32 aborted; // 0x118
	private Boolean gotRequestStream; // 0x11c
	private Int32 redirects; // 0x120
	private Boolean expectContinue; // 0x124
	private Boolean getResponseCalled; // 0x125
	private Object locker; // 0x128
	private Boolean finished_reading; // 0x130
	private DecompressionMethods auto_decomp; // 0x134
	private static Int32 defaultMaxResponseHeadersLength; // 0x0
	private static Int32 defaultMaximumErrorResponseLength; // 0x4
	private static RequestCachePolicy defaultCachePolicy; // 0x8
	private Int32 readWriteTimeout; // 0x138
	private MobileTlsProvider tlsProvider; // 0x140
	private MonoTlsSettings tlsSettings; // 0x148
	private ServerCertValidationCallback certValidationCallback; // 0x150
	private Boolean hostHasPort; // 0x158
	private Uri hostUri; // 0x160
	private AuthorizationState auth_state; // 0x168
	private AuthorizationState proxy_auth_state; // 0x178
	internal Func`2 ResendContentFactory; // 0x188
	private Boolean <ThrowOnError>k__BackingField; // 0x190
	private Boolean unsafe_auth_blah; // 0x191

	public String Accept { set; }
	public Uri Address { get; }
	public virtual Boolean AllowWriteStreamBuffering { get; }
	public DecompressionMethods AutomaticDecompression { get; }
	internal Boolean InternalAllowBuffering { get; }
	private Boolean MethodWithBuffer { get; }
	internal MobileTlsProvider TlsProvider { get; }
	internal MonoTlsSettings TlsSettings { get; }
	public X509CertificateCollection ClientCertificates { get; }
	public String Connection { set; }
	public override Int64 ContentLength { get; set; }
	internal Int64 InternalContentLength { set; }
	internal Boolean ThrowOnError { get; set; }
	public override String ContentType { get; set; }
	public override ICredentials Credentials { get; set; }
	public static Int32 DefaultMaximumErrorResponseLength { get; }
	public String Expect { set; }
	public override WebHeaderCollection Headers { get; set; }
	public String Host { get; set; }
	public Boolean KeepAlive { get; }
	public Int32 ReadWriteTimeout { get; }
	public override String Method { get; set; }
	public Version ProtocolVersion { get; }
	public override IWebProxy Proxy { get; set; }
	public String Referer { set; }
	public override Uri RequestUri { get; }
	public Boolean SendChunked { get; }
	public ServicePoint ServicePoint { get; }
	internal ServicePoint ServicePointNoLock { get; }
	public override Int32 Timeout { get; }
	public String TransferEncoding { get; }
	public override Boolean UseDefaultCredentials { get; }
	public String UserAgent { set; }
	public Boolean UnsafeAuthenticatedConnectionSharing { get; }
	internal Boolean ExpectContinue { get; set; }
	internal Uri AuthUri { get; }
	internal Boolean ProxyQuery { get; }
	internal ServerCertValidationCallback ServerCertValidationCallback { get; }
	public RemoteCertificateValidationCallback ServerCertificateValidationCallback { get; }
	internal Boolean FinishedReading { set; }
	internal Boolean Aborted { get; }

	// RVA: 0x63270d8 VA: 0x759893f0d8
	private static Void .cctor() { }
	// RVA: 0x6326ec4 VA: 0x759893eec4
	public Void .ctor(Uri uri) { }
	// RVA: 0x63271dc VA: 0x759893f1dc
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x6327168 VA: 0x759893f168
	private Void ResetAuthorization() { }
	// RVA: 0x6327384 VA: 0x759893f384
	private Void SetSpecialHeaders(String HeaderName, String value) { }
	// RVA: 0x6327444 VA: 0x759893f444
	public Void set_Accept(String value) { }
	// RVA: 0x6327504 VA: 0x759893f504
	public Uri get_Address() { }
	// RVA: 0x632750c VA: 0x759893f50c
	public virtual Boolean get_AllowWriteStreamBuffering() { }
	// RVA: 0x6327514 VA: 0x759893f514
	public DecompressionMethods get_AutomaticDecompression() { }
	// RVA: 0x632751c VA: 0x759893f51c
	internal Boolean get_InternalAllowBuffering() { }
	// RVA: 0x6327530 VA: 0x759893f530
	private Boolean get_MethodWithBuffer() { }
	// RVA: 0x632762c VA: 0x759893f62c
	internal MobileTlsProvider get_TlsProvider() { }
	// RVA: 0x6327634 VA: 0x759893f634
	internal MonoTlsSettings get_TlsSettings() { }
	// RVA: 0x632763c VA: 0x759893f63c
	public X509CertificateCollection get_ClientCertificates() { }
	// RVA: 0x63276b4 VA: 0x759893f6b4
	public Void set_Connection(String value) { }
	// RVA: 0x6327848 VA: 0x759893f848
	public override Int64 get_ContentLength() { }
	// RVA: 0x6327850 VA: 0x759893f850
	public override Void set_ContentLength(Int64 value) { }
	// RVA: 0x63278e0 VA: 0x759893f8e0
	internal Void set_InternalContentLength(Int64 value) { }
	// RVA: 0x63278e8 VA: 0x759893f8e8
	internal Boolean get_ThrowOnError() { }
	// RVA: 0x63278f0 VA: 0x759893f8f0
	internal Void set_ThrowOnError(Boolean value) { }
	// RVA: 0x63278fc VA: 0x759893f8fc
	public override String get_ContentType() { }
	// RVA: 0x6327950 VA: 0x759893f950
	public override Void set_ContentType(String value) { }
	// RVA: 0x63279a8 VA: 0x759893f9a8
	public override ICredentials get_Credentials() { }
	// RVA: 0x63279b0 VA: 0x759893f9b0
	public override Void set_Credentials(ICredentials value) { }
	// RVA: 0x63279b8 VA: 0x759893f9b8
	public static Int32 get_DefaultMaximumErrorResponseLength() { }
	// RVA: 0x6327a10 VA: 0x759893fa10
	public Void set_Expect(String value) { }
	// RVA: 0x6327b3c VA: 0x759893fb3c
	public override WebHeaderCollection get_Headers() { }
	// RVA: 0x6327b44 VA: 0x759893fb44
	public override Void set_Headers(WebHeaderCollection value) { }
	// RVA: 0x6327c50 VA: 0x759893fc50
	public String get_Host() { }
	// RVA: 0x6327d5c VA: 0x759893fd5c
	public Void set_Host(String value) { }
	// RVA: 0x6327ed8 VA: 0x759893fed8
	private Boolean TryGetHostUri(String hostName, out Uri hostUri) { }
	// RVA: 0x6327fa8 VA: 0x759893ffa8
	public Boolean get_KeepAlive() { }
	// RVA: 0x6327fb0 VA: 0x759893ffb0
	public Int32 get_ReadWriteTimeout() { }
	// RVA: 0x6327fb8 VA: 0x759893ffb8
	public override String get_Method() { }
	// RVA: 0x6327fc0 VA: 0x759893ffc0
	public override Void set_Method(String value) { }
	// RVA: 0x6328210 VA: 0x7598940210
	public Version get_ProtocolVersion() { }
	// RVA: 0x6328218 VA: 0x7598940218
	public override IWebProxy get_Proxy() { }
	// RVA: 0x6328220 VA: 0x7598940220
	public override Void set_Proxy(IWebProxy value) { }
	// RVA: 0x632839c VA: 0x759894039c
	public Void set_Referer(String value) { }
	// RVA: 0x6328438 VA: 0x7598940438
	public override Uri get_RequestUri() { }
	// RVA: 0x6328440 VA: 0x7598940440
	public Boolean get_SendChunked() { }
	// RVA: 0x6328448 VA: 0x7598940448
	public ServicePoint get_ServicePoint() { }
	// RVA: 0x632844c VA: 0x759894044c
	internal ServicePoint get_ServicePointNoLock() { }
	// RVA: 0x6328454 VA: 0x7598940454
	public override Int32 get_Timeout() { }
	// RVA: 0x632845c VA: 0x759894045c
	public String get_TransferEncoding() { }
	// RVA: 0x63284b0 VA: 0x75989404b0
	public override Boolean get_UseDefaultCredentials() { }
	// RVA: 0x6328528 VA: 0x7598940528
	public Void set_UserAgent(String value) { }
	// RVA: 0x6328584 VA: 0x7598940584
	public Boolean get_UnsafeAuthenticatedConnectionSharing() { }
	// RVA: 0x632858c VA: 0x759894058c
	internal Boolean get_ExpectContinue() { }
	// RVA: 0x6328594 VA: 0x7598940594
	internal Void set_ExpectContinue(Boolean value) { }
	// RVA: 0x63285a0 VA: 0x75989405a0
	internal Uri get_AuthUri() { }
	// RVA: 0x63285a8 VA: 0x75989405a8
	internal Boolean get_ProxyQuery() { }
	// RVA: 0x63285dc VA: 0x75989405dc
	internal ServerCertValidationCallback get_ServerCertValidationCallback() { }
	// RVA: 0x63285e4 VA: 0x75989405e4
	public RemoteCertificateValidationCallback get_ServerCertificateValidationCallback() { }
	// RVA: 0x6328264 VA: 0x7598940264
	internal ServicePoint GetServicePoint() { }
	// RVA: 0x6328c68 VA: 0x7598940c68
	private WebOperation SendRequest(Boolean redirecting, BufferOffsetSize writeBuffer, CancellationToken cancellationToken) { }
	// RVA: 0x VA: 0x0
	internal static Task`1 RunWithTimeout(Func`2 func, Int32 timeout, Action abort, Func`1 aborted, CancellationToken cancellationToken) { }
	// RVA: 0x VA: 0x0
	private static Task`1 RunWithTimeoutWorker(Task`1 workerTask, Int32 timeout, Action abort, Func`1 aborted, CancellationTokenSource cts) { }
	// RVA: 0x VA: 0x0
	private Task`1 RunWithTimeout(Func`2 func) { }
	// RVA: 0x6329030 VA: 0x7598941030
	private Task`1 MyGetResponseAsync(CancellationToken cancellationToken) { }
	// RVA: 0x6329164 VA: 0x7598941164
	private Task`1 GetResponseFromData(WebResponseStream stream, CancellationToken cancellationToken) { }
	// RVA: 0x63292b4 VA: 0x75989412b4
	internal static Exception FlattenException(Exception e) { }
	// RVA: 0x6329374 VA: 0x7598941374
	private WebException GetWebException(Exception e) { }
	// RVA: 0x6329420 VA: 0x7598941420
	private static WebException GetWebException(Exception e, Boolean aborted) { }
	// RVA: 0x63295d0 VA: 0x75989415d0
	internal static WebException CreateRequestAbortedException() { }
	// RVA: 0x6329694 VA: 0x7598941694
	public override IAsyncResult BeginGetResponse(AsyncCallback callback, Object state) { }
	// RVA: 0x6329810 VA: 0x7598941810
	public override WebResponse EndGetResponse(IAsyncResult asyncResult) { }
	// RVA: 0x6329934 VA: 0x7598941934
	public override WebResponse GetResponse() { }
	// RVA: 0x6329a34 VA: 0x7598941a34
	internal Void set_FinishedReading(Boolean value) { }
	// RVA: 0x63293f8 VA: 0x75989413f8
	internal Boolean get_Aborted() { }
	// RVA: 0x6329a40 VA: 0x7598941a40
	public override Void Abort() { }
	// RVA: 0x6329b5c VA: 0x7598941b5c
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x6329b9c VA: 0x7598941b9c
	protected override Void GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x63274a4 VA: 0x759893f4a4
	private Void CheckRequestStarted() { }
	// RVA: 0x6329bdc VA: 0x7598941bdc
	internal Void DoContinueDelegate(Int32 statusCode, WebHeaderCollection headers) { }
	// RVA: 0x6329bf8 VA: 0x7598941bf8
	private Void RewriteRedirectToGet() { }
	// RVA: 0x6329c7c VA: 0x7598941c7c
	private Boolean Redirect(HttpStatusCode code, WebResponse response) { }
	// RVA: 0x632a170 VA: 0x7598942170
	private String GetHeaders() { }
	// RVA: 0x632a858 VA: 0x7598942858
	private Void DoPreAuthenticate() { }
	// RVA: 0x632aa58 VA: 0x7598942a58
	internal Byte[] GetRequestHeaders() { }
	// RVA: 0x632ada8 VA: 0x7598942da8
	private ValueTuple`2 HandleNtlmAuth(WebResponseStream stream, HttpWebResponse response, BufferOffsetSize writeBuffer, CancellationToken cancellationToken) { }
	// RVA: 0x632b044 VA: 0x7598943044
	private Boolean CheckAuthorization(WebResponse response, HttpStatusCode code) { }
	// RVA: 0x632b378 VA: 0x7598943378
	private ValueTuple`2 GetRewriteHandler(HttpWebResponse response, Boolean redirect) { }
	// RVA: 0x632b570 VA: 0x7598943570
	private ValueTuple`4 CheckFinalStatus(HttpWebResponse response) { }
	// RVA: 0x VA: 0x0
	private Boolean <RunWithTimeout>b__242_0() { }
	// RVA: 0x632ba98 VA: 0x7598943a98
	private Task`1 <GetRewriteHandler>b__271_0() { }
	// RVA: 0x632bbac VA: 0x7598943bac
	public Void .ctor() { }
}
```