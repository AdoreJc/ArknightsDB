# UnmanagedMemoryStream

**Namespace:** `System.IO`


## Fields

- `SafeBuffer _buffer`

- `Int64 _length`

- `Int64 _capacity`

- `Int64 _position`

- `Int64 _offset`

- `FileAccess _access`


## Methods

- `Void Initialize(Byte*, Int64, Int64, FileAccess)`

- `Void EnsureNotClosed()`

- `Void EnsureReadable()`

- `Void EnsureWriteable()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class UnmanagedMemoryStream : Stream
{
	private SafeBuffer _buffer; // 0x28
	private Byte* _mem; // 0x30
	private Int64 _length; // 0x38
	private Int64 _capacity; // 0x40
	private Int64 _position; // 0x48
	private Int64 _offset; // 0x50
	private FileAccess _access; // 0x58
	internal Boolean _isOpen; // 0x5c
	private Task`1 _lastReadTask; // 0x60

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }
	public Byte* PositionPointer { get; }

	// RVA: 0x5fffec4 VA: 0x7598617ec4
	protected Void .ctor() { }
	// RVA: 0x60055dc VA: 0x759861d5dc
	public Void .ctor(Byte* pointer, Int64 length) { }
	// RVA: 0x600565c VA: 0x759861d65c
	public Void .ctor(Byte* pointer, Int64 length, Int64 capacity, FileAccess access) { }
	// RVA: 0x5ffff28 VA: 0x7598617f28
	protected Void Initialize(Byte* pointer, Int64 length, Int64 capacity, FileAccess access) { }
	// RVA: 0x60056ec VA: 0x759861d6ec
	public override Boolean get_CanRead() { }
	// RVA: 0x6005708 VA: 0x759861d708
	public override Boolean get_CanSeek() { }
	// RVA: 0x6005710 VA: 0x759861d710
	public override Boolean get_CanWrite() { }
	// RVA: 0x6000744 VA: 0x7598618744
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6005730 VA: 0x759861d730
	private Void EnsureNotClosed() { }
	// RVA: 0x6005764 VA: 0x759861d764
	private Void EnsureReadable() { }
	// RVA: 0x60057a0 VA: 0x759861d7a0
	private Void EnsureWriteable() { }
	// RVA: 0x60057dc VA: 0x759861d7dc
	public override Void Flush() { }
	// RVA: 0x60057e0 VA: 0x759861d7e0
	public override Task FlushAsync(CancellationToken cancellationToken) { }
	// RVA: 0x6005980 VA: 0x759861d980
	public override Int64 get_Length() { }
	// RVA: 0x600599c VA: 0x759861d99c
	public override Int64 get_Position() { }
	// RVA: 0x60059e4 VA: 0x759861d9e4
	public override Void set_Position(Int64 value) { }
	// RVA: 0x6005a8c VA: 0x759861da8c
	public Byte* get_PositionPointer() { }
	// RVA: 0x6005b4c VA: 0x759861db4c
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6005d0c VA: 0x759861dd0c
	public override Int32 Read(Span`1 buffer) { }
	// RVA: 0x6000134 VA: 0x7598618134
	internal Int32 ReadCore(Span`1 buffer) { }
	// RVA: 0x6005dec VA: 0x759861ddec
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6006130 VA: 0x759861e130
	public override ValueTask`1 ReadAsync(Memory`1 buffer, CancellationToken cancellationToken) { }
	// RVA: 0x6006474 VA: 0x759861e474
	public override Int32 ReadByte() { }
	// RVA: 0x60065d4 VA: 0x759861e5d4
	public override Int64 Seek(Int64 offset, SeekOrigin loc) { }
	// RVA: 0x60066e4 VA: 0x759861e6e4
	public override Void SetLength(Int64 value) { }
	// RVA: 0x6006874 VA: 0x759861e874
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6006a60 VA: 0x759861ea60
	public override Void Write(ReadOnlySpan`1 buffer) { }
	// RVA: 0x6000364 VA: 0x7598618364
	internal Void WriteCore(ReadOnlySpan`1 buffer) { }
	// RVA: 0x6006b40 VA: 0x759861eb40
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6006e24 VA: 0x759861ee24
	public override ValueTask WriteAsync(ReadOnlyMemory`1 buffer, CancellationToken cancellationToken) { }
	// RVA: 0x60070e4 VA: 0x759861f0e4
	public override Void WriteByte(Byte value) { }
}
```