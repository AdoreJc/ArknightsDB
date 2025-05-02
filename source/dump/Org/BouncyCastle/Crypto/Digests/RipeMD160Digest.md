# RipeMD160Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `Int32 H0`

- `Int32 H1`

- `Int32 H2`

- `Int32 H3`

- `Int32 H4`

- `Int32 xOff`


## Methods

- `Void CopyIn(RipeMD160Digest)`

- `Void UnpackWord(Int32, Byte[], Int32)`

- `Int32 RL(Int32, Int32)`

- `Int32 F1(Int32, Int32, Int32)`

- `Int32 F2(Int32, Int32, Int32)`

- `Int32 F3(Int32, Int32, Int32)`

- `Int32 F4(Int32, Int32, Int32)`

- `Int32 F5(Int32, Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class RipeMD160Digest : GeneralDigest
{
	private const Int32 DigestLength; // 0x0
	private Int32 H0; // 0x28
	private Int32 H1; // 0x2c
	private Int32 H2; // 0x30
	private Int32 H3; // 0x34
	private Int32 H4; // 0x38
	private Int32[] X; // 0x40
	private Int32 xOff; // 0x48

	public override String AlgorithmName { get; }

	// RVA: 0x658142c VA: 0x7598b9942c
	public Void .ctor() { }
	// RVA: 0x65814a4 VA: 0x7598b994a4
	public Void .ctor(RipeMD160Digest t) { }
	// RVA: 0x6581524 VA: 0x7598b99524
	private Void CopyIn(RipeMD160Digest t) { }
	// RVA: 0x6581588 VA: 0x7598b99588
	public override String get_AlgorithmName() { }
	// RVA: 0x65815c8 VA: 0x7598b995c8
	public override Int32 GetDigestSize() { }
	// RVA: 0x65815d0 VA: 0x7598b995d0
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x658168c VA: 0x7598b9968c
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x65816f8 VA: 0x7598b996f8
	private Void UnpackWord(Int32 word, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6581778 VA: 0x7598b99778
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6581808 VA: 0x7598b99808
	public override Void Reset() { }
	// RVA: 0x6581874 VA: 0x7598b99874
	private Int32 RL(Int32 x, Int32 n) { }
	// RVA: 0x6581880 VA: 0x7598b99880
	private Int32 F1(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x658188c VA: 0x7598b9988c
	private Int32 F2(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x658189c VA: 0x7598b9989c
	private Int32 F3(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x65818a8 VA: 0x7598b998a8
	private Int32 F4(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x65818b8 VA: 0x7598b998b8
	private Int32 F5(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x65818c4 VA: 0x7598b998c4
	internal override Void ProcessBlock() { }
	// RVA: 0x6583044 VA: 0x7598b9b044
	public override IMemoable Copy() { }
	// RVA: 0x65830a4 VA: 0x7598b9b0a4
	public override Void Reset(IMemoable other) { }
}
```