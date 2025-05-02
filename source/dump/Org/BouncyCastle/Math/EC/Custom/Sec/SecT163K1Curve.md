# SecT163K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT163K1Curve : AbstractF2mCurve
{
	private const Int32 SecT163K1_DEFAULT_COORDS; // 0x0
	protected readonly SecT163K1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64ac07c VA: 0x7598ac407c
	public Void .ctor() { }
	// RVA: 0x64ac224 VA: 0x7598ac4224
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64ac27c VA: 0x7598ac427c
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64ac288 VA: 0x7598ac4288
	protected override ECMultiplier CreateDefaultMultiplier() { }
	// RVA: 0x64ac2e4 VA: 0x7598ac42e4
	public override ECPoint get_Infinity() { }
	// RVA: 0x64ac2ec VA: 0x7598ac42ec
	public override Int32 get_FieldSize() { }
	// RVA: 0x64ac2f4 VA: 0x7598ac42f4
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64ac354 VA: 0x7598ac4354
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64ac468 VA: 0x7598ac4468
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64ac508 VA: 0x7598ac4508
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64ac510 VA: 0x7598ac4510
	public virtual Int32 get_M() { }
	// RVA: 0x64ac518 VA: 0x7598ac4518
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64ac520 VA: 0x7598ac4520
	public virtual Int32 get_K1() { }
	// RVA: 0x64ac528 VA: 0x7598ac4528
	public virtual Int32 get_K2() { }
	// RVA: 0x64ac530 VA: 0x7598ac4530
	public virtual Int32 get_K3() { }
}
```