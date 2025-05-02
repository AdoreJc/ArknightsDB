# SecP256R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP256R1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SecP256R1_DEFAULT_COORDS; // 0x0
	protected readonly SecP256R1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x6497664 VA: 0x7598aaf664
	public Void .ctor() { }
	// RVA: 0x64978c4 VA: 0x7598aaf8c4
	protected override ECCurve CloneCurve() { }
	// RVA: 0x649791c VA: 0x7598aaf91c
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x6497928 VA: 0x7598aaf928
	public virtual BigInteger get_Q() { }
	// RVA: 0x6497980 VA: 0x7598aaf980
	public override ECPoint get_Infinity() { }
	// RVA: 0x6497988 VA: 0x7598aaf988
	public override Int32 get_FieldSize() { }
	// RVA: 0x64979ec VA: 0x7598aaf9ec
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x6497b6c VA: 0x7598aafb6c
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6497c80 VA: 0x7598aafc80
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6497d20 VA: 0x7598aafd20
	private static Void .cctor() { }
}
```