# LongArray

**Namespace:** `Org.BouncyCastle.Math.EC`


## Properties

- `Int32 Length`


## Methods

- `Boolean IsOne()`

- `Boolean IsZero()`

- `Int32 GetUsedLength()`

- `Int32 GetUsedLengthFrom(Int32)`

- `Int32 Degree()`

- `Int32 DegreeFrom(Int32)`

- `BigInteger ToBigInteger()`

- `LongArray AddOne()`

- `Void AddShiftedByBitsSafe(LongArray, Int32, Int32)`

- `Void AddShiftedByWords(LongArray, Int32)`

- `Int32 get_Length()`

- `Boolean TestBitZero()`

- `LongArray ModMultiplyLD(LongArray, Int32, Int32[])`

- `LongArray ModMultiply(LongArray, Int32, Int32[])`

- `LongArray ModMultiplyAlt(LongArray, Int32, Int32[])`

- `LongArray ModReduce(Int32, Int32[])`

- `LongArray Multiply(LongArray, Int32, Int32[])`

- `Void Reduce(Int32, Int32[])`

- `LongArray ModSquare(Int32, Int32[])`

- `LongArray ModSquareN(Int32, Int32, Int32[])`

- `LongArray Square(Int32, Int32[])`

- `LongArray ModInverse(Int32, Int32[])`

