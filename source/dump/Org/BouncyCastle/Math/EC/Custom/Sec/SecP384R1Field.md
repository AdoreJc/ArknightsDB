# SecP384R1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP384R1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P11; // 0x0
	private const UInt32 PExt23; // 0x0


	// RVA: 0x649b098 VA: 0x7598ab3098
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x649b238 VA: 0x7598ab3238
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x649b36c VA: 0x7598ab336c
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x649b43c VA: 0x7598ab343c
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x649b514 VA: 0x7598ab3514
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x649b5d4 VA: 0x7598ab35d4
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x649b8e4 VA: 0x7598ab38e4
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x649b660 VA: 0x7598ab3660
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x649b980 VA: 0x7598ab3980
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x649bae4 VA: 0x7598ab3ae4
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x649bb68 VA: 0x7598ab3b68
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x649bc38 VA: 0x7598ab3c38
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x649bd84 VA: 0x7598ab3d84
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x649be68 VA: 0x7598ab3e68
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x649b17c VA: 0x7598ab317c
	private static Void AddPInvTo(UInt32[] z) { }
	// RVA: 0x649bcc8 VA: 0x7598ab3cc8
	private static Void SubPInvFrom(UInt32[] z) { }
	// RVA: 0x649bf3c VA: 0x7598ab3f3c
	public Void .ctor() { }
	// RVA: 0x649bf44 VA: 0x7598ab3f44
	private static Void .cctor() { }
}
```