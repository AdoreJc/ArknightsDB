# SecP256R1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP256R1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	internal const UInt32 P7; // 0x0
	internal const UInt32 PExt15; // 0x0


	// RVA: 0x6497df8 VA: 0x7598aafdf8
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6497fc4 VA: 0x7598aaffc4
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x64980bc VA: 0x7598ab00bc
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6498188 VA: 0x7598ab0188
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x6498254 VA: 0x7598ab0254
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6498310 VA: 0x7598ab0310
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6498580 VA: 0x7598ab0580
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x6498674 VA: 0x7598ab0674
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6498398 VA: 0x7598ab0398
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x6498704 VA: 0x7598ab0704
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x6498894 VA: 0x7598ab0894
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6498914 VA: 0x7598ab0914
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x64989e0 VA: 0x7598ab09e0
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6498b5c VA: 0x7598ab0b5c
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x6498c00 VA: 0x7598ab0c00
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6497ed4 VA: 0x7598aafed4
	private static Void AddPInvTo(UInt32[] z) { }
	// RVA: 0x6498a6c VA: 0x7598ab0a6c
	private static Void SubPInvFrom(UInt32[] z) { }
	// RVA: 0x6498cd0 VA: 0x7598ab0cd0
	public Void .ctor() { }
	// RVA: 0x6498cd8 VA: 0x7598ab0cd8
	private static Void .cctor() { }
}
```