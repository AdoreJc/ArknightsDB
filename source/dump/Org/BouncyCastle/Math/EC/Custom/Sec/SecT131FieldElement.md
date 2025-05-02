# SecT131FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT131FieldElement : ECFieldElement
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

	// RVA: 0x64a654c VA: 0x7598abe54c
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64a6640 VA: 0x7598abe640
	public Void .ctor() { }
	// RVA: 0x64a666c VA: 0x7598abe66c
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64a669c VA: 0x7598abe69c
	public override Boolean get_IsOne() { }
	// RVA: 0x64a66a8 VA: 0x7598abe6a8
	public override Boolean get_IsZero() { }
	// RVA: 0x64a66b4 VA: 0x7598abe6b4
	public override Boolean TestBitZero() { }
	// RVA: 0x64a66e0 VA: 0x7598abe6e0
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64a66ec VA: 0x7598abe6ec
	public override String get_FieldName() { }
	// RVA: 0x64a672c VA: 0x7598abe72c
	public override Int32 get_FieldSize() { }
	// RVA: 0x64a6734 VA: 0x7598abe734
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64a6830 VA: 0x7598abe830
	public override ECFieldElement AddOne() { }
	// RVA: 0x64a68e4 VA: 0x7598abe8e4
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64a68f0 VA: 0x7598abe8f0
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64a69ec VA: 0x7598abe9ec
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a69fc VA: 0x7598abe9fc
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a6b98 VA: 0x7598abeb98
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64a6bd8 VA: 0x7598abebd8
	public override ECFieldElement Negate() { }
	// RVA: 0x64a6bdc VA: 0x7598abebdc
	public override ECFieldElement Square() { }
	// RVA: 0x64a6c90 VA: 0x7598abec90
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a6ca0 VA: 0x7598abeca0
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a6dfc VA: 0x7598abedfc
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64a6ec8 VA: 0x7598abeec8
	public override ECFieldElement Invert() { }
	// RVA: 0x64a6f7c VA: 0x7598abef7c
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64a7030 VA: 0x7598abf030
	public virtual Int32 get_Representation() { }
	// RVA: 0x64a7038 VA: 0x7598abf038
	public virtual Int32 get_M() { }
	// RVA: 0x64a7040 VA: 0x7598abf040
	public virtual Int32 get_K1() { }
	// RVA: 0x64a7048 VA: 0x7598abf048
	public virtual Int32 get_K2() { }
	// RVA: 0x64a7050 VA: 0x7598abf050
	public virtual Int32 get_K3() { }
	// RVA: 0x64a7058 VA: 0x7598abf058
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64a70e4 VA: 0x7598abf0e4
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64a7170 VA: 0x7598abf170
	public virtual Boolean Equals(SecT131FieldElement other) { }
	// RVA: 0x64a719c VA: 0x7598abf19c
	public override Int32 GetHashCode() { }
}
```