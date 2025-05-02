# Sha1Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `UInt32 H1`

- `UInt32 H2`

- `UInt32 H3`

- `UInt32 H4`

- `UInt32 H5`

- `Int32 xOff`


## Methods

- `Void CopyIn(Sha1Digest)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class Sha1Digest : GeneralDigest
{
	private const Int32 DigestLength; // 0x0
	private UInt32 H1; // 0x28
	private UInt32 H2; // 0x2c
	private UInt32 H3; // 0x30
	private UInt32 H4; // 0x34
	private UInt32 H5; // 0x38
	private UInt32[] X; // 0x40
	private Int32 xOff; // 0x48
	private const UInt32 Y1; // 0x0
	private const UInt32 Y2; // 0x0
	private const UInt32 Y3; // 0x0
	private const UInt32 Y4; // 0x0

	public override String AlgorithmName { get; }

	// RVA: 0x658655c VA: 0x7598b9e55c
	public Void .ctor() { }
	// RVA: 0x65865d4 VA: 0x7598b9e5d4
	public Void .ctor(Sha1Digest t) { }
	// RVA: 0x6586654 VA: 0x7598b9e654
	private Void CopyIn(Sha1Digest t) { }
	// RVA: 0x65866b8 VA: 0x7598b9e6b8
	public override String get_AlgorithmName() { }
	// RVA: 0x65866f8 VA: 0x7598b9e6f8
	public override Int32 GetDigestSize() { }
	// RVA: 0x6586700 VA: 0x7598b9e700
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x6586780 VA: 0x7598b9e780
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x65867ec VA: 0x7598b9e7ec
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6586890 VA: 0x7598b9e890
	public override Void Reset() { }
	// RVA: 0x65868dc VA: 0x7598b9e8dc
	private static UInt32 F(UInt32 u, UInt32 v, UInt32 w) { }
	// RVA: 0x65868ec VA: 0x7598b9e8ec
	private static UInt32 H(UInt32 u, UInt32 v, UInt32 w) { }
	// RVA: 0x65868f8 VA: 0x7598b9e8f8
	private static UInt32 G(UInt32 u, UInt32 v, UInt32 w) { }
	// RVA: 0x658690c VA: 0x7598b9e90c
	internal override Void ProcessBlock() { }
	// RVA: 0x6586e48 VA: 0x7598b9ee48
	public override IMemoable Copy() { }
	// RVA: 0x6586ea8 VA: 0x7598b9eea8
	public override Void Reset(IMemoable other) { }
}
```