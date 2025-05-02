# HttpWebResponse

**Namespace:** `System.Net`


## Fields

- `Uri uri`

- `WebHeaderCollection webHeaders`

- `CookieCollection cookieCollection`

- `String method`

- `Version version`

- `HttpStatusCode statusCode`

- `String statusDescription`

- `Int64 contentLength`

- `String contentType`

- `CookieContainer cookie_container`

- `Boolean disposed`

- `Stream stream`


## Methods

- `Void CheckDisposed()`

- `Void FillCookies()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class HttpWebResponse : WebResponse, ISerializable, IDisposable
{
	private Uri uri; // 0x20
	private WebHeaderCollection webHeaders; // 0x28
	private CookieCollection cookieCollection; // 0x30
	private String method; // 0x38
	private Version version; // 0x40
	private HttpStatusCode statusCode; // 0x48
	private String statusDescription; // 0x50
	private Int64 contentLength; // 0x58
	private String contentType; // 0x60
	private CookieContainer cookie_container; // 0x68
	private Boolean disposed; // 0x70
	private Stream stream; // 0x78

	public override Int64 ContentLength { get; }
	public override WebHeaderCollection Headers { get; }
	public override Uri ResponseUri { get; }
	public virtual HttpStatusCode StatusCode { get; }
	public virtual String StatusDescription { get; }

	// RVA: 0x632dfc4 VA: 0x7598945fc4
	public Void .ctor() { }
	// RVA: 0x632dfcc VA: 0x7598945fcc
	internal Void .ctor(Uri uri, String method, HttpStatusCode status, WebHeaderCollection headers) { }
	// RVA: 0x632d6f4 VA: 0x75989456f4
	internal Void .ctor(Uri uri, String method, WebResponseStream stream, CookieContainer container) { }
	// RVA: 0x632e2e0 VA: 0x75989462e0
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x632e6e4 VA: 0x75989466e4
	public override Int64 get_ContentLength() { }
	// RVA: 0x632e6ec VA: 0x75989466ec
	public override WebHeaderCollection get_Headers() { }
	// RVA: 0x632e6f4 VA: 0x75989466f4
	public override Uri get_ResponseUri() { }
	// RVA: 0x632e790 VA: 0x7598946790
	public virtual HttpStatusCode get_StatusCode() { }
	// RVA: 0x632e798 VA: 0x7598946798
	public virtual String get_StatusDescription() { }
	// RVA: 0x632e7b0 VA: 0x75989467b0
	public override Stream GetResponseStream() { }
	// RVA: 0x632e84c VA: 0x759894684c
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x632e858 VA: 0x7598946858
	protected override Void GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x632ea18 VA: 0x7598946a18
	public override Void Close() { }
	// RVA: 0x632ea48 VA: 0x7598946a48
	private Void System.IDisposable.Dispose() { }
	// RVA: 0x632ea58 VA: 0x7598946a58
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x632e70c VA: 0x759894670c
	private Void CheckDisposed() { }
	// RVA: 0x632e0b8 VA: 0x75989460b8
	private Void FillCookies() { }
}
```