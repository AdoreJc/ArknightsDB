# SecT163R2Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT163R2Curve : AbstractF2mCurve
{
	private const Int32 SecT163R2_DEFAULT_COORDS; // 0x0
	protected readonly SecT163R2Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64af010 VA: 0x7598ac7010
	public Void .ctor() { }
	// RVA: 0x64af210 VA: 0x7598ac7210
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64af268 VA: 0x7598ac7268
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64af274 VA: 0x7598ac7274
	public override ECPoint get_Infinity() { }
	// RVA: 0x64af27c VA: 0x7598ac727c
	public override Int32 get_FieldSize() { }
	// RVA: 0x64af284 VA: 0x7598ac7284
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64af2e4 VA: 0x7598ac72e4
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64af3f8 VA: 0x7598ac73f8
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64af498 VA: 0x7598ac7498
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64af4a0 VA: 0x7598ac74a0
	public virtual Int32 get_M() { }
	// RVA: 0x64af4a8 VA: 0x7598ac74a8
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64af4b0 VA: 0x7598ac74b0
	public virtual Int32 get_K1() { }
	// RVA: 0x64af4b8 VA: 0x7598ac74b8
	public virtual Int32 get_K2() { }
	// RVA: 0x64af4c0 VA: 0x7598ac74c0
	public virtual Int32 get_K3() { }
}
```