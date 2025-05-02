# BigInteger

**Namespace:** `Mono.Math`


## Fields

- `UInt32 length`


## Methods

- `Int32 BitCount()`

- `Boolean TestBit(Int32)`

- `Void SetBit(UInt32)`

- `Void SetBit(UInt32, Boolean)`

- `Int32 LowestSetBit()`

- `String ToString(UInt32)`

- `String ToString(UInt32, String)`

- `Void Normalize()`

- `Void Clear()`

- `BigInteger ModInverse(BigInteger)`

- `BigInteger ModPow(BigInteger, BigInteger)`

- `Void Incr2()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Math
public class BigInteger
{
	private UInt32 length; // 0x10
	private UInt32[] data; // 0x18
	internal static readonly UInt32[] smallPrimes; // 0x0
	private static RandomNumberGenerator rng; // 0x8

	private static RandomNumberGenerator Rng { get; }

	// RVA: 0x5ef2be4 VA: 0x759850abe4
	public Void .ctor(Sign sign, UInt32 len) { }
	// RVA: 0x5ef2c64 VA: 0x759850ac64
	public Void .ctor(BigInteger bi) { }
	// RVA: 0x5ef2d4c VA: 0x759850ad4c
	public Void .ctor(BigInteger bi, UInt32 len) { }
	// RVA: 0x5eeebc8 VA: 0x7598506bc8
	public Void .ctor(Byte[] inData) { }
	// RVA: 0x5ef2e8c VA: 0x759850ae8c
	public Void .ctor(UInt32 ui) { }
	// RVA: 0x5eee024 VA: 0x7598506024
	public static BigInteger op_Implicit(UInt32 value) { }
	// RVA: 0x5eee3d4 VA: 0x75985063d4
	public static BigInteger op_Implicit(Int32 value) { }
	// RVA: 0x5eeef18 VA: 0x7598506f18
	public static BigInteger op_Addition(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5eee484 VA: 0x7598506484
	public static BigInteger op_Subtraction(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5eee0f0 VA: 0x75985060f0
	public static UInt32 op_Modulus(BigInteger bi, UInt32 ui) { }
	// RVA: 0x5eee608 VA: 0x7598506608
	public static BigInteger op_Modulus(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5ef3950 VA: 0x759850b950
	public static BigInteger op_Division(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5eee1a4 VA: 0x75985061a4
	public static BigInteger op_Multiply(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5ef3a74 VA: 0x759850ba74
	public static BigInteger op_LeftShift(BigInteger bi1, Int32 shiftVal) { }
	// RVA: 0x5ef3c48 VA: 0x759850bc48
	public static BigInteger op_RightShift(BigInteger bi1, Int32 shiftVal) { }
	// RVA: 0x5ef3dc8 VA: 0x759850bdc8
	private static RandomNumberGenerator get_Rng() { }
	// RVA: 0x5ef3e74 VA: 0x759850be74
	public static BigInteger GenerateRandom(Int32 bits, RandomNumberGenerator rng) { }
	// RVA: 0x5eeee2c VA: 0x7598506e2c
	public static BigInteger GenerateRandom(Int32 bits) { }
	// RVA: 0x5eee354 VA: 0x7598506354
	public Int32 BitCount() { }
	// RVA: 0x5ef3fd8 VA: 0x759850bfd8
	public Boolean TestBit(Int32 bitNum) { }
	// RVA: 0x5ef4070 VA: 0x759850c070
	public Void SetBit(UInt32 bitNum) { }
	// RVA: 0x5ef4078 VA: 0x759850c078
	public Void SetBit(UInt32 bitNum, Boolean value) { }
	// RVA: 0x5ef40d4 VA: 0x759850c0d4
	public Int32 LowestSetBit() { }
	// RVA: 0x5eef59c VA: 0x759850759c
	public Byte[] GetBytes() { }
	// RVA: 0x5ef2f1c VA: 0x759850af1c
	public static Boolean op_Equality(BigInteger bi1, UInt32 ui) { }
	// RVA: 0x5ef4150 VA: 0x759850c150
	public static Boolean op_Inequality(BigInteger bi1, UInt32 ui) { }
	// RVA: 0x5eee7b8 VA: 0x75985067b8
	public static Boolean op_Equality(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5eee0f4 VA: 0x75985060f4
	public static Boolean op_Inequality(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5eeef00 VA: 0x7598506f00
	public static Boolean op_GreaterThan(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5eee3c0 VA: 0x75985063c0
	public static Boolean op_LessThan(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5ef41bc VA: 0x759850c1bc
	public static Boolean op_GreaterThanOrEqual(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5ef41d4 VA: 0x759850c1d4
	public static Boolean op_LessThanOrEqual(BigInteger bi1, BigInteger bi2) { }
	// RVA: 0x5ef41ec VA: 0x759850c1ec
	public String ToString(UInt32 radix) { }
	// RVA: 0x5ef4244 VA: 0x759850c244
	public String ToString(UInt32 radix, String characterSet) { }
	// RVA: 0x5ef2e34 VA: 0x759850ae34
	private Void Normalize() { }
	// RVA: 0x5eeeff8 VA: 0x7598506ff8
	public Void Clear() { }
	// RVA: 0x5ef4504 VA: 0x759850c504
	public override Int32 GetHashCode() { }
	// RVA: 0x5ef455c VA: 0x759850c55c
	public override String ToString() { }
	// RVA: 0x5ef4564 VA: 0x759850c564
	public override Boolean Equals(Object o) { }
	// RVA: 0x5eee604 VA: 0x7598506604
	public BigInteger ModInverse(BigInteger modulus) { }
	// RVA: 0x5eeee88 VA: 0x7598506e88
	public BigInteger ModPow(BigInteger exp, BigInteger n) { }
	// RVA: 0x5eee084 VA: 0x7598506084
	public static BigInteger GeneratePseudoPrime(Int32 bits) { }
	// RVA: 0x5ef4eb4 VA: 0x759850ceb4
	public Void Incr2() { }
	// RVA: 0x5ef4f38 VA: 0x759850cf38
	private static Void .cctor() { }
}
```