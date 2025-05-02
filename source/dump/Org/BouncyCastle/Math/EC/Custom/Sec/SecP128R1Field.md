# SecP128R1Field

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP128R1Field
{
	internal static readonly UInt32[] P; // 0x0
	internal static readonly UInt32[] PExt; // 0x8
	private static readonly UInt32[] PExtInv; // 0x10
	private const UInt32 P3; // 0x0
	private const UInt32 PExt7; // 0x0


	// RVA: 0x647ceb8 VA: 0x7598a94eb8
	public static Void Add(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x647d014 VA: 0x7598a95014
	public static Void AddExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x647d108 VA: 0x7598a95108
	public static Void AddOne(UInt32[] x, UInt32[] z) { }
	// RVA: 0x647d1d4 VA: 0x7598a951d4
	public static UInt32[] FromBigInteger(BigInteger x) { }
	// RVA: 0x647d2a0 VA: 0x7598a952a0
	public static Void Half(UInt32[] x, UInt32[] z) { }
	// RVA: 0x647d35c VA: 0x7598a9535c
	public static Void Multiply(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x647d4fc VA: 0x7598a954fc
	public static Void MultiplyAddToExt(UInt32[] x, UInt32[] y, UInt32[] zz) { }
	// RVA: 0x647d5f0 VA: 0x7598a955f0
	public static Void Negate(UInt32[] x, UInt32[] z) { }
	// RVA: 0x647d3e4 VA: 0x7598a953e4
	public static Void Reduce(UInt32[] xx, UInt32[] z) { }
	// RVA: 0x647d680 VA: 0x7598a95680
	public static Void Reduce32(UInt32 x, UInt32[] z) { }
	// RVA: 0x647d708 VA: 0x7598a95708
	public static Void Square(UInt32[] x, UInt32[] z) { }
	// RVA: 0x647d788 VA: 0x7598a95788
	public static Void SquareN(UInt32[] x, Int32 n, UInt32[] z) { }
	// RVA: 0x647d854 VA: 0x7598a95854
	public static Void Subtract(UInt32[] x, UInt32[] y, UInt32[] z) { }
	// RVA: 0x647d960 VA: 0x7598a95960
	public static Void SubtractExt(UInt32[] xx, UInt32[] yy, UInt32[] zz) { }
	// RVA: 0x647da0c VA: 0x7598a95a0c
	public static Void Twice(UInt32[] x, UInt32[] z) { }
	// RVA: 0x647cf94 VA: 0x7598a94f94
	private static Void AddPInvTo(UInt32[] z) { }
	// RVA: 0x647d8e0 VA: 0x7598a958e0
	private static Void SubPInvFrom(UInt32[] z) { }
	// RVA: 0x647dadc VA: 0x7598a95adc
	public Void .ctor() { }
	// RVA: 0x647dae4 VA: 0x7598a95ae4
	private static Void .cctor() { }
}
```