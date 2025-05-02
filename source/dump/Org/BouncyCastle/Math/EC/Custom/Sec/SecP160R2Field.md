# SecP160R2Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160R2Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P4; // 0x0
	private const UInt32 PExt9; // 0x0
	private const UInt32 PInv33; // 0x0


	// RVA: 0x6484854 VA: 0x7598a9c854
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x648492c VA: 0x7598a9c92c
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x6484a60 VA: 0x7598a9ca60
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6484b28 VA: 0x7598a9cb28
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x6484bf4 VA: 0x7598a9cbf4
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6480618 VA: 0x7598a98618
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6480864 VA: 0x7598a98864
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x64806d4 VA: 0x7598a986d4
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6480994 VA: 0x7598a98994
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x6480764 VA: 0x7598a98764
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x6480598 VA: 0x7598a98598
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6484cb0 VA: 0x7598a9ccb0
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x64806a0 VA: 0x7598a986a0
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6484d7c VA: 0x7598a9cd7c
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x6480f00 VA: 0x7598a98f00
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6484e60 VA: 0x7598a9ce60
	public Void .ctor() { }
	// RVA: 0x6484e68 VA: 0x7598a9ce68
	private static Void .cctor() { }
}
```