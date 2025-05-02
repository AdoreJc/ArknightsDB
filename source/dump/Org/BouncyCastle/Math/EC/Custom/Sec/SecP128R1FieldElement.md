# SecP128R1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP128R1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x647cb0c VA: 0x7598a94b0c
	public Void .ctor(BigInteger x) { }
	// RVA: 0x647dc14 VA: 0x7598a95c14
	public Void .ctor() { }
	// RVA: 0x647dc40 VA: 0x7598a95c40
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x647dc70 VA: 0x7598a95c70
	public override Boolean get_IsZero() { }
	// RVA: 0x647dc7c VA: 0x7598a95c7c
	public override Boolean get_IsOne() { }
	// RVA: 0x647dc88 VA: 0x7598a95c88
	public override Boolean TestBitZero() { }
	// RVA: 0x647dcac VA: 0x7598a95cac
	public override BigInteger ToBigInteger() { }
	// RVA: 0x647dcb8 VA: 0x7598a95cb8
	public override String get_FieldName() { }
	// RVA: 0x647dcf8 VA: 0x7598a95cf8
	public override Int32 get_FieldSize() { }
	// RVA: 0x647dd5c VA: 0x7598a95d5c
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x647de58 VA: 0x7598a95e58
	public override ECFieldElement AddOne() { }
	// RVA: 0x647df0c VA: 0x7598a95f0c
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x647e008 VA: 0x7598a96008
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x647e104 VA: 0x7598a96104
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x647e244 VA: 0x7598a96244
	public override ECFieldElement Negate() { }
	// RVA: 0x647e2f8 VA: 0x7598a962f8
	public override ECFieldElement Square() { }
	// RVA: 0x647e3ac VA: 0x7598a963ac
	public override ECFieldElement Invert() { }
	// RVA: 0x647e4a0 VA: 0x7598a964a0
	public override ECFieldElement Sqrt() { }
	// RVA: 0x647e694 VA: 0x7598a96694
	public override Boolean Equals(Object obj) { }
	// RVA: 0x647e720 VA: 0x7598a96720
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x647e7ac VA: 0x7598a967ac
	public virtual Boolean Equals(SecP128R1FieldElement other) { }
	// RVA: 0x647e7d8 VA: 0x7598a967d8
	public override Int32 GetHashCode() { }
	// RVA: 0x647e868 VA: 0x7598a96868
	private static Void .cctor() { }
}
```