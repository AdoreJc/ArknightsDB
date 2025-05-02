# SecT239Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT239Field
{
	private const UInt64 M47; // 0x0
	private const UInt64 M60; // 0x0


	// RVA: 0x64b9e28 VA: 0x7598ad1e28
	public static Void Add(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64b9f00 VA: 0x7598ad1f00
	public static Void AddExt(UInt64[] xx, UInt64[] yy, UInt64[] zz) { }
	// RVA: 0x64ba098 VA: 0x7598ad2098
	public static Void AddOne(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64ba124 VA: 0x7598ad2124
	public static UInt64[] FromBigInteger(BigInteger x) { }
	// RVA: 0x64ba1c8 VA: 0x7598ad21c8
	public static Void Invert(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64ba3f8 VA: 0x7598ad23f8
	public static Void Multiply(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64ba924 VA: 0x7598ad2924
	public static Void MultiplyAddToExt(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64ba830 VA: 0x7598ad2830
	public static Void Reduce(UInt64[] xx, UInt64[] z) { }
	// RVA: 0x64ba148 VA: 0x7598ad2148
	public static Void Reduce17(UInt64[] z, Int32 zOff) { }
	// RVA: 0x64ba974 VA: 0x7598ad2974
	public static Void Sqrt(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64ba3bc VA: 0x7598ad23bc
	public static Void Square(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64bacb4 VA: 0x7598ad2cb4
	public static Void SquareAddToExt(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64ba444 VA: 0x7598ad2444
	public static Void SquareN(UInt64[] x, Int32 n, UInt64[] z) { }
	// RVA: 0x64bacf4 VA: 0x7598ad2cf4
	public static UInt32 Trace(UInt64[] x) { }
	// RVA: 0x64bad40 VA: 0x7598ad2d40
	protected static Void ImplCompactExt(UInt64[] zz) { }
	// RVA: 0x64badf4 VA: 0x7598ad2df4
	protected static Void ImplExpand(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64ba4c0 VA: 0x7598ad24c0
	protected static Void ImplMultiply(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64bae80 VA: 0x7598ad2e80
	protected static Void ImplMulwAcc(UInt64 x, UInt64 y, UInt64[] z, Int32 zOff) { }
	// RVA: 0x64babe4 VA: 0x7598ad2be4
	protected static Void ImplSquare(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64bb04c VA: 0x7598ad304c
	public Void .ctor() { }
}
```