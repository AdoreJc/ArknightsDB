# F2mCurve

**Namespace:** `Org.BouncyCastle.Math.EC`


## Properties

- `Int32 M`

- `Int32 K1`

- `Int32 K2`

- `Int32 K3`

- `BigInteger N`

- `BigInteger H`


## Methods

- `Int32 get_M()`

- `Boolean IsTrinomial()`

- `Int32 get_K1()`

- `Int32 get_K2()`

- `Int32 get_K3()`

- `BigInteger get_N()`

- `BigInteger get_H()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC
public class F2mCurve : AbstractF2mCurve
{
	private const Int32 F2M_DEFAULT_COORDS; // 0x0
	private readonly Int32 m; // 0x58
	private readonly Int32 k1; // 0x5c
	private readonly Int32 k2; // 0x60
	private readonly Int32 k3; // 0x64
	protected readonly F2mPoint m_infinity; // 0x68

	public override Int32 FieldSize { get; }
	public override ECPoint Infinity { get; }
	public Int32 M { get; }
	public Int32 K1 { get; }
	public Int32 K2 { get; }
	public Int32 K3 { get; }
	public BigInteger N { get; }
	public BigInteger H { get; }

	// RVA: 0x6731ddc VA: 0x7598d49ddc
	public Void .ctor(Int32 m, Int32 k, BigInteger a, BigInteger b) { }
	// RVA: 0x6732028 VA: 0x7598d4a028
	public Void .ctor(Int32 m, Int32 k, BigInteger a, BigInteger b, BigInteger order, BigInteger cofactor) { }
	// RVA: 0x673205c VA: 0x7598d4a05c
	public Void .ctor(Int32 m, Int32 k1, Int32 k2, Int32 k3, BigInteger a, BigInteger b) { }
	// RVA: 0x6731e0c VA: 0x7598d49e0c
	public Void .ctor(Int32 m, Int32 k1, Int32 k2, Int32 k3, BigInteger a, BigInteger b, BigInteger order, BigInteger cofactor) { }
	// RVA: 0x6732084 VA: 0x7598d4a084
	protected Void .ctor(Int32 m, Int32 k1, Int32 k2, Int32 k3, ECFieldElement a, ECFieldElement b, BigInteger order, BigInteger cofactor) { }
	// RVA: 0x67321a4 VA: 0x7598d4a1a4
	protected override ECCurve CloneCurve() { }
	// RVA: 0x6732258 VA: 0x7598d4a258
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x6732274 VA: 0x7598d4a274
	protected override ECMultiplier CreateDefaultMultiplier() { }
	// RVA: 0x67322fc VA: 0x7598d4a2fc
	public override Int32 get_FieldSize() { }
	// RVA: 0x6732304 VA: 0x7598d4a304
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x67325b4 VA: 0x7598d4a5b4
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6732704 VA: 0x7598d4a704
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x673279c VA: 0x7598d4a79c
	public override ECPoint get_Infinity() { }
	// RVA: 0x67327a4 VA: 0x7598d4a7a4
	public Int32 get_M() { }
	// RVA: 0x67327ac VA: 0x7598d4a7ac
	public Boolean IsTrinomial() { }
	// RVA: 0x67327cc VA: 0x7598d4a7cc
	public Int32 get_K1() { }
	// RVA: 0x67327d4 VA: 0x7598d4a7d4
	public Int32 get_K2() { }
	// RVA: 0x67327dc VA: 0x7598d4a7dc
	public Int32 get_K3() { }
	// RVA: 0x67327e4 VA: 0x7598d4a7e4
	public BigInteger get_N() { }
	// RVA: 0x67327ec VA: 0x7598d4a7ec
	public BigInteger get_H() { }
}
```