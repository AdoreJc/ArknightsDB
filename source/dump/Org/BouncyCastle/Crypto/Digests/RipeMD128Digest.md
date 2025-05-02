# RipeMD128Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `Int32 H0`

- `Int32 H1`

- `Int32 H2`

- `Int32 H3`

- `Int32 xOff`


## Methods

- `Void CopyIn(RipeMD128Digest)`

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
public class RipeMD128Digest : GeneralDigest
{
	private const Int32 DigestLength; // 0x0
	private Int32 H0; // 0x28
	private Int32 H1; // 0x2c
	private Int32 H2; // 0x30
	private Int32 H3; // 0x34
	private Int32[] X; // 0x38
	private Int32 xOff; // 0x40

	public override String AlgorithmName { get; }

	// RVA: 0x657eee0 VA: 0x7598b96ee0
	public Void .ctor() { }
	// RVA: 0x657ef54 VA: 0x7598b96f54
	public Void .ctor(RipeMD128Digest t) { }
	// RVA: 0x657efd0 VA: 0x7598b96fd0
	private Void CopyIn(RipeMD128Digest t) { }
	// RVA: 0x657f028 VA: 0x7598b97028
	public override String get_AlgorithmName() { }
	// RVA: 0x657f068 VA: 0x7598b97068
	public override Int32 GetDigestSize() { }
	// RVA: 0x657f070 VA: 0x7598b97070
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x657f12c VA: 0x7598b9712c
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x657f198 VA: 0x7598b97198
	private Void UnpackWord(Int32 word, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x657f218 VA: 0x7598b97218
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x657f294 VA: 0x7598b97294
	public override Void Reset() { }
	// RVA: 0x657f2f0 VA: 0x7598b972f0
	private Int32 RL(Int32 x, Int32 n) { }
	// RVA: 0x657f2fc VA: 0x7598b972fc
	private Int32 F1(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x657f308 VA: 0x7598b97308
	private Int32 F2(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x657f318 VA: 0x7598b97318
	private Int32 F3(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x657f324 VA: 0x7598b97324
	private Int32 F4(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x657f334 VA: 0x7598b97334
	private Int32 F1(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x657f350 VA: 0x7598b97350
	private Int32 F2(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x657f37c VA: 0x7598b9737c
	private Int32 F3(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x657f3a4 VA: 0x7598b973a4
	private Int32 F4(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x657f3d0 VA: 0x7598b973d0
	private Int32 FF1(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x657f3ec VA: 0x7598b973ec
	private Int32 FF2(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x657f418 VA: 0x7598b97418
	private Int32 FF3(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x657f440 VA: 0x7598b97440
	private Int32 FF4(Int32 a, Int32 b, Int32 c, Int32 d, Int32 x, Int32 s) { }
	// RVA: 0x657f46c VA: 0x7598b9746c
	internal override Void ProcessBlock() { }
	// RVA: 0x6580348 VA: 0x7598b98348
	public override IMemoable Copy() { }
	// RVA: 0x65803a8 VA: 0x7598b983a8
	public override Void Reset(IMemoable other) { }
}
```