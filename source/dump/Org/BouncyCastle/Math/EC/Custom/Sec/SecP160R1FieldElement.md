# SecP160R1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160R1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x64815c8 VA: 0x7598a995c8
	public Void .ctor(BigInteger x) { }
	// RVA: 0x6482680 VA: 0x7598a9a680
	public Void .ctor() { }
	// RVA: 0x64826ac VA: 0x7598a9a6ac
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x64826dc VA: 0x7598a9a6dc
	public override Boolean get_IsZero() { }
	// RVA: 0x64826e8 VA: 0x7598a9a6e8
	public override Boolean get_IsOne() { }
	// RVA: 0x64826f4 VA: 0x7598a9a6f4
	public override Boolean TestBitZero() { }
	// RVA: 0x6482718 VA: 0x7598a9a718
	public override BigInteger ToBigInteger() { }
	// RVA: 0x6482724 VA: 0x7598a9a724
	public override String get_FieldName() { }
	// RVA: 0x6482764 VA: 0x7598a9a764
	public override Int32 get_FieldSize() { }
	// RVA: 0x64827c8 VA: 0x7598a9a7c8
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64828c4 VA: 0x7598a9a8c4
	public override ECFieldElement AddOne() { }
	// RVA: 0x6482978 VA: 0x7598a9a978
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x6482a74 VA: 0x7598a9aa74
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x6482b70 VA: 0x7598a9ab70
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x6482cb0 VA: 0x7598a9acb0
	public override ECFieldElement Negate() { }
	// RVA: 0x6482d64 VA: 0x7598a9ad64
	public override ECFieldElement Square() { }
	// RVA: 0x6482e18 VA: 0x7598a9ae18
	public override ECFieldElement Invert() { }
	// RVA: 0x6482f0c VA: 0x7598a9af0c
	public override ECFieldElement Sqrt() { }
	// RVA: 0x648310c VA: 0x7598a9b10c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6483198 VA: 0x7598a9b198
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x6483224 VA: 0x7598a9b224
	public virtual Boolean Equals(SecP160R1FieldElement other) { }
	// RVA: 0x6483250 VA: 0x7598a9b250
	public override Int32 GetHashCode() { }
	// RVA: 0x64832e0 VA: 0x7598a9b2e0
	private static Void .cctor() { }
}
```