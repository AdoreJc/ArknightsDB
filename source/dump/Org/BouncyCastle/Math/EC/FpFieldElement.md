# FpFieldElement

**Namespace:** `Org.BouncyCastle.Math.EC`


## Properties

- `BigInteger Q`


## Methods

- `BigInteger get_Q()`

- `ECFieldElement CheckSqrt(ECFieldElement)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC
public class FpFieldElement : ECFieldElement
{
	private readonly BigInteger q; // 0x10
	private readonly BigInteger r; // 0x18
	private readonly BigInteger x; // 0x20

	public override String FieldName { get; }
	public override Int32 FieldSize { get; }
	public BigInteger Q { get; }

	// RVA: 0x6730268 VA: 0x7598d48268
	internal static BigInteger CalculateResidue(BigInteger p) { }
	// RVA: 0x6732bf8 VA: 0x7598d4abf8
	public Void .ctor(BigInteger q, BigInteger x) { }
	// RVA: 0x673060c VA: 0x7598d4860c
	internal Void .ctor(BigInteger q, BigInteger r, BigInteger x) { }
	// RVA: 0x6732c30 VA: 0x7598d4ac30
	public override BigInteger ToBigInteger() { }
	// RVA: 0x6732c38 VA: 0x7598d4ac38
	public override String get_FieldName() { }
	// RVA: 0x6732c78 VA: 0x7598d4ac78
	public override Int32 get_FieldSize() { }
	// RVA: 0x6732c94 VA: 0x7598d4ac94
	public BigInteger get_Q() { }
	// RVA: 0x6732c9c VA: 0x7598d4ac9c
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x6732d58 VA: 0x7598d4ad58
	public override ECFieldElement AddOne() { }
	// RVA: 0x6732e44 VA: 0x7598d4ae44
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x6732f00 VA: 0x7598d4af00
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x6732fbc VA: 0x7598d4afbc
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x67330e8 VA: 0x7598d4b0e8
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6733290 VA: 0x7598d4b290
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x6733364 VA: 0x7598d4b364
	public override ECFieldElement Negate() { }
	// RVA: 0x6733404 VA: 0x7598d4b404
	public override ECFieldElement Square() { }
	// RVA: 0x673349c VA: 0x7598d4b49c
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x67335ac VA: 0x7598d4b5ac
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6733738 VA: 0x7598d4b738
	public override ECFieldElement Invert() { }
	// RVA: 0x67337cc VA: 0x7598d4b7cc
	public override ECFieldElement Sqrt() { }
	// RVA: 0x6733dac VA: 0x7598d4bdac
	private ECFieldElement CheckSqrt(ECFieldElement z) { }
	// RVA: 0x6733e04 VA: 0x7598d4be04
	private BigInteger[] LucasSequence(BigInteger P, BigInteger Q, BigInteger k) { }
	// RVA: 0x6734358 VA: 0x7598d4c358
	protected virtual BigInteger ModAdd(BigInteger x1, BigInteger x2) { }
	// RVA: 0x67343bc VA: 0x7598d4c3bc
	protected virtual BigInteger ModDouble(BigInteger x) { }
	// RVA: 0x6734424 VA: 0x7598d4c424
	protected virtual BigInteger ModHalf(BigInteger x) { }
	// RVA: 0x6734484 VA: 0x7598d4c484
	protected virtual BigInteger ModHalfAbs(BigInteger x) { }
	// RVA: 0x67344e4 VA: 0x7598d4c4e4
	protected virtual BigInteger ModInverse(BigInteger x) { }
	// RVA: 0x67345b4 VA: 0x7598d4c5b4
	protected virtual BigInteger ModMult(BigInteger x1, BigInteger x2) { }
	// RVA: 0x67345f0 VA: 0x7598d4c5f0
	protected virtual BigInteger ModReduce(BigInteger x) { }
	// RVA: 0x6734900 VA: 0x7598d4c900
	protected virtual BigInteger ModSubtract(BigInteger x1, BigInteger x2) { }
	// RVA: 0x6734944 VA: 0x7598d4c944
	public override Boolean Equals(Object obj) { }
	// RVA: 0x67349ec VA: 0x7598d4c9ec
	public virtual Boolean Equals(FpFieldElement other) { }
	// RVA: 0x6734a44 VA: 0x7598d4ca44
	public override Int32 GetHashCode() { }
}
```