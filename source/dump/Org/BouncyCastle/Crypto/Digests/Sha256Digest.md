# Sha256Digest

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

- `Void CopyIn(Sha256Digest)`

- `Void initHs()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class Sha256Digest : GeneralDigest
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
	private static readonly UInt32[] K; // 0x0

	public override String AlgorithmName { get; }

	// RVA: 0x6587a28 VA: 0x7598b9fa28
	public Void .ctor() { }
	// RVA: 0x6587ac4 VA: 0x7598b9fac4
	public Void .ctor(Sha256Digest t) { }
	// RVA: 0x6587b44 VA: 0x7598b9fb44
	private Void CopyIn(Sha256Digest t) { }
	// RVA: 0x6587ba8 VA: 0x7598b9fba8
	public override String get_AlgorithmName() { }
	// RVA: 0x6587be8 VA: 0x7598b9fbe8
	public override Int32 GetDigestSize() { }
	// RVA: 0x6587bf0 VA: 0x7598b9fbf0
	internal override Void ProcessWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x6587c70 VA: 0x7598b9fc70
	internal override Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x6587cdc VA: 0x7598b9fcdc
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6587dbc VA: 0x7598b9fdbc
	public override Void Reset() { }
	// RVA: 0x6587aa8 VA: 0x7598b9faa8
	private Void initHs() { }
	// RVA: 0x6587e08 VA: 0x7598b9fe08
	internal override Void ProcessBlock() { }
	// RVA: 0x6588394 VA: 0x7598ba0394
	private static UInt32 Sum1Ch(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x65883b4 VA: 0x7598ba03b4
	private static UInt32 Sum0Maj(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x6588384 VA: 0x7598ba0384
	private static UInt32 Theta0(UInt32 x) { }
	// RVA: 0x6588374 VA: 0x7598ba0374
	private static UInt32 Theta1(UInt32 x) { }
	// RVA: 0x65883d8 VA: 0x7598ba03d8
	public override IMemoable Copy() { }
	// RVA: 0x6588438 VA: 0x7598ba0438
	public override Void Reset(IMemoable other) { }
	// RVA: 0x65884bc VA: 0x7598ba04bc
	private static Void .cctor() { }
}
```