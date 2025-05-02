# DHValidationParms

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Properties

- `DerBitString Seed`

- `DerInteger PgenCounter`


## Methods

- `DerBitString get_Seed()`

- `DerInteger get_PgenCounter()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class DHValidationParms : Asn1Encodable
{
	private readonly DerBitString seed; // 0x10
	private readonly DerInteger pgenCounter; // 0x18

	public DerBitString Seed { get; }
	public DerInteger PgenCounter { get; }

	// RVA: 0x65a5b9c VA: 0x7598bbdb9c
	public static DHValidationParms GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x65a554c VA: 0x7598bbd54c
	public static DHValidationParms GetInstance(Object obj) { }
	// RVA: 0x65a5d34 VA: 0x7598bbdd34
	public Void .ctor(DerBitString seed, DerInteger pgenCounter) { }
	// RVA: 0x65a5bb4 VA: 0x7598bbdbb4
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65a5df0 VA: 0x7598bbddf0
	public DerBitString get_Seed() { }
	// RVA: 0x65a5df8 VA: 0x7598bbddf8
	public DerInteger get_PgenCounter() { }
	// RVA: 0x65a5e00 VA: 0x7598bbde00
	public override Asn1Object ToAsn1Object() { }
}
```