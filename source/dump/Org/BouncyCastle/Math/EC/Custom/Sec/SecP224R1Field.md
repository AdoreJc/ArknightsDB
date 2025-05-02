# SecP224R1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP224R1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P6; // 0x0
	private const UInt32 PExt13; // 0x0


	// RVA: 0x64905d8 VA: 0x7598aa85d8
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6490754 VA: 0x7598aa8754
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x6490888 VA: 0x7598aa8888
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6490954 VA: 0x7598aa8954
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x6490a20 VA: 0x7598aa8a20
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6490adc VA: 0x7598aa8adc
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x6490d54 VA: 0x7598aa8d54
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x6490e84 VA: 0x7598aa8e84
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x6490b64 VA: 0x7598aa8b64
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x6490f14 VA: 0x7598aa8f14
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x6491058 VA: 0x7598aa9058
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64910d8 VA: 0x7598aa90d8
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x64911a4 VA: 0x7598aa91a4
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x64912d0 VA: 0x7598aa92d0
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x64913b4 VA: 0x7598aa93b4
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x64906b4 VA: 0x7598aa86b4
	private static Void AddPInvTo(UInt32[] z) { }
	// RVA: 0x6491230 VA: 0x7598aa9230
	private static Void SubPInvFrom(UInt32[] z) { }
	// RVA: 0x6491484 VA: 0x7598aa9484
	public Void .ctor() { }
	// RVA: 0x649148c VA: 0x7598aa948c
	private static Void .cctor() { }
}
```