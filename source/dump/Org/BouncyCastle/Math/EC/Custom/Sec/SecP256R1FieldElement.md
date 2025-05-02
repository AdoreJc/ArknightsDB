# SecP256R1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP256R1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x6497a4c VA: 0x7598aafa4c
	public Void .ctor(BigInteger x) { }
	// RVA: 0x6498dbc VA: 0x7598ab0dbc
	public Void .ctor() { }
	// RVA: 0x6498de8 VA: 0x7598ab0de8
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x6498e18 VA: 0x7598ab0e18
	public override Boolean get_IsZero() { }
	// RVA: 0x6498e24 VA: 0x7598ab0e24
	public override Boolean get_IsOne() { }
	// RVA: 0x6498e30 VA: 0x7598ab0e30
	public override Boolean TestBitZero() { }
	// RVA: 0x6498e54 VA: 0x7598ab0e54
	public override BigInteger ToBigInteger() { }
	// RVA: 0x6498e60 VA: 0x7598ab0e60
	public override String get_FieldName() { }
	// RVA: 0x6498ea0 VA: 0x7598ab0ea0
	public override Int32 get_FieldSize() { }
	// RVA: 0x6498f04 VA: 0x7598ab0f04
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x6499000 VA: 0x7598ab1000
	public override ECFieldElement AddOne() { }
	// RVA: 0x64990b4 VA: 0x7598ab10b4
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64991b0 VA: 0x7598ab11b0
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x64992ac VA: 0x7598ab12ac
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x64993ec VA: 0x7598ab13ec
	public override ECFieldElement Negate() { }
	// RVA: 0x64994a0 VA: 0x7598ab14a0
	public override ECFieldElement Square() { }
	// RVA: 0x6499554 VA: 0x7598ab1554
	public override ECFieldElement Invert() { }
	// RVA: 0x6499648 VA: 0x7598ab1648
	public override ECFieldElement Sqrt() { }
	// RVA: 0x6499830 VA: 0x7598ab1830
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64998bc VA: 0x7598ab18bc
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x6499948 VA: 0x7598ab1948
	public virtual Boolean Equals(SecP256R1FieldElement other) { }
	// RVA: 0x6499974 VA: 0x7598ab1974
	public override Int32 GetHashCode() { }
	// RVA: 0x6499a04 VA: 0x7598ab1a04
	private static Void .cctor() { }
}
```