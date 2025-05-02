# SecT193R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT193R1Curve : AbstractF2mCurve
{
	private const Int32 SecT193R1_DEFAULT_COORDS; // 0x0
	protected readonly SecT193R1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64b2218 VA: 0x7598aca218
	public Void .ctor() { }
	// RVA: 0x64b2458 VA: 0x7598aca458
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64b24b0 VA: 0x7598aca4b0
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64b24bc VA: 0x7598aca4bc
	public override ECPoint get_Infinity() { }
	// RVA: 0x64b24c4 VA: 0x7598aca4c4
	public override Int32 get_FieldSize() { }
	// RVA: 0x64b24cc VA: 0x7598aca4cc
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64b252c VA: 0x7598aca52c
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64b2640 VA: 0x7598aca640
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64b26e0 VA: 0x7598aca6e0
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64b26e8 VA: 0x7598aca6e8
	public virtual Int32 get_M() { }
	// RVA: 0x64b26f0 VA: 0x7598aca6f0
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64b26f8 VA: 0x7598aca6f8
	public virtual Int32 get_K1() { }
	// RVA: 0x64b2700 VA: 0x7598aca700
	public virtual Int32 get_K2() { }
	// RVA: 0x64b2708 VA: 0x7598aca708
	public virtual Int32 get_K3() { }
}
```