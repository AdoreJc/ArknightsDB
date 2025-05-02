# SecT571K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT571K1Curve : AbstractF2mCurve
{
	private const Int32 SecT571K1_DEFAULT_COORDS; // 0x0
	protected readonly SecT571K1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64c8af4 VA: 0x7598ae0af4
	public Void .ctor() { }
	// RVA: 0x64c8cb8 VA: 0x7598ae0cb8
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64c8d10 VA: 0x7598ae0d10
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64c8d1c VA: 0x7598ae0d1c
	protected override ECMultiplier CreateDefaultMultiplier() { }
	// RVA: 0x64c8d78 VA: 0x7598ae0d78
	public override ECPoint get_Infinity() { }
	// RVA: 0x64c8d80 VA: 0x7598ae0d80
	public override Int32 get_FieldSize() { }
	// RVA: 0x64c8d88 VA: 0x7598ae0d88
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64c8de8 VA: 0x7598ae0de8
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64c8efc VA: 0x7598ae0efc
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64c8f9c VA: 0x7598ae0f9c
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64c8fa4 VA: 0x7598ae0fa4
	public virtual Int32 get_M() { }
	// RVA: 0x64c8fac VA: 0x7598ae0fac
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64c8fb4 VA: 0x7598ae0fb4
	public virtual Int32 get_K1() { }
	// RVA: 0x64c8fbc VA: 0x7598ae0fbc
	public virtual Int32 get_K2() { }
	// RVA: 0x64c8fc4 VA: 0x7598ae0fc4
	public virtual Int32 get_K3() { }
}
```