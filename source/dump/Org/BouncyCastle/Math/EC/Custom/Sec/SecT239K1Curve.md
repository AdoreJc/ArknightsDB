# SecT239K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT239K1Curve : AbstractF2mCurve
{
	private const Int32 SecT239K1_DEFAULT_COORDS; // 0x0
	protected readonly SecT239K1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64bbb2c VA: 0x7598ad3b2c
	public Void .ctor() { }
	// RVA: 0x64bbcf0 VA: 0x7598ad3cf0
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64bbd48 VA: 0x7598ad3d48
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64bbd54 VA: 0x7598ad3d54
	protected override ECMultiplier CreateDefaultMultiplier() { }
	// RVA: 0x64bbdb0 VA: 0x7598ad3db0
	public override ECPoint get_Infinity() { }
	// RVA: 0x64bbdb8 VA: 0x7598ad3db8
	public override Int32 get_FieldSize() { }
	// RVA: 0x64bbdc0 VA: 0x7598ad3dc0
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64bbe20 VA: 0x7598ad3e20
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64bbf34 VA: 0x7598ad3f34
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64bbfd4 VA: 0x7598ad3fd4
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64bbfdc VA: 0x7598ad3fdc
	public virtual Int32 get_M() { }
	// RVA: 0x64bbfe4 VA: 0x7598ad3fe4
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64bbfec VA: 0x7598ad3fec
	public virtual Int32 get_K1() { }
	// RVA: 0x64bbff4 VA: 0x7598ad3ff4
	public virtual Int32 get_K2() { }
	// RVA: 0x64bbffc VA: 0x7598ad3ffc
	public virtual Int32 get_K3() { }
}
```