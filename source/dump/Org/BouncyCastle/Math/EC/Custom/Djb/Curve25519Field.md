# Curve25519Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Djb`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Djb
internal class Curve25519Field
{
	internal static readonly UInt32[] P; // 0x0
	private const UInt32 P7; // 0x0
	private static readonly UInt32[] PExt; // 0x8
	private const UInt32 PInv; // 0x0


	// RVA: 0x64cc298 VA: 0x7598ae4298
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x64cc3c0 VA: 0x7598ae43c0
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x64cc5e4 VA: 0x7598ae45e4
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64cc694 VA: 0x7598ae4694
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x64cc740 VA: 0x7598ae4740
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64cc7fc VA: 0x7598ae47fc
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x64cc9c0 VA: 0x7598ae49c0
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x64cca78 VA: 0x7598ae4a78
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64cc884 VA: 0x7598ae4884
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x64ccb08 VA: 0x7598ae4b08
	public static Void Reduce27(UInt32 x, UInt32[] z) { }
	// RVA: 0x64ccbf4 VA: 0x7598ae4bf4
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64ccc74 VA: 0x7598ae4c74
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x64ccd40 VA: 0x7598ae4d40
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x64cce44 VA: 0x7598ae4e44
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x64cd038 VA: 0x7598ae5038
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64ccdcc VA: 0x7598ae4dcc
	private static UInt32 AddPTo(UInt32[] z) { }
	// RVA: 0x64cced4 VA: 0x7598ae4ed4
	private static UInt32 AddPExtTo(UInt32[] zz) { }
	// RVA: 0x64cc34c VA: 0x7598ae434c
	private static Int32 SubPFrom(UInt32[] z) { }
	// RVA: 0x64cc47c VA: 0x7598ae447c
	private static Int32 SubPExtFrom(UInt32[] zz) { }
	// RVA: 0x64cd0ec VA: 0x7598ae50ec
	public Void .ctor() { }
	// RVA: 0x64cd0f4 VA: 0x7598ae50f4
	private static Void .cctor() { }
}
```