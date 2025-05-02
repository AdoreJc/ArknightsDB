# SecP192R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP192R1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SecP192R1_DEFAULT_COORDS; // 0x0
	protected readonly SecP192R1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x6489b48 VA: 0x7598aa1b48
	public Void .ctor() { }
	// RVA: 0x6489da8 VA: 0x7598aa1da8
	protected override ECCurve CloneCurve() { }
	// RVA: 0x6489e00 VA: 0x7598aa1e00
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x6489e0c VA: 0x7598aa1e0c
	public virtual BigInteger get_Q() { }
	// RVA: 0x6489e64 VA: 0x7598aa1e64
	public override ECPoint get_Infinity() { }
	// RVA: 0x6489e6c VA: 0x7598aa1e6c
	public override Int32 get_FieldSize() { }
	// RVA: 0x6489ed0 VA: 0x7598aa1ed0
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x648a050 VA: 0x7598aa2050
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x648a164 VA: 0x7598aa2164
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x648a204 VA: 0x7598aa2204
	private static Void .cctor() { }
}
```