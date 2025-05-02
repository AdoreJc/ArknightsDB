# SecP224K1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP224K1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	private static readonly UInt32[] PRECOMP_POW2; // 0x8
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x648d110 VA: 0x7598aa5110
	public Void .ctor(BigInteger x) { }
	// RVA: 0x648e188 VA: 0x7598aa6188
	public Void .ctor() { }
	// RVA: 0x648e1b4 VA: 0x7598aa61b4
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x648e1e4 VA: 0x7598aa61e4
	public override Boolean get_IsZero() { }
	// RVA: 0x648e1f0 VA: 0x7598aa61f0
	public override Boolean get_IsOne() { }
	// RVA: 0x648e1fc VA: 0x7598aa61fc
	public override Boolean TestBitZero() { }
	// RVA: 0x648e220 VA: 0x7598aa6220
	public override BigInteger ToBigInteger() { }
	// RVA: 0x648e22c VA: 0x7598aa622c
	public override String get_FieldName() { }
	// RVA: 0x648e26c VA: 0x7598aa626c
	public override Int32 get_FieldSize() { }
	// RVA: 0x648e2d0 VA: 0x7598aa62d0
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x648e3cc VA: 0x7598aa63cc
	public override ECFieldElement AddOne() { }
	// RVA: 0x648e480 VA: 0x7598aa6480
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x648e57c VA: 0x7598aa657c
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x648e678 VA: 0x7598aa6678
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x648e7b8 VA: 0x7598aa67b8
	public override ECFieldElement Negate() { }
	// RVA: 0x648e86c VA: 0x7598aa686c
	public override ECFieldElement Square() { }
	// RVA: 0x648e920 VA: 0x7598aa6920
	public override ECFieldElement Invert() { }
	// RVA: 0x648ea14 VA: 0x7598aa6a14
	public override ECFieldElement Sqrt() { }
	// RVA: 0x648ed90 VA: 0x7598aa6d90
	public override Boolean Equals(Object obj) { }
	// RVA: 0x648ee1c VA: 0x7598aa6e1c
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x648eea8 VA: 0x7598aa6ea8
	public virtual Boolean Equals(SecP224K1FieldElement other) { }
	// RVA: 0x648eed4 VA: 0x7598aa6ed4
	public override Int32 GetHashCode() { }
	// RVA: 0x648ef64 VA: 0x7598aa6f64
	private static Void .cctor() { }
}
```