# DefiniteLengthInputStream

**Namespace:** `Org.BouncyCastle.Asn1`


## Fields

- `Int32 _remaining`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
internal class DefiniteLengthInputStream : LimitedInputStream
{
	private static readonly Byte[] EmptyBytes; // 0x0
	private readonly Int32 _originalLength; // 0x3c
	private Int32 _remaining; // 0x40

	internal Int32 Remaining { get; }

	// RVA: 0x658e10c VA: 0x7598ba610c
	internal Void .ctor(Stream inStream, Int32 length) { }
	// RVA: 0x659a0e0 VA: 0x7598bb20e0
	internal Int32 get_Remaining() { }
	// RVA: 0x659a0e8 VA: 0x7598bb20e8
	public override Int32 ReadByte() { }
	// RVA: 0x659a214 VA: 0x7598bb2214
	public override Int32 Read(Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x65901a8 VA: 0x7598ba81a8
	internal Void ReadAllIntoByteArray(Byte[] buf) { }
	// RVA: 0x658e1bc VA: 0x7598ba61bc
	internal Byte[] ToArray() { }
	// RVA: 0x659a3b0 VA: 0x7598bb23b0
	private static Void .cctor() { }
}
```