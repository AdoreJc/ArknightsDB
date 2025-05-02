# SecP256K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP256K1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SECP256K1_DEFAULT_COORDS; // 0x0
	protected readonly SecP256K1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x64946c0 VA: 0x7598aac6c0
	public Void .ctor() { }
	// RVA: 0x64948a4 VA: 0x7598aac8a4
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64948fc VA: 0x7598aac8fc
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x6494908 VA: 0x7598aac908
	public virtual BigInteger get_Q() { }
	// RVA: 0x6494960 VA: 0x7598aac960
	public override ECPoint get_Infinity() { }
	// RVA: 0x6494968 VA: 0x7598aac968
	public override Int32 get_FieldSize() { }
	// RVA: 0x64949cc VA: 0x7598aac9cc
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x6494b4c VA: 0x7598aacb4c
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6494c60 VA: 0x7598aacc60
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6494d00 VA: 0x7598aacd00
	private static Void .cctor() { }
}
```