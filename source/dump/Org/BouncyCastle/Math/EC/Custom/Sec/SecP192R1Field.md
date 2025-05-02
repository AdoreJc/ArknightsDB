# SecP192R1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP192R1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P5; // 0x0
	private const UInt32 PExt11; // 0x0


	// RVA: 0x648a2dc VA: 0x7598aa22dc
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x648a444 VA: 0x7598aa2444
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x648a578 VA: 0x7598aa2578
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648a644 VA: 0x7598aa2644
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x648a710 VA: 0x7598aa2710
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648a7cc VA: 0x7598aa27cc
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x648aa20 VA: 0x7598aa2a20
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x648ab50 VA: 0x7598aa2b50
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648a854 VA: 0x7598aa2854
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x648abe0 VA: 0x7598aa2be0
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x648ad10 VA: 0x7598aa2d10
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648ad90 VA: 0x7598aa2d90
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x648ae5c VA: 0x7598aa2e5c
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x648af74 VA: 0x7598aa2f74
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x648b058 VA: 0x7598aa3058
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648a3b8 VA: 0x7598aa23b8
	private static Void AddPInvTo(UInt32[] z) { }
	// RVA: 0x648aee8 VA: 0x7598aa2ee8
	private static Void SubPInvFrom(UInt32[] z) { }
	// RVA: 0x648b128 VA: 0x7598aa3128
	public Void .ctor() { }
	// RVA: 0x648b130 VA: 0x7598aa3130
	private static Void .cctor() { }
}
```