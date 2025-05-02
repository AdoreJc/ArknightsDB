# SecT131R2Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT131R2Curve : AbstractF2mCurve
{
	private const Int32 SecT131R2_DEFAULT_COORDS; // 0x0
	protected readonly SecT131R2Point m_infinity; // 0x58

	public override Int32 FieldSize { get; }
	public override ECPoint Infinity { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64a8a40 VA: 0x7598ac0a40
	public Void .ctor() { }
	// RVA: 0x64a8c80 VA: 0x7598ac0c80
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64a8cd8 VA: 0x7598ac0cd8
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64a8ce4 VA: 0x7598ac0ce4
	public override Int32 get_FieldSize() { }
	// RVA: 0x64a8cec VA: 0x7598ac0cec
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64a8d4c VA: 0x7598ac0d4c
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64a8e60 VA: 0x7598ac0e60
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64a8f00 VA: 0x7598ac0f00
	public override ECPoint get_Infinity() { }
	// RVA: 0x64a8f08 VA: 0x7598ac0f08
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64a8f10 VA: 0x7598ac0f10
	public virtual Int32 get_M() { }
	// RVA: 0x64a8f18 VA: 0x7598ac0f18
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64a8f20 VA: 0x7598ac0f20
	public virtual Int32 get_K1() { }
	// RVA: 0x64a8f28 VA: 0x7598ac0f28
	public virtual Int32 get_K2() { }
	// RVA: 0x64a8f30 VA: 0x7598ac0f30
	public virtual Int32 get_K3() { }
}
```