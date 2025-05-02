# TigerDigest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `Int64 a`

- `Int64 b`

- `Int64 c`

- `Int64 byteCount`

- `Int32 bOff`

- `Int32 xOff`


## Properties

- `String AlgorithmName`


## Methods

- `String get_AlgorithmName()`

- `Int32 GetDigestSize()`

- `Int32 GetByteLength()`

- `Void ProcessWord(Byte[], Int32)`

- `Void Update(Byte)`

- `Void BlockUpdate(Byte[], Int32, Int32)`

- `Void RoundABC(Int64, Int64)`

- `Void RoundBCA(Int64, Int64)`

- `Void RoundCAB(Int64, Int64)`

- `Void KeySchedule()`

- `Void ProcessBlock()`

- `Void UnpackWord(Int64, Byte[], Int32)`

- `Void ProcessLength(Int64)`

- `Void Finish()`

- `Int32 DoFinal(Byte[], Int32)`

- `Void Reset()`

- `IMemoable Copy()`

- `Void Reset(IMemoable)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class TigerDigest : IDigest, IMemoable
{
	private const Int32 MyByteLength; // 0x0
	private static readonly Int64[] t1; // 0x0
	private static readonly Int64[] t2; // 0x8
	private static readonly Int64[] t3; // 0x10
	private static readonly Int64[] t4; // 0x18
	private const Int32 DigestLength; // 0x0
	private Int64 a; // 0x10
	private Int64 b; // 0x18
	private Int64 c; // 0x20
	private Int64 byteCount; // 0x28
	private Byte[] Buffer; // 0x30
	private Int32 bOff; // 0x38
	private Int64[] x; // 0x40
	private Int32 xOff; // 0x48

	public String AlgorithmName { get; }

	// RVA: 0x6589cd4 VA: 0x7598ba1cd4
	public Void .ctor() { }
	// RVA: 0x6589e1c VA: 0x7598ba1e1c
	public Void .ctor(TigerDigest t) { }
	// RVA: 0x6589fb0 VA: 0x7598ba1fb0
	public String get_AlgorithmName() { }
	// RVA: 0x6589ff0 VA: 0x7598ba1ff0
	public Int32 GetDigestSize() { }
	// RVA: 0x6589ff8 VA: 0x7598ba1ff8
	public Int32 GetByteLength() { }
	// RVA: 0x658a000 VA: 0x7598ba2000
	private Void ProcessWord(Byte[] b, Int32 off) { }
	// RVA: 0x658a500 VA: 0x7598ba2500
	public Void Update(Byte input) { }
	// RVA: 0x658a570 VA: 0x7598ba2570
	public Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x658a680 VA: 0x7598ba2680
	private Void RoundABC(Int64 x, Int64 mul) { }
	// RVA: 0x658a804 VA: 0x7598ba2804
	private Void RoundBCA(Int64 x, Int64 mul) { }
	// RVA: 0x658a984 VA: 0x7598ba2984
	private Void RoundCAB(Int64 x, Int64 mul) { }
	// RVA: 0x658ab04 VA: 0x7598ba2b04
	private Void KeySchedule() { }
	// RVA: 0x658a11c VA: 0x7598ba211c
	private Void ProcessBlock() { }
	// RVA: 0x658abe0 VA: 0x7598ba2be0
	private Void UnpackWord(Int64 r, Byte[] output, Int32 outOff) { }
	// RVA: 0x658acd0 VA: 0x7598ba2cd0
	private Void ProcessLength(Int64 bitLength) { }
	// RVA: 0x658acfc VA: 0x7598ba2cfc
	private Void Finish() { }
	// RVA: 0x658ad48 VA: 0x7598ba2d48
	public Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6589d78 VA: 0x7598ba1d78
	public Void Reset() { }
	// RVA: 0x658ada8 VA: 0x7598ba2da8
	public IMemoable Copy() { }
	// RVA: 0x6589ec8 VA: 0x7598ba1ec8
	public Void Reset(IMemoable other) { }
	// RVA: 0x658ae08 VA: 0x7598ba2e08
	private static Void .cctor() { }
}
```