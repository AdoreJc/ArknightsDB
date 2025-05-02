# OfbBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Properties

- `String AlgorithmName`

- `Boolean IsPartialBlockOkay`


## Methods

- `IBlockCipher GetUnderlyingCipher()`

- `Void Init(Boolean, ICipherParameters)`

- `String get_AlgorithmName()`

- `Boolean get_IsPartialBlockOkay()`

- `Int32 GetBlockSize()`

- `Int32 ProcessBlock(Byte[], Int32, Byte[], Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class OfbBlockCipher : IBlockCipher
{
	private Byte[] IV; // 0x10
	private Byte[] ofbV; // 0x18
	private Byte[] ofbOutV; // 0x20
	private readonly Int32 blockSize; // 0x28
	private readonly IBlockCipher cipher; // 0x30

	public String AlgorithmName { get; }
	public Boolean IsPartialBlockOkay { get; }

	// RVA: 0x6529d48 VA: 0x7598b41d48
	public Void .ctor(IBlockCipher cipher, Int32 blockSize) { }
	// RVA: 0x6529f58 VA: 0x7598b41f58
	public IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x6529f60 VA: 0x7598b41f60
	public Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x652a1dc VA: 0x7598b421dc
	public String get_AlgorithmName() { }
	// RVA: 0x652a2d0 VA: 0x7598b422d0
	public Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x652a2d8 VA: 0x7598b422d8
	public Int32 GetBlockSize() { }
	// RVA: 0x652a2e0 VA: 0x7598b422e0
	public Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x652a118 VA: 0x7598b42118
	public Void Reset() { }
}
```