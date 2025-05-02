# WebRequestStream

**Namespace:** `System.Net`


## Fields

- `MemoryStream writeBuffer`

- `Boolean requestWritten`

- `Boolean allowBuffering`

- `Boolean sendChunked`

- `WebCompletionSource pendingWrite`

- `Int64 totalWritten`

- `Boolean headersSent`

- `Int32 completeRequestWritten`

- `Int32 chunkTrailerWritten`


## Properties

- `Boolean KeepAlive`


## Methods

- `Boolean get_KeepAlive()`

- `Task FinishWriting(CancellationToken)`

- `Task WriteAsyncInner(Byte[], Int32, Int32, WebCompletionSource, CancellationToken)`

- `Task ProcessWrite(Byte[], Int32, Int32, CancellationToken)`

- `Void CheckWriteOverflow(Int64, Int64, Int64)`

- `Task SetHeadersAsync(Boolean, CancellationToken)`

- `Task WriteChunkTrailer_inner(CancellationToken)`

- `Task WriteChunkTrailer()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class WebRequestStream : WebConnectionStream
{
	private static Byte[] crlf; // 0x0
	private MemoryStream writeBuffer; // 0x58
	private Boolean requestWritten; // 0x60
	private Boolean allowBuffering; // 0x61
	private Boolean sendChunked; // 0x62
	private WebCompletionSource pendingWrite; // 0x68
	private Int64 totalWritten; // 0x70
	private Byte[] headers; // 0x78
	private Boolean headersSent; // 0x80
	private Int32 completeRequestWritten; // 0x84
	private Int32 chunkTrailerWritten; // 0x88
	private readonly Stream <InnerStream>k__BackingField; // 0x90
	private readonly Boolean <KeepAlive>k__BackingField; // 0x98

	internal Stream InnerStream { get; }
	public Boolean KeepAlive { get; }
	public override Boolean CanRead { get; }
	public override Boolean CanWrite { get; }
	internal Boolean HasWriteBuffer { get; }
	internal Int32 WriteBufferLength { get; }

	// RVA: 0x633e9b4 VA: 0x75989569b4
	public Void .ctor(WebConnection connection, WebOperation operation, Stream stream, WebConnectionTunnel tunnel) { }
	// RVA: 0x633eb30 VA: 0x7598956b30
	internal Stream get_InnerStream() { }
	// RVA: 0x633eb38 VA: 0x7598956b38
	public Boolean get_KeepAlive() { }
	// RVA: 0x633eb40 VA: 0x7598956b40
	public override Boolean get_CanRead() { }
	// RVA: 0x633eb48 VA: 0x7598956b48
	public override Boolean get_CanWrite() { }
	// RVA: 0x633eb50 VA: 0x7598956b50
	internal Boolean get_HasWriteBuffer() { }
	// RVA: 0x633eb84 VA: 0x7598956b84
	internal Int32 get_WriteBufferLength() { }
	// RVA: 0x633ebc8 VA: 0x7598956bc8
	internal BufferOffsetSize GetWriteBuffer() { }
	// RVA: 0x633eca4 VA: 0x7598956ca4
	private Task FinishWriting(CancellationToken cancellationToken) { }
	// RVA: 0x633eda4 VA: 0x7598956da4
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x633f024 VA: 0x7598957024
	private Task WriteAsyncInner(Byte[] buffer, Int32 offset, Int32 size, WebCompletionSource completion, CancellationToken cancellationToken) { }
	// RVA: 0x633f178 VA: 0x7598957178
	private Task ProcessWrite(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
	// RVA: 0x633f2b4 VA: 0x75989572b4
	private Void CheckWriteOverflow(Int64 contentLength, Int64 totalWritten, Int64 size) { }
	// RVA: 0x633d488 VA: 0x7598955488
	internal Task Initialize(CancellationToken cancellationToken) { }
	// RVA: 0x633f358 VA: 0x7598957358
	private Task SetHeadersAsync(Boolean setInternalLength, CancellationToken cancellationToken) { }
	// RVA: 0x633f46c VA: 0x759895746c
	internal Task WriteRequestAsync(CancellationToken cancellationToken) { }
	// RVA: 0x633f570 VA: 0x7598957570
	private Task WriteChunkTrailer_inner(CancellationToken cancellationToken) { }
	// RVA: 0x633f670 VA: 0x7598957670
	private Task WriteChunkTrailer() { }
	// RVA: 0x633f34c VA: 0x759895734c
	internal Void KillBuffer() { }
	// RVA: 0x633f764 VA: 0x7598957764
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
	// RVA: 0x633f814 VA: 0x7598957814
	protected override Boolean TryReadFromBufferedContent(Byte[] buffer, Int32 offset, Int32 count, out Int32 result) { }
	// RVA: 0x633f854 VA: 0x7598957854
	protected override Void Close_internal(ref Boolean disposed) { }
	// RVA: 0x633f9d4 VA: 0x75989579d4
	private static Void .cctor() { }
}
```