# WebResponseStream

**Namespace:** `System.Net`


## Fields

- `WebReadStream innerStream`

- `Boolean nextReadCalled`

- `Boolean bufferedEntireContent`

- `WebCompletionSource pendingRead`

- `Object locker`

- `Int32 nestedRead`

- `Boolean read_eof`

- `WebHeaderCollection <Headers>k__BackingField`

- `HttpStatusCode <StatusCode>k__BackingField`

- `String <StatusDescription>k__BackingField`

- `Version <Version>k__BackingField`

- `Boolean <KeepAlive>k__BackingField`

- `Boolean <ChunkedRead>k__BackingField`


## Properties

- `WebRequestStream RequestStream`

- `WebHeaderCollection Headers`

- `HttpStatusCode StatusCode`

- `String StatusDescription`

- `Version Version`

- `Boolean KeepAlive`

- `Boolean ChunkedRead`

- `Boolean ExpectContent`


## Methods

- `WebRequestStream get_RequestStream()`

- `WebHeaderCollection get_Headers()`

- `Void set_Headers(WebHeaderCollection)`

- `HttpStatusCode get_StatusCode()`

- `Void set_StatusCode(HttpStatusCode)`

- `String get_StatusDescription()`

- `Void set_StatusDescription(String)`

- `Version get_Version()`

- `Void set_Version(Version)`

- `Boolean get_KeepAlive()`

- `Void set_KeepAlive(Boolean)`

- `Boolean get_ChunkedRead()`

- `Void set_ChunkedRead(Boolean)`

- `Boolean get_ExpectContent()`

- `Void Initialize(BufferOffsetSize)`

- `WebException GetReadException(WebExceptionStatus, Exception, String)`

- `Boolean GetResponse(BufferOffsetSize, ref, ref)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class WebResponseStream : WebConnectionStream
{
	private WebReadStream innerStream; // 0x58
	private Boolean nextReadCalled; // 0x60
	private Boolean bufferedEntireContent; // 0x61
	private WebCompletionSource pendingRead; // 0x68
	private Object locker; // 0x70
	private Int32 nestedRead; // 0x78
	private Boolean read_eof; // 0x7c
	private readonly WebRequestStream <RequestStream>k__BackingField; // 0x80
	private WebHeaderCollection <Headers>k__BackingField; // 0x88
	private HttpStatusCode <StatusCode>k__BackingField; // 0x90
	private String <StatusDescription>k__BackingField; // 0x98
	private Version <Version>k__BackingField; // 0xa0
	private Boolean <KeepAlive>k__BackingField; // 0xa8
	private Boolean <ChunkedRead>k__BackingField; // 0xa9

	public WebRequestStream RequestStream { get; }
	public WebHeaderCollection Headers { get; set; }
	public HttpStatusCode StatusCode { get; set; }
	public String StatusDescription { get; set; }
	public Version Version { get; set; }
	public Boolean KeepAlive { get; set; }
	public override Boolean CanRead { get; }
	public override Boolean CanWrite { get; }
	private Boolean ChunkedRead { get; set; }
	private Boolean ExpectContent { get; }

	// RVA: 0x63426a0 VA: 0x759895a6a0
	public WebRequestStream get_RequestStream() { }
	// RVA: 0x63426a8 VA: 0x759895a6a8
	public WebHeaderCollection get_Headers() { }
	// RVA: 0x63426b0 VA: 0x759895a6b0
	private Void set_Headers(WebHeaderCollection value) { }
	// RVA: 0x63426b8 VA: 0x759895a6b8
	public HttpStatusCode get_StatusCode() { }
	// RVA: 0x63426c0 VA: 0x759895a6c0
	private Void set_StatusCode(HttpStatusCode value) { }
	// RVA: 0x63426c8 VA: 0x759895a6c8
	public String get_StatusDescription() { }
	// RVA: 0x63426d0 VA: 0x759895a6d0
	private Void set_StatusDescription(String value) { }
	// RVA: 0x63426d8 VA: 0x759895a6d8
	public Version get_Version() { }
	// RVA: 0x63426e0 VA: 0x759895a6e0
	private Void set_Version(Version value) { }
	// RVA: 0x63426e8 VA: 0x759895a6e8
	public Boolean get_KeepAlive() { }
	// RVA: 0x63426f0 VA: 0x759895a6f0
	private Void set_KeepAlive(Boolean value) { }
	// RVA: 0x633d58c VA: 0x759895558c
	public Void .ctor(WebRequestStream request) { }
	// RVA: 0x63426fc VA: 0x759895a6fc
	public override Boolean get_CanRead() { }
	// RVA: 0x6342704 VA: 0x759895a704
	public override Boolean get_CanWrite() { }
	// RVA: 0x634270c VA: 0x759895a70c
	private Boolean get_ChunkedRead() { }
	// RVA: 0x6342714 VA: 0x759895a714
	private Void set_ChunkedRead(Boolean value) { }
	// RVA: 0x6342720 VA: 0x759895a720
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6342894 VA: 0x759895a894
	private Task`1 ProcessRead(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
	// RVA: 0x6342b60 VA: 0x759895ab60
	protected override Boolean TryReadFromBufferedContent(Byte[] buffer, Int32 offset, Int32 count, out Int32 result) { }
	// RVA: 0x6342c2c VA: 0x759895ac2c
	private Boolean get_ExpectContent() { }
	// RVA: 0x6342cbc VA: 0x759895acbc
	private Void Initialize(BufferOffsetSize buffer) { }
	// RVA: 0x6343218 VA: 0x759895b218
	private Task`1 ReadAllAsyncInner(CancellationToken cancellationToken) { }
	// RVA: 0x6343354 VA: 0x759895b354
	internal Task ReadAllAsync(Boolean resending, CancellationToken cancellationToken) { }
	// RVA: 0x6343470 VA: 0x759895b470
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x634350c VA: 0x759895b50c
	protected override Void Close_internal(ref Boolean disposed) { }
	// RVA: 0x63435b0 VA: 0x759895b5b0
	private WebException GetReadException(WebExceptionStatus status, Exception error, String where) { }
	// RVA: 0x633d624 VA: 0x7598955624
	internal Task InitReadAsync(CancellationToken cancellationToken) { }
	// RVA: 0x6343848 VA: 0x759895b848
	private Boolean GetResponse(BufferOffsetSize buffer, ref Int32 pos, ref ReadState state) { }
}
```