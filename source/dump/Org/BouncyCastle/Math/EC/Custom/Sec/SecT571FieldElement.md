# SecT571FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT571FieldElement : ECFieldElement
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

	// RVA: 0x64c7e80 VA: 0x7598adfe80
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64c7f74 VA: 0x7598adff74
	public Void .ctor() { }
	// RVA: 0x64c7fa0 VA: 0x7598adffa0
	protected internal Void .ctor(UInt64[] x) { }
	// RVA: 0x64c7fd0 VA: 0x7598adffd0
	public override Boolean get_IsOne() { }
	// RVA: 0x64c7fdc VA: 0x7598adffdc
	public override Boolean get_IsZero() { }
	// RVA: 0x64c7fe8 VA: 0x7598adffe8
	public override Boolean TestBitZero() { }
	// RVA: 0x64c8014 VA: 0x7598ae0014
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64c8020 VA: 0x7598ae0020
	public override String get_FieldName() { }
	// RVA: 0x64c8060 VA: 0x7598ae0060
	public override Int32 get_FieldSize() { }
	// RVA: 0x64c8068 VA: 0x7598ae0068
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64c8164 VA: 0x7598ae0164
	public override ECFieldElement AddOne() { }
	// RVA: 0x64c8218 VA: 0x7598ae0218
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64c8224 VA: 0x7598ae0224
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64c8320 VA: 0x7598ae0320
	public override ECFieldElement MultiplyMinusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c8330 VA: 0x7598ae0330
	public override ECFieldElement MultiplyPlusProduct(ECFieldElement b, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c84c8 VA: 0x7598ae04c8
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64c8508 VA: 0x7598ae0508
	public override ECFieldElement Negate() { }
	// RVA: 0x64c850c VA: 0x7598ae050c
	public override ECFieldElement Square() { }
	// RVA: 0x64c85c0 VA: 0x7598ae05c0
	public override ECFieldElement SquareMinusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c85d0 VA: 0x7598ae05d0
	public override ECFieldElement SquarePlusProduct(ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c8728 VA: 0x7598ae0728
	public override ECFieldElement SquarePow(Int32 pow) { }
	// RVA: 0x64c87f4 VA: 0x7598ae07f4
	public override ECFieldElement Invert() { }
	// RVA: 0x64c88a8 VA: 0x7598ae08a8
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64c895c VA: 0x7598ae095c
	public virtual Int32 get_Representation() { }
	// RVA: 0x64c8964 VA: 0x7598ae0964
	public virtual Int32 get_M() { }
	// RVA: 0x64c896c VA: 0x7598ae096c
	public virtual Int32 get_K1() { }
	// RVA: 0x64c8974 VA: 0x7598ae0974
	public virtual Int32 get_K2() { }
	// RVA: 0x64c897c VA: 0x7598ae097c
	public virtual Int32 get_K3() { }
	// RVA: 0x64c8984 VA: 0x7598ae0984
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64c8a10 VA: 0x7598ae0a10
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64c8a9c VA: 0x7598ae0a9c
	public virtual Boolean Equals(SecT571FieldElement other) { }
	// RVA: 0x64c8ac8 VA: 0x7598ae0ac8
	public override Int32 GetHashCode() { }
}
```