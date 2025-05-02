# SecT163Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT163Field
{
	private const UInt64 M35; // 0x0
	private const UInt64 M55; // 0x0
	private static readonly UInt64[] ROOT_Z; // 0x0


	// RVA: 0x64aa2b8 VA: 0x7598ac22b8
	public static Void Add(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64aa360 VA: 0x7598ac2360
	public static Void AddExt(UInt64[] xx, UInt64[] yy, UInt64[] zz) { }
	// RVA: 0x64aa498 VA: 0x7598ac2498
	public static Void AddOne(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64aa508 VA: 0x7598ac2508
	public static UInt64[] FromBigInteger(BigInteger x) { }
	// RVA: 0x64aa5e8 VA: 0x7598ac25e8
	public static Void Invert(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64aa91c VA: 0x7598ac291c
	public static Void Multiply(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64aadc0 VA: 0x7598ac2dc0
	public static Void MultiplyAddToExt(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64aaccc VA: 0x7598ac2ccc
	public static Void Reduce(UInt64[] xx, UInt64[] z) { }
	// RVA: 0x64aa57c VA: 0x7598ac257c
	public static Void Reduce29(UInt64[] z, Int32 zOff) { }
	// RVA: 0x64aae4c VA: 0x7598ac2e4c
	public static Void Sqrt(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64aa7d4 VA: 0x7598ac27d4
	public static Void Square(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64ab040 VA: 0x7598ac3040
	public static Void SquareAddToExt(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64aa854 VA: 0x7598ac2854
	public static Void SquareN(UInt64[] x, Int32 n, UInt64[] z) { }
	// RVA: 0x64ab0c4 VA: 0x7598ac30c4
	public static UInt32 Trace(UInt64[] x) { }
	// RVA: 0x64ab0fc VA: 0x7598ac30fc
	protected static Void ImplCompactExt(UInt64[] zz) { }
	// RVA: 0x64aa9a4 VA: 0x7598ac29a4
	protected static Void ImplMultiply(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64ab188 VA: 0x7598ac3188
	protected static Void ImplMulw(UInt64 x, UInt64 y, UInt64[] z, Int32 zOff) { }
	// RVA: 0x64aaf90 VA: 0x7598ac2f90
	protected static Void ImplSquare(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64ab328 VA: 0x7598ac3328
	public Void .ctor() { }
	// RVA: 0x64ab330 VA: 0x7598ac3330
	private static Void .cctor() { }
}
```