# SecT113R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Methods

- `ECFieldElement SolveQuadraticEquation(ECFieldElement)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT113R1Curve : AbstractF2mCurve
{
	private const Int32 SecT113R1_DEFAULT_COORDS; // 0x0
	protected readonly SecT113R1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64a1f1c VA: 0x7598ab9f1c
	public Void .ctor() { }
	// RVA: 0x64a215c VA: 0x7598aba15c
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64a21b4 VA: 0x7598aba1b4
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64a21c0 VA: 0x7598aba1c0
	public override ECPoint get_Infinity() { }
	// RVA: 0x64a21c8 VA: 0x7598aba1c8
	public override Int32 get_FieldSize() { }
	// RVA: 0x64a21d0 VA: 0x7598aba1d0
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64a2230 VA: 0x7598aba230
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64a2344 VA: 0x7598aba344
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64a23e4 VA: 0x7598aba3e4
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64a23ec VA: 0x7598aba3ec
	protected override ECPoint DecompressPoint(Int32 yTilde, BigInteger X1) { }
	// RVA: 0x64a2600 VA: 0x7598aba600
	private ECFieldElement SolveQuadraticEquation(ECFieldElement beta) { }
	// RVA: 0x64a2810 VA: 0x7598aba810
	public virtual Int32 get_M() { }
	// RVA: 0x64a2818 VA: 0x7598aba818
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64a2820 VA: 0x7598aba820
	public virtual Int32 get_K1() { }
	// RVA: 0x64a2828 VA: 0x7598aba828
	public virtual Int32 get_K2() { }
	// RVA: 0x64a2830 VA: 0x7598aba830
	public virtual Int32 get_K3() { }
}
```