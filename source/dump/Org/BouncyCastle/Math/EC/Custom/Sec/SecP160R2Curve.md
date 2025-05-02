# SecP160R2Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160R2Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SecP160R2_DEFAULT_COORDS; // 0x0
	protected readonly SecP160R2Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x64841e0 VA: 0x7598a9c1e0
	public Void .ctor() { }
	// RVA: 0x6484440 VA: 0x7598a9c440
	protected override ECCurve CloneCurve() { }
	// RVA: 0x6484498 VA: 0x7598a9c498
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64844a4 VA: 0x7598a9c4a4
	public virtual BigInteger get_Q() { }
	// RVA: 0x64844fc VA: 0x7598a9c4fc
	public override ECPoint get_Infinity() { }
	// RVA: 0x6484504 VA: 0x7598a9c504
	public override Int32 get_FieldSize() { }
	// RVA: 0x6484568 VA: 0x7598a9c568
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64845c8 VA: 0x7598a9c5c8
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64846dc VA: 0x7598a9c6dc
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x648477c VA: 0x7598a9c77c
	private static Void .cctor() { }
}
```