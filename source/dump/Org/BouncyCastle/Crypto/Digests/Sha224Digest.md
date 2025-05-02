# Sha224Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `UInt32 H1`

- `UInt32 H2`

- `UInt32 H3`

- `UInt32 H4`

- `UInt32 H5`

- `UInt32 H6`

- `UInt32 H7`

- `UInt32 H8`

- `Int32 xOff`


## Methods

- `Void CopyIn(Sha224Digest)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class Sha224Digest : GeneralDigest
{
	private const Int32 DigestLength; // 0x0
	private UInt32 H1; // 0x28
	private UInt32 H2; // 0x2c
	private UInt32 H3; // 0x30
	private UInt32 H4; // 0x34
	private UInt32 H5; // 0x38
	private UInt32 H6; // 0x3c
	private UInt32 H7; // 0x40
	private UInt32 H8; // 0x44
	private UInt32[] X; // 0x48
	private Int32 xOff; // 0x50
	internal static readonly UInt32[] K; // 0x0

	public override String AlgorithmName { get; }

	// RVA: 0x6586f2c VA: 0x7598b9ef2c
	public Void .ctor() { }
	// RVA: 0x6586fa4 VA: 0x7598b9efa4
	public Void .ctor(Sha224Digest t) { }
	// RVA: 0x6587024 VA: 0x7598b9f024
	private Void CopyIn(Sha224Digest t) { }
	// RVA: 0x6587088 VA: 0x7598b9f088
	public override String get_AlgorithmName() { }
	// RVA: 0x65870c8 VA: 0x7598b9f0c8
	public override Int32 GetDigestSize() { }
	// RVA: 0x65870d0 VA: 0x7598b9f0d0
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x6587150 VA: 0x7598b9f150
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x65871bc VA: 0x7598b9f1bc
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6587288 VA: 0x7598b9f288
	public override Void Reset() { }
	// RVA: 0x65872d4 VA: 0x7598b9f2d4
	internal override Void ProcessBlock() { }
	// RVA: 0x6587870 VA: 0x7598b9f870
	private static UInt32 Ch(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x6587890 VA: 0x7598b9f890
	private static UInt32 Maj(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x6587880 VA: 0x7598b9f880
	private static UInt32 Sum0(UInt32 x) { }
	// RVA: 0x6587860 VA: 0x7598b9f860
	private static UInt32 Sum1(UInt32 x) { }
	// RVA: 0x6587850 VA: 0x7598b9f850
	private static UInt32 Theta0(UInt32 x) { }
	// RVA: 0x6587840 VA: 0x7598b9f840
	private static UInt32 Theta1(UInt32 x) { }
	// RVA: 0x65878a4 VA: 0x7598b9f8a4
	public override IMemoable Copy() { }
	// RVA: 0x6587904 VA: 0x7598b9f904
	public override Void Reset(IMemoable other) { }
	// RVA: 0x6587988 VA: 0x7598b9f988
	private static Void .cctor() { }
}
```