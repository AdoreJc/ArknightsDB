# SecP128R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP128R1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SecP128R1_DEFAULT_COORDS; // 0x0
	protected readonly SecP128R1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x647c724 VA: 0x7598a94724
	public Void .ctor() { }
	// RVA: 0x647c984 VA: 0x7598a94984
	protected override ECCurve CloneCurve() { }
	// RVA: 0x647c9dc VA: 0x7598a949dc
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x647c9e8 VA: 0x7598a949e8
	public virtual BigInteger get_Q() { }
	// RVA: 0x647ca40 VA: 0x7598a94a40
	public override ECPoint get_Infinity() { }
	// RVA: 0x647ca48 VA: 0x7598a94a48
	public override Int32 get_FieldSize() { }
	// RVA: 0x647caac VA: 0x7598a94aac
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x647cc2c VA: 0x7598a94c2c
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x647cd40 VA: 0x7598a94d40
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x647cde0 VA: 0x7598a94de0
	private static Void .cctor() { }
}
```