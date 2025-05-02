# IdeaEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Methods

- `Int32 BytesToWord(Byte[], Int32)`

- `Void WordToBytes(Int32, Byte[], Int32)`

- `Int32 Mul(Int32, Int32)`

- `Void IdeaFunc(Int32[], Byte[], Int32, Byte[], Int32)`

- `Int32 MulInv(Int32)`

- `Int32 AddInv(Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class IdeaEngine : IBlockCipher
{
	private const Int32 BLOCK_SIZE; // 0x0
	private Int32[] workingKey; // 0x10
	private static readonly Int32 MASK; // 0x0
	private static readonly Int32 BASE; // 0x4

	public virtual String AlgorithmName { get; }
	public virtual Boolean IsPartialBlockOkay { get; }

	// RVA: 0x654b8a8 VA: 0x7598b638a8
	public Void .ctor() { }
	// RVA: 0x654b8b0 VA: 0x7598b638b0
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x654ba00 VA: 0x7598b63a00
	public virtual String get_AlgorithmName() { }
	// RVA: 0x654ba40 VA: 0x7598b63a40
	public virtual Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x654ba48 VA: 0x7598b63a48
	public virtual Int32 GetBlockSize() { }
	// RVA: 0x654ba50 VA: 0x7598b63a50
	public virtual Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x654be00 VA: 0x7598b63e00
	public virtual Void Reset() { }
	// RVA: 0x654be04 VA: 0x7598b63e04
	private Int32 BytesToWord(Byte[] input, Int32 inOff) { }
	// RVA: 0x654be44 VA: 0x7598b63e44
	private Void WordToBytes(Int32 word, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x654be8c VA: 0x7598b63e8c
	private Int32 Mul(Int32 x, Int32 y) { }
	// RVA: 0x654bb68 VA: 0x7598b63b68
	private Void IdeaFunc(Int32[] workingKey, Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x654bf68 VA: 0x7598b63f68
	private Int32[] ExpandKey(Byte[] uKey) { }
	// RVA: 0x654c160 VA: 0x7598b64160
	private Int32 MulInv(Int32 x) { }
	// RVA: 0x654c278 VA: 0x7598b64278
	private Int32 AddInv(Int32 x) { }
	// RVA: 0x654c2dc VA: 0x7598b642dc
	private Int32[] InvertKey(Int32[] inKey) { }
	// RVA: 0x654b9d8 VA: 0x7598b639d8
	private Int32[] GenerateWorkingKey(Boolean forEncryption, Byte[] userKey) { }
	// RVA: 0x654c564 VA: 0x7598b64564
	private static Void .cctor() { }
}
```