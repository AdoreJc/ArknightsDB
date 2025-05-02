# SecP160K1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160K1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SECP160K1_DEFAULT_COORDS; // 0x0
	protected readonly SecP160K1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x647f768 VA: 0x7598a97768
	public Void .ctor() { }
	// RVA: 0x647f94c VA: 0x7598a9794c
	protected override ECCurve CloneCurve() { }
	// RVA: 0x647f9a4 VA: 0x7598a979a4
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x647f9b0 VA: 0x7598a979b0
	public virtual BigInteger get_Q() { }
	// RVA: 0x647fa08 VA: 0x7598a97a08
	public override ECPoint get_Infinity() { }
	// RVA: 0x647fa10 VA: 0x7598a97a10
	public override Int32 get_FieldSize() { }
	// RVA: 0x647fa74 VA: 0x7598a97a74
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x647fbf4 VA: 0x7598a97bf4
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x647fd08 VA: 0x7598a97d08
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x647fda8 VA: 0x7598a97da8
	private static Void .cctor() { }
}
```