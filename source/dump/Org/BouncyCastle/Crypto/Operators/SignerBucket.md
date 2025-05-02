# SignerBucket

**Namespace:** `Org.BouncyCastle.Crypto.Operators`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Operators
internal class SignerBucket : Stream
{
	protected readonly ISigner signer; // 0x28

	public override Boolean CanRead { get; }
	public override Boolean CanWrite { get; }
	public override Boolean CanSeek { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x651f468 VA: 0x7598b37468
	public Void .ctor(ISigner signer) { }
	// RVA: 0x651f4dc VA: 0x7598b374dc
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x651f51c VA: 0x7598b3751c
	public override Int32 ReadByte() { }
	// RVA: 0x651f55c VA: 0x7598b3755c
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x651f638 VA: 0x7598b37638
	public override Void WriteByte(Byte b) { }
	// RVA: 0x651f6e4 VA: 0x7598b376e4
	public override Boolean get_CanRead() { }
	// RVA: 0x651f6ec VA: 0x7598b376ec
	public override Boolean get_CanWrite() { }
	// RVA: 0x651f6f4 VA: 0x7598b376f4
	public override Boolean get_CanSeek() { }
	// RVA: 0x651f6fc VA: 0x7598b376fc
	public override Int64 get_Length() { }
	// RVA: 0x651f704 VA: 0x7598b37704
	public override Int64 get_Position() { }
	// RVA: 0x651f744 VA: 0x7598b37744
	public override Void set_Position(Int64 value) { }
	// RVA: 0x651f784 VA: 0x7598b37784
	public override Void Flush() { }
	// RVA: 0x651f788 VA: 0x7598b37788
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x651f7c8 VA: 0x7598b377c8
	public override Void SetLength(Int64 length) { }
}
```