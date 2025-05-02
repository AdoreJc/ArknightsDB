# MacCFBBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Properties

- `String AlgorithmName`

- `Boolean IsPartialBlockOkay`


## Methods

- `Void Init(Boolean, ICipherParameters)`

- `String get_AlgorithmName()`

- `Boolean get_IsPartialBlockOkay()`

- `Int32 GetBlockSize()`

- `Int32 ProcessBlock(Byte[], Int32, Byte[], Int32)`

- `Void Reset()`

- `Void GetMacBlock(Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Macs
internal class MacCFBBlockCipher : IBlockCipher
{
	private Byte[] IV; // 0x10
	private Byte[] cfbV; // 0x18
	private Byte[] cfbOutV; // 0x20
	private readonly Int32 blockSize; // 0x28
	private readonly IBlockCipher cipher; // 0x30

	public String AlgorithmName { get; }
	public Boolean IsPartialBlockOkay { get; }

	// RVA: 0x652e724 VA: 0x7598b46724
	public Void .ctor(IBlockCipher cipher, Int32 bitBlockSize) { }
	// RVA: 0x652e934 VA: 0x7598b46934
	public Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x652eb28 VA: 0x7598b46b28
	public String get_AlgorithmName() { }
	// RVA: 0x652ec1c VA: 0x7598b46c1c
	public Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x652ec24 VA: 0x7598b46c24
	public Int32 GetBlockSize() { }
	// RVA: 0x652ec2c VA: 0x7598b46c2c
	public Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x652ea6c VA: 0x7598b46a6c
	public Void Reset() { }
	// RVA: 0x652ee84 VA: 0x7598b46e84
	public Void GetMacBlock(Byte[] mac) { }
}
```