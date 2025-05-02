# F2mFieldElement

**Namespace:** `Org.BouncyCastle.Math.EC`


## Fields

- `Int32 representation`

- `Int32 m`

- `LongArray x`


## Properties

- `Int32 Representation`

- `Int32 M`

- `Int32 K1`

- `Int32 K2`

- `Int32 K3`


## Methods

- `Int32 get_Representation()`

- `Int32 get_M()`

- `Int32 get_K1()`

- `Int32 get_K2()`

- `Int32 get_K3()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC
public class F2mFieldElement : ECFieldElement
{
	public const Int32 Gnb; // 0x0
	public const Int32 Tpb; // 0x0
	public const Int32 Ppb; // 0x0
	private Int32 representation; // 0x10
	private Int32 m; // 0x14
	private Int32[] ks; // 0x18
	private LongArray x; // 0x20

	public override Int32 BitLength { get; }
	public override Boolean IsOne { get; }
	public override Boolean IsZero { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }
	public Int32 Representation { get; }
	public Int32 M { get; }
	public Int32 K1 { get; }
	public Int32 K2 { get; }
	public Int32 K3 { get; }

	// RVA: 0x6732390 VA: 0x7598d4a390
	public Void .ctor(Int32 m, Int32 k1, Int32 k2, Int32 k3, BigInteger x) { }
	// RVA: 0x6734a84 VA: 0x7598d4ca84
	public Void .ctor(Int32 m, Int32 k, BigInteger x) { }
	// RVA: 0x6734a94 VA: 0x7598d4ca94
	private Void .ctor(Int32 m, Int32[] ks, LongArray x) { }
	// RVA: 0x6734b04 VA: 0x7598d4cb04
	public override Int32 get_BitLength() { }
	// RVA: 0x6734bc0 VA: 0x7598d4cbc0
	public override Boolean get_IsOne() { }
	// RVA: 0x6734c38 VA: 0x7598d4cc38
	public override Boolean get_IsZero() { }
	// RVA: 0x6734cd8 VA: 0x7598d4ccd8
	public override Boolean TestBitZero() { }
	// RVA: 0x6734d28 VA: 0x7598d4cd28
	public override BigInteger ToBigInteger() { }
	// RVA: 0x6734d40 VA: 0x7598d4cd40
	public override String get_FieldName() { }
	// RVA: 0x6734d80 VA: 0x7598d4cd80
	public override Int32 get_FieldSize() { }
	// RVA: 0x6734d88 VA: 0x7598d4cd88
	public static Void CheckFieldElements(ECFieldElement a, ECFieldElement b) { }
	// RVA: 0x6734ee8 VA: 0x7598d4cee8
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x6735128 VA: 0x7598d4d128
	public override ECFieldElement AddOne() { }
	// RVA: 0x67352dc VA: 0x7598d4d2dc
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x67352e8 VA: 0x7598d4d2e8
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x673580c VA: 0x7598d4d80c
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x673581c VA: 0x7598d4d81c
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6735ed0 VA: 0x7598d4ded0
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x6735f10 VA: 0x7598d4df10
	public override ECFieldElement Negate() { }
	// RVA: 0x6735f14 VA: 0x7598d4df14
	public override ECFieldElement Square() { }
	// RVA: 0x6736138 VA: 0x7598d4e138
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6736148 VA: 0x7598d4e148
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x67363ec VA: 0x7598d4e3ec
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x67365c4 VA: 0x7598d4e5c4
	public override ECFieldElement Invert() { }
	// RVA: 0x6736658 VA: 0x7598d4e658
	public override ECFieldElement Sqrt() { }
	// RVA: 0x67366d4 VA: 0x7598d4e6d4
	public Int32 get_Representation() { }
	// RVA: 0x67366dc VA: 0x7598d4e6dc
	public Int32 get_M() { }
	// RVA: 0x67366e4 VA: 0x7598d4e6e4
	public Int32 get_K1() { }
	// RVA: 0x673670c VA: 0x7598d4e70c
	public Int32 get_K2() { }
	// RVA: 0x673673c VA: 0x7598d4e73c
	public Int32 get_K3() { }
	// RVA: 0x673676c VA: 0x7598d4e76c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6736814 VA: 0x7598d4e814
	public virtual Boolean Equals(F2mFieldElement other) { }
	// RVA: 0x6736890 VA: 0x7598d4e890
	public override Int32 GetHashCode() { }
}
```