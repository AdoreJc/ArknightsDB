# RipeMD256Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `Int32 H0`

- `Int32 H1`

- `Int32 H2`

- `Int32 H3`

- `Int32 H4`

- `Int32 H5`

- `Int32 H6`

- `Int32 H7`

- `Int32 xOff`


## Methods

- `Void CopyIn(RipeMD256Digest)`

- `Void UnpackWord(Int32, Byte[], Int32)`

- `Int32 RL(Int32, Int32)`

- `Int32 F1(Int32, Int32, Int32)`

- `Int32 F2(Int32, Int32, Int32)`

- `Int32 F3(Int32, Int32, Int32)`

- `Int32 F4(Int32, Int32, Int32)`

- `Int32 F1(Int32, Int32, Int32, Int32, Int32, Int32)`

- `Int32 F2(Int32, Int32, Int32, Int32, Int32, Int32)`

- `Int32 F3(Int32, Int32, Int32, Int32, Int32, Int32)`

- `Int32 F4(Int32, Int32, Int32, Int32, Int32, Int32)`

- `Int32 FF1(Int32, Int32, Int32, Int32, Int32, Int32)`

- `Int32 FF2(Int32, Int32, Int32, Int32, Int32, Int32)`

- `Int32 FF3(Int32, Int32, Int32, Int32, Int32, Int32)`

- `Int32 FF4(Int32, Int32, Int32, Int32, Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class RipeMD256Digest : GeneralDigest
{
	private const Int32 DigestLength; // 0x0
	private Int32 H0; // 0x28
	private Int32 H1; // 0x2c
	private Int32 H2; // 0x30
	private Int32 H3; // 0x34
	private Int32 H4; // 0x38
	private Int32 H5; // 0x3c
	private Int32 H6; // 0x40
	private Int32 H7; // 0x44
	private Int32[] X; // 0x48
	private Int32 xOff; // 0x50

	public override String AlgorithmName { get; }

	// RVA: 0x6583128 VA: 0x7598b9b128
	public override String get_AlgorithmName() { }
	// RVA: 0x6583168 VA: 0x7598b9b168
	public override Int32 GetDigestSize() { }
	// RVA: 0x6583170 VA: 0x7598b9b170
	public Void .ctor() { }
	// RVA: 0x65831e8 VA: 0x7598b9b1e8
	public Void .ctor(RipeMD256Digest t) { }
	// RVA: 0x6583268 VA: 0x7598b9b268
	private Void CopyIn(RipeMD256Digest t) { }
	// RVA: 0x65832cc VA: 0x7598b9b2cc
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x6583388 VA: 0x7598b9b388
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x65833f4 VA: 0x7598b9b3f4
	private Void UnpackWord(Int32 word, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6583474 VA: 0x7598b9b474
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6583534 VA: 0x7598b9b534
	public override Void Reset() { }
	// RVA: 0x65835a0 VA: 0x7598b9b5a0
	private Int32 RL(Int32 x, Int32 n) { }
	// RVA: 0x65835ac VA: 0x7598b9b5ac
	private Int32 F1(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x65835b8 VA: 0x7598b9b5b8
	private Int32 F2(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x65835c8 VA: 0x7598b9b5c8
	private Int32 F3(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x65835d4 VA: 0x7598b9b5d4
	private Int32 F4(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x65835e4 VA: 0x7598b9b5e4
	private Int32 F1(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x6583600 VA: 0x7598b9b600
	private Int32 F2(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x658362c VA: 0x7598b9b62c
	private Int32 F3(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x6583654 VA: 0x7598b9b654
	private Int32 F4(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x6583680 VA: 0x7598b9b680
	private Int32 FF1(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x658369c VA: 0x7598b9b69c
	private Int32 FF2(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x65836c8 VA: 0x7598b9b6c8
	private Int32 FF3(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x65836f0 VA: 0x7598b9b6f0
	private Int32 FF4(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x658371c VA: 0x7598b9b71c
	internal override Void ProcessBlock() { }
	// RVA: 0x658467c VA: 0x7598b9c67c
	public override IMemoable Copy() { }
	// RVA: 0x65846dc VA: 0x7598b9c6dc
	public override Void Reset(IMemoable other) { }
}
```