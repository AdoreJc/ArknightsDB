# CfbBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Fields

- `Boolean encrypting`


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

- `Int32 EncryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 DecryptBlock(Byte[], Int32, Byte[], Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class CfbBlockCipher : IBlockCipher
{
	private Byte[] IV; // 0x10
	private Byte[] cfbV; // 0x18
	private Byte[] cfbOutV; // 0x20
	private Boolean encrypting; // 0x28
	private readonly Int32 blockSize; // 0x2c
	private readonly IBlockCipher cipher; // 0x30

	public String AlgorithmName { get; }
	public Boolean IsPartialBlockOkay { get; }

	// RVA: 0x65229b0 VA: 0x7598b3a9b0
	public Void .ctor(IBlockCipher cipher, Int32 bitBlockSize) { }
	// RVA: 0x6522bc0 VA: 0x7598b3abc0
	public IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x6522bc8 VA: 0x7598b3abc8
	public Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6522e10 VA: 0x7598b3ae10
	public String get_AlgorithmName() { }
	// RVA: 0x6522f04 VA: 0x7598b3af04
	public Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x6522f0c VA: 0x7598b3af0c
	public Int32 GetBlockSize() { }
	// RVA: 0x6522f14 VA: 0x7598b3af14
	public Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x652317c VA: 0x7598b3b17c
	public Int32 EncryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6522f24 VA: 0x7598b3af24
	public Int32 DecryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x6522d4c VA: 0x7598b3ad4c
	public Void Reset() { }
}
```