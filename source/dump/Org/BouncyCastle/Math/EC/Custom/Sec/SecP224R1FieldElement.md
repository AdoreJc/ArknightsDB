# SecP224R1FieldElement

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP224R1FieldElement : ECFieldElement
{
	public static readonly BigInteger Q; // 0x0
	protected internal readonly UInt32[] x; // 0x10

	public override Boolean IsZero { get; }
	public override Boolean IsOne { get; }
	public override String FieldName { get; }
	public override Int32 FieldSize { get; }

	// RVA: 0x649022c VA: 0x7598aa822c
	public Void .ctor(BigInteger x) { }
	// RVA: 0x64915bc VA: 0x7598aa95bc
	public Void .ctor() { }
	// RVA: 0x64915e8 VA: 0x7598aa95e8
	protected internal Void .ctor(UInt32[] x) { }
	// RVA: 0x6491618 VA: 0x7598aa9618
	public override Boolean get_IsZero() { }
	// RVA: 0x6491624 VA: 0x7598aa9624
	public override Boolean get_IsOne() { }
	// RVA: 0x6491630 VA: 0x7598aa9630
	public override Boolean TestBitZero() { }
	// RVA: 0x6491654 VA: 0x7598aa9654
	public override BigInteger ToBigInteger() { }
	// RVA: 0x6491660 VA: 0x7598aa9660
	public override String get_FieldName() { }
	// RVA: 0x64916a0 VA: 0x7598aa96a0
	public override Int32 get_FieldSize() { }
	// RVA: 0x6491704 VA: 0x7598aa9704
	public override ECFieldElement Add(ECFieldElement b) { }
	// RVA: 0x6491800 VA: 0x7598aa9800
	public override ECFieldElement AddOne() { }
	// RVA: 0x64918b4 VA: 0x7598aa98b4
	public override ECFieldElement Subtract(ECFieldElement b) { }
	// RVA: 0x64919b0 VA: 0x7598aa99b0
	public override ECFieldElement Multiply(ECFieldElement b) { }
	// RVA: 0x6491aac VA: 0x7598aa9aac
	public override ECFieldElement Divide(ECFieldElement b) { }
	// RVA: 0x6491bec VA: 0x7598aa9bec
	public override ECFieldElement Negate() { }
	// RVA: 0x6491ca0 VA: 0x7598aa9ca0
	public override ECFieldElement Square() { }
	// RVA: 0x6491d54 VA: 0x7598aa9d54
	public override ECFieldElement Invert() { }
	// RVA: 0x6491e48 VA: 0x7598aa9e48
	public override ECFieldElement Sqrt() { }
	// RVA: 0x64922e0 VA: 0x7598aaa2e0
	public override Boolean Equals(Object obj) { }
	// RVA: 0x649236c VA: 0x7598aaa36c
	public override Boolean Equals(ECFieldElement other) { }
	// RVA: 0x64923f8 VA: 0x7598aaa3f8
	public virtual Boolean Equals(SecP224R1FieldElement other) { }
	// RVA: 0x6492424 VA: 0x7598aaa424
	public override Int32 GetHashCode() { }
	// RVA: 0x6492010 VA: 0x7598aaa010
	private static Boolean IsSquare(UInt32[] x) { }
	// RVA: 0x64924b4 VA: 0x7598aaa4b4
	private static Void RM(UInt32[] nc, UInt32[] d0, UInt32[] e0, UInt32[] d1, UInt32[] e1, UInt32[] f1, UInt32[] t) { }
	// RVA: 0x64925cc VA: 0x7598aaa5cc
	private static Void RP(UInt32[] nc, UInt32[] d1, UInt32[] e1, UInt32[] f1, UInt32[] t) { }
	// RVA: 0x64926f0 VA: 0x7598aaa6f0
	private static Void RS(UInt32[] d, UInt32[] e, UInt32[] f, UInt32[] t) { }
	// RVA: 0x64920fc VA: 0x7598aaa0fc
	private static Boolean TrySqrt(UInt32[] nc, UInt32[] r, UInt32[] t) { }
	// RVA: 0x64927c0 VA: 0x7598aaa7c0
	private static Void .cctor() { }
}
```