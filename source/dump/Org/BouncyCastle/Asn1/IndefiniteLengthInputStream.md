# IndefiniteLengthInputStream

**Namespace:** `Org.BouncyCastle.Asn1`


## Fields

- `Int32 _lookAhead`

- `Boolean _eofOn00`


## Methods

- `Boolean CheckForEof()`

- `Int32 RequireByte()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
internal class IndefiniteLengthInputStream : LimitedInputStream
{
	private Int32 _lookAhead; // 0x3c
	private Boolean _eofOn00; // 0x40


	// RVA: 0x65a4380 VA: 0x7598bbc380
	internal Void .ctor(Stream inStream, Int32 limit) { }
	// RVA: 0x65a451c VA: 0x7598bbc51c
	internal Void SetEofOn00(Boolean eofOn00) { }
	// RVA: 0x65a4478 VA: 0x7598bbc478
	private Boolean CheckForEof() { }
	// RVA: 0x65a4530 VA: 0x7598bbc530
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x65a4638 VA: 0x7598bbc638
	public override Int32 ReadByte() { }
	// RVA: 0x65a4410 VA: 0x7598bbc410
	private Int32 RequireByte() { }
}
```