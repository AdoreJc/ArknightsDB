# DeflateStream

**Namespace:** `System.IO.Compression`


## Fields

- `Stream base_stream`

- `CompressionMode mode`

- `Boolean leaveOpen`

- `Boolean disposed`

- `DeflateStreamNative native`


## Methods

- `Int32 ReadInternal(Byte[], Int32, Int32)`

- `Void WriteInternal(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.IO.Compression
public class DeflateStream : Stream
{
	private Stream base_stream; // 0x28
	private CompressionMode mode; // 0x30
	private Boolean leaveOpen; // 0x34
	private Boolean disposed; // 0x35
	private DeflateStreamNative native; // 0x38

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x64112c4 VA: 0x7598a292c4
	public Void .ctor(Stream stream, CompressionMode mode) { }
	// RVA: 0x641145c VA: 0x7598a2945c
	internal Void .ctor(Stream stream, CompressionMode mode, Boolean leaveOpen, Int32 windowsBits) { }
	// RVA: 0x64112d0 VA: 0x7598a292d0
	internal Void .ctor(Stream compressedStream, CompressionMode mode, Boolean leaveOpen, Boolean gzip) { }
	// RVA: 0x64115d8 VA: 0x7598a295d8
	protected override Void Finalize() { }
	// RVA: 0x641167c VA: 0x7598a2967c
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6411860 VA: 0x7598a29860
	private Int32 ReadInternal(Byte[] array, Int32 offset, Int32 count) { }
	// RVA: 0x6411920 VA: 0x7598a29920
	internal ValueTask`1 ReadAsyncMemory(Memory`1 destination, CancellationToken cancellationToken) { }
	// RVA: 0x6411928 VA: 0x7598a29928
	internal Int32 ReadCore(Span`1 destination) { }
	// RVA: 0x6411a44 VA: 0x7598a29a44
	public override Int32 Read(Byte[] array, Int32 offset, Int32 count) { }
	// RVA: 0x6411c30 VA: 0x7598a29c30
	private Void WriteInternal(Byte[] array, Int32 offset, Int32 count) { }
	// RVA: 0x6411ce0 VA: 0x7598a29ce0
	internal ValueTask WriteAsyncMemory(ReadOnlyMemory`1 source, CancellationToken cancellationToken) { }
	// RVA: 0x6411ce8 VA: 0x7598a29ce8
	internal Void WriteCore(ReadOnlySpan`1 source) { }
	// RVA: 0x6411d6c VA: 0x7598a29d6c
	public override Void Write(Byte[] array, Int32 offset, Int32 count) { }
	// RVA: 0x6411f64 VA: 0x7598a29f64
	public override Void Flush() { }
	// RVA: 0x6412070 VA: 0x7598a2a070
	public override IAsyncResult BeginRead(Byte[] array, Int32 offset, Int32 count, AsyncCallback asyncCallback, Object asyncState) { }
	// RVA: 0x6412480 VA: 0x7598a2a480
	public override IAsyncResult BeginWrite(Byte[] array, Int32 offset, Int32 count, AsyncCallback asyncCallback, Object asyncState) { }
	// RVA: 0x6412890 VA: 0x7598a2a890
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x64129fc VA: 0x7598a2a9fc
	public override Void EndWrite(IAsyncResult asyncResult) { }
	// RVA: 0x6412b50 VA: 0x7598a2ab50
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x6412b90 VA: 0x7598a2ab90
	public override Void SetLength(Int64 value) { }
	// RVA: 0x6412bd0 VA: 0x7598a2abd0
	public override Boolean get_CanRead() { }
	// RVA: 0x6412c0c VA: 0x7598a2ac0c
	public override Boolean get_CanSeek() { }
	// RVA: 0x6412c14 VA: 0x7598a2ac14
	public override Boolean get_CanWrite() { }
	// RVA: 0x6412c54 VA: 0x7598a2ac54
	public override Int64 get_Length() { }
	// RVA: 0x6412c94 VA: 0x7598a2ac94
	public override Int64 get_Position() { }
	// RVA: 0x6412cd4 VA: 0x7598a2acd4
	public override Void set_Position(Int64 value) { }
}
```