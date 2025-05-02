# MD4Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `Int32 H1`

- `Int32 H2`

- `Int32 H3`

- `Int32 H4`

- `Int32 xOff`


## Methods

- `Void CopyIn(MD4Digest)`

- `Void UnpackWord(Int32, Byte[], Int32)`

- `Int32 RotateLeft(Int32, Int32)`

- `Int32 F(Int32, Int32, Int32)`

- `Int32 G(Int32, Int32, Int32)`

- `Int32 H(Int32, Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class MD4Digest : GeneralDigest
{
	private const Int32 DigestLength; // 0x0
	private Int32 H1; // 0x28
	private Int32 H2; // 0x2c
	private Int32 H3; // 0x30
	private Int32 H4; // 0x34
	private Int32[] X; // 0x38
	private Int32 xOff; // 0x40
	private const Int32 S11; // 0x0
	private const Int32 S12; // 0x0
	private const Int32 S13; // 0x0
	private const Int32 S14; // 0x0
	private const Int32 S21; // 0x0
	private const Int32 S22; // 0x0
	private const Int32 S23; // 0x0
	private const Int32 S24; // 0x0
	private const Int32 S31; // 0x0
	private const Int32 S32; // 0x0
	private const Int32 S33; // 0x0
	private const Int32 S34; // 0x0

	public override String AlgorithmName { get; }

	// RVA: 0x657d0f0 VA: 0x7598b950f0
	public Void .ctor() { }
	// RVA: 0x657d164 VA: 0x7598b95164
	public Void .ctor(MD4Digest t) { }
	// RVA: 0x657d1e0 VA: 0x7598b951e0
	private Void CopyIn(MD4Digest t) { }
	// RVA: 0x657d238 VA: 0x7598b95238
	public override String get_AlgorithmName() { }
	// RVA: 0x657d278 VA: 0x7598b95278
	public override Int32 GetDigestSize() { }
	// RVA: 0x657d280 VA: 0x7598b95280
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x657d33c VA: 0x7598b9533c
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x657d3a8 VA: 0x7598b953a8
	private Void UnpackWord(Int32 word, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x657d428 VA: 0x7598b95428
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x657d4a4 VA: 0x7598b954a4
	public override Void Reset() { }
	// RVA: 0x657d500 VA: 0x7598b95500
	private Int32 RotateLeft(Int32 x, Int32 n) { }
	// RVA: 0x657d50c VA: 0x7598b9550c
	private Int32 F(Int32 u, Int32 v, Int32 w) { }
	// RVA: 0x657d51c VA: 0x7598b9551c
	private Int32 G(Int32 u, Int32 v, Int32 w) { }
	// RVA: 0x657d530 VA: 0x7598b95530
	private Int32 H(Int32 u, Int32 v, Int32 w) { }
	// RVA: 0x657d53c VA: 0x7598b9553c
	internal override Void ProcessBlock() { }
	// RVA: 0x657db84 VA: 0x7598b95b84
	public override IMemoable Copy() { }
	// RVA: 0x657dbe4 VA: 0x7598b95be4
	public override Void Reset(IMemoable other) { }
}
```