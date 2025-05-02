# DHDomainParameters

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Properties

- `DerInteger P`

- `DerInteger G`

- `DerInteger Q`

- `DerInteger J`

- `DHValidationParms ValidationParms`


## Methods

- `DerInteger get_P()`

- `DerInteger get_G()`

- `DerInteger get_Q()`

- `DerInteger get_J()`

- `DHValidationParms get_ValidationParms()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class DHDomainParameters : Asn1Encodable
{
	private readonly DerInteger p; // 0x10
	private readonly DerInteger g; // 0x18
	private readonly DerInteger q; // 0x20
	private readonly DerInteger j; // 0x28
	private readonly DHValidationParms validationParms; // 0x30

	public DerInteger P { get; }
	public DerInteger G { get; }
	public DerInteger Q { get; }
	public DerInteger J { get; }
	public DHValidationParms ValidationParms { get; }

	// RVA: 0x65a4f08 VA: 0x7598bbcf08
	public static DHDomainParameters GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x65a4f20 VA: 0x7598bbcf20
	public static DHDomainParameters GetInstance(Object obj) { }
	// RVA: 0x65a52cc VA: 0x7598bbd2cc
	public Void .ctor(DerInteger p, DerInteger g, DerInteger q, DerInteger j, DHValidationParms validationParms) { }
	// RVA: 0x65a50a8 VA: 0x7598bbd0a8
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65a53fc VA: 0x7598bbd3fc
	private static Asn1Encodable GetNext(IEnumerator e) { }
	// RVA: 0x65a570c VA: 0x7598bbd70c
	public DerInteger get_P() { }
	// RVA: 0x65a5714 VA: 0x7598bbd714
	public DerInteger get_G() { }
	// RVA: 0x65a571c VA: 0x7598bbd71c
	public DerInteger get_Q() { }
	// RVA: 0x65a5724 VA: 0x7598bbd724
	public DerInteger get_J() { }
	// RVA: 0x65a572c VA: 0x7598bbd72c
	public DHValidationParms get_ValidationParms() { }
	// RVA: 0x65a5734 VA: 0x7598bbd734
	public override Asn1Object ToAsn1Object() { }
}
```