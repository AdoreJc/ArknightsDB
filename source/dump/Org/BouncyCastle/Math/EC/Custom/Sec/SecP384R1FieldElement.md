# SecP384R1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP384R1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x649acec VA: 0x7598ab2cec
	public Void .ctor(BigInteger x) { }
	// RVA: 0x649c074 VA: 0x7598ab4074
	public Void .ctor() { }
	// RVA: 0x649c0a4 VA: 0x7598ab40a4
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x649c0d4 VA: 0x7598ab40d4
	public override Boolean get_IsZero() { }
	// RVA: 0x649c0e4 VA: 0x7598ab40e4
	public override Boolean get_IsOne() { }
	// RVA: 0x649c0f4 VA: 0x7598ab40f4
	public override Boolean TestBitZero() { }
	// RVA: 0x649c118 VA: 0x7598ab4118
	public override BigInteger ToBigInteger() { }
	// RVA: 0x649c128 VA: 0x7598ab4128
	public override String get_FieldName() { }
	// RVA: 0x649c168 VA: 0x7598ab4168
	public override Int32 get_FieldSize() { }
	// RVA: 0x649c1cc VA: 0x7598ab41cc
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x649c2cc VA: 0x7598ab42cc
	public override ECFieldElement AddOne() { }
	// RVA: 0x649c384 VA: 0x7598ab4384
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x649c484 VA: 0x7598ab4484
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x649c584 VA: 0x7598ab4584
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x649c6c8 VA: 0x7598ab46c8
	public override ECFieldElement Negate() { }
	// RVA: 0x649c780 VA: 0x7598ab4780
	public override ECFieldElement Square() { }
	// RVA: 0x649c838 VA: 0x7598ab4838
	public override ECFieldElement Invert() { }
	// RVA: 0x649c930 VA: 0x7598ab4930
	public override ECFieldElement Sqrt() { }
	// RVA: 0x649cc0c VA: 0x7598ab4c0c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x649cc98 VA: 0x7598ab4c98
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x649cd24 VA: 0x7598ab4d24
	public virtual Boolean Equals(SecP384R1FieldElement other) { }
	// RVA: 0x649cd58 VA: 0x7598ab4d58
	public override Int32 GetHashCode() { }
	// RVA: 0x649cde8 VA: 0x7598ab4de8
	private static Void .cctor() { }
}
```