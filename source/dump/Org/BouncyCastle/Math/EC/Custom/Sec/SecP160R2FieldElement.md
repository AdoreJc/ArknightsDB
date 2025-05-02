# SecP160R2FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160R2FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x647fad4 VA: 0x7598a97ad4
	public Void .ctor(BigInteger x) { }
	// RVA: 0x6484f98 VA: 0x7598a9cf98
	public Void .ctor() { }
	// RVA: 0x6480834 VA: 0x7598a98834
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x6484fc4 VA: 0x7598a9cfc4
	public override Boolean get_IsZero() { }
	// RVA: 0x6484fd0 VA: 0x7598a9cfd0
	public override Boolean get_IsOne() { }
	// RVA: 0x6484fdc VA: 0x7598a9cfdc
	public override Boolean TestBitZero() { }
	// RVA: 0x6485000 VA: 0x7598a9d000
	public override BigInteger ToBigInteger() { }
	// RVA: 0x648500c VA: 0x7598a9d00c
	public override String get_FieldName() { }
	// RVA: 0x648504c VA: 0x7598a9d04c
	public override Int32 get_FieldSize() { }
	// RVA: 0x64850b0 VA: 0x7598a9d0b0
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x64851ac VA: 0x7598a9d1ac
	public override ECFieldElement AddOne() { }
	// RVA: 0x6485260 VA: 0x7598a9d260
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x648535c VA: 0x7598a9d35c
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x6485458 VA: 0x7598a9d458
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x6485598 VA: 0x7598a9d598
	public override ECFieldElement Negate() { }
	// RVA: 0x648564c VA: 0x7598a9d64c
	public override ECFieldElement Square() { }
	// RVA: 0x6485700 VA: 0x7598a9d700
	public override ECFieldElement Invert() { }
	// RVA: 0x64857f4 VA: 0x7598a9d7f4
	public override ECFieldElement Sqrt() { }
	// RVA: 0x6485af4 VA: 0x7598a9daf4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6485b80 VA: 0x7598a9db80
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x6485c0c VA: 0x7598a9dc0c
	public virtual Boolean Equals(SecP160R2FieldElement other) { }
	// RVA: 0x6485c38 VA: 0x7598a9dc38
	public override Int32 GetHashCode() { }
	// RVA: 0x6485cc8 VA: 0x7598a9dcc8
	private static Void .cctor() { }
}
```