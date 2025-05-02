# SecT233K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT233K1Curve : AbstractF2mCurve
{
	private const Int32 SecT233K1_DEFAULT_COORDS; // 0x0
	protected readonly SecT233K1Point m_infinity; // 0x58

	public override Int32 FieldSize { get; }
	public override ECPoint Infinity { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64b6f98 VA: 0x7598acef98
	public Void .ctor() { }
	// RVA: 0x64b715c VA: 0x7598acf15c
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64b71b4 VA: 0x7598acf1b4
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64b71c0 VA: 0x7598acf1c0
	protected override ECMultiplier CreateDefaultMultiplier() { }
	// RVA: 0x64b721c VA: 0x7598acf21c
	public override Int32 get_FieldSize() { }
	// RVA: 0x64b7224 VA: 0x7598acf224
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64b7284 VA: 0x7598acf284
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64b7398 VA: 0x7598acf398
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64b7438 VA: 0x7598acf438
	public override ECPoint get_Infinity() { }
	// RVA: 0x64b7440 VA: 0x7598acf440
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64b7448 VA: 0x7598acf448
	public virtual Int32 get_M() { }
	// RVA: 0x64b7450 VA: 0x7598acf450
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64b7458 VA: 0x7598acf458
	public virtual Int32 get_K1() { }
	// RVA: 0x64b7460 VA: 0x7598acf460
	public virtual Int32 get_K2() { }
	// RVA: 0x64b7468 VA: 0x7598acf468
	public virtual Int32 get_K3() { }
}
```