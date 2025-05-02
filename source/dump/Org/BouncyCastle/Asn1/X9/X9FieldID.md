# X9FieldID

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Properties

- `DerObjectIdentifier Identifier`

- `Asn1Object Parameters`


## Methods

- `DerObjectIdentifier get_Identifier()`

- `Asn1Object get_Parameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class X9FieldID : Asn1Encodable
{
	private readonly DerObjectIdentifier id; // 0x10
	private readonly Asn1Object parameters; // 0x18

	public DerObjectIdentifier Identifier { get; }
	public Asn1Object Parameters { get; }

	// RVA: 0x65ad348 VA: 0x7598bc5348
	public Void .ctor(BigInteger primeP) { }
	// RVA: 0x65ad408 VA: 0x7598bc5408
	public Void .ctor(Int32 m, Int32 k1) { }
	// RVA: 0x65ad414 VA: 0x7598bc5414
	public Void .ctor(Int32 m, Int32 k1, Int32 k2, Int32 k3) { }
	// RVA: 0x65adfd0 VA: 0x7598bc5fd0
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65ad19c VA: 0x7598bc519c
	public static X9FieldID GetInstance(Object obj) { }
	// RVA: 0x65ae0a0 VA: 0x7598bc60a0
	public DerObjectIdentifier get_Identifier() { }
	// RVA: 0x65ae0a8 VA: 0x7598bc60a8
	public Asn1Object get_Parameters() { }
	// RVA: 0x65ae0b0 VA: 0x7598bc60b0
	public override Asn1Object ToAsn1Object() { }
}
```