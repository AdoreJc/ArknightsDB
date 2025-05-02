# SecP192K1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP192K1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x6486f34 VA: 0x7598a9ef34
	public Void .ctor(BigInteger x) { }
	// RVA: 0x6487fac VA: 0x7598a9ffac
	public Void .ctor() { }
	// RVA: 0x6487fd8 VA: 0x7598a9ffd8
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x6488008 VA: 0x7598aa0008
	public override Boolean get_IsZero() { }
	// RVA: 0x6488014 VA: 0x7598aa0014
	public override Boolean get_IsOne() { }
	// RVA: 0x6488020 VA: 0x7598aa0020
	public override Boolean TestBitZero() { }
	// RVA: 0x6488044 VA: 0x7598aa0044
	public override BigInteger ToBigInteger() { }
	// RVA: 0x6488050 VA: 0x7598aa0050
	public override String get_FieldName() { }
	// RVA: 0x6488090 VA: 0x7598aa0090
	public override Int32 get_FieldSize() { }
	// RVA: 0x64880f4 VA: 0x7598aa00f4
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64881f0 VA: 0x7598aa01f0
	public override ECFieldElement AddOne() { }
	// RVA: 0x64882a4 VA: 0x7598aa02a4
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64883a0 VA: 0x7598aa03a0
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x648849c VA: 0x7598aa049c
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64885dc VA: 0x7598aa05dc
	public override ECFieldElement Negate() { }
	// RVA: 0x6488690 VA: 0x7598aa0690
	public override ECFieldElement Square() { }
	// RVA: 0x6488744 VA: 0x7598aa0744
	public override ECFieldElement Invert() { }
	// RVA: 0x6488838 VA: 0x7598aa0838
	public override ECFieldElement Sqrt() { }
	// RVA: 0x6488af4 VA: 0x7598aa0af4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6488b80 VA: 0x7598aa0b80
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x6488c0c VA: 0x7598aa0c0c
	public virtual Boolean Equals(SecP192K1FieldElement other) { }
	// RVA: 0x6488c38 VA: 0x7598aa0c38
	public override Int32 GetHashCode() { }
	// RVA: 0x6488cc8 VA: 0x7598aa0cc8
	private static Void .cctor() { }
}
```