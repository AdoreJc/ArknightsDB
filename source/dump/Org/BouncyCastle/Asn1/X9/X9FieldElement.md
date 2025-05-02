# X9FieldElement

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Fields

- `ECFieldElement f`


## Properties

- `ECFieldElement Value`


## Methods

- `ECFieldElement get_Value()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class X9FieldElement : Asn1Encodable
{
	private ECFieldElement f; // 0x10

	public ECFieldElement Value { get; }

	// RVA: 0x65acca4 VA: 0x7598bc4ca4
	public Void .ctor(ECFieldElement f) { }
	// RVA: 0x65ac704 VA: 0x7598bc4704
	public Void .ctor(BigInteger p, Asn1OctetString s) { }
	// RVA: 0x65ac7e0 VA: 0x7598bc47e0
	public Void .ctor(Int32 m, Int32 k1, Int32 k2, Int32 k3, Asn1OctetString s) { }
	// RVA: 0x65ade04 VA: 0x7598bc5e04
	public ECFieldElement get_Value() { }
	// RVA: 0x65ade0c VA: 0x7598bc5e0c
	public override Asn1Object ToAsn1Object() { }
}
```