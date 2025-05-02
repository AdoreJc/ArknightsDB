# SecP160R1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160R1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P4; // 0x0
	private const UInt32 PExt9; // 0x0
	private const UInt32 PInv; // 0x0


	// RVA: 0x6481974 VA: 0x7598a99974
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6481a4c VA: 0x7598a99a4c
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x6481b80 VA: 0x7598a99b80
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6481c48 VA: 0x7598a99c48
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x6481d14 VA: 0x7598a99d14
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6481dd0 VA: 0x7598a99dd0
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6481f88 VA: 0x7598a99f88
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x64820b8 VA: 0x7598a9a0b8
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6481e58 VA: 0x7598a99e58
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x6482148 VA: 0x7598a9a148
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x6482218 VA: 0x7598a9a218
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6482298 VA: 0x7598a9a298
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x6482364 VA: 0x7598a9a364
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6482398 VA: 0x7598a9a398
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x648247c VA: 0x7598a9a47c
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6482548 VA: 0x7598a9a548
	public Void .ctor() { }
	// RVA: 0x6482550 VA: 0x7598a9a550
	private static Void .cctor() { }
}
```