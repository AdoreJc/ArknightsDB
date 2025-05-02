# X9Curve

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Properties

- `ECCurve Curve`


## Methods

- `ECCurve get_Curve()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class X9Curve : Asn1Encodable
{
	private readonly ECCurve curve; // 0x10
	private readonly Byte[] seed; // 0x18
	private readonly DerObjectIdentifier fieldIdentifier; // 0x20

	public ECCurve Curve { get; }

	// RVA: 0x65abcc0 VA: 0x7598bc3cc0
	public Void .ctor(ECCurve curve) { }
	// RVA: 0x65abcc8 VA: 0x7598bc3cc8
	public Void .ctor(ECCurve curve, Byte[] seed) { }
	// RVA: 0x65abe3c VA: 0x7598bc3e3c
	public Void .ctor(X9FieldID fieldID, Asn1Sequence seq) { }
	// RVA: 0x65ac8e4 VA: 0x7598bc48e4
	public ECCurve get_Curve() { }
	// RVA: 0x65ac8ec VA: 0x7598bc48ec
	public Byte[] GetSeed() { }
	// RVA: 0x65ac8f8 VA: 0x7598bc48f8
	public override Asn1Object ToAsn1Object() { }
}
```