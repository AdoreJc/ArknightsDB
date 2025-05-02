# SecT113FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT113FieldElement : ECFieldElement
{
	protected internal readonly UInt64[] x; // 0x10

	public override Boolean IsOne { get; }
	public override Boolean IsZero { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }
	public virtual Int32 Representation { get; }
	public virtual Int32 M { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64a1444 VA: 0x7598ab9444
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64a150c VA: 0x7598ab950c
	public Void .ctor() { }
	// RVA: 0x64a1538 VA: 0x7598ab9538
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64a1568 VA: 0x7598ab9568
	public override Boolean get_IsOne() { }
	// RVA: 0x64a1574 VA: 0x7598ab9574
	public override Boolean get_IsZero() { }
	// RVA: 0x64a1580 VA: 0x7598ab9580
	public override Boolean TestBitZero() { }
	// RVA: 0x64a15ac VA: 0x7598ab95ac
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64a15b8 VA: 0x7598ab95b8
	public override String get_FieldName() { }
	// RVA: 0x64a15f8 VA: 0x7598ab95f8
	public override Int32 get_FieldSize() { }
	// RVA: 0x64a1600 VA: 0x7598ab9600
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64a16d0 VA: 0x7598ab96d0
	public override ECFieldElement AddOne() { }
	// RVA: 0x64a175c VA: 0x7598ab975c
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64a1768 VA: 0x7598ab9768
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64a1838 VA: 0x7598ab9838
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a1848 VA: 0x7598ab9848
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a19b8 VA: 0x7598ab99b8
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64a19f8 VA: 0x7598ab99f8
	public override ECFieldElement Negate() { }
	// RVA: 0x64a19fc VA: 0x7598ab99fc
	public override ECFieldElement Square() { }
	// RVA: 0x64a1a88 VA: 0x7598ab9a88
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a1a98 VA: 0x7598ab9a98
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a1bc8 VA: 0x7598ab9bc8
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64a1c6c VA: 0x7598ab9c6c
	public override ECFieldElement Invert() { }
	// RVA: 0x64a1cf8 VA: 0x7598ab9cf8
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64a1d84 VA: 0x7598ab9d84
	public virtual Int32 get_Representation() { }
	// RVA: 0x64a1d8c VA: 0x7598ab9d8c
	public virtual Int32 get_M() { }
	// RVA: 0x64a1d94 VA: 0x7598ab9d94
	public virtual Int32 get_K1() { }
	// RVA: 0x64a1d9c VA: 0x7598ab9d9c
	public virtual Int32 get_K2() { }
	// RVA: 0x64a1da4 VA: 0x7598ab9da4
	public virtual Int32 get_K3() { }
	// RVA: 0x64a1dac VA: 0x7598ab9dac
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64a1e38 VA: 0x7598ab9e38
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64a1ec4 VA: 0x7598ab9ec4
	public virtual Boolean Equals(SecT113FieldElement other) { }
	// RVA: 0x64a1ef0 VA: 0x7598ab9ef0
	public override Int32 GetHashCode() { }
}
```