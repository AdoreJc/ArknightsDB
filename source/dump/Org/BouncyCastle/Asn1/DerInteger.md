# DerInteger

**Namespace:** `Org.BouncyCastle.Asn1`


## Properties

- `BigInteger Value`

- `BigInteger PositiveValue`


## Methods

- `BigInteger get_Value()`

- `BigInteger get_PositiveValue()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerInteger : Asn1Object
{
	private readonly Byte[] bytes; // 0x10

	public BigInteger Value { get; }
	public BigInteger PositiveValue { get; }

	// RVA: 0x659e824 VA: 0x7598bb6824
	public static DerInteger GetInstance(Object obj) { }
	// RVA: 0x659e914 VA: 0x7598bb6914
	public static DerInteger GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x659ea48 VA: 0x7598bb6a48
	public Void .ctor(Int32 value) { }
	// RVA: 0x659ead8 VA: 0x7598bb6ad8
	public Void .ctor(BigInteger value) { }
	// RVA: 0x6590ba0 VA: 0x7598ba8ba0
	public Void .ctor(Byte[] bytes) { }
	// RVA: 0x659eb64 VA: 0x7598bb6b64
	public BigInteger get_Value() { }
	// RVA: 0x659ebcc VA: 0x7598bb6bcc
	public BigInteger get_PositiveValue() { }
	// RVA: 0x659ec38 VA: 0x7598bb6c38
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659ec5c VA: 0x7598bb6c5c
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x659ec68 VA: 0x7598bb6c68
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659ed04 VA: 0x7598bb6d04
	public override String ToString() { }
}
```