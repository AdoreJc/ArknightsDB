# SecT131R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT131R1Curve : AbstractF2mCurve
{
	private const Int32 SecT131R1_DEFAULT_COORDS; // 0x0
	protected readonly SecT131R1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64a71c8 VA: 0x7598abf1c8
	public Void .ctor() { }
	// RVA: 0x64a7408 VA: 0x7598abf408
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64a7460 VA: 0x7598abf460
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64a746c VA: 0x7598abf46c
	public override ECPoint get_Infinity() { }
	// RVA: 0x64a7474 VA: 0x7598abf474
	public override Int32 get_FieldSize() { }
	// RVA: 0x64a747c VA: 0x7598abf47c
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64a74dc VA: 0x7598abf4dc
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64a75f0 VA: 0x7598abf5f0
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64a7690 VA: 0x7598abf690
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64a7698 VA: 0x7598abf698
	public virtual Int32 get_M() { }
	// RVA: 0x64a76a0 VA: 0x7598abf6a0
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64a76a8 VA: 0x7598abf6a8
	public virtual Int32 get_K1() { }
	// RVA: 0x64a76b0 VA: 0x7598abf6b0
	public virtual Int32 get_K2() { }
	// RVA: 0x64a76b8 VA: 0x7598abf6b8
	public virtual Int32 get_K3() { }
}
```