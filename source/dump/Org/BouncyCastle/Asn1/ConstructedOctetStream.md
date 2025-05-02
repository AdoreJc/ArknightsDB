# ConstructedOctetStream

**Namespace:** `Org.BouncyCastle.Asn1`


## Fields

- `Boolean _first`

- `Stream _currentStream`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
internal class ConstructedOctetStream : BaseInputStream
{
	private readonly Asn1StreamParser _parser; // 0x30
	private Boolean _first; // 0x38
	private Stream _currentStream; // 0x40


	// RVA: 0x659789c VA: 0x7598baf89c
	internal Void .ctor(Asn1StreamParser parser) { }
	// RVA: 0x6599cdc VA: 0x7598bb1cdc
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6599f30 VA: 0x7598bb1f30
	public override Int32 ReadByte() { }
}
```