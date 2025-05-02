# DHPublicKey

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Properties

- `DerInteger Y`


## Methods

- `DerInteger get_Y()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class DHPublicKey : Asn1Encodable
{
	private readonly DerInteger y; // 0x10

	public DerInteger Y { get; }

	// RVA: 0x65a596c VA: 0x7598bbd96c
	public static DHPublicKey GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x65a5984 VA: 0x7598bbd984
	public static DHPublicKey GetInstance(Object obj) { }
	// RVA: 0x65a5b0c VA: 0x7598bbdb0c
	public Void .ctor(DerInteger y) { }
	// RVA: 0x65a5b8c VA: 0x7598bbdb8c
	public DerInteger get_Y() { }
	// RVA: 0x65a5b94 VA: 0x7598bbdb94
	public override Asn1Object ToAsn1Object() { }
}
```