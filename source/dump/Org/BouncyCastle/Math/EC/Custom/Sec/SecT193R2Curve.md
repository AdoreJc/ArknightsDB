# SecT193R2Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT193R2Curve : AbstractF2mCurve
{
	private const Int32 SecT193R2_DEFAULT_COORDS; // 0x0
	protected readonly SecT193R2Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64b3a90 VA: 0x7598acba90
	public Void .ctor() { }
	// RVA: 0x64b3cd0 VA: 0x7598acbcd0
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64b3d28 VA: 0x7598acbd28
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64b3d34 VA: 0x7598acbd34
	public override ECPoint get_Infinity() { }
	// RVA: 0x64b3d3c VA: 0x7598acbd3c
	public override Int32 get_FieldSize() { }
	// RVA: 0x64b3d44 VA: 0x7598acbd44
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64b3da4 VA: 0x7598acbda4
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64b3eb8 VA: 0x7598acbeb8
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64b3f58 VA: 0x7598acbf58
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64b3f60 VA: 0x7598acbf60
	public virtual Int32 get_M() { }
	// RVA: 0x64b3f68 VA: 0x7598acbf68
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64b3f70 VA: 0x7598acbf70
	public virtual Int32 get_K1() { }
	// RVA: 0x64b3f78 VA: 0x7598acbf78
	public virtual Int32 get_K2() { }
	// RVA: 0x64b3f80 VA: 0x7598acbf80
	public virtual Int32 get_K3() { }
}
```