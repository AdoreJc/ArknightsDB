# SecP192R1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP192R1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x6489f30 VA: 0x7598aa1f30
	public Void .ctor(BigInteger x) { }
	// RVA: 0x648b260 VA: 0x7598aa3260
	public Void .ctor() { }
	// RVA: 0x648b28c VA: 0x7598aa328c
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x648b2bc VA: 0x7598aa32bc
	public override Boolean get_IsZero() { }
	// RVA: 0x648b2c8 VA: 0x7598aa32c8
	public override Boolean get_IsOne() { }
	// RVA: 0x648b2d4 VA: 0x7598aa32d4
	public override Boolean TestBitZero() { }
	// RVA: 0x648b2f8 VA: 0x7598aa32f8
	public override BigInteger ToBigInteger() { }
	// RVA: 0x648b304 VA: 0x7598aa3304
	public override String get_FieldName() { }
	// RVA: 0x648b344 VA: 0x7598aa3344
	public override Int32 get_FieldSize() { }
	// RVA: 0x648b3a8 VA: 0x7598aa33a8
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x648b4a4 VA: 0x7598aa34a4
	public override ECFieldElement AddOne() { }
	// RVA: 0x648b558 VA: 0x7598aa3558
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x648b654 VA: 0x7598aa3654
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x648b750 VA: 0x7598aa3750
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x648b890 VA: 0x7598aa3890
	public override ECFieldElement Negate() { }
	// RVA: 0x648b944 VA: 0x7598aa3944
	public override ECFieldElement Square() { }
	// RVA: 0x648b9f8 VA: 0x7598aa39f8
	public override ECFieldElement Invert() { }
	// RVA: 0x648baec VA: 0x7598aa3aec
	public override ECFieldElement Sqrt() { }
	// RVA: 0x648bcd0 VA: 0x7598aa3cd0
	public override Boolean Equals(Object obj) { }
	// RVA: 0x648bd5c VA: 0x7598aa3d5c
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x648bde8 VA: 0x7598aa3de8
	public virtual Boolean Equals(SecP192R1FieldElement other) { }
	// RVA: 0x648be14 VA: 0x7598aa3e14
	public override Int32 GetHashCode() { }
	// RVA: 0x648bea4 VA: 0x7598aa3ea4
	private static Void .cctor() { }
}
```