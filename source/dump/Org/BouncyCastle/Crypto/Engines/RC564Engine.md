# RC564Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Int32 _noRounds`

- `Boolean forEncryption`


## Methods

- `Void SetKey(Byte[])`

- `Int32 EncryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 DecryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int64 RotateLeft(Int64, Int64)`

- `Int64 RotateRight(Int64, Int64)`

- `Int64 BytesToWord(Byte[], Int32)`

- `Void WordToBytes(Int64, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class RC564Engine : IBlockCipher
{
	private static readonly Int32 wordSize; // 0x0
	private static readonly Int32 bytesPerWord; // 0x4
	private Int32 _noRounds; // 0x10
	private Int64[] _S; // 0x18
	private static readonly Int64 P64; // 0x8
	private static readonly Int64 Q64; // 0x10
	private Boolean forEncryption; // 0x20

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x655149c VA: 0x7598b6949c
	public Void .ctor() { }
	// RVA: 0x65514bc VA: 0x7598b694bc
	public virtual String get_AlgorithmName() { }
	// RVA: 0x65514fc VA: 0x7598b694fc
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x6551504 VA: 0x7598b69504
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x6551560 VA: 0x7598b69560
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x65519dc VA: 0x7598b699dc
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x6551d3c VA: 0x7598b69d3c
	public virtual Void Reset() { }
	// RVA: 0x6551700 VA: 0x7598b69700
	private Void SetKey(Byte[] key) { }
	// RVA: 0x6551b90 VA: 0x7598b69b90
	private Int32 EncryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x65519ec VA: 0x7598b699ec
	private Int32 DecryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6551d40 VA: 0x7598b69d40
	private Int64 RotateLeft(Int64 x, Int64 y) { }
	// RVA: 0x6551f30 VA: 0x7598b69f30
	private Int64 RotateRight(Int64 x, Int64 y) { }
	// RVA: 0x6551dc0 VA: 0x7598b69dc0
	private Int64 BytesToWord(Byte[] src, Int32 srcOff) { }
	// RVA: 0x6551e70 VA: 0x7598b69e70
	private Void WordToBytes(Int64 word, Byte[] dst, Int32 dstOff) { }
	// RVA: 0x6551fb0 VA: 0x7598b69fb0
	private static Void .cctor() { }
}
```