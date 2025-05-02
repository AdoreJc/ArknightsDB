# SecT409FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT409FieldElement : ECFieldElement
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

	// RVA: 0x64c33ec VA: 0x7598adb3ec
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64c34b4 VA: 0x7598adb4b4
	public Void .ctor() { }
	// RVA: 0x64c34e0 VA: 0x7598adb4e0
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64c3510 VA: 0x7598adb510
	public override Boolean get_IsOne() { }
	// RVA: 0x64c351c VA: 0x7598adb51c
	public override Boolean get_IsZero() { }
	// RVA: 0x64c3528 VA: 0x7598adb528
	public override Boolean TestBitZero() { }
	// RVA: 0x64c3554 VA: 0x7598adb554
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64c3560 VA: 0x7598adb560
	public override String get_FieldName() { }
	// RVA: 0x64c35a0 VA: 0x7598adb5a0
	public override Int32 get_FieldSize() { }
	// RVA: 0x64c35a8 VA: 0x7598adb5a8
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64c3678 VA: 0x7598adb678
	public override ECFieldElement AddOne() { }
	// RVA: 0x64c3704 VA: 0x7598adb704
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64c3710 VA: 0x7598adb710
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64c37e0 VA: 0x7598adb7e0
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c37f0 VA: 0x7598adb7f0
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c3964 VA: 0x7598adb964
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64c39a4 VA: 0x7598adb9a4
	public override ECFieldElement Negate() { }
	// RVA: 0x64c39a8 VA: 0x7598adb9a8
	public override ECFieldElement Square() { }
	// RVA: 0x64c3a34 VA: 0x7598adba34
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c3a44 VA: 0x7598adba44
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c3b78 VA: 0x7598adbb78
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64c3c1c VA: 0x7598adbc1c
	public override ECFieldElement Invert() { }
	// RVA: 0x64c3ca8 VA: 0x7598adbca8
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64c3d34 VA: 0x7598adbd34
	public virtual Int32 get_Representation() { }
	// RVA: 0x64c3d3c VA: 0x7598adbd3c
	public virtual Int32 get_M() { }
	// RVA: 0x64c3d44 VA: 0x7598adbd44
	public virtual Int32 get_K1() { }
	// RVA: 0x64c3d4c VA: 0x7598adbd4c
	public virtual Int32 get_K2() { }
	// RVA: 0x64c3d54 VA: 0x7598adbd54
	public virtual Int32 get_K3() { }
	// RVA: 0x64c3d5c VA: 0x7598adbd5c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64c3de8 VA: 0x7598adbde8
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64c3e74 VA: 0x7598adbe74
	public virtual Boolean Equals(SecT409FieldElement other) { }
	// RVA: 0x64c3ea0 VA: 0x7598adbea0
	public override Int32 GetHashCode() { }
}
```