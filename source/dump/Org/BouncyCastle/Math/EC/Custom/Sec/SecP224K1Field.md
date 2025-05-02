# SecP224K1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP224K1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P6; // 0x0
	private const UInt32 PExt13; // 0x0
	private const UInt32 PInv33; // 0x0


	// RVA: 0x648d4bc VA: 0x7598aa54bc
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x648d594 VA: 0x7598aa5594
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x648d6c8 VA: 0x7598aa56c8
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648d790 VA: 0x7598aa5790
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x648d85c VA: 0x7598aa585c
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648d918 VA: 0x7598aa5918
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x648da90 VA: 0x7598aa5a90
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x648dbc0 VA: 0x7598aa5bc0
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648d9a0 VA: 0x7598aa59a0
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x648dc50 VA: 0x7598aa5c50
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x648dd20 VA: 0x7598aa5d20
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648dda0 VA: 0x7598aa5da0
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x648de6c VA: 0x7598aa5e6c
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x648dea0 VA: 0x7598aa5ea0
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x648df84 VA: 0x7598aa5f84
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x648e050 VA: 0x7598aa6050
	public Void .ctor() { }
	// RVA: 0x648e058 VA: 0x7598aa6058
	private static Void .cctor() { }
}
```