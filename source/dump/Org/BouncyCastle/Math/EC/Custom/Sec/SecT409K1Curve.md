# SecT409K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT409K1Curve : AbstractF2mCurve
{
	private const Int32 SecT409K1_DEFAULT_COORDS; // 0x0
	protected readonly SecT409K1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64c3ecc VA: 0x7598adbecc
	public Void .ctor() { }
	// RVA: 0x64c4090 VA: 0x7598adc090
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64c40e8 VA: 0x7598adc0e8
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64c40f4 VA: 0x7598adc0f4
	protected override ECMultiplier CreateDefaultMultiplier() { }
	// RVA: 0x64c4150 VA: 0x7598adc150
	public override ECPoint get_Infinity() { }
	// RVA: 0x64c4158 VA: 0x7598adc158
	public override Int32 get_FieldSize() { }
	// RVA: 0x64c4160 VA: 0x7598adc160
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64c41c0 VA: 0x7598adc1c0
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64c42d4 VA: 0x7598adc2d4
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64c4374 VA: 0x7598adc374
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64c437c VA: 0x7598adc37c
	public virtual Int32 get_M() { }
	// RVA: 0x64c4384 VA: 0x7598adc384
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64c438c VA: 0x7598adc38c
	public virtual Int32 get_K1() { }
	// RVA: 0x64c4394 VA: 0x7598adc394
	public virtual Int32 get_K2() { }
	// RVA: 0x64c439c VA: 0x7598adc39c
	public virtual Int32 get_K3() { }
}
```