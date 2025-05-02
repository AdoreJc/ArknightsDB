# SecP192K1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP192K1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P5; // 0x0
	private const UInt32 PExt11; // 0x0
	private const UInt32 PInv33; // 0x0


	// RVA: 0x64872e0 VA: 0x7598a9f2e0
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x64873b8 VA: 0x7598a9f3b8
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x64874ec VA: 0x7598a9f4ec
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64875b4 VA: 0x7598a9f5b4
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x6487680 VA: 0x7598a9f680
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648773c VA: 0x7598a9f73c
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x64878b4 VA: 0x7598a9f8b4
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x64879e4 VA: 0x7598a9f9e4
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64877c4 VA: 0x7598a9f7c4
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x6487a74 VA: 0x7598a9fa74
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x6487b44 VA: 0x7598a9fb44
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6487bc4 VA: 0x7598a9fbc4
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x6487c90 VA: 0x7598a9fc90
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6487cc4 VA: 0x7598a9fcc4
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x6487da8 VA: 0x7598a9fda8
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6487e74 VA: 0x7598a9fe74
	public Void .ctor() { }
	// RVA: 0x6487e7c VA: 0x7598a9fe7c
	private static Void .cctor() { }
}
```