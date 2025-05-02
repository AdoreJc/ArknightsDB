# SecT239FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT239FieldElement : ECFieldElement
{
	protected UInt64[] x; // 0x10

	public override Boolean IsOne { get; }
	public override Boolean IsZero { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }
	public virtual Int32 Representation { get; }
	public virtual Int32 M { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64bb054 VA: 0x7598ad3054
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64bb11c VA: 0x7598ad311c
	public Void .ctor() { }
	// RVA: 0x64bb148 VA: 0x7598ad3148
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64bb178 VA: 0x7598ad3178
	public override Boolean get_IsOne() { }
	// RVA: 0x64bb184 VA: 0x7598ad3184
	public override Boolean get_IsZero() { }
	// RVA: 0x64bb190 VA: 0x7598ad3190
	public override Boolean TestBitZero() { }
	// RVA: 0x64bb1bc VA: 0x7598ad31bc
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64bb1c8 VA: 0x7598ad31c8
	public override String get_FieldName() { }
	// RVA: 0x64bb208 VA: 0x7598ad3208
	public override Int32 get_FieldSize() { }
	// RVA: 0x64bb210 VA: 0x7598ad3210
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64bb2e0 VA: 0x7598ad32e0
	public override ECFieldElement AddOne() { }
	// RVA: 0x64bb36c VA: 0x7598ad336c
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64bb378 VA: 0x7598ad3378
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64bb448 VA: 0x7598ad3448
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bb458 VA: 0x7598ad3458
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bb5c8 VA: 0x7598ad35c8
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64bb608 VA: 0x7598ad3608
	public override ECFieldElement Negate() { }
	// RVA: 0x64bb60c VA: 0x7598ad360c
	public override ECFieldElement Square() { }
	// RVA: 0x64bb698 VA: 0x7598ad3698
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bb6a8 VA: 0x7598ad36a8
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bb7d8 VA: 0x7598ad37d8
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64bb87c VA: 0x7598ad387c
	public override ECFieldElement Invert() { }
	// RVA: 0x64bb908 VA: 0x7598ad3908
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64bb994 VA: 0x7598ad3994
	public virtual Int32 get_Representation() { }
	// RVA: 0x64bb99c VA: 0x7598ad399c
	public virtual Int32 get_M() { }
	// RVA: 0x64bb9a4 VA: 0x7598ad39a4
	public virtual Int32 get_K1() { }
	// RVA: 0x64bb9ac VA: 0x7598ad39ac
	public virtual Int32 get_K2() { }
	// RVA: 0x64bb9b4 VA: 0x7598ad39b4
	public virtual Int32 get_K3() { }
	// RVA: 0x64bb9bc VA: 0x7598ad39bc
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64bba48 VA: 0x7598ad3a48
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64bbad4 VA: 0x7598ad3ad4
	public virtual Boolean Equals(SecT239FieldElement other) { }
	// RVA: 0x64bbb00 VA: 0x7598ad3b00
	public override Int32 GetHashCode() { }
}
```