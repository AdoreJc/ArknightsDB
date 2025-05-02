# GZipStream

**Namespace:** `System.IO.Compression`


## Fields

- `DeflateStream _deflateStream`


## Methods

- `Void CheckDeflateStream()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.IO.Compression
public class GZipStream : Stream
{
	private DeflateStream _deflateStream; // 0x28

	public override Boolean CanRead { get; }
	public override Boolean CanWrite { get; }
	public override Boolean CanSeek { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x640f850 VA: 0x7598a27850
	public Void .ctor(Stream stream, CompressionMode mode) { }
	// RVA: 0x640f858 VA: 0x7598a27858
	public Void .ctor(Stream stream, CompressionMode mode, Boolean leaveOpen) { }
	// RVA: 0x640f91c VA: 0x7598a2791c
	public override Boolean get_CanRead() { }
	// RVA: 0x640f934 VA: 0x7598a27934
	public override Boolean get_CanWrite() { }
	// RVA: 0x640f94c VA: 0x7598a2794c
	public override Boolean get_CanSeek() { }
	// RVA: 0x640f964 VA: 0x7598a27964
	public override Int64 get_Length() { }
	// RVA: 0x640f9b4 VA: 0x7598a279b4
	public override Int64 get_Position() { }
	// RVA: 0x640fa04 VA: 0x7598a27a04
	public override Void set_Position(Int64 value) { }
	// RVA: 0x640fa54 VA: 0x7598a27a54
	public override Void Flush() { }
	// RVA: 0x640fa90 VA: 0x7598a27a90
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x640fae0 VA: 0x7598a27ae0
	public override Void SetLength(Int64 value) { }
	// RVA: 0x640fb30 VA: 0x7598a27b30
	public override Int32 ReadByte() { }
	// RVA: 0x640fb54 VA: 0x7598a27b54
	public override IAsyncResult BeginRead(Byte[] array, Int32 offset, Int32 count, AsyncCallback asyncCallback, Object asyncState) { }
	// RVA: 0x640fc08 VA: 0x7598a27c08
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x640fc50 VA: 0x7598a27c50
	public override Int32 Read(Byte[] array, Int32 offset, Int32 count) { }
	// RVA: 0x640fc74 VA: 0x7598a27c74
	public override Int32 Read(Span`1 buffer) { }
	// RVA: 0x640fd64 VA: 0x7598a27d64
	public override IAsyncResult BeginWrite(Byte[] array, Int32 offset, Int32 count, AsyncCallback asyncCallback, Object asyncState) { }
	// RVA: 0x640fe18 VA: 0x7598a27e18
	public override Void EndWrite(IAsyncResult asyncResult) { }
	// RVA: 0x640fe24 VA: 0x7598a27e24
	public override Void Write(Byte[] array, Int32 offset, Int32 count) { }
	// RVA: 0x640fe48 VA: 0x7598a27e48
	public override Void Write(ReadOnlySpan`1 buffer) { }
	// RVA: 0x640ff38 VA: 0x7598a27f38
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x641000c VA: 0x7598a2800c
	public override Task`1 ReadAsync(Byte[] array, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6410030 VA: 0x7598a28030
	public override ValueTask`1 ReadAsync(Memory`1 buffer, CancellationToken cancellationToken) { }
	// RVA: 0x641012c VA: 0x7598a2812c
	public override Task WriteAsync(Byte[] array, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6410150 VA: 0x7598a28150
	public override ValueTask WriteAsync(ReadOnlyMemory`1 buffer, CancellationToken cancellationToken) { }
	// RVA: 0x641024c VA: 0x7598a2824c
	public override Task FlushAsync(CancellationToken cancellationToken) { }
	// RVA: 0x640fa78 VA: 0x7598a27a78
	private Void CheckDeflateStream() { }
	// RVA: 0x6410270 VA: 0x7598a28270
	private static Void ThrowStreamClosedException() { }
}
```