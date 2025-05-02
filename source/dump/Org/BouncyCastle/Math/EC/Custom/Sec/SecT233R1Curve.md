# SecT233R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT233R1Curve : AbstractF2mCurve
{
	private const Int32 SecT233R1_DEFAULT_COORDS; // 0x0
	protected readonly SecT233R1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64b86e8 VA: 0x7598ad06e8
	public Void .ctor() { }
	// RVA: 0x64b88e8 VA: 0x7598ad08e8
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64b8940 VA: 0x7598ad0940
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64b894c VA: 0x7598ad094c
	public override ECPoint get_Infinity() { }
	// RVA: 0x64b8954 VA: 0x7598ad0954
	public override Int32 get_FieldSize() { }
	// RVA: 0x64b895c VA: 0x7598ad095c
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64b89bc VA: 0x7598ad09bc
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64b8ad0 VA: 0x7598ad0ad0
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64b8b70 VA: 0x7598ad0b70
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64b8b78 VA: 0x7598ad0b78
	public virtual Int32 get_M() { }
	// RVA: 0x64b8b80 VA: 0x7598ad0b80
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64b8b88 VA: 0x7598ad0b88
	public virtual Int32 get_K1() { }
	// RVA: 0x64b8b90 VA: 0x7598ad0b90
	public virtual Int32 get_K2() { }
	// RVA: 0x64b8b98 VA: 0x7598ad0b98
	public virtual Int32 get_K3() { }
}
```