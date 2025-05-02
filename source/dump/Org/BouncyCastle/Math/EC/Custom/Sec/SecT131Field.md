# SecT131Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT131Field
{
	private const UInt64 M03; // 0x0
	private const UInt64 M44; // 0x0
	private static readonly UInt64[] ROOT_Z; // 0x0


	// RVA: 0x64a5430 VA: 0x7598abd430
	public static Void Add(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64a54d8 VA: 0x7598abd4d8
	public static Void AddExt(UInt64[] xx, UInt64[] yy, UInt64[] zz) { }
	// RVA: 0x64a55e0 VA: 0x7598abd5e0
	public static Void AddOne(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64a5650 VA: 0x7598abd650
	public static UInt64[] FromBigInteger(BigInteger x) { }
	// RVA: 0x64a5754 VA: 0x7598abd754
	public static Void Invert(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64a599c VA: 0x7598abd99c
	public static Void Multiply(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64a5f00 VA: 0x7598abdf00
	public static Void MultiplyAddToExt(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64a5e20 VA: 0x7598abde20
	public static Void Reduce(UInt64[] xx, UInt64[] z) { }
	// RVA: 0x64a56c4 VA: 0x7598abd6c4
	public static Void Reduce61(UInt64[] z, Int32 zOff) { }
	// RVA: 0x64a5f8c VA: 0x7598abdf8c
	public static Void Sqrt(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64a5918 VA: 0x7598abd918
	public static Void Square(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64a6160 VA: 0x7598abe160
	public static Void SquareAddToExt(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64a5a24 VA: 0x7598abda24
	public static Void SquareN(UInt64[] x, Int32 n, UInt64[] z) { }
	// RVA: 0x64a61e8 VA: 0x7598abe1e8
	public static UInt32 Trace(UInt64[] x) { }
	// RVA: 0x64a6230 VA: 0x7598abe230
	protected static Void ImplCompactExt(UInt64[] zz) { }
	// RVA: 0x64a5af0 VA: 0x7598abdaf0
	protected static Void ImplMultiply(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64a62c0 VA: 0x7598abe2c0
	protected static Void ImplMulw(UInt64 x, UInt64 y, UInt64[] z, Int32 zOff) { }
	// RVA: 0x64a60d0 VA: 0x7598abe0d0
	protected static Void ImplSquare(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64a64a4 VA: 0x7598abe4a4
	public Void .ctor() { }
	// RVA: 0x64a64ac VA: 0x7598abe4ac
	private static Void .cctor() { }
}
```