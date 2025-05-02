# RC6Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean forEncryption`


## Methods

- `Void SetKey(Byte[])`

- `Int32 EncryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 DecryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 RotateLeft(Int32, Int32)`

- `Int32 RotateRight(Int32, Int32)`

- `Int32 BytesToWord(Byte[], Int32)`

- `Void WordToBytes(Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class RC6Engine : IBlockCipher
{
	private static readonly Int32 wordSize; // 0x0
	private static readonly Int32 bytesPerWord; // 0x4
	private static readonly Int32 _noRounds; // 0x8
	private Int32[] _S; // 0x10
	private static readonly Int32 P32; // 0xc
	private static readonly Int32 Q32; // 0x10
	private static readonly Int32 LGW; // 0x14
	private Boolean forEncryption; // 0x18

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x655200c VA: 0x7598b6a00c
	public Void .ctor() { }
	// RVA: 0x6552014 VA: 0x7598b6a014
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6552054 VA: 0x7598b6a054
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x655205c VA: 0x7598b6a05c
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x65520b8 VA: 0x7598b6a0b8
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x65524a4 VA: 0x7598b6a4a4
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6552ba4 VA: 0x7598b6aba4
	public virtual Void Reset() { }
	// RVA: 0x65521f8 VA: 0x7598b6a1f8
	private Void SetKey(Byte[] key) { }
	// RVA: 0x65528c8 VA: 0x7598b6a8c8
	private Int32 EncryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x65525f4 VA: 0x7598b6a5f4
	private Int32 DecryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6552ba8 VA: 0x7598b6aba8
	private Int32 RotateLeft(Int32 x, Int32 y) { }
	// RVA: 0x6552d98 VA: 0x7598b6ad98
	private Int32 RotateRight(Int32 x, Int32 y) { }
	// RVA: 0x6552c28 VA: 0x7598b6ac28
	private Int32 BytesToWord(Byte[] src, Int32 srcOff) { }
	// RVA: 0x6552cd8 VA: 0x7598b6acd8
	private Void WordToBytes(Int32 word, Byte[] dst, Int32 dstOff) { }
	// RVA: 0x6552e18 VA: 0x7598b6ae18
	private static Void .cctor() { }
}
```