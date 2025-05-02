# SecT193Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT193Field
{
	private const UInt64 M01; // 0x0
	private const UInt64 M49; // 0x0


	// RVA: 0x64b0750 VA: 0x7598ac8750
	public static Void Add(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64b0828 VA: 0x7598ac8828
	public static Void AddExt(UInt64[] xx, UInt64[] yy, UInt64[] zz) { }
	// RVA: 0x64b0990 VA: 0x7598ac8990
	public static Void AddOne(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64b0a1c VA: 0x7598ac8a1c
	public static UInt64[] FromBigInteger(BigInteger x) { }
	// RVA: 0x64b0ac4 VA: 0x7598ac8ac4
	public static Void Invert(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64b0d08 VA: 0x7598ac8d08
	public static Void Multiply(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64b11a8 VA: 0x7598ac91a8
	public static Void MultiplyAddToExt(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64b10c4 VA: 0x7598ac90c4
	public static Void Reduce(UInt64[] xx, UInt64[] z) { }
	// RVA: 0x64b0a40 VA: 0x7598ac8a40
	public static Void Reduce63(UInt64[] z, Int32 zOff) { }
	// RVA: 0x64b11f8 VA: 0x7598ac91f8
	public static Void Sqrt(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64b0c50 VA: 0x7598ac8c50
	public static Void Square(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64b139c VA: 0x7598ac939c
	public static Void SquareAddToExt(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64b0c8c VA: 0x7598ac8c8c
	public static Void SquareN(UInt64[] x, Int32 n, UInt64[] z) { }
	// RVA: 0x64b13dc VA: 0x7598ac93dc
	public static UInt32 Trace(UInt64[] x) { }
	// RVA: 0x64b1404 VA: 0x7598ac9404
	protected static Void ImplCompactExt(UInt64[] zz) { }
	// RVA: 0x64b14b8 VA: 0x7598ac94b8
	protected static Void ImplExpand(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64b0d54 VA: 0x7598ac8d54
	protected static Void ImplMultiply(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64b1544 VA: 0x7598ac9544
	protected static Void ImplMulwAcc(UInt64 x, UInt64 y, UInt64[] z, Int32 zOff) { }
	// RVA: 0x64b12f4 VA: 0x7598ac92f4
	protected static Void ImplSquare(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64b1738 VA: 0x7598ac9738
	public Void .ctor() { }
}
```