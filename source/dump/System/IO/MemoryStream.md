# MemoryStream

**Namespace:** `System.IO`


## Fields

- `Int32 _origin`

- `Int32 _position`

- `Int32 _length`

- `Int32 _capacity`

- `Boolean _expandable`

- `Boolean _writable`

- `Boolean _exposable`

- `Boolean _isOpen`


## Methods

- `Void EnsureNotClosed()`

- `Void EnsureWriteable()`

- `Boolean EnsureCapacity(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class MemoryStream : Stream
{
	private Byte[] _buffer; // 0x28
	private Int32 _origin; // 0x30
	private Int32 _position; // 0x34
	private Int32 _length; // 0x38
	private Int32 _capacity; // 0x3c
	private Boolean _expandable; // 0x40
	private Boolean _writable; // 0x41
	private Boolean _exposable; // 0x42
	private Boolean _isOpen; // 0x43
	private Task`1 _lastReadTask; // 0x48
	private const Int32 MemStreamMaxLength; // 0x0

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public virtual Int32 Capacity { get; set; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x5ffc8a8 VA: 0x75986148a8
	public Void .ctor() { }
	// RVA: 0x5ffc8b0 VA: 0x75986148b0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x5ffca24 VA: 0x7598614a24
	public Void .ctor(Byte[] buffer) { }
	// RVA: 0x5ffca2c VA: 0x7598614a2c
	public Void .ctor(Byte[] buffer, Boolean writable) { }
	// RVA: 0x5ffcb28 VA: 0x7598614b28
	public Void .ctor(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x5ffcb34 VA: 0x7598614b34
	public Void .ctor(Byte[] buffer, Int32 index, Int32 count, Boolean writable, Boolean publiclyVisible) { }
	// RVA: 0x5ffcd18 VA: 0x7598614d18
	public override Boolean get_CanRead() { }
	// RVA: 0x5ffcd20 VA: 0x7598614d20
	public override Boolean get_CanSeek() { }
	// RVA: 0x5ffcd28 VA: 0x7598614d28
	public override Boolean get_CanWrite() { }
	// RVA: 0x5ffcd30 VA: 0x7598614d30
	private Void EnsureNotClosed() { }
	// RVA: 0x5ffcd64 VA: 0x7598614d64
	private Void EnsureWriteable() { }
	// RVA: 0x5ffcda0 VA: 0x7598614da0
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x5ffcdf8 VA: 0x7598614df8
	private Boolean EnsureCapacity(Int32 value) { }
	// RVA: 0x5ffcea8 VA: 0x7598614ea8
	public override Void Flush() { }
	// RVA: 0x5ffceac VA: 0x7598614eac
	public override Task FlushAsync(CancellationToken cancellationToken) { }
	// RVA: 0x5ffd04c VA: 0x759861504c
	public virtual Byte[] GetBuffer() { }
	// RVA: 0x5ffd0b0 VA: 0x75986150b0
	internal Byte[] InternalGetBuffer() { }
	// RVA: 0x5ffd0b8 VA: 0x75986150b8
	internal Int32 InternalGetPosition() { }
	// RVA: 0x5ffd0c0 VA: 0x75986150c0
	internal Int32 InternalReadInt32() { }
	// RVA: 0x5ffd178 VA: 0x7598615178
	internal Int32 InternalEmulateRead(Int32 count) { }
	// RVA: 0x5ffd1b4 VA: 0x75986151b4
	public virtual Int32 get_Capacity() { }
	// RVA: 0x5ffd1d4 VA: 0x75986151d4
	public virtual Void set_Capacity(Int32 value) { }
	// RVA: 0x5ffd368 VA: 0x7598615368
	public override Int64 get_Length() { }
	// RVA: 0x5ffd38c VA: 0x759861538c
	public override Int64 get_Position() { }
	// RVA: 0x5ffd3ac VA: 0x75986153ac
	public override Void set_Position(Int64 value) { }
	// RVA: 0x5ffd47c VA: 0x759861547c
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ffd670 VA: 0x7598615670
	public override Int32 Read(Span`1 buffer) { }
	// RVA: 0x5ffdafc VA: 0x7598615afc
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x5ffde98 VA: 0x7598615e98
	public override ValueTask`1 ReadAsync(Memory`1 buffer, CancellationToken cancellationToken) { }
	// RVA: 0x5ffe220 VA: 0x7598616220
	public override Int32 ReadByte() { }
	// RVA: 0x5ffe278 VA: 0x7598616278
	public override Int64 Seek(Int64 offset, SeekOrigin loc) { }
	// RVA: 0x5ffe3d0 VA: 0x75986163d0
	public override Void SetLength(Int64 value) { }
	// RVA: 0x5ffe4b0 VA: 0x75986164b0
	public virtual Byte[] ToArray() { }
	// RVA: 0x5ffe58c VA: 0x759861658c
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ffe824 VA: 0x7598616824
	public override Void Write(ReadOnlySpan`1 buffer) { }
	// RVA: 0x5ffec3c VA: 0x7598616c3c
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x5ffef78 VA: 0x7598616f78
	public override ValueTask WriteAsync(ReadOnlyMemory`1 buffer, CancellationToken cancellationToken) { }
	// RVA: 0x5fff27c VA: 0x759861727c
	public override Void WriteByte(Byte value) { }
	// RVA: 0x5fff338 VA: 0x7598617338
	public virtual Void WriteTo(Stream stream) { }
}
```