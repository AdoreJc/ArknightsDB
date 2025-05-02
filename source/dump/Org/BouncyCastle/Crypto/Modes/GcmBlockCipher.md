# GcmBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Fields

- `IGcmExponentiator exp`

- `Boolean forEncryption`

- `Int32 macSize`

- `UInt32 blocksRemaining`

- `Int32 bufOff`

- `UInt64 totalLength`

- `Int32 atBlockPos`

- `UInt64 atLength`

- `UInt64 atLengthPre`


## Methods

- `IBlockCipher GetUnderlyingCipher()`

- `Void InitCipher()`

- `Void OutputBlock(Byte[], Int32)`

- `Int32 DoFinal(Byte[], Int32)`

- `Void Reset(Boolean)`

- `Void gCTRBlock(Byte[], Byte[], Int32)`

- `Void gCTRPartial(Byte[], Int32, Int32, Byte[], Int32)`

- `Void gHASH(Byte[], Byte[], Int32)`

- `Void gHASHBlock(Byte[], Byte[])`

- `Void gHASHPartial(Byte[], Byte[], Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class GcmBlockCipher : IAeadBlockCipher
{
	private const Int32 BlockSize; // 0x0
	private readonly IBlockCipher cipher; // 0x10
	private readonly IGcmMultiplier multiplier; // 0x18
	private IGcmExponentiator exp; // 0x20
	private Boolean forEncryption; // 0x28
	private Int32 macSize; // 0x2c
	private Byte[] nonce; // 0x30
	private Byte[] initialAssociatedText; // 0x38
	private Byte[] H; // 0x40
	private Byte[] J0; // 0x48
	private Byte[] bufBlock; // 0x50
	private Byte[] macBlock; // 0x58
	private Byte[] S; // 0x60
	private Byte[] S_at; // 0x68
	private Byte[] S_atPre; // 0x70
	private Byte[] counter; // 0x78
	private UInt32 blocksRemaining; // 0x80
	private Int32 bufOff; // 0x84
	private UInt64 totalLength; // 0x88
	private Byte[] atBlock; // 0x90
	private Int32 atBlockPos; // 0x98
	private UInt64 atLength; // 0xa0
	private UInt64 atLengthPre; // 0xa8

	public virtual String AlgorithmName { get; }

	// RVA: 0x6525758 VA: 0x7598b3d758
	public Void .ctor(IBlockCipher c) { }
	// RVA: 0x6525760 VA: 0x7598b3d760
	public Void .ctor(IBlockCipher c, IGcmMultiplier m) { }
	// RVA: 0x652590c VA: 0x7598b3d90c
	public virtual String get_AlgorithmName() { }
	// RVA: 0x65259cc VA: 0x7598b3d9cc
	public IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x65259d4 VA: 0x7598b3d9d4
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x65259dc VA: 0x7598b3d9dc
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x65261f4 VA: 0x7598b3e1f4
	public virtual Byte[] GetMac() { }
	// RVA: 0x6526200 VA: 0x7598b3e200
	public virtual Int32 GetOutputSize(Int32 len) { }
	// RVA: 0x6526228 VA: 0x7598b3e228
	public virtual Int32 GetUpdateOutputSize(Int32 len) { }
	// RVA: 0x6526260 VA: 0x7598b3e260
	public virtual Void ProcessAadByte(Byte input) { }
	// RVA: 0x65262cc VA: 0x7598b3e2cc
	public virtual Void ProcessAadBytes(Byte[] inBytes, Int32 inOff, Int32 len) { }
	// RVA: 0x6526384 VA: 0x7598b3e384
	private Void InitCipher() { }
	// RVA: 0x6526518 VA: 0x7598b3e518
	public virtual Int32 ProcessByte(Byte input, Byte[] output, Int32 outOff) { }
	// RVA: 0x6526644 VA: 0x7598b3e644
	public virtual Int32 ProcessBytes(Byte[] input, Int32 inOff, Int32 len, Byte[] output, Int32 outOff) { }
	// RVA: 0x6526584 VA: 0x7598b3e584
	private Void OutputBlock(Byte[] output, Int32 offset) { }
	// RVA: 0x652684c VA: 0x7598b3e84c
	public Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x65271a0 VA: 0x7598b3f1a0
	public virtual Void Reset() { }
	// RVA: 0x6526fd8 VA: 0x7598b3efd8
	private Void Reset(Boolean clearMac) { }
	// RVA: 0x652677c VA: 0x7598b3e77c
	private Void gCTRBlock(Byte[] block, Byte[] output, Int32 outOff) { }
	// RVA: 0x6526d68 VA: 0x7598b3ed68
	private Void gCTRPartial(Byte[] buf, Int32 off, Int32 len, Byte[] output, Int32 outOff) { }
	// RVA: 0x6526058 VA: 0x7598b3e058
	private Void gHASH(Byte[] Y, Byte[] b, Int32 len) { }
	// RVA: 0x652610c VA: 0x7598b3e10c
	private Void gHASHBlock(Byte[] Y, Byte[] b) { }
	// RVA: 0x6526418 VA: 0x7598b3e418
	private Void gHASHPartial(Byte[] Y, Byte[] b, Int32 off, Int32 len) { }
	// RVA: 0x65271a8 VA: 0x7598b3f1a8
	private Byte[] GetNextCounterBlock() { }
}
```