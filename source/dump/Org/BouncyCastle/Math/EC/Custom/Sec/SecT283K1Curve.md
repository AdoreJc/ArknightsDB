# SecT283K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT283K1Curve : AbstractF2mCurve
{
	private const Int32 SecT283K1_DEFAULT_COORDS; // 0x0
	protected readonly SecT283K1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64bf5cc VA: 0x7598ad75cc
	public Void .ctor() { }
	// RVA: 0x64bf790 VA: 0x7598ad7790
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64bf7e8 VA: 0x7598ad77e8
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64bf7f4 VA: 0x7598ad77f4
	protected override ECMultiplier CreateDefaultMultiplier() { }
	// RVA: 0x64bf850 VA: 0x7598ad7850
	public override ECPoint get_Infinity() { }
	// RVA: 0x64bf858 VA: 0x7598ad7858
	public override Int32 get_FieldSize() { }
	// RVA: 0x64bf860 VA: 0x7598ad7860
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64bf8c0 VA: 0x7598ad78c0
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64bf9d4 VA: 0x7598ad79d4
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64bfa74 VA: 0x7598ad7a74
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64bfa7c VA: 0x7598ad7a7c
	public virtual Int32 get_M() { }
	// RVA: 0x64bfa84 VA: 0x7598ad7a84
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64bfa8c VA: 0x7598ad7a8c
	public virtual Int32 get_K1() { }
	// RVA: 0x64bfa94 VA: 0x7598ad7a94
	public virtual Int32 get_K2() { }
	// RVA: 0x64bfa9c VA: 0x7598ad7a9c
	public virtual Int32 get_K3() { }
}
```