# RipeMD320Digest

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

- `Int32 H8`

- `Int32 H9`

- `Int32 xOff`


## Methods

- `Void CopyIn(RipeMD320Digest)`

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
public class RipeMD320Digest : GeneralDigest
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
	private Int32 H8; // 0x48
	private Int32 H9; // 0x4c
	private Int32[] X; // 0x50
	private Int32 xOff; // 0x58

	public override String AlgorithmName { get; }

	// RVA: 0x6584760 VA: 0x7598b9c760
	public override String get_AlgorithmName() { }
	// RVA: 0x65847a0 VA: 0x7598b9c7a0
	public override Int32 GetDigestSize() { }
	// RVA: 0x65847a8 VA: 0x7598b9c7a8
	public Void .ctor() { }
	// RVA: 0x6584820 VA: 0x7598b9c820
	public Void .ctor(RipeMD320Digest t) { }
	// RVA: 0x65848a0 VA: 0x7598b9c8a0
	private Void CopyIn(RipeMD320Digest t) { }
	// RVA: 0x6584914 VA: 0x7598b9c914
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x65849d0 VA: 0x7598b9c9d0
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x6584a3c VA: 0x7598b9ca3c
	private Void UnpackWord(Int32 word, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6584abc VA: 0x7598b9cabc
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6584b9c VA: 0x7598b9cb9c
	public override Void Reset() { }
	// RVA: 0x6584c1c VA: 0x7598b9cc1c
	private Int32 RL(Int32 x, Int32 n) { }
	// RVA: 0x6584c28 VA: 0x7598b9cc28
	private Int32 F1(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x6584c34 VA: 0x7598b9cc34
	private Int32 F2(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x6584c44 VA: 0x7598b9cc44
	private Int32 F3(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x6584c50 VA: 0x7598b9cc50
	private Int32 F4(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x6584c60 VA: 0x7598b9cc60
	private Int32 F5(Int32 x, Int32 y, Int32 z) { }
	// RVA: 0x6584c6c VA: 0x7598b9cc6c
	internal override Void ProcessBlock() { }
	// RVA: 0x6586478 VA: 0x7598b9e478
	public override IMemoable Copy() { }
	// RVA: 0x65864d8 VA: 0x7598b9e4d8
	public override Void Reset(IMemoable other) { }
}
```