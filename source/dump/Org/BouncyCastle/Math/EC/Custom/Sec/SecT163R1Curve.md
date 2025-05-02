# SecT163R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT163R1Curve : AbstractF2mCurve
{
	private const Int32 SecT163R1_DEFAULT_COORDS; // 0x0
	protected readonly SecT163R1Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64ad798 VA: 0x7598ac5798
	public Void .ctor() { }
	// RVA: 0x64ad9d8 VA: 0x7598ac59d8
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64ada30 VA: 0x7598ac5a30
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64ada3c VA: 0x7598ac5a3c
	public override ECPoint get_Infinity() { }
	// RVA: 0x64ada44 VA: 0x7598ac5a44
	public override Int32 get_FieldSize() { }
	// RVA: 0x64ada4c VA: 0x7598ac5a4c
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64adaac VA: 0x7598ac5aac
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64adbc0 VA: 0x7598ac5bc0
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64adc60 VA: 0x7598ac5c60
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64adc68 VA: 0x7598ac5c68
	public virtual Int32 get_M() { }
	// RVA: 0x64adc70 VA: 0x7598ac5c70
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64adc78 VA: 0x7598ac5c78
	public virtual Int32 get_K1() { }
	// RVA: 0x64adc80 VA: 0x7598ac5c80
	public virtual Int32 get_K2() { }
	// RVA: 0x64adc88 VA: 0x7598ac5c88
	public virtual Int32 get_K3() { }
}
```