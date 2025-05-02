# SecP256K1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP256K1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P7; // 0x0
	private const UInt32 PExt15; // 0x0
	private const UInt32 PInv33; // 0x0


	// RVA: 0x6494dd8 VA: 0x7598aacdd8
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6494eb0 VA: 0x7598aaceb0
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x6494fe4 VA: 0x7598aacfe4
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64950ac VA: 0x7598aad0ac
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x6495178 VA: 0x7598aad178
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6495234 VA: 0x7598aad234
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x64953ac VA: 0x7598aad3ac
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x64954dc VA: 0x7598aad4dc
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64952bc VA: 0x7598aad2bc
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x649556c VA: 0x7598aad56c
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x649563c VA: 0x7598aad63c
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64956bc VA: 0x7598aad6bc
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x6495788 VA: 0x7598aad788
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x64957bc VA: 0x7598aad7bc
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x64958a0 VA: 0x7598aad8a0
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x649596c VA: 0x7598aad96c
	public Void .ctor() { }
	// RVA: 0x6495974 VA: 0x7598aad974
	private static Void .cctor() { }
}
```