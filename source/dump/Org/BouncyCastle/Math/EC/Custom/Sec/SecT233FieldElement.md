# SecT233FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT233FieldElement : ECFieldElement
{
	protected readonly UInt64[] x; // 0x10

	public override Boolean IsOne { get; }
	public override Boolean IsZero { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }
	public virtual Int32 Representation { get; }
	public virtual Int32 M { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64b64c0 VA: 0x7598ace4c0
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64b6588 VA: 0x7598ace588
	public Void .ctor() { }
	// RVA: 0x64b65b4 VA: 0x7598ace5b4
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64b65e4 VA: 0x7598ace5e4
	public override Boolean get_IsOne() { }
	// RVA: 0x64b65f0 VA: 0x7598ace5f0
	public override Boolean get_IsZero() { }
	// RVA: 0x64b65fc VA: 0x7598ace5fc
	public override Boolean TestBitZero() { }
	// RVA: 0x64b6628 VA: 0x7598ace628
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64b6634 VA: 0x7598ace634
	public override String get_FieldName() { }
	// RVA: 0x64b6674 VA: 0x7598ace674
	public override Int32 get_FieldSize() { }
	// RVA: 0x64b667c VA: 0x7598ace67c
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64b674c VA: 0x7598ace74c
	public override ECFieldElement AddOne() { }
	// RVA: 0x64b67d8 VA: 0x7598ace7d8
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64b67e4 VA: 0x7598ace7e4
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64b68b4 VA: 0x7598ace8b4
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b68c4 VA: 0x7598ace8c4
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b6a34 VA: 0x7598acea34
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64b6a74 VA: 0x7598acea74
	public override ECFieldElement Negate() { }
	// RVA: 0x64b6a78 VA: 0x7598acea78
	public override ECFieldElement Square() { }
	// RVA: 0x64b6b04 VA: 0x7598aceb04
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b6b14 VA: 0x7598aceb14
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b6c44 VA: 0x7598acec44
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64b6ce8 VA: 0x7598acece8
	public override ECFieldElement Invert() { }
	// RVA: 0x64b6d74 VA: 0x7598aced74
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64b6e00 VA: 0x7598acee00
	public virtual Int32 get_Representation() { }
	// RVA: 0x64b6e08 VA: 0x7598acee08
	public virtual Int32 get_M() { }
	// RVA: 0x64b6e10 VA: 0x7598acee10
	public virtual Int32 get_K1() { }
	// RVA: 0x64b6e18 VA: 0x7598acee18
	public virtual Int32 get_K2() { }
	// RVA: 0x64b6e20 VA: 0x7598acee20
	public virtual Int32 get_K3() { }
	// RVA: 0x64b6e28 VA: 0x7598acee28
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64b6eb4 VA: 0x7598aceeb4
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64b6f40 VA: 0x7598acef40
	public virtual Boolean Equals(SecT233FieldElement other) { }
	// RVA: 0x64b6f6c VA: 0x7598acef6c
	public override Int32 GetHashCode() { }
}
```