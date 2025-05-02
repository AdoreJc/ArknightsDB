# CamelliaEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean initialised`

- `Boolean _keyIs128`


## Methods

- `Void setKey(Boolean, Byte[])`

- `Int32 processBlock128(Byte[], Int32, Byte[], Int32)`

- `Int32 processBlock192or256(Byte[], Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class CamelliaEngine : IBlockCipher
{
	private Boolean initialised; // 0x10
	private Boolean _keyIs128; // 0x11
	private const Int32 BLOCK_SIZE; // 0x0
	private UInt32[] subkey; // 0x18
	private UInt32[] kw; // 0x20
	private UInt32[] ke; // 0x28
	private UInt32[] state; // 0x30
	private static readonly UInt32[] SIGMA; // 0x0
	private static readonly UInt32[] SBOX1_1110; // 0x8
	private static readonly UInt32[] SBOX4_4404; // 0x10
	private static readonly UInt32[] SBOX2_0222; // 0x18
	private static readonly UInt32[] SBOX3_3033; // 0x20

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x653dd5c VA: 0x7598b55d5c
	private static UInt32 rightRotate(UInt32 x, Int32 s) { }
	// RVA: 0x653dd70 VA: 0x7598b55d70
	private static UInt32 leftRotate(UInt32 x, Int32 s) { }
	// RVA: 0x653dd84 VA: 0x7598b55d84
	private static Void roldq(Int32 rot, UInt32[] ki, Int32 ioff, UInt32[] ko, Int32 ooff) { }
	// RVA: 0x653deac VA: 0x7598b55eac
	private static Void decroldq(Int32 rot, UInt32[] ki, Int32 ioff, UInt32[] ko, Int32 ooff) { }
	// RVA: 0x653dfd4 VA: 0x7598b55fd4
	private static Void roldqo32(Int32 rot, UInt32[] ki, Int32 ioff, UInt32[] ko, Int32 ooff) { }
	// RVA: 0x653e0fc VA: 0x7598b560fc
	private static Void decroldqo32(Int32 rot, UInt32[] ki, Int32 ioff, UInt32[] ko, Int32 ooff) { }
	// RVA: 0x653e224 VA: 0x7598b56224
	private static UInt32 bytes2uint(Byte[] src, Int32 offset) { }
	// RVA: 0x653e284 VA: 0x7598b56284
	private static Void uint2bytes(UInt32 word, Byte[] dst, Int32 offset) { }
	// RVA: 0x653e2cc VA: 0x7598b562cc
	private static Void camelliaF2(UInt32[] s, UInt32[] skey, Int32 keyoff) { }
	// RVA: 0x653e5b4 VA: 0x7598b565b4
	private static Void camelliaFLs(UInt32[] s, UInt32[] fkey, Int32 keyoff) { }
	// RVA: 0x653e6e8 VA: 0x7598b566e8
	private Void setKey(Boolean forEncryption, Byte[] key) { }
	// RVA: 0x653f5f4 VA: 0x7598b575f4
	private Int32 processBlock128(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x653f8a4 VA: 0x7598b578a4
	private Int32 processBlock192or256(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x653fb90 VA: 0x7598b57b90
	public Void .ctor() { }
	// RVA: 0x653fc48 VA: 0x7598b57c48
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x653fd38 VA: 0x7598b57d38
	public virtual String get_AlgorithmName() { }
	// RVA: 0x653fd78 VA: 0x7598b57d78
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x653fd80 VA: 0x7598b57d80
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x653fd88 VA: 0x7598b57d88
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x653fec0 VA: 0x7598b57ec0
	public virtual Void Reset() { }
	// RVA: 0x653fec4 VA: 0x7598b57ec4
	private static Void .cctor() { }
}
```