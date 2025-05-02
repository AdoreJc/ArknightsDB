# Curve25519FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Djb`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Djb
internal class Curve25519FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	private static readonly UInt32[] PRECOMP_POW2; // 0x8
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x64cbf38 VA: 0x7598ae3f38
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64cd1d8 VA: 0x7598ae51d8
	public Void .ctor() { }
	// RVA: 0x64cd204 VA: 0x7598ae5204
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x64cd234 VA: 0x7598ae5234
	public override Boolean get_IsZero() { }
	// RVA: 0x64cd240 VA: 0x7598ae5240
	public override Boolean get_IsOne() { }
	// RVA: 0x64cd24c VA: 0x7598ae524c
	public override Boolean TestBitZero() { }
	// RVA: 0x64cd270 VA: 0x7598ae5270
	public override BigInteger ToBigInteger() { }
	// RVA: 0x64cd27c VA: 0x7598ae527c
	public override String get_FieldName() { }
	// RVA: 0x64cd2bc VA: 0x7598ae52bc
	public override Int32 get_FieldSize() { }
	// RVA: 0x64cd320 VA: 0x7598ae5320
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64cd41c VA: 0x7598ae541c
	public override ECFieldElement AddOne() { }
	// RVA: 0x64cd4d0 VA: 0x7598ae54d0
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64cd5cc VA: 0x7598ae55cc
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64cd6c8 VA: 0x7598ae56c8
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64cd808 VA: 0x7598ae5808
	public override ECFieldElement Negate() { }
	// RVA: 0x64cd8bc VA: 0x7598ae58bc
	public override ECFieldElement Square() { }
	// RVA: 0x64cd970 VA: 0x7598ae5970
	public override ECFieldElement Invert() { }
	// RVA: 0x64cda64 VA: 0x7598ae5a64
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64cdd40 VA: 0x7598ae5d40
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64cddcc VA: 0x7598ae5dcc
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64cde58 VA: 0x7598ae5e58
	public virtual Boolean Equals(Curve25519FieldElement other) { }
	// RVA: 0x64cde84 VA: 0x7598ae5e84
	public override Int32 GetHashCode() { }
	// RVA: 0x64cdf14 VA: 0x7598ae5f14
	private static Void .cctor() { }
}
```