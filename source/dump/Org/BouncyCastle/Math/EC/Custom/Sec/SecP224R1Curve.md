# SecP224R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP224R1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SecP224R1_DEFAULT_COORDS; // 0x0
	protected readonly SecP224R1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x648fe44 VA: 0x7598aa7e44
	public Void .ctor() { }
	// RVA: 0x64900a4 VA: 0x7598aa80a4
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64900fc VA: 0x7598aa80fc
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x6490108 VA: 0x7598aa8108
	public virtual BigInteger get_Q() { }
	// RVA: 0x6490160 VA: 0x7598aa8160
	public override ECPoint get_Infinity() { }
	// RVA: 0x6490168 VA: 0x7598aa8168
	public override Int32 get_FieldSize() { }
	// RVA: 0x64901cc VA: 0x7598aa81cc
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x649034c VA: 0x7598aa834c
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6490460 VA: 0x7598aa8460
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6490500 VA: 0x7598aa8500
	private static Void .cctor() { }
}
```