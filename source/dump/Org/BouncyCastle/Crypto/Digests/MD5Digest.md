# MD5Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `UInt32 H1`

- `UInt32 H2`

- `UInt32 H3`

- `UInt32 H4`

- `Int32 xOff`


## Methods

- `Void CopyIn(MD5Digest)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class MD5Digest : GeneralDigest
{
	private const Int32 DigestLength; // 0x0
	private UInt32 H1; // 0x28
	private UInt32 H2; // 0x2c
	private UInt32 H3; // 0x30
	private UInt32 H4; // 0x34
	private UInt32[] X; // 0x38
	private Int32 xOff; // 0x40
	private static readonly Int32 S11; // 0x0
	private static readonly Int32 S12; // 0x4
	private static readonly Int32 S13; // 0x8
	private static readonly Int32 S14; // 0xc
	private static readonly Int32 S21; // 0x10
	private static readonly Int32 S22; // 0x14
	private static readonly Int32 S23; // 0x18
	private static readonly Int32 S24; // 0x1c
	private static readonly Int32 S31; // 0x20
	private static readonly Int32 S32; // 0x24
	private static readonly Int32 S33; // 0x28
	private static readonly Int32 S34; // 0x2c
	private static readonly Int32 S41; // 0x30
	private static readonly Int32 S42; // 0x34
	private static readonly Int32 S43; // 0x38
	private static readonly Int32 S44; // 0x3c

	public override String AlgorithmName { get; }

	// RVA: 0x657dc68 VA: 0x7598b95c68
	public Void .ctor() { }
	// RVA: 0x657dcdc VA: 0x7598b95cdc
	public Void .ctor(MD5Digest t) { }
	// RVA: 0x657dd58 VA: 0x7598b95d58
	private Void CopyIn(MD5Digest t) { }
	// RVA: 0x657ddb0 VA: 0x7598b95db0
	public override String get_AlgorithmName() { }
	// RVA: 0x657ddf0 VA: 0x7598b95df0
	public override Int32 GetDigestSize() { }
	// RVA: 0x657ddf8 VA: 0x7598b95df8
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x657de78 VA: 0x7598b95e78
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x657df30 VA: 0x7598b95f30
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x657dfbc VA: 0x7598b95fbc
	public override Void Reset() { }
	// RVA: 0x657e018 VA: 0x7598b96018
	private static UInt32 RotateLeft(UInt32 x, Int32 n) { }
	// RVA: 0x657e024 VA: 0x7598b96024
	private static UInt32 F(UInt32 u, UInt32 v, UInt32 w) { }
	// RVA: 0x657e034 VA: 0x7598b96034
	private static UInt32 G(UInt32 u, UInt32 v, UInt32 w) { }
	// RVA: 0x657e044 VA: 0x7598b96044
	private static UInt32 H(UInt32 u, UInt32 v, UInt32 w) { }
	// RVA: 0x657e050 VA: 0x7598b96050
	private static UInt32 K(UInt32 u, UInt32 v, UInt32 w) { }
	// RVA: 0x657e05c VA: 0x7598b9605c
	internal override Void ProcessBlock() { }
	// RVA: 0x657ebc4 VA: 0x7598b96bc4
	public override IMemoable Copy() { }
	// RVA: 0x657ec24 VA: 0x7598b96c24
	public override Void Reset(IMemoable other) { }
	// RVA: 0x657eca8 VA: 0x7598b96ca8
	private static Void .cctor() { }
}
```