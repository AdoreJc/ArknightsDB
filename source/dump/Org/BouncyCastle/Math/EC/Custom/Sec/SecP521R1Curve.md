# SecP521R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP521R1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SecP521R1_DEFAULT_COORDS; // 0x0
	protected readonly SecP521R1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x649dd58 VA: 0x7598ab5d58
	public Void .ctor() { }
	// RVA: 0x649dfb8 VA: 0x7598ab5fb8
	protected override ECCurve CloneCurve() { }
	// RVA: 0x649e010 VA: 0x7598ab6010
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x649e01c VA: 0x7598ab601c
	public virtual BigInteger get_Q() { }
	// RVA: 0x649e074 VA: 0x7598ab6074
	public override ECPoint get_Infinity() { }
	// RVA: 0x649e07c VA: 0x7598ab607c
	public override Int32 get_FieldSize() { }
	// RVA: 0x649e0e0 VA: 0x7598ab60e0
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x649e260 VA: 0x7598ab6260
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x649e374 VA: 0x7598ab6374
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x649e414 VA: 0x7598ab6414
	private static Void .cctor() { }
}
```