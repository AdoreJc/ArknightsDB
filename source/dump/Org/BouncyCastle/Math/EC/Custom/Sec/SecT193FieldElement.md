# SecT193FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT193FieldElement : ECFieldElement
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

	// RVA: 0x64b1740 VA: 0x7598ac9740
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64b1808 VA: 0x7598ac9808
	public Void .ctor() { }
	// RVA: 0x64b1834 VA: 0x7598ac9834
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64b1864 VA: 0x7598ac9864
	public override Boolean get_IsOne() { }
	// RVA: 0x64b1870 VA: 0x7598ac9870
	public override Boolean get_IsZero() { }
	// RVA: 0x64b187c VA: 0x7598ac987c
	public override Boolean TestBitZero() { }
	// RVA: 0x64b18a8 VA: 0x7598ac98a8
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64b18b4 VA: 0x7598ac98b4
	public override String get_FieldName() { }
	// RVA: 0x64b18f4 VA: 0x7598ac98f4
	public override Int32 get_FieldSize() { }
	// RVA: 0x64b18fc VA: 0x7598ac98fc
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64b19cc VA: 0x7598ac99cc
	public override ECFieldElement AddOne() { }
	// RVA: 0x64b1a58 VA: 0x7598ac9a58
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64b1a64 VA: 0x7598ac9a64
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64b1b34 VA: 0x7598ac9b34
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b1b44 VA: 0x7598ac9b44
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b1cb4 VA: 0x7598ac9cb4
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64b1cf4 VA: 0x7598ac9cf4
	public override ECFieldElement Negate() { }
	// RVA: 0x64b1cf8 VA: 0x7598ac9cf8
	public override ECFieldElement Square() { }
	// RVA: 0x64b1d84 VA: 0x7598ac9d84
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b1d94 VA: 0x7598ac9d94
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b1ec4 VA: 0x7598ac9ec4
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64b1f68 VA: 0x7598ac9f68
	public override ECFieldElement Invert() { }
	// RVA: 0x64b1ff4 VA: 0x7598ac9ff4
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64b2080 VA: 0x7598aca080
	public virtual Int32 get_Representation() { }
	// RVA: 0x64b2088 VA: 0x7598aca088
	public virtual Int32 get_M() { }
	// RVA: 0x64b2090 VA: 0x7598aca090
	public virtual Int32 get_K1() { }
	// RVA: 0x64b2098 VA: 0x7598aca098
	public virtual Int32 get_K2() { }
	// RVA: 0x64b20a0 VA: 0x7598aca0a0
	public virtual Int32 get_K3() { }
	// RVA: 0x64b20a8 VA: 0x7598aca0a8
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64b2134 VA: 0x7598aca134
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64b21c0 VA: 0x7598aca1c0
	public virtual Boolean Equals(SecT193FieldElement other) { }
	// RVA: 0x64b21ec VA: 0x7598aca1ec
	public override Int32 GetHashCode() { }
}
```