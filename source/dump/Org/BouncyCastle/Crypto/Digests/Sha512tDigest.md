# Sha512tDigest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `UInt64 H1t`

- `UInt64 H2t`

- `UInt64 H3t`

- `UInt64 H4t`

- `UInt64 H5t`

- `UInt64 H6t`

- `UInt64 H7t`

- `UInt64 H8t`


## Methods

- `Void tIvGenerate(Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class Sha512tDigest : LongDigest
{
	private const UInt64 A5; // 0x0
	private readonly Int32 digestLength; // 0x84
	private UInt64 H1t; // 0x88
	private UInt64 H2t; // 0x90
	private UInt64 H3t; // 0x98
	private UInt64 H4t; // 0xa0
	private UInt64 H5t; // 0xa8
	private UInt64 H6t; // 0xb0
	private UInt64 H7t; // 0xb8
	private UInt64 H8t; // 0xc0

	public override String AlgorithmName { get; }

	// RVA: 0x6588f84 VA: 0x7598ba0f84
	public Void .ctor(Int32 bitLength) { }
	// RVA: 0x6589274 VA: 0x7598ba1274
	public Void .ctor(Sha512tDigest t) { }
	// RVA: 0x6589304 VA: 0x7598ba1304
	public override String get_AlgorithmName() { }
	// RVA: 0x6589378 VA: 0x7598ba1378
	public override Int32 GetDigestSize() { }
	// RVA: 0x6589380 VA: 0x7598ba1380
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x65894e0 VA: 0x7598ba14e0
	public override Void Reset() { }
	// RVA: 0x65890ec VA: 0x7598ba10ec
	private Void tIvGenerate(Int32 bitLength) { }
	// RVA: 0x658947c VA: 0x7598ba147c
	private static Void UInt64_To_BE(UInt64 n, Byte[] bs, Int32 off, Int32 max) { }
	// RVA: 0x6589518 VA: 0x7598ba1518
	private static Void UInt32_To_BE(UInt32 n, Byte[] bs, Int32 off, Int32 max) { }
	// RVA: 0x65895d8 VA: 0x7598ba15d8
	public override IMemoable Copy() { }
	// RVA: 0x6589638 VA: 0x7598ba1638
	public override Void Reset(IMemoable other) { }
}
```