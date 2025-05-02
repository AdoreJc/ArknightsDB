# FilterStream

**Namespace:** `Org.BouncyCastle.Asn1.Utilities`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Utilities
public class FilterStream : Stream
{
	protected readonly Stream s; // 0x28

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x65c78c0 VA: 0x7598bdf8c0
	public Void .ctor(Stream s) { }
	// RVA: 0x65c7934 VA: 0x7598bdf934
	public override Boolean get_CanRead() { }
	// RVA: 0x65c7954 VA: 0x7598bdf954
	public override Boolean get_CanSeek() { }
	// RVA: 0x65c7974 VA: 0x7598bdf974
	public override Boolean get_CanWrite() { }
	// RVA: 0x65c7994 VA: 0x7598bdf994
	public override Int64 get_Length() { }
	// RVA: 0x65c79b4 VA: 0x7598bdf9b4
	public override Int64 get_Position() { }
	// RVA: 0x65c79d4 VA: 0x7598bdf9d4
	public override Void set_Position(Int64 value) { }
	// RVA: 0x65c79f8 VA: 0x7598bdf9f8
	public override Void Close() { }
	// RVA: 0x65c7a60 VA: 0x7598bdfa60
	public override Void Flush() { }
	// RVA: 0x65c7a84 VA: 0x7598bdfa84
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x65c7aa8 VA: 0x7598bdfaa8
	public override Void SetLength(Int64 value) { }
	// RVA: 0x65c7acc VA: 0x7598bdfacc
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x65c7af0 VA: 0x7598bdfaf0
	public override Int32 ReadByte() { }
	// RVA: 0x65c7b14 VA: 0x7598bdfb14
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x65c7b38 VA: 0x7598bdfb38
	public override Void WriteByte(Byte value) { }
}
```