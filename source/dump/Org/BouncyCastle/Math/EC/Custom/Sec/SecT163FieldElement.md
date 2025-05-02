# SecT163FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT163FieldElement : ECFieldElement
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

	// RVA: 0x64ab3d0 VA: 0x7598ac33d0
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64ab4c8 VA: 0x7598ac34c8
	public Void .ctor() { }
	// RVA: 0x64ab4f4 VA: 0x7598ac34f4
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64ab524 VA: 0x7598ac3524
	public override Boolean get_IsOne() { }
	// RVA: 0x64ab530 VA: 0x7598ac3530
	public override Boolean get_IsZero() { }
	// RVA: 0x64ab53c VA: 0x7598ac353c
	public override Boolean TestBitZero() { }
	// RVA: 0x64ab568 VA: 0x7598ac3568
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64ab574 VA: 0x7598ac3574
	public override String get_FieldName() { }
	// RVA: 0x64ab5b4 VA: 0x7598ac35b4
	public override Int32 get_FieldSize() { }
	// RVA: 0x64ab5bc VA: 0x7598ac35bc
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64ab6bc VA: 0x7598ac36bc
	public override ECFieldElement AddOne() { }
	// RVA: 0x64ab774 VA: 0x7598ac3774
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64ab780 VA: 0x7598ac3780
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64ab880 VA: 0x7598ac3880
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64ab890 VA: 0x7598ac3890
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64aba34 VA: 0x7598ac3a34
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64aba74 VA: 0x7598ac3a74
	public override ECFieldElement Negate() { }
	// RVA: 0x64aba78 VA: 0x7598ac3a78
	public override ECFieldElement Square() { }
	// RVA: 0x64abb30 VA: 0x7598ac3b30
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64abb40 VA: 0x7598ac3b40
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64abca4 VA: 0x7598ac3ca4
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64abd74 VA: 0x7598ac3d74
	public override ECFieldElement Invert() { }
	// RVA: 0x64abe2c VA: 0x7598ac3e2c
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64abee4 VA: 0x7598ac3ee4
	public virtual Int32 get_Representation() { }
	// RVA: 0x64abeec VA: 0x7598ac3eec
	public virtual Int32 get_M() { }
	// RVA: 0x64abef4 VA: 0x7598ac3ef4
	public virtual Int32 get_K1() { }
	// RVA: 0x64abefc VA: 0x7598ac3efc
	public virtual Int32 get_K2() { }
	// RVA: 0x64abf04 VA: 0x7598ac3f04
	public virtual Int32 get_K3() { }
	// RVA: 0x64abf0c VA: 0x7598ac3f0c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64abf98 VA: 0x7598ac3f98
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64ac024 VA: 0x7598ac4024
	public virtual Boolean Equals(SecT163FieldElement other) { }
	// RVA: 0x64ac050 VA: 0x7598ac4050
	public override Int32 GetHashCode() { }
}
```