- `LongArray Copy()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC
internal class LongArray
{
	private static readonly UInt16[] INTERLEAVE2_TABLE; // 0x0
	private static readonly Int32[] INTERLEAVE3_TABLE; // 0x8
	private static readonly Int32[] INTERLEAVE4_TABLE; // 0x10
	private static readonly Int32[] INTERLEAVE5_TABLE; // 0x18
	private static readonly Int64[] INTERLEAVE7_TABLE; // 0x20
	private const String ZEROES; // 0x0
	internal static readonly Byte[] BitLengths; // 0x28
	private Int64[] m_ints; // 0x10

	public Int32 Length { get; }

	// RVA: 0x673de8c VA: 0x7598d55e8c
	public Void .ctor(Int32 intLen) { }
	// RVA: 0x673defc VA: 0x7598d55efc
	public Void .ctor(Int64[] ints) { }
	// RVA: 0x673df2c VA: 0x7598d55f2c
	public Void .ctor(Int64[] ints, Int32 off, Int32 len) { }
	// RVA: 0x6730b3c VA: 0x7598d48b3c
	public Void .ctor(BigInteger bigInt) { }
	// RVA: 0x6734bd8 VA: 0x7598d4cbd8
	public Boolean IsOne() { }
	// RVA: 0x6734c8c VA: 0x7598d4cc8c
	public Boolean IsZero() { }
	// RVA: 0x673dff4 VA: 0x7598d55ff4
	public Int32 GetUsedLength() { }
	// RVA: 0x673e010 VA: 0x7598d56010
	public Int32 GetUsedLengthFrom(Int32 from) { }
	// RVA: 0x6734b1c VA: 0x7598d4cb1c
	public Int32 Degree() { }
	// RVA: 0x673e210 VA: 0x7598d56210
	private Int32 DegreeFrom(Int32 limit) { }
	// RVA: 0x673e0f0 VA: 0x7598d560f0
	private static Int32 BitLength(Int64 w) { }
	// RVA: 0x673e2bc VA: 0x7598d562bc
	private Int64[] ResizedInts(Int32 newLen) { }
	// RVA: 0x6731238 VA: 0x7598d49238
	public BigInteger ToBigInteger() { }
	// RVA: 0x673e378 VA: 0x7598d56378
	private static Int64 ShiftUp(Int64[] x, Int32 xOff, Int32 count, Int32 shift) { }
	// RVA: 0x673e3f8 VA: 0x7598d563f8
	private static Int64 ShiftUp(Int64[] x, Int32 xOff, Int64[] z, Int32 zOff, Int32 count, Int32 shift) { }
	// RVA: 0x67351b4 VA: 0x7598d4d1b4
	public LongArray AddOne() { }
	// RVA: 0x673e490 VA: 0x7598d56490
	private Void AddShiftedByBitsSafe(LongArray other, Int32 otherDegree, Int32 bits) { }
	// RVA: 0x673e608 VA: 0x7598d56608
	private static Int64 AddShiftedUp(Int64[] x, Int32 xOff, Int64[] y, Int32 yOff, Int32 count, Int32 shift) { }
	// RVA: 0x673e6a8 VA: 0x7598d566a8
	private static Int64 AddShiftedDown(Int64[] x, Int32 xOff, Int64[] y, Int32 yOff, Int32 count, Int32 shift) { }
	// RVA: 0x6735044 VA: 0x7598d4d044
	public Void AddShiftedByWords(LongArray other, Int32 words) { }
	// RVA: 0x673e590 VA: 0x7598d56590
	private static Void Add(Int64[] x, Int32 xOff, Int64[] y, Int32 yOff, Int32 count) { }
	// RVA: 0x673e734 VA: 0x7598d56734
	private static Void Add(Int64[] x, Int32 xOff, Int64[] y, Int32 yOff, Int64[] z, Int32 zOff, Int32 count) { }
	// RVA: 0x673e7c4 VA: 0x7598d567c4
	private static Void AddBoth(Int64[] x, Int32 xOff, Int64[] y1, Int32 y1Off, Int64[] y2, Int32 y2Off, Int32 count) { }
	// RVA: 0x673e85c VA: 0x7598d5685c
	private static Void Distribute(Int64[] x, Int32 src, Int32 dst1, Int32 dst2, Int32 count) { }
	// RVA: 0x673e904 VA: 0x7598d56904
	public Int32 get_Length() { }
	// RVA: 0x673e920 VA: 0x7598d56920
	private static Void FlipWord(Int64[] buf, Int32 off, Int32 bit, Int64 word) { }
	// RVA: 0x6734cf0 VA: 0x7598d4ccf0
	public Boolean TestBitZero() { }
	// RVA: 0x673e998 VA: 0x7598d56998
	private static Boolean TestBit(Int64[] buf, Int32 off, Int32 n) { }
	// RVA: 0x673e9d8 VA: 0x7598d569d8
	private static Void FlipBit(Int64[] buf, Int32 off, Int32 n) { }
	// RVA: 0x673ea18 VA: 0x7598d56a18
	private static Void MultiplyWord(Int64 a, Int64[] b, Int32 bLen, Int64[] c, Int32 cOff) { }
	// RVA: 0x673eb30 VA: 0x7598d56b30
	public LongArray ModMultiplyLD(LongArray other, Int32 m, Int32[] ks) { }
	// RVA: 0x67353bc VA: 0x7598d4d3bc
	public LongArray ModMultiply(LongArray other, Int32 m, Int32[] ks) { }
	// RVA: 0x673f100 VA: 0x7598d57100
	public LongArray ModMultiplyAlt(LongArray other, Int32 m, Int32[] ks) { }
	// RVA: 0x673f734 VA: 0x7598d57734
	public LongArray ModReduce(Int32 m, Int32[] ks) { }
	// RVA: 0x67359b4 VA: 0x7598d4d9b4
	public LongArray Multiply(LongArray other, Int32 m, Int32[] ks) { }
	// RVA: 0x6735de4 VA: 0x7598d4dde4
	public Void Reduce(Int32 m, Int32[] ks) { }
	// RVA: 0x673f048 VA: 0x7598d57048
	private static LongArray ReduceResult(Int64[] buf, Int32 off, Int32 len, Int32 m, Int32[] ks) { }
	// RVA: 0x673f7f0 VA: 0x7598d577f0
	private static Int32 ReduceInPlace(Int64[] buf, Int32 off, Int32 len, Int32 m, Int32[] ks) { }
	// RVA: 0x673fce0 VA: 0x7598d57ce0
	private static Void ReduceBitWise(Int64[] buf, Int32 off, Int32 BitLength, Int32 m, Int32[] ks) { }
	// RVA: 0x673fda4 VA: 0x7598d57da4
	private static Void ReduceBit(Int64[] buf, Int32 off, Int32 bit, Int32 m, Int32[] ks) { }
	// RVA: 0x673fb70 VA: 0x7598d57b70
	private static Void ReduceWordWise(Int64[] buf, Int32 off, Int32 len, Int32 toBit, Int32 m, Int32[] ks) { }
	// RVA: 0x673feb8 VA: 0x7598d57eb8
	private static Void ReduceWord(Int64[] buf, Int32 off, Int32 bit, Int64 word, Int32 m, Int32[] ks) { }
	// RVA: 0x673fa38 VA: 0x7598d57a38
	private static Void ReduceVectorWise(Int64[] buf, Int32 off, Int32 len, Int32 words, Int32 m, Int32[] ks) { }
	// RVA: 0x673ffc0 VA: 0x7598d57fc0
	private static Void FlipVector(Int64[] x, Int32 xOff, Int64[] y, Int32 yOff, Int32 yLen, Int32 bits) { }
	// RVA: 0x6735fa8 VA: 0x7598d4dfa8
	public LongArray ModSquare(Int32 m, Int32[] ks) { }
	// RVA: 0x6736490 VA: 0x7598d4e490
	public LongArray ModSquareN(Int32 n, Int32 m, Int32[] ks) { }
	// RVA: 0x673629c VA: 0x7598d4e29c
	public LongArray Square(Int32 m, Int32[] ks) { }
	// RVA: 0x674017c VA: 0x7598d5817c
	private static Void SquareInPlace(Int64[] x, Int32 xLen, Int32 m, Int32[] ks) { }
	// RVA: 0x673f5bc VA: 0x7598d575bc
	private static Void Interleave(Int64[] x, Int32 xOff, Int64[] z, Int32 zOff, Int32 count, Int32 width) { }
	// RVA: 0x674025c VA: 0x7598d5825c
	private static Void Interleave3(Int64[] x, Int32 xOff, Int64[] z, Int32 zOff, Int32 count) { }
	// RVA: 0x67405fc VA: 0x7598d585fc
	private static Int64 Interleave3(Int64 x) { }
	// RVA: 0x674067c VA: 0x7598d5867c
	private static Int64 Interleave3_21to63(Int32 x) { }
	// RVA: 0x6740340 VA: 0x7598d58340
	private static Void Interleave5(Int64[] x, Int32 xOff, Int64[] z, Int32 zOff, Int32 count) { }
	// RVA: 0x6740728 VA: 0x7598d58728
	private static Int64 Interleave5(Int64 x) { }
	// RVA: 0x67407c8 VA: 0x7598d587c8
	private static Int64 Interleave3_13to65(Int32 x) { }
	// RVA: 0x6740424 VA: 0x7598d58424
	private static Void Interleave7(Int64[] x, Int32 xOff, Int64[] z, Int32 zOff, Int32 count) { }
	// RVA: 0x674085c VA: 0x7598d5885c
	private static Int64 Interleave7(Int64 x) { }
	// RVA: 0x6740508 VA: 0x7598d58508
	private static Void Interleave2_n(Int64[] x, Int32 xOff, Int64[] z, Int32 zOff, Int32 count, Int32 rounds) { }
	// RVA: 0x6740970 VA: 0x7598d58970
	private static Int64 Interleave2_n(Int64 x, Int32 rounds) { }
	// RVA: 0x6740a5c VA: 0x7598d58a5c
	private static Int64 Interleave4_16to64(Int32 x) { }
	// RVA: 0x67400bc VA: 0x7598d580bc
	private static Int64 Interleave2_32to64(Int32 x) { }
	// RVA: 0x6730d90 VA: 0x7598d48d90
	public LongArray ModInverse(Int32 m, Int32[] ks) { }
	// RVA: 0x6740af0 VA: 0x7598d58af0
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6740b78 VA: 0x7598d58b78
	public virtual Boolean Equals(LongArray other) { }
	// RVA: 0x6740c28 VA: 0x7598d58c28
	public override Int32 GetHashCode() { }
	// RVA: 0x6734fc0 VA: 0x7598d4cfc0
	public LongArray Copy() { }
	// RVA: 0x6740ca4 VA: 0x7598d58ca4
	public override String ToString() { }
	// RVA: 0x6740e64 VA: 0x7598d58e64
	private static Void .cctor() { }
}
```