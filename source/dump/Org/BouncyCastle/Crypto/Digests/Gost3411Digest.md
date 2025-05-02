# Gost3411Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `Int32 xBufOff`

- `UInt64 byteCount`


## Properties

- `String AlgorithmName`


## Methods

- `String get_AlgorithmName()`

- `Int32 GetDigestSize()`

- `Void Update(Byte)`

- `Void BlockUpdate(Byte[], Int32, Int32)`

- `Void E(Byte[], Byte[], Int32, Byte[], Int32)`

- `Void fw(Byte[])`

- `Void processBlock(Byte[], Int32)`

- `Void finish()`

- `Int32 DoFinal(Byte[], Int32)`

- `Void Reset()`

- `Void sumByteArray(Byte[])`

- `Int32 GetByteLength()`

- `IMemoable Copy()`

- `Void Reset(IMemoable)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class Gost3411Digest : IDigest, IMemoable
{
	private const Int32 DIGEST_LENGTH; // 0x0
	private Byte[] H; // 0x10
	private Byte[] L; // 0x18
	private Byte[] M; // 0x20
	private Byte[] Sum; // 0x28
	private Byte[][] C; // 0x30
	private Byte[] xBuf; // 0x38
	private Int32 xBufOff; // 0x40
	private UInt64 byteCount; // 0x48
	private readonly IBlockCipher cipher; // 0x50
	private Byte[] sBox; // 0x58
	private Byte[] K; // 0x60
	private Byte[] a; // 0x68
	internal Int16[] wS; // 0x70
	internal Int16[] w_S; // 0x78
	internal Byte[] S; // 0x80
	internal Byte[] U; // 0x88
	internal Byte[] V; // 0x90
	internal Byte[] W; // 0x98
	private static readonly Byte[] C2; // 0x0

	public String AlgorithmName { get; }

	// RVA: 0x6578870 VA: 0x7598b90870
	private static Byte[][] MakeC() { }
	// RVA: 0x657895c VA: 0x7598b9095c
	public Void .ctor() { }
	// RVA: 0x6578e0c VA: 0x7598b90e0c
	public Void .ctor(Byte[] sBoxParam) { }
	// RVA: 0x6579144 VA: 0x7598b91144
	public Void .ctor(Gost3411Digest t) { }
	// RVA: 0x6579688 VA: 0x7598b91688
	public String get_AlgorithmName() { }
	// RVA: 0x65796c8 VA: 0x7598b916c8
	public Int32 GetDigestSize() { }
	// RVA: 0x65796d0 VA: 0x7598b916d0
	public Void Update(Byte input) { }
	// RVA: 0x6579b04 VA: 0x7598b91b04
	public Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x6579c34 VA: 0x7598b91c34
	private Byte[] P(Byte[] input) { }
	// RVA: 0x6579d44 VA: 0x7598b91d44
	private Byte[] A(Byte[] input) { }
	// RVA: 0x6579e04 VA: 0x7598b91e04
	private Void E(Byte[] key, Byte[] s, Int32 sOff, Byte[] input, Int32 inOff) { }
	// RVA: 0x6579f80 VA: 0x7598b91f80
	private Void fw(Byte[] input) { }
	// RVA: 0x65797c8 VA: 0x7598b917c8
	private Void processBlock(Byte[] input, Int32 inOff) { }
	// RVA: 0x657a1b4 VA: 0x7598b921b4
	private Void finish() { }
	// RVA: 0x657a20c VA: 0x7598b9220c
	public Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6578cac VA: 0x7598b90cac
	public Void Reset() { }
	// RVA: 0x6579750 VA: 0x7598b91750
	private Void sumByteArray(Byte[] input) { }
	// RVA: 0x657a08c VA: 0x7598b9208c
	private static Void cpyBytesToShort(Byte[] S, Int16[] wS) { }
	// RVA: 0x657a118 VA: 0x7598b92118
	private static Void cpyShortToBytes(Int16[] wS, Byte[] S) { }
	// RVA: 0x657a258 VA: 0x7598b92258
	public Int32 GetByteLength() { }
	// RVA: 0x657a260 VA: 0x7598b92260
	public IMemoable Copy() { }
	// RVA: 0x657939c VA: 0x7598b9139c
	public Void Reset(IMemoable other) { }
	// RVA: 0x657a2c0 VA: 0x7598b922c0
	private static Void .cctor() { }
}
```