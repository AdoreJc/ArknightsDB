# FpCurve

**Namespace:** `Org.BouncyCastle.Math.EC`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC
public class FpCurve : AbstractFpCurve
{
	private const Int32 FP_DEFAULT_COORDS; // 0x0
	protected readonly BigInteger m_q; // 0x50
	protected readonly BigInteger m_r; // 0x58
	protected readonly FpPoint m_infinity; // 0x60

	public virtual BigInteger Q { get; }
	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x6730114 VA: 0x7598d48114
	public Void .ctor(BigInteger q, BigInteger a, BigInteger b) { }
	// RVA: 0x6730120 VA: 0x7598d48120
	public Void .ctor(BigInteger q, BigInteger a, BigInteger b, BigInteger order, BigInteger cofactor) { }
	// RVA: 0x6730394 VA: 0x7598d48394
	protected Void .ctor(BigInteger q, BigInteger r, ECFieldElement a, ECFieldElement b) { }
	// RVA: 0x67303a0 VA: 0x7598d483a0
	protected Void .ctor(BigInteger q, BigInteger r, ECFieldElement a, ECFieldElement b, BigInteger order, BigInteger cofactor) { }
	// RVA: 0x67304bc VA: 0x7598d484bc
	protected override ECCurve CloneCurve() { }
	// RVA: 0x673054c VA: 0x7598d4854c
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x6730568 VA: 0x7598d48568
	public virtual BigInteger get_Q() { }
	// RVA: 0x6730570 VA: 0x7598d48570
	public override ECPoint get_Infinity() { }
	// RVA: 0x6730578 VA: 0x7598d48578
	public override Int32 get_FieldSize() { }
	// RVA: 0x6730594 VA: 0x7598d48594
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x67306ec VA: 0x7598d486ec
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x67307fc VA: 0x7598d487fc
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6730894 VA: 0x7598d48894
	public override ECPoint ImportPoint(ECPoint p) { }
}
```