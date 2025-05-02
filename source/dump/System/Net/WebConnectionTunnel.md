# WebConnectionTunnel

**Namespace:** `System.Net`


## Fields

- `HttpWebRequest connectRequest`

- `NtlmAuthState ntlmAuthState`

- `Boolean <Success>k__BackingField`

- `Boolean <CloseConnection>k__BackingField`

- `Int32 <StatusCode>k__BackingField`

- `String <StatusDescription>k__BackingField`

- `WebHeaderCollection <Headers>k__BackingField`

- `Version <ProxyVersion>k__BackingField`


## Properties

- `HttpWebRequest Request`

- `Uri ConnectUri`

- `Boolean Success`

- `Boolean CloseConnection`

- `Int32 StatusCode`

- `String StatusDescription`

- `WebHeaderCollection Headers`

- `Version ProxyVersion`


## Methods

- `HttpWebRequest get_Request()`

- `Uri get_ConnectUri()`

- `Boolean get_Success()`

- `Void set_Success(Boolean)`

- `Boolean get_CloseConnection()`

- `Void set_CloseConnection(Boolean)`

- `Int32 get_StatusCode()`

- `Void set_StatusCode(Int32)`

- `Void set_StatusDescription(String)`

- `Void set_Challenge(String[])`

- `WebHeaderCollection get_Headers()`

- `Void set_Headers(WebHeaderCollection)`

- `Version get_ProxyVersion()`

- `Void set_ProxyVersion(Version)`

- `Void set_Data(Byte[])`

- `Void FlushContents(Stream, Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class WebConnectionTunnel
{
	private readonly HttpWebRequest <Request>k__BackingField; // 0x10
	private readonly Uri <ConnectUri>k__BackingField; // 0x18
	private HttpWebRequest connectRequest; // 0x20
	private NtlmAuthState ntlmAuthState; // 0x28
	private Boolean <Success>k__BackingField; // 0x2c
	private Boolean <CloseConnection>k__BackingField; // 0x2d
	private Int32 <StatusCode>k__BackingField; // 0x30
	private String <StatusDescription>k__BackingField; // 0x38
	private String[] <Challenge>k__BackingField; // 0x40
	private WebHeaderCollection <Headers>k__BackingField; // 0x48
	private Version <ProxyVersion>k__BackingField; // 0x50
	private Byte[] <Data>k__BackingField; // 0x58

	public HttpWebRequest Request { get; }
	public Uri ConnectUri { get; }
	public Boolean Success { get; set; }
	public Boolean CloseConnection { get; set; }
	public Int32 StatusCode { get; set; }
	private String StatusDescription { set; }
	public String[] Challenge { get; set; }
	public WebHeaderCollection Headers { get; set; }
	public Version ProxyVersion { get; set; }
	public Byte[] Data { get; set; }

	// RVA: 0x6339178 VA: 0x7598951178
	public HttpWebRequest get_Request() { }
	// RVA: 0x6339180 VA: 0x7598951180
	public Uri get_ConnectUri() { }
	// RVA: 0x6337954 VA: 0x759894f954
	public Void .ctor(HttpWebRequest request, Uri connectUri) { }
	// RVA: 0x6339188 VA: 0x7598951188
	public Boolean get_Success() { }
	// RVA: 0x6339190 VA: 0x7598951190
	private Void set_Success(Boolean value) { }
	// RVA: 0x633919c VA: 0x759895119c
	public Boolean get_CloseConnection() { }
	// RVA: 0x63391a4 VA: 0x75989511a4
	private Void set_CloseConnection(Boolean value) { }
	// RVA: 0x63391b0 VA: 0x75989511b0
	public Int32 get_StatusCode() { }
	// RVA: 0x63391b8 VA: 0x75989511b8
	private Void set_StatusCode(Int32 value) { }
	// RVA: 0x63391c0 VA: 0x75989511c0
	private Void set_StatusDescription(String value) { }
	// RVA: 0x63391c8 VA: 0x75989511c8
	public String[] get_Challenge() { }
	// RVA: 0x63391d0 VA: 0x75989511d0
	private Void set_Challenge(String[] value) { }
	// RVA: 0x63391d8 VA: 0x75989511d8
	public WebHeaderCollection get_Headers() { }
	// RVA: 0x63391e0 VA: 0x75989511e0
	private Void set_Headers(WebHeaderCollection value) { }
	// RVA: 0x63391e8 VA: 0x75989511e8
	public Version get_ProxyVersion() { }
	// RVA: 0x63391f0 VA: 0x75989511f0
	private Void set_ProxyVersion(Version value) { }
	// RVA: 0x63391f8 VA: 0x75989511f8
	public Byte[] get_Data() { }
	// RVA: 0x6339200 VA: 0x7598951200
	private Void set_Data(Byte[] value) { }
	// RVA: 0x6337998 VA: 0x759894f998
	internal Task Initialize(Stream stream, CancellationToken cancellationToken) { }
	// RVA: 0x6339208 VA: 0x7598951208
	private Task`1 ReadHeaders(Stream stream, CancellationToken cancellationToken) { }
	// RVA: 0x6339358 VA: 0x7598951358
	private Void FlushContents(Stream stream, Int32 contentLength) { }
}
```