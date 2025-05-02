# SecP521R1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP521R1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x649e140 VA: 0x7598ab6140
	public Void .ctor(BigInteger x) { }
	// RVA: 0x649ef1c VA: 0x7598ab6f1c
	public Void .ctor() { }
	// RVA: 0x649ef4c VA: 0x7598ab6f4c
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x649ef7c VA: 0x7598ab6f7c
	public override Boolean get_IsZero() { }
	// RVA: 0x649ef8c VA: 0x7598ab6f8c
	public override Boolean get_IsOne() { }
	// RVA: 0x649ef9c VA: 0x7598ab6f9c
	public override Boolean TestBitZero() { }
	// RVA: 0x649efc0 VA: 0x7598ab6fc0
	public override BigInteger ToBigInteger() { }
	// RVA: 0x649efd0 VA: 0x7598ab6fd0
	public override String get_FieldName() { }
	// RVA: 0x649f010 VA: 0x7598ab7010
	public override Int32 get_FieldSize() { }
	// RVA: 0x649f074 VA: 0x7598ab7074
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x649f174 VA: 0x7598ab7174
	public override ECFieldElement AddOne() { }
	// RVA: 0x649f22c VA: 0x7598ab722c
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x649f32c VA: 0x7598ab732c
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x649f42c VA: 0x7598ab742c
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x649f570 VA: 0x7598ab7570
	public override ECFieldElement Negate() { }
	// RVA: 0x649f628 VA: 0x7598ab7628
	public override ECFieldElement Square() { }
	// RVA: 0x649f6e0 VA: 0x7598ab76e0
	public override ECFieldElement Invert() { }
	// RVA: 0x649f7d8 VA: 0x7598ab77d8
	public override ECFieldElement Sqrt() { }
	// RVA: 0x649f8f4 VA: 0x7598ab78f4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x649f980 VA: 0x7598ab7980
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x649fa0c VA: 0x7598ab7a0c
	public virtual Boolean Equals(SecP521R1FieldElement other) { }
	// RVA: 0x649fa40 VA: 0x7598ab7a40
	public override Int32 GetHashCode() { }
	// RVA: 0x649fad0 VA: 0x7598ab7ad0
	private static Void .cctor() { }
}
```