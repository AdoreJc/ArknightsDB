# SecT409Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT409Field
{
	private const UInt64 M25; // 0x0
	private const UInt64 M59; // 0x0


	// RVA: 0x64c2460 VA: 0x7598ada460
	public static Void Add(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64c25c8 VA: 0x7598ada5c8
	public static Void AddExt(UInt64[] xx, UInt64[] yy, UInt64[] zz) { }
	// RVA: 0x64c2638 VA: 0x7598ada638
	public static Void AddOne(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64c2718 VA: 0x7598ada718
	public static UInt64[] FromBigInteger(BigInteger x) { }
	// RVA: 0x64c27bc VA: 0x7598ada7bc
	public static Void Invert(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64c2a54 VA: 0x7598adaa54
	public static Void Multiply(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64c2cd0 VA: 0x7598adacd0
	public static Void MultiplyAddToExt(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64c2b70 VA: 0x7598adab70
	public static Void Reduce(UInt64[] xx, UInt64[] z) { }
	// RVA: 0x64c273c VA: 0x7598ada73c
	public static Void Reduce39(UInt64[] z, Int32 zOff) { }
	// RVA: 0x64c2d20 VA: 0x7598adad20
	public static Void Sqrt(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64c2994 VA: 0x7598ada994
	public static Void Square(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64c2f88 VA: 0x7598adaf88
	public static Void SquareAddToExt(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64c29d4 VA: 0x7598ada9d4
	public static Void SquareN(UInt64[] x, Int32 n, UInt64[] z) { }
	// RVA: 0x64c2fcc VA: 0x7598adafcc
	public static UInt32 Trace(UInt64[] x) { }
	// RVA: 0x64c2ff4 VA: 0x7598adaff4
	protected static Void ImplCompactExt(UInt64[] zz) { }
	// RVA: 0x64c3120 VA: 0x7598adb120
	protected static Void ImplExpand(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64c2aa0 VA: 0x7598adaaa0
	protected static Void ImplMultiply(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64c3208 VA: 0x7598adb208
	protected static Void ImplMulwAcc(UInt64[] xs, UInt64 y, UInt64[] z, Int32 zOff) { }
	// RVA: 0x64c2ef0 VA: 0x7598adaef0
	protected static Void ImplSquare(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64c33e4 VA: 0x7598adb3e4
	public Void .ctor() { }
}
```