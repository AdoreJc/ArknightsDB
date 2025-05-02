# UnityWebRequest

**Namespace:** `UnityEngine.Networking`


## Fields

- `Boolean <disposeCertificateHandlerOnDispose>k__BackingField`

- `Boolean <disposeDownloadHandlerOnDispose>k__BackingField`

- `Boolean <disposeUploadHandlerOnDispose>k__BackingField`


## Properties

- `Boolean disposeCertificateHandlerOnDispose`

- `Boolean disposeDownloadHandlerOnDispose`

- `Boolean disposeUploadHandlerOnDispose`

- `String method`

- `String error`

- `String url`

- `Int64 responseCode`

- `Boolean isModifiable`

- `Boolean isDone`

- `Boolean isNetworkError`

- `Boolean isHttpError`

- `Result result`

- `Boolean chunkedTransfer`

- `UploadHandler uploadHandler`

- `DownloadHandler downloadHandler`

- `CertificateHandler certificateHandler`

- `Int32 timeout`


## Methods

- `Boolean get_disposeCertificateHandlerOnDispose()`

- `Void set_disposeCertificateHandlerOnDispose(Boolean)`

- `Boolean get_disposeDownloadHandlerOnDispose()`

- `Void set_disposeDownloadHandlerOnDispose(Boolean)`

- `Boolean get_disposeUploadHandlerOnDispose()`

- `Void set_disposeUploadHandlerOnDispose(Boolean)`

- `Void Release()`

- `Void InternalSetDefaults()`

- `Void Dispose()`

- `Void DisposeHandlers()`

- `AsyncOperation Send()`

- `UnityWebRequestAsyncOperation SendWebRequest()`

- `Void Abort()`

- `UnityWebRequestError SetMethod(UnityWebRequestMethod)`

- `UnityWebRequestError SetCustomMethod(String)`

- `Void set_method(String)`

- `UnityWebRequestError GetError()`

- `String get_error()`

- `String get_url()`

- `Void set_url(String)`

- `String GetUrl()`

- `UnityWebRequestError SetUrl(String)`

- `Void InternalSetUrl(String)`

- `Int64 get_responseCode()`

- `Boolean get_isModifiable()`

- `Boolean get_isDone()`

- `Boolean get_isNetworkError()`

- `Boolean get_isHttpError()`

- `Result get_result()`

- `UnityWebRequestError SetChunked(Boolean)`

- `Void set_chunkedTransfer(Boolean)`

- `Void SetRequestHeader(String, String)`

- `String GetResponseHeader(String)`

- `UnityWebRequestError SetUploadHandler(UploadHandler)`

- `UploadHandler get_uploadHandler()`

- `Void set_uploadHandler(UploadHandler)`

- `UnityWebRequestError SetDownloadHandler(DownloadHandler)`

- `DownloadHandler get_downloadHandler()`

- `Void set_downloadHandler(DownloadHandler)`

- `CertificateHandler get_certificateHandler()`

- `UnityWebRequestError SetTimeoutMsec(Int32)`

- `Void set_timeout(Int32)`


## Dump
```C#
// Dll : UnityEngine.UnityWebRequestModule.dll
// Namespace : UnityEngine.Networking
public class UnityWebRequest : IDisposable
{
	internal IntPtr m_Ptr; // 0x10
	internal DownloadHandler m_DownloadHandler; // 0x18
	internal UploadHandler m_UploadHandler; // 0x20
	internal CertificateHandler m_CertificateHandler; // 0x28
	internal Uri m_Uri; // 0x30
	public const String kHttpVerbGET; // 0x0
	public const String kHttpVerbHEAD; // 0x0
	public const String kHttpVerbPOST; // 0x0
	public const String kHttpVerbPUT; // 0x0
	public const String kHttpVerbCREATE; // 0x0
	public const String kHttpVerbDELETE; // 0x0
	private Boolean <disposeCertificateHandlerOnDispose>k__BackingField; // 0x38
	private Boolean <disposeDownloadHandlerOnDispose>k__BackingField; // 0x39
	private Boolean <disposeUploadHandlerOnDispose>k__BackingField; // 0x3a

	public Boolean disposeCertificateHandlerOnDispose { get; set; }
	public Boolean disposeDownloadHandlerOnDispose { get; set; }
	public Boolean disposeUploadHandlerOnDispose { get; set; }
	public String method { set; }
	public String error { get; }
	public String url { get; set; }
	public Int64 responseCode { get; }
	public Boolean isModifiable { get; }
	public Boolean isDone { get; }
	public Boolean isNetworkError { get; }
	public Boolean isHttpError { get; }
	public Result result { get; }
	public Boolean chunkedTransfer { set; }
	public UploadHandler uploadHandler { get; set; }
	public DownloadHandler downloadHandler { get; set; }
	public CertificateHandler certificateHandler { get; }
	public Int32 timeout { set; }

	// RVA: 0x6a85934 VA: 0x759909d934
	private static String GetWebErrorString(UnityWebRequestError err) { }
	// RVA: 0x6a85970 VA: 0x759909d970
	internal static String GetHTTPStatusString(Int64 responseCode) { }
	// RVA: 0x6a859ac VA: 0x759909d9ac
	public Boolean get_disposeCertificateHandlerOnDispose() { }
	// RVA: 0x6a859b4 VA: 0x759909d9b4
	public Void set_disposeCertificateHandlerOnDispose(Boolean value) { }
	// RVA: 0x6a859c0 VA: 0x759909d9c0
	public Boolean get_disposeDownloadHandlerOnDispose() { }
	// RVA: 0x6a859c8 VA: 0x759909d9c8
	public Void set_disposeDownloadHandlerOnDispose(Boolean value) { }
	// RVA: 0x6a859d4 VA: 0x759909d9d4
	public Boolean get_disposeUploadHandlerOnDispose() { }
	// RVA: 0x6a859dc VA: 0x759909d9dc
	public Void set_disposeUploadHandlerOnDispose(Boolean value) { }
	// RVA: 0x6a859e8 VA: 0x759909d9e8
	internal static IntPtr Create() { }
	// RVA: 0x6a85a10 VA: 0x759909da10
	private Void Release() { }
	// RVA: 0x6a85a4c VA: 0x759909da4c
	internal Void InternalDestroy() { }
	// RVA: 0x6a85b44 VA: 0x759909db44
	private Void InternalSetDefaults() { }
	// RVA: 0x6a85b58 VA: 0x759909db58
	public Void .ctor(String url, String method) { }
	// RVA: 0x6a85de0 VA: 0x759909dde0
	public Void .ctor(String url, String method, DownloadHandler downloadHandler, UploadHandler uploadHandler) { }
	// RVA: 0x6a860b4 VA: 0x759909e0b4
	protected override Void Finalize() { }
	// RVA: 0x6a861b0 VA: 0x759909e1b0
	public Void Dispose() { }
	// RVA: 0x6a86150 VA: 0x759909e150
	private Void DisposeHandlers() { }
	// RVA: 0x6a862c4 VA: 0x759909e2c4
	internal UnityWebRequestAsyncOperation BeginWebRequest() { }
	// RVA: 0x6a86300 VA: 0x759909e300
	public AsyncOperation Send() { }
	// RVA: 0x6a86304 VA: 0x759909e304
	public UnityWebRequestAsyncOperation SendWebRequest() { }
	// RVA: 0x6a85b08 VA: 0x759909db08
	public Void Abort() { }
	// RVA: 0x6a86360 VA: 0x759909e360
	private UnityWebRequestError SetMethod(UnityWebRequestMethod methodType) { }
	// RVA: 0x6a863a4 VA: 0x759909e3a4
	internal Void InternalSetMethod(UnityWebRequestMethod methodType) { }
	// RVA: 0x6a864ec VA: 0x759909e4ec
	private UnityWebRequestError SetCustomMethod(String customMethodName) { }
	// RVA: 0x6a86530 VA: 0x759909e530
	internal Void InternalSetCustomMethod(String customMethodName) { }
	// RVA: 0x6a85c5c VA: 0x759909dc5c
	public Void set_method(String value) { }
	// RVA: 0x6a8663c VA: 0x759909e63c
	private UnityWebRequestError GetError() { }
	// RVA: 0x6a86678 VA: 0x759909e678
	public String get_error() { }
	// RVA: 0x6a86894 VA: 0x759909e894
	public String get_url() { }
	// RVA: 0x6a85bd4 VA: 0x759909dbd4
	public Void set_url(String value) { }
	// RVA: 0x6a868d0 VA: 0x759909e8d0
	private String GetUrl() { }
	// RVA: 0x6a86a18 VA: 0x759909ea18
	private UnityWebRequestError SetUrl(String url) { }
	// RVA: 0x6a8690c VA: 0x759909e90c
	private Void InternalSetUrl(String url) { }
	// RVA: 0x6a86858 VA: 0x759909e858
	public Int64 get_responseCode() { }
	// RVA: 0x6a864b0 VA: 0x759909e4b0
	public Boolean get_isModifiable() { }
	// RVA: 0x6a86a5c VA: 0x759909ea5c
	public Boolean get_isDone() { }
	// RVA: 0x6a86aa4 VA: 0x759909eaa4
	public Boolean get_isNetworkError() { }
	// RVA: 0x6a86aec VA: 0x759909eaec
	public Boolean get_isHttpError() { }
	// RVA: 0x6a8681c VA: 0x759909e81c
	public Result get_result() { }
	// RVA: 0x6a86b34 VA: 0x759909eb34
	private UnityWebRequestError SetChunked(Boolean chunked) { }
	// RVA: 0x6a86b78 VA: 0x759909eb78
	public Void set_chunkedTransfer(Boolean value) { }
	// RVA: 0x6a86c84 VA: 0x759909ec84
	internal UnityWebRequestError InternalSetRequestHeader(String name, String value) { }
	// RVA: 0x6a86cd8 VA: 0x759909ecd8
	public Void SetRequestHeader(String name, String value) { }
	// RVA: 0x6a86e64 VA: 0x759909ee64
	public String GetResponseHeader(String name) { }
	// RVA: 0x6a86ea8 VA: 0x759909eea8
	internal String[] GetResponseHeaderKeys() { }
	// RVA: 0x6a86ee4 VA: 0x759909eee4
	public Dictionary`2 GetResponseHeaders() { }
	// RVA: 0x6a870b4 VA: 0x759909f0b4
	private UnityWebRequestError SetUploadHandler(UploadHandler uh) { }
	// RVA: 0x6a86220 VA: 0x759909e220
	public UploadHandler get_uploadHandler() { }
	// RVA: 0x6a85f9c VA: 0x759909df9c
	public Void set_uploadHandler(UploadHandler value) { }
	// RVA: 0x6a870f8 VA: 0x759909f0f8
	private UnityWebRequestError SetDownloadHandler(DownloadHandler dh) { }
	// RVA: 0x6a86218 VA: 0x759909e218
	public DownloadHandler get_downloadHandler() { }
	// RVA: 0x6a85e84 VA: 0x759909de84
	public Void set_downloadHandler(DownloadHandler value) { }
	// RVA: 0x6a86228 VA: 0x759909e228
	public CertificateHandler get_certificateHandler() { }
	// RVA: 0x6a8713c VA: 0x759909f13c
	private UnityWebRequestError SetTimeoutMsec(Int32 timeout) { }
	// RVA: 0x6a87180 VA: 0x759909f180
	public Void set_timeout(Int32 value) { }
	// RVA: 0x6a872dc VA: 0x759909f2dc
	public static UnityWebRequest Get(String uri) { }
	// RVA: 0x6a873d0 VA: 0x759909f3d0
	public static UnityWebRequest Post(String uri, String postData) { }
	// RVA: 0x6a87460 VA: 0x759909f460
	private static Void SetupPost(UnityWebRequest request, String postData) { }
	// RVA: 0x6a87658 VA: 0x759909f658
	public static UnityWebRequest Post(String uri, WWWForm formData) { }
	// RVA: 0x6a876e8 VA: 0x759909f6e8
	private static Void SetupPost(UnityWebRequest request, WWWForm formData) { }
	// RVA: 0x6a878d4 VA: 0x759909f8d4
	public static String EscapeURL(String s) { }
	// RVA: 0x6a878f4 VA: 0x759909f8f4
	public static String EscapeURL(String s, Encoding e) { }
	// RVA: 0x6a879cc VA: 0x759909f9cc
	public static String UnEscapeURL(String s) { }
	// RVA: 0x6a879ec VA: 0x759909f9ec
	public static String UnEscapeURL(String s, Encoding e) { }
}
```