# SecP192K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP192K1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SECP192K1_DEFAULT_COORDS; // 0x0
	protected readonly SecP192K1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x6486bc8 VA: 0x7598a9ebc8
	public Void .ctor() { }
	// RVA: 0x6486dac VA: 0x7598a9edac
	protected override ECCurve CloneCurve() { }
	// RVA: 0x6486e04 VA: 0x7598a9ee04
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x6486e10 VA: 0x7598a9ee10
	public virtual BigInteger get_Q() { }
	// RVA: 0x6486e68 VA: 0x7598a9ee68
	public override ECPoint get_Infinity() { }
	// RVA: 0x6486e70 VA: 0x7598a9ee70
	public override Int32 get_FieldSize() { }
	// RVA: 0x6486ed4 VA: 0x7598a9eed4
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x6487054 VA: 0x7598a9f054
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6487168 VA: 0x7598a9f168
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6487208 VA: 0x7598a9f208
	private static Void .cctor() { }
}
```