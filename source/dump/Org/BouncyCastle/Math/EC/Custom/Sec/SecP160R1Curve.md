# SecP160R1Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160R1Curve : AbstractFpCurve
{
	public static readonly BigInteger q; // 0x0
	private const Int32 SecP160R1_DEFAULT_COORDS; // 0x0
	protected readonly SecP160R1Point m_infinity; // 0x50

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x64811e0 VA: 0x7598a991e0
	public Void .ctor() { }
	// RVA: 0x6481440 VA: 0x7598a99440
	protected override ECCurve CloneCurve() { }
	// RVA: 0x6481498 VA: 0x7598a99498
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64814a4 VA: 0x7598a994a4
	public virtual BigInteger get_Q() { }
	// RVA: 0x64814fc VA: 0x7598a994fc
	public override ECPoint get_Infinity() { }
	// RVA: 0x6481504 VA: 0x7598a99504
	public override Int32 get_FieldSize() { }
	// RVA: 0x6481568 VA: 0x7598a99568
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64816e8 VA: 0x7598a996e8
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64817fc VA: 0x7598a997fc
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x648189c VA: 0x7598a9989c
	private static Void .cctor() { }
}
```