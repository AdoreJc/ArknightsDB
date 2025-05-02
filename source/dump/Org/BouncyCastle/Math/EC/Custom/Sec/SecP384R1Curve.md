# SecP384R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP384R1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SecP384R1_DEFAULT_COORDS; // 0x0
	protected readonly SecP384R1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x649a904 VA: 0x7598ab2904
	public Void .ctor() { }
	// RVA: 0x649ab64 VA: 0x7598ab2b64
	protected override ECCurve CloneCurve() { }
	// RVA: 0x649abbc VA: 0x7598ab2bbc
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x649abc8 VA: 0x7598ab2bc8
	public virtual BigInteger get_Q() { }
	// RVA: 0x649ac20 VA: 0x7598ab2c20
	public override ECPoint get_Infinity() { }
	// RVA: 0x649ac28 VA: 0x7598ab2c28
	public override Int32 get_FieldSize() { }
	// RVA: 0x649ac8c VA: 0x7598ab2c8c
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x649ae0c VA: 0x7598ab2e0c
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x649af20 VA: 0x7598ab2f20
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x649afc0 VA: 0x7598ab2fc0
	private static Void .cctor() { }
}
```