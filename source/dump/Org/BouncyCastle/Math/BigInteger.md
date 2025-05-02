# BigInteger

**Namespace:** `Org.BouncyCastle.Math`


## Fields

- `Int32 sign`

- `Int32 nBits`

- `Int32 nBitLength`

- `Int32 mQuote`


## Properties

- `Int32 BitCount`

- `Int32 BitLength`

- `Int32 IntValue`

- `Int64 LongValue`

- `Int32 SignValue`


## Methods

- `BigInteger Abs()`

- `BigInteger Add(BigInteger)`

- `BigInteger AddToMagnitude(Int32[])`

- `BigInteger And(BigInteger)`

- `BigInteger AndNot(BigInteger)`

- `Int32 get_BitCount()`

- `Int32 get_BitLength()`

- `Boolean QuickPow2Check()`

- `Int32 CompareTo(Object)`

- `Int32 CompareTo(BigInteger)`

- `BigInteger Divide(BigInteger)`

- `Boolean IsEqualMagnitude(BigInteger)`

- `BigInteger Gcd(BigInteger)`

- `BigInteger Inc()`

- `Int32 get_IntValue()`

- `Boolean IsProbablePrime(Int32)`

- `Boolean CheckProbablePrime(Int32, Random, Boolean)`

- `Boolean RabinMillerTest(Int32, Random)`

- `Int64 get_LongValue()`

- `BigInteger Max(BigInteger)`

- `BigInteger Min(BigInteger)`

- `BigInteger Mod(BigInteger)`

- `BigInteger ModInverse(BigInteger)`

- `BigInteger ModInversePow2(BigInteger)`

- `BigInteger ModPow(BigInteger, BigInteger)`

- `Int32 GetMQuote()`

- `BigInteger Multiply(BigInteger)`

- `BigInteger Square()`

- `BigInteger Negate()`

- `BigInteger NextProbablePrime()`

- `BigInteger Not()`

- `BigInteger Pow(Int32)`

- `Int32 Remainder(Int32)`

- `BigInteger Remainder(BigInteger)`

- `BigInteger DivideWords(Int32)`

- `BigInteger RemainderWords(Int32)`

- `BigInteger ShiftLeft(Int32)`

- `BigInteger ShiftRight(Int32)`

- `Int32 get_SignValue()`

- `BigInteger Subtract(BigInteger)`

- `String ToString(Int32)`

- `Int32 GetLowestSetBit()`

- `Int32 GetLowestSetBitMaskFirst(Int32)`

- `Boolean TestBit(Int32)`

- `BigInteger Or(BigInteger)`

- `BigInteger Xor(BigInteger)`

- `BigInteger SetBit(Int32)`

- `BigInteger ClearBit(Int32)`

- `BigInteger FlipBit(Int32)`

- `BigInteger FlipExistingBit(Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math
public class BigInteger
{
	internal static readonly Int32[][] primeLists; // 0x0
	internal static readonly Int32[] primeProducts; // 0x8
	private const Int64 IMASK; // 0x0
	private const UInt64 UIMASK; // 0x0
	private static readonly Int32[] ZeroMagnitude; // 0x10
	private static readonly Byte[] ZeroEncoding; // 0x18
	private static readonly BigInteger[] SMALL_CONSTANTS; // 0x20
	public static readonly BigInteger Zero; // 0x28
	public static readonly BigInteger One; // 0x30
	public static readonly BigInteger Two; // 0x38
	public static readonly BigInteger Three; // 0x40
	public static readonly BigInteger Ten; // 0x48
	private static readonly Byte[] BitLengthTable; // 0x50
	private const Int32 chunk2; // 0x0
	private const Int32 chunk8; // 0x0
	private const Int32 chunk10; // 0x0
	private const Int32 chunk16; // 0x0
	private static readonly BigInteger radix2; // 0x58
	private static readonly BigInteger radix2E; // 0x60
	private static readonly BigInteger radix8; // 0x68
	private static readonly BigInteger radix8E; // 0x70
	private static readonly BigInteger radix10; // 0x78
	private static readonly BigInteger radix10E; // 0x80
	private static readonly BigInteger radix16; // 0x88
	private static readonly BigInteger radix16E; // 0x90
	private static readonly SecureRandom RandomSource; // 0x98
	private static readonly Int32[] ExpWindowThresholds; // 0xa0
	private const Int32 BitsPerByte; // 0x0
	private const Int32 BitsPerInt; // 0x0
	private const Int32 BytesPerInt; // 0x0
	private Int32[] magnitude; // 0x10
	private Int32 sign; // 0x18
	private Int32 nBits; // 0x1c
	private Int32 nBitLength; // 0x20
	private Int32 mQuote; // 0x24

	public Int32 BitCount { get; }
	public Int32 BitLength { get; }
	public Int32 IntValue { get; }
	public Int64 LongValue { get; }
	public Int32 SignValue { get; }

	// RVA: 0x670e8a8 VA: 0x7598d268a8
	private static Void .cctor() { }
	// RVA: 0x6710c74 VA: 0x7598d28c74
	private static Int32 GetByteLength(Int32 nBits) { }
	// RVA: 0x6710c8c VA: 0x7598d28c8c
	internal static BigInteger Arbitrary(Int32 sizeInBits) { }
	// RVA: 0x671076c VA: 0x7598d2876c
	private Void .ctor(Int32 signum, Int32[] mag, Boolean checkMag) { }
	// RVA: 0x6710ec8 VA: 0x7598d28ec8
	public Void .ctor(String value) { }
	// RVA: 0x6710ed0 VA: 0x7598d28ed0
	public Void .ctor(String str, Int32 radix) { }
	// RVA: 0x671176c VA: 0x7598d2976c
	public Void .ctor(Byte[] bytes) { }
	// RVA: 0x6711788 VA: 0x7598d29788
	public Void .ctor(Byte[] bytes, Int32 offset, Int32 length) { }
	// RVA: 0x6711a14 VA: 0x7598d29a14
	private static Int32[] MakeMagnitude(Byte[] bytes, Int32 offset, Int32 length) { }
	// RVA: 0x6711bb4 VA: 0x7598d29bb4
	public Void .ctor(Int32 sign, Byte[] bytes) { }
	// RVA: 0x6711bd0 VA: 0x7598d29bd0
	public Void .ctor(Int32 sign, Byte[] bytes, Int32 offset, Int32 length) { }
	// RVA: 0x6710d08 VA: 0x7598d28d08
	public Void .ctor(Int32 sizeInBits, Random random) { }
	// RVA: 0x6711d2c VA: 0x7598d29d2c
	public Void .ctor(Int32 bitLength, Int32 certainty, Random random) { }
	// RVA: 0x6712260 VA: 0x7598d2a260
	public BigInteger Abs() { }
	// RVA: 0x67122e4 VA: 0x7598d2a2e4
	private static Int32[] AddMagnitudes(Int32[] a, Int32[] b) { }
	// RVA: 0x67116e0 VA: 0x7598d296e0
	public BigInteger Add(BigInteger value) { }
	// RVA: 0x67124e4 VA: 0x7598d2a4e4
	private BigInteger AddToMagnitude(Int32[] magToAdd) { }
	// RVA: 0x6712650 VA: 0x7598d2a650
	public BigInteger And(BigInteger value) { }
	// RVA: 0x67128dc VA: 0x7598d2a8dc
	public BigInteger AndNot(BigInteger val) { }
	// RVA: 0x6712904 VA: 0x7598d2a904
	public Int32 get_BitCount() { }
	// RVA: 0x6712a08 VA: 0x7598d2aa08
	public static Int32 BitCnt(Int32 i) { }
	// RVA: 0x6712a3c VA: 0x7598d2aa3c
	private static Int32 CalcBitLength(Int32 sign, Int32 indx, Int32[] mag) { }
	// RVA: 0x6712c64 VA: 0x7598d2ac64
	public Int32 get_BitLength() { }
	// RVA: 0x6712b40 VA: 0x7598d2ab40
	internal static Int32 BitLen(Int32 w) { }
	// RVA: 0x6712ce8 VA: 0x7598d2ace8
	private Boolean QuickPow2Check() { }
	// RVA: 0x6712d0c VA: 0x7598d2ad0c
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x6712e3c VA: 0x7598d2ae3c
	private static Int32 CompareTo(Int32 xIndx, Int32[] x, Int32 yIndx, Int32[] y) { }
	// RVA: 0x6712f18 VA: 0x7598d2af18
	private static Int32 CompareNoLeadingZeroes(Int32 xIndx, Int32[] x, Int32 yIndx, Int32[] y) { }
	// RVA: 0x6712d90 VA: 0x7598d2ad90
	public Int32 CompareTo(BigInteger value) { }
	// RVA: 0x6712fa4 VA: 0x7598d2afa4
	private Int32[] Divide(Int32[] x, Int32[] y) { }
	// RVA: 0x67137f8 VA: 0x7598d2b7f8
	public BigInteger Divide(BigInteger val) { }
	// RVA: 0x6713bd0 VA: 0x7598d2bbd0
	public BigInteger[] DivideAndRemainder(BigInteger val) { }
	// RVA: 0x6714064 VA: 0x7598d2c064
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6714118 VA: 0x7598d2c118
	private Boolean IsEqualMagnitude(BigInteger x) { }
	// RVA: 0x6714198 VA: 0x7598d2c198
	public BigInteger Gcd(BigInteger value) { }
	// RVA: 0x6714298 VA: 0x7598d2c298
	public override Int32 GetHashCode() { }
	// RVA: 0x67142f4 VA: 0x7598d2c2f4
	private BigInteger Inc() { }
	// RVA: 0x67144b0 VA: 0x7598d2c4b0
	public Int32 get_IntValue() { }
	// RVA: 0x67144fc VA: 0x7598d2c4fc
	public Boolean IsProbablePrime(Int32 certainty) { }
	// RVA: 0x6714504 VA: 0x7598d2c504
	internal Boolean IsProbablePrime(Int32 certainty, Boolean randomlySelected) { }
	// RVA: 0x6712078 VA: 0x7598d2a078
	private Boolean CheckProbablePrime(Int32 certainty, Random random, Boolean randomlySelected) { }
	// RVA: 0x6714a40 VA: 0x7598d2ca40
	public Boolean RabinMillerTest(Int32 certainty, Random random) { }
	// RVA: 0x6714760 VA: 0x7598d2c760
	internal Boolean RabinMillerTest(Int32 certainty, Random random, Boolean randomlySelected) { }
	// RVA: 0x671532c VA: 0x7598d2d32c
	public Int64 get_LongValue() { }
	// RVA: 0x6715398 VA: 0x7598d2d398
	public BigInteger Max(BigInteger value) { }
	// RVA: 0x67153c0 VA: 0x7598d2d3c0
	public BigInteger Min(BigInteger value) { }
	// RVA: 0x6714208 VA: 0x7598d2c208
	public BigInteger Mod(BigInteger m) { }
	// RVA: 0x67153e8 VA: 0x7598d2d3e8
	public BigInteger ModInverse(BigInteger m) { }
	// RVA: 0x6715548 VA: 0x7598d2d548
	private BigInteger ModInversePow2(BigInteger m) { }
	// RVA: 0x67158a4 VA: 0x7598d2d8a4
	private static Int32 ModInverse32(Int32 d) { }
	// RVA: 0x671586c VA: 0x7598d2d86c
	private static Int64 ModInverse64(Int64 d) { }
	// RVA: 0x671574c VA: 0x7598d2d74c
	private static BigInteger ExtEuclid(BigInteger a, BigInteger b, out BigInteger u1Out) { }
	// RVA: 0x67158d4 VA: 0x7598d2d8d4
	private static Void ZeroOut(Int32[] x) { }
	// RVA: 0x67158f4 VA: 0x7598d2d8f4
	public BigInteger ModPow(BigInteger e, BigInteger m) { }
	// RVA: 0x6715b0c VA: 0x7598d2db0c
	private static BigInteger ModPowBarrett(BigInteger b, BigInteger e, BigInteger m) { }
	// RVA: 0x67160a4 VA: 0x7598d2e0a4
	private static BigInteger ReduceBarrett(BigInteger x, BigInteger m, BigInteger mr, BigInteger yu) { }
	// RVA: 0x6714d2c VA: 0x7598d2cd2c
	private static BigInteger ModPowMonty(BigInteger b, BigInteger e, BigInteger m, Boolean convert) { }
	// RVA: 0x67161b8 VA: 0x7598d2e1b8
	private static Int32[] GetWindowList(Int32[] mag, Int32 extraBits) { }
	// RVA: 0x6716f34 VA: 0x7598d2ef34
	private static Int32 CreateWindowEntry(Int32 mult, Int32 zeroes) { }
	// RVA: 0x6716f50 VA: 0x7598d2ef50
	private static Int32[] Square(Int32[] w, Int32[] x) { }
	// RVA: 0x67170e8 VA: 0x7598d2f0e8
	private static Int32[] Multiply(Int32[] x, Int32[] y, Int32[] z) { }
	// RVA: 0x671657c VA: 0x7598d2e57c
	private Int32 GetMQuote() { }
	// RVA: 0x6716dc8 VA: 0x7598d2edc8
	private static Void MontgomeryReduce(Int32[] x, Int32[] m, UInt32 mDash) { }
	// RVA: 0x6716a60 VA: 0x7598d2ea60
	private static Void MultiplyMonty(Int32[] a, Int32[] x, Int32[] y, Int32[] m, UInt32 mDash, Boolean smallMontyModulus) { }
	// RVA: 0x671662c VA: 0x7598d2e62c
	private static Void SquareMonty(Int32[] a, Int32[] x, Int32[] m, UInt32 mDash, Boolean smallMontyModulus) { }
	// RVA: 0x67171c8 VA: 0x7598d2f1c8
	private static UInt32 MultiplyMontyNIsOne(UInt32 x, UInt32 y, UInt32 m, UInt32 mDash) { }
	// RVA: 0x6711518 VA: 0x7598d29518
	public BigInteger Multiply(BigInteger val) { }
	// RVA: 0x6715f78 VA: 0x7598d2df78
	public BigInteger Square() { }
	// RVA: 0x6712270 VA: 0x7598d2a270
	public BigInteger Negate() { }
	// RVA: 0x67171f4 VA: 0x7598d2f1f4
	public BigInteger NextProbablePrime() { }
	// RVA: 0x67128c4 VA: 0x7598d2a8c4
	public BigInteger Not() { }
	// RVA: 0x6710ac8 VA: 0x7598d28ac8
	public BigInteger Pow(Int32 exp) { }
	// RVA: 0x6717464 VA: 0x7598d2f464
	public static BigInteger ProbablePrime(Int32 bitLength, Random random) { }
	// RVA: 0x67146f4 VA: 0x7598d2c6f4
	private Int32 Remainder(Int32 m) { }
	// RVA: 0x67174d8 VA: 0x7598d2f4d8
	private static Int32[] Remainder(Int32[] x, Int32[] y) { }
	// RVA: 0x6714ae0 VA: 0x7598d2cae0
	public BigInteger Remainder(BigInteger n) { }
	// RVA: 0x6713f10 VA: 0x7598d2bf10
	private Int32[] LastNBits(Int32 n) { }
	// RVA: 0x67163bc VA: 0x7598d2e3bc
	private BigInteger DivideWords(Int32 w) { }
	// RVA: 0x67164ac VA: 0x7598d2e4ac
	private BigInteger RemainderWords(Int32 w) { }
	// RVA: 0x6713430 VA: 0x7598d2b430
	private static Int32[] ShiftLeft(Int32[] mag, Int32 n) { }
	// RVA: 0x6717830 VA: 0x7598d2f830
	private static Int32 ShiftLeftOneInPlace(Int32[] x, Int32 carry) { }
	// RVA: 0x67113f0 VA: 0x7598d293f0
	public BigInteger ShiftLeft(Int32 n) { }
	// RVA: 0x67136e8 VA: 0x7598d2b6e8
	private static Void ShiftRightInPlace(Int32 start, Int32[] mag, Int32 n) { }
	// RVA: 0x6713654 VA: 0x7598d2b654
	private static Void ShiftRightOneInPlace(Int32 start, Int32[] mag) { }
	// RVA: 0x67139e0 VA: 0x7598d2b9e0
	public BigInteger ShiftRight(Int32 n) { }
	// RVA: 0x6717884 VA: 0x7598d2f884
	public Int32 get_SignValue() { }
	// RVA: 0x67135b4 VA: 0x7598d2b5b4
	private static Int32[] Subtract(Int32 xStart, Int32[] x, Int32 yStart, Int32[] y) { }
	// RVA: 0x6712388 VA: 0x7598d2a388
	public BigInteger Subtract(BigInteger n) { }
	// RVA: 0x67143f4 VA: 0x7598d2c3f4
	private static Int32[] doSubBigLil(Int32[] bigMag, Int32[] lilMag) { }
	// RVA: 0x671788c VA: 0x7598d2f88c
	public Byte[] ToByteArray() { }
	// RVA: 0x6717c48 VA: 0x7598d2fc48
	public Byte[] ToByteArrayUnsigned() { }
	// RVA: 0x6717894 VA: 0x7598d2f894
	private Byte[] ToByteArray(Boolean unsigned) { }
	// RVA: 0x6717c50 VA: 0x7598d2fc50
	public override String ToString() { }
	// RVA: 0x6717c58 VA: 0x7598d2fc58
	public String ToString(Int32 radix) { }
	// RVA: 0x6718594 VA: 0x7598d30594
	private static Void AppendZeroExtendedString(StringBuilder sb, String s, Int32 minLength) { }
	// RVA: 0x67108c0 VA: 0x7598d288c0
	private static BigInteger CreateUValueOf(UInt64 value) { }
	// RVA: 0x67185f8 VA: 0x7598d305f8
	private static BigInteger CreateValueOf(Int64 value) { }
	// RVA: 0x67109f8 VA: 0x7598d289f8
	public static BigInteger ValueOf(Int64 value) { }
	// RVA: 0x67186a0 VA: 0x7598d306a0
	public Int32 GetLowestSetBit() { }
	// RVA: 0x6714a48 VA: 0x7598d2ca48
	private Int32 GetLowestSetBitMaskFirst(Int32 firstWordMask) { }
	// RVA: 0x6714624 VA: 0x7598d2c624
	public Boolean TestBit(Int32 n) { }
	// RVA: 0x67186b8 VA: 0x7598d306b8
	public BigInteger Or(BigInteger value) { }
	// RVA: 0x6718914 VA: 0x7598d30914
	public BigInteger Xor(BigInteger value) { }
	// RVA: 0x6717348 VA: 0x7598d2f348
	public BigInteger SetBit(Int32 n) { }
	// RVA: 0x6718c68 VA: 0x7598d30c68
	public BigInteger ClearBit(Int32 n) { }
	// RVA: 0x6718d84 VA: 0x7598d30d84
	public BigInteger FlipBit(Int32 n) { }
	// RVA: 0x6718b74 VA: 0x7598d30b74
	private BigInteger FlipExistingBit(Int32 n) { }
}
```