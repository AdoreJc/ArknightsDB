# SecP224K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP224K1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SECP224K1_DEFAULT_COORDS; // 0x0
	protected readonly SecP224K1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x648cda4 VA: 0x7598aa4da4
	public Void .ctor() { }
	// RVA: 0x648cf88 VA: 0x7598aa4f88
	protected override ECCurve CloneCurve() { }
	// RVA: 0x648cfe0 VA: 0x7598aa4fe0
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x648cfec VA: 0x7598aa4fec
	public virtual BigInteger get_Q() { }
	// RVA: 0x648d044 VA: 0x7598aa5044
	public override ECPoint get_Infinity() { }
	// RVA: 0x648d04c VA: 0x7598aa504c
	public override Int32 get_FieldSize() { }
	// RVA: 0x648d0b0 VA: 0x7598aa50b0
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x648d230 VA: 0x7598aa5230
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x648d344 VA: 0x7598aa5344
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x648d3e4 VA: 0x7598aa53e4
	private static Void .cctor() { }
}
```