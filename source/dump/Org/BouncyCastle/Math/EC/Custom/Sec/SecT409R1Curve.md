# SecT409R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT409R1Curve : AbstractF2mCurve
{
	private const Int32 SecT409R1_DEFAULT_COORDS; // 0x0
	protected readonly SecT409R1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64c561c VA: 0x7598add61c
	public Void .ctor() { }
	// RVA: 0x64c581c VA: 0x7598add81c
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64c5874 VA: 0x7598add874
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64c5880 VA: 0x7598add880
	public override ECPoint get_Infinity() { }
	// RVA: 0x64c5888 VA: 0x7598add888
	public override Int32 get_FieldSize() { }
	// RVA: 0x64c5890 VA: 0x7598add890
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64c58f0 VA: 0x7598add8f0
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64c5a04 VA: 0x7598adda04
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64c5aa4 VA: 0x7598addaa4
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64c5aac VA: 0x7598addaac
	public virtual Int32 get_M() { }
	// RVA: 0x64c5ab4 VA: 0x7598addab4
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64c5abc VA: 0x7598addabc
	public virtual Int32 get_K1() { }
	// RVA: 0x64c5ac4 VA: 0x7598addac4
	public virtual Int32 get_K2() { }
	// RVA: 0x64c5acc VA: 0x7598addacc
	public virtual Int32 get_K3() { }
}
```