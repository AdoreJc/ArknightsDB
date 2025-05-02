# BerApplicationSpecificParser

**Namespace:** `Org.BouncyCastle.Asn1`


## Methods

- `IAsn1Convertible ReadObject()`

- `Asn1Object ToAsn1Object()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class BerApplicationSpecificParser : IAsn1ApplicationSpecificParser, IAsn1Convertible
{
	private readonly Int32 tag; // 0x10
	private readonly Asn1StreamParser parser; // 0x18


	// RVA: 0x658fb98 VA: 0x7598ba7b98
	internal Void .ctor(Int32 tag, Asn1StreamParser parser) { }
	// RVA: 0x6596494 VA: 0x7598bae494
	public IAsn1Convertible ReadObject() { }
	// RVA: 0x658fbd0 VA: 0x7598ba7bd0
	public Asn1Object ToAsn1Object() { }
}
```