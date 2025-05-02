# X9ECParameters

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Fields

- `X9FieldID fieldID`

- `ECCurve curve`

- `X9ECPoint g`

- `BigInteger n`

- `BigInteger h`


## Properties

- `ECCurve Curve`

- `ECPoint G`

- `BigInteger N`

- `BigInteger H`

- `X9Curve CurveEntry`

- `X9FieldID FieldIDEntry`

- `X9ECPoint BaseEntry`


## Methods

- `ECCurve get_Curve()`

- `ECPoint get_G()`

- `BigInteger get_N()`

- `BigInteger get_H()`

- `X9Curve get_CurveEntry()`

- `X9FieldID get_FieldIDEntry()`

- `X9ECPoint get_BaseEntry()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class X9ECParameters : Asn1Encodable
{
	private X9FieldID fieldID; // 0x10
	private ECCurve curve; // 0x18
	private X9ECPoint g; // 0x20
	private BigInteger n; // 0x28
	private BigInteger h; // 0x30
	private Byte[] seed; // 0x38

	public ECCurve Curve { get; }
	public ECPoint G { get; }
	public BigInteger N { get; }
	public BigInteger H { get; }
	public X9Curve CurveEntry { get; }
	public X9FieldID FieldIDEntry { get; }
	public X9ECPoint BaseEntry { get; }

	// RVA: 0x65accd4 VA: 0x7598bc4cd4
	public static X9ECParameters GetInstance(Object obj) { }
	// RVA: 0x65acd78 VA: 0x7598bc4d78
	public Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65ad280 VA: 0x7598bc5280
	public Void .ctor(ECCurve curve, ECPoint g, BigInteger n) { }
	// RVA: 0x65ad330 VA: 0x7598bc5330
	public Void .ctor(ECCurve curve, X9ECPoint g, BigInteger n, BigInteger h) { }
	// RVA: 0x65ad338 VA: 0x7598bc5338
	public Void .ctor(ECCurve curve, ECPoint g, BigInteger n, BigInteger h) { }
	// RVA: 0x65ad28c VA: 0x7598bc528c
	public Void .ctor(ECCurve curve, ECPoint g, BigInteger n, BigInteger h, Byte[] seed) { }
	// RVA: 0x65a797c VA: 0x7598bbf97c
	public Void .ctor(ECCurve curve, X9ECPoint g, BigInteger n, BigInteger h, Byte[] seed) { }
	// RVA: 0x65ad860 VA: 0x7598bc5860
	public ECCurve get_Curve() { }
	// RVA: 0x65ad868 VA: 0x7598bc5868
	public ECPoint get_G() { }
	// RVA: 0x65ad908 VA: 0x7598bc5908
	public BigInteger get_N() { }
	// RVA: 0x65ad910 VA: 0x7598bc5910
	public BigInteger get_H() { }
	// RVA: 0x65ad918 VA: 0x7598bc5918
	public Byte[] GetSeed() { }
	// RVA: 0x65ad920 VA: 0x7598bc5920
	public X9Curve get_CurveEntry() { }
	// RVA: 0x65ad98c VA: 0x7598bc598c
	public X9FieldID get_FieldIDEntry() { }
	// RVA: 0x65ad994 VA: 0x7598bc5994
	public X9ECPoint get_BaseEntry() { }
	// RVA: 0x65ad99c VA: 0x7598bc599c
	public override Asn1Object ToAsn1Object() { }
}
```