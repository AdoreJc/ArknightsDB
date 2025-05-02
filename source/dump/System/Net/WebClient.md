# WebClient

**Namespace:** `System.Net`


## Fields

- `Uri _baseAddress`

- `ICredentials _credentials`

- `WebHeaderCollection _headers`

- `NameValueCollection _requestParameters`

- `WebResponse _webResponse`

- `WebRequest _webRequest`

- `Encoding _encoding`

- `String _method`

- `Int64 _contentLength`

- `Boolean _canceled`

- `ProgressData _progress`

- `IWebProxy _proxy`

- `Boolean _proxySet`

- `Int32 _callNesting`

- `RequestCachePolicy <CachePolicy>k__BackingField`


## Properties

- `Encoding Encoding`

- `ICredentials Credentials`

- `RequestCachePolicy CachePolicy`


## Methods

- `Void StartOperation()`

- `Void EndOperation()`

- `Encoding get_Encoding()`

- `ICredentials get_Credentials()`

- `RequestCachePolicy get_CachePolicy()`

- `String DownloadString(String)`

- `String DownloadString(Uri)`

- `Void CopyHeadersTo(WebRequest)`

- `Uri GetUri(String)`

- `Uri GetUri(Uri)`

- `String GetStringUsingEncoding(WebRequest, Byte[])`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class WebClient : Component
{
	private Uri _baseAddress; // 0x28
	private ICredentials _credentials; // 0x30
	private WebHeaderCollection _headers; // 0x38
	private NameValueCollection _requestParameters; // 0x40
	private WebResponse _webResponse; // 0x48
	private WebRequest _webRequest; // 0x50
	private Encoding _encoding; // 0x58
	private String _method; // 0x60
	private Int64 _contentLength; // 0x68
	private Boolean _canceled; // 0x70
	private ProgressData _progress; // 0x78
	private IWebProxy _proxy; // 0x80
	private Boolean _proxySet; // 0x88
	private Int32 _callNesting; // 0x8c
	private RequestCachePolicy <CachePolicy>k__BackingField; // 0x90
	private static readonly Char[] s_parseContentTypeSeparators; // 0x0
	private static readonly Encoding[] s_knownEncodings; // 0x8

	public Encoding Encoding { get; }
	public ICredentials Credentials { get; }
	public RequestCachePolicy CachePolicy { get; }

	// RVA: 0x64276f4 VA: 0x7598a3f6f4
	public Void .ctor() { }
	// RVA: 0x6427828 VA: 0x7598a3f828
	private Void StartOperation() { }
	// RVA: 0x64278f4 VA: 0x7598a3f8f4
	private Void EndOperation() { }
	// RVA: 0x6427914 VA: 0x7598a3f914
	public Encoding get_Encoding() { }
	// RVA: 0x642791c VA: 0x7598a3f91c
	public ICredentials get_Credentials() { }
	// RVA: 0x6427924 VA: 0x7598a3f924
	public RequestCachePolicy get_CachePolicy() { }
	// RVA: 0x642792c VA: 0x7598a3f92c
	protected virtual WebRequest GetWebRequest(Uri address) { }
	// RVA: 0x6427e4c VA: 0x7598a3fe4c
	protected virtual WebResponse GetWebResponse(WebRequest request) { }
	// RVA: 0x6427e9c VA: 0x7598a3fe9c
	private Byte[] DownloadDataInternal(Uri address, out WebRequest request) { }
	// RVA: 0x6428a1c VA: 0x7598a40a1c
	public String DownloadString(String address) { }
	// RVA: 0x6428bc0 VA: 0x7598a40bc0
	public String DownloadString(Uri address) { }
	// RVA: 0x642893c VA: 0x7598a4093c
	private static Void AbortRequest(WebRequest request) { }
	// RVA: 0x6427a4c VA: 0x7598a3fa4c
	private Void CopyHeadersTo(WebRequest request) { }
	// RVA: 0x6428a38 VA: 0x7598a40a38
	private Uri GetUri(String address) { }
	// RVA: 0x6428128 VA: 0x7598a40128
	private Uri GetUri(Uri address) { }
	// RVA: 0x64283f8 VA: 0x7598a403f8
	private Byte[] DownloadBits(WebRequest request, Stream writeStream) { }
	// RVA: 0x6429180 VA: 0x7598a41180
	private static Boolean ByteArrayHasPrefix(Byte[] prefix, Byte[] byteArray) { }
	// RVA: 0x6428d3c VA: 0x7598a40d3c
	private String GetStringUsingEncoding(WebRequest request, Byte[] data) { }
	// RVA: 0x6428ce8 VA: 0x7598a40ce8
	private static Void ThrowIfNull(Object argument, String parameterName) { }
	// RVA: 0x64291f8 VA: 0x7598a411f8
	private static Void .cctor() { }
}
```