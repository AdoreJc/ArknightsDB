# SecT283FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT283FieldElement : ECFieldElement
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

	// RVA: 0x64be950 VA: 0x7598ad6950
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64bea44 VA: 0x7598ad6a44
	public Void .ctor() { }
	// RVA: 0x64bea70 VA: 0x7598ad6a70
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64beaa0 VA: 0x7598ad6aa0
	public override Boolean get_IsOne() { }
	// RVA: 0x64beaac VA: 0x7598ad6aac
	public override Boolean get_IsZero() { }
	// RVA: 0x64beab8 VA: 0x7598ad6ab8
	public override Boolean TestBitZero() { }
	// RVA: 0x64beae4 VA: 0x7598ad6ae4
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64beaf0 VA: 0x7598ad6af0
	public override String get_FieldName() { }
	// RVA: 0x64beb30 VA: 0x7598ad6b30
	public override Int32 get_FieldSize() { }
	// RVA: 0x64beb38 VA: 0x7598ad6b38
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64bec34 VA: 0x7598ad6c34
	public override ECFieldElement AddOne() { }
	// RVA: 0x64bece8 VA: 0x7598ad6ce8
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64becf4 VA: 0x7598ad6cf4
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64bedf0 VA: 0x7598ad6df0
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bee00 VA: 0x7598ad6e00
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bef9c VA: 0x7598ad6f9c
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64befdc VA: 0x7598ad6fdc
	public override ECFieldElement Negate() { }
	// RVA: 0x64befe0 VA: 0x7598ad6fe0
	public override ECFieldElement Square() { }
	// RVA: 0x64bf094 VA: 0x7598ad7094
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bf0a4 VA: 0x7598ad70a4
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bf200 VA: 0x7598ad7200
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64bf2cc VA: 0x7598ad72cc
	public override ECFieldElement Invert() { }
	// RVA: 0x64bf380 VA: 0x7598ad7380
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64bf434 VA: 0x7598ad7434
	public virtual Int32 get_Representation() { }
	// RVA: 0x64bf43c VA: 0x7598ad743c
	public virtual Int32 get_M() { }
	// RVA: 0x64bf444 VA: 0x7598ad7444
	public virtual Int32 get_K1() { }
	// RVA: 0x64bf44c VA: 0x7598ad744c
	public virtual Int32 get_K2() { }
	// RVA: 0x64bf454 VA: 0x7598ad7454
	public virtual Int32 get_K3() { }
	// RVA: 0x64bf45c VA: 0x7598ad745c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64bf4e8 VA: 0x7598ad74e8
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64bf574 VA: 0x7598ad7574
	public virtual Boolean Equals(SecT283FieldElement other) { }
	// RVA: 0x64bf5a0 VA: 0x7598ad75a0
	public override Int32 GetHashCode() { }
}
```