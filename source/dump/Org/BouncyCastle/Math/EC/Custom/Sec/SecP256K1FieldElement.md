# SecP256K1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP256K1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x6494a2c VA: 0x7598aaca2c
	public Void .ctor(BigInteger x) { }
	// RVA: 0x6495aa4 VA: 0x7598aadaa4
	public Void .ctor() { }
	// RVA: 0x6495ad0 VA: 0x7598aadad0
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x6495b00 VA: 0x7598aadb00
	public override Boolean get_IsZero() { }
	// RVA: 0x6495b0c VA: 0x7598aadb0c
	public override Boolean get_IsOne() { }
	// RVA: 0x6495b18 VA: 0x7598aadb18
	public override Boolean TestBitZero() { }
	// RVA: 0x6495b3c VA: 0x7598aadb3c
	public override BigInteger ToBigInteger() { }
	// RVA: 0x6495b48 VA: 0x7598aadb48
	public override String get_FieldName() { }
	// RVA: 0x6495b88 VA: 0x7598aadb88
	public override Int32 get_FieldSize() { }
	// RVA: 0x6495bec VA: 0x7598aadbec
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x6495ce8 VA: 0x7598aadce8
	public override ECFieldElement AddOne() { }
	// RVA: 0x6495d9c VA: 0x7598aadd9c
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x6495e98 VA: 0x7598aade98
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x6495f94 VA: 0x7598aadf94
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64960d4 VA: 0x7598aae0d4
	public override ECFieldElement Negate() { }
	// RVA: 0x6496188 VA: 0x7598aae188
	public override ECFieldElement Square() { }
	// RVA: 0x649623c VA: 0x7598aae23c
	public override ECFieldElement Invert() { }
	// RVA: 0x6496330 VA: 0x7598aae330
	public override ECFieldElement Sqrt() { }
	// RVA: 0x6496610 VA: 0x7598aae610
	public override Boolean Equals(Object obj) { }
	// RVA: 0x649669c VA: 0x7598aae69c
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x6496728 VA: 0x7598aae728
	public virtual Boolean Equals(SecP256K1FieldElement other) { }
	// RVA: 0x6496754 VA: 0x7598aae754
	public override Int32 GetHashCode() { }
	// RVA: 0x64967e4 VA: 0x7598aae7e4
	private static Void .cctor() { }
}
```