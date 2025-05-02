# SecT283Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT283Field
{
	private const UInt64 M27; // 0x0
	private const UInt64 M57; // 0x0
	private static readonly UInt64[] ROOT_Z; // 0x0


	// RVA: 0x64bd27c VA: 0x7598ad527c
	public static Void Add(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64bd384 VA: 0x7598ad5384
	public static Void AddExt(UInt64[] xx, UInt64[] yy, UInt64[] zz) { }
	// RVA: 0x64bd54c VA: 0x7598ad554c
	public static Void AddOne(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64bd5f4 VA: 0x7598ad55f4
	public static UInt64[] FromBigInteger(BigInteger x) { }
	// RVA: 0x64bd6d4 VA: 0x7598ad56d4
	public static Void Invert(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64bd974 VA: 0x7598ad5974
	public static Void Multiply(UInt64[] x, UInt64[] y, UInt64[] z) { }
	// RVA: 0x64be1c8 VA: 0x7598ad61c8
	public static Void MultiplyAddToExt(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64be07c VA: 0x7598ad607c
	public static Void Reduce(UInt64[] xx, UInt64[] z) { }
	// RVA: 0x64bd668 VA: 0x7598ad5668
	public static Void Reduce37(UInt64[] z, Int32 zOff) { }
	// RVA: 0x64be254 VA: 0x7598ad6254
	public static Void Sqrt(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64bd8f0 VA: 0x7598ad58f0
	public static Void Square(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64be4a0 VA: 0x7598ad64a0
	public static Void SquareAddToExt(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64bd9fc VA: 0x7598ad59fc
	public static Void SquareN(UInt64[] x, Int32 n, UInt64[] z) { }
	// RVA: 0x64be528 VA: 0x7598ad6528
	public static UInt32 Trace(UInt64[] x) { }
	// RVA: 0x64be560 VA: 0x7598ad6560
	protected static Void ImplCompactExt(UInt64[] zz) { }
	// RVA: 0x64be63c VA: 0x7598ad663c
	protected static Void ImplExpand(UInt64[] x, UInt64[] z) { }
	// RVA: 0x64bdac8 VA: 0x7598ad5ac8
	protected static Void ImplMultiply(UInt64[] x, UInt64[] y, UInt64[] zz) { }
	// RVA: 0x64be6e8 VA: 0x7598ad66e8
	protected static Void ImplMulw(UInt64 x, UInt64 y, UInt64[] z, Int32 zOff) { }
	// RVA: 0x64be408 VA: 0x7598ad6408
	protected static Void ImplSquare(UInt64[] x, UInt64[] zz) { }
	// RVA: 0x64be8a8 VA: 0x7598ad68a8
	public Void .ctor() { }
	// RVA: 0x64be8b0 VA: 0x7598ad68b0
	private static Void .cctor() { }
}
```