# SecT283R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT283R1Curve : AbstractF2mCurve
{
	private const Int32 SecT283R1_DEFAULT_COORDS; // 0x0
	protected readonly SecT283R1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64c0d1c VA: 0x7598ad8d1c
	public Void .ctor() { }
	// RVA: 0x64c0f1c VA: 0x7598ad8f1c
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64c0f74 VA: 0x7598ad8f74
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64c0f80 VA: 0x7598ad8f80
	public override ECPoint get_Infinity() { }
	// RVA: 0x64c0f88 VA: 0x7598ad8f88
	public override Int32 get_FieldSize() { }
	// RVA: 0x64c0f90 VA: 0x7598ad8f90
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64c0ff4 VA: 0x7598ad8ff4
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64c1108 VA: 0x7598ad9108
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64c11a8 VA: 0x7598ad91a8
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64c11b0 VA: 0x7598ad91b0
	public virtual Int32 get_M() { }
	// RVA: 0x64c11b8 VA: 0x7598ad91b8
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64c11c0 VA: 0x7598ad91c0
	public virtual Int32 get_K1() { }
	// RVA: 0x64c11c8 VA: 0x7598ad91c8
	public virtual Int32 get_K2() { }
	// RVA: 0x64c11d0 VA: 0x7598ad91d0
	public virtual Int32 get_K3() { }
}
```