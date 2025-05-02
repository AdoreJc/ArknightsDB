# FilterStream

**Namespace:** `Org.BouncyCastle.Utilities.IO`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.IO
public class FilterStream : Stream
{
	protected readonly Stream s; // 0x28

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x66f6cf0 VA: 0x7598d0ecf0
	public Void .ctor(Stream s) { }
	// RVA: 0x66f6d64 VA: 0x7598d0ed64
	public override Boolean get_CanRead() { }
	// RVA: 0x66f6d84 VA: 0x7598d0ed84
	public override Boolean get_CanSeek() { }
	// RVA: 0x66f6da4 VA: 0x7598d0eda4
	public override Boolean get_CanWrite() { }
	// RVA: 0x66f6dc4 VA: 0x7598d0edc4
	public override Int64 get_Length() { }
	// RVA: 0x66f6de4 VA: 0x7598d0ede4
	public override Int64 get_Position() { }
	// RVA: 0x66f6e04 VA: 0x7598d0ee04
	public override Void set_Position(Int64 value) { }
	// RVA: 0x66f6e28 VA: 0x7598d0ee28
	public override Void Close() { }
	// RVA: 0x66f6e90 VA: 0x7598d0ee90
	public override Void Flush() { }
	// RVA: 0x66f6eb4 VA: 0x7598d0eeb4
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x66f6ed8 VA: 0x7598d0eed8
	public override Void SetLength(Int64 value) { }
	// RVA: 0x66f6efc VA: 0x7598d0eefc
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x66f6f20 VA: 0x7598d0ef20
	public override Int32 ReadByte() { }
	// RVA: 0x66f6f44 VA: 0x7598d0ef44
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x66f6f68 VA: 0x7598d0ef68
	public override Void WriteByte(Byte value) { }
}
```