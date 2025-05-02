# SecT571R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT571R1Curve : AbstractF2mCurve
{
	private const Int32 SecT571R1_DEFAULT_COORDS; // 0x0
	protected readonly SecT571R1Point m_infinity; // 0x58
	internal static readonly SecT571FieldElement SecT571R1_B; // 0x0
	internal static readonly SecT571FieldElement SecT571R1_B_SQRT; // 0x8

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64ca254 VA: 0x7598ae2254
	public Void .ctor() { }
	// RVA: 0x64ca424 VA: 0x7598ae2424
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64ca47c VA: 0x7598ae247c
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64ca488 VA: 0x7598ae2488
	public override ECPoint get_Infinity() { }
	// RVA: 0x64ca490 VA: 0x7598ae2490
	public override Int32 get_FieldSize() { }
	// RVA: 0x64ca498 VA: 0x7598ae2498
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64ca4f8 VA: 0x7598ae24f8
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64ca60c VA: 0x7598ae260c
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64ca6ac VA: 0x7598ae26ac
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64ca6b4 VA: 0x7598ae26b4
	public virtual Int32 get_M() { }
	// RVA: 0x64ca6bc VA: 0x7598ae26bc
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64ca6c4 VA: 0x7598ae26c4
	public virtual Int32 get_K1() { }
	// RVA: 0x64ca6cc VA: 0x7598ae26cc
	public virtual Int32 get_K2() { }
	// RVA: 0x64ca6d4 VA: 0x7598ae26d4
	public virtual Int32 get_K3() { }
	// RVA: 0x64ca6dc VA: 0x7598ae26dc
	private static Void .cctor() { }
}
```