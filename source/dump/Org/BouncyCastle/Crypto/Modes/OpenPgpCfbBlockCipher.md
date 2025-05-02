# OpenPgpCfbBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Fields

- `Int32 count`

- `Boolean forEncryption`


## Properties

- `String AlgorithmName`

- `Boolean IsPartialBlockOkay`


## Methods

- `IBlockCipher GetUnderlyingCipher()`

- `String get_AlgorithmName()`

- `Boolean get_IsPartialBlockOkay()`

- `Int32 GetBlockSize()`

- `Int32 ProcessBlock(Byte[], Int32, Byte[], Int32)`

- `Void Reset()`

- `Void Init(Boolean, ICipherParameters)`

- `Byte EncryptByte(Byte, Int32)`

- `Int32 EncryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 DecryptBlock(Byte[], Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class OpenPgpCfbBlockCipher : IBlockCipher
{
	private Byte[] IV; // 0x10
	private Byte[] FR; // 0x18
	private Byte[] FRE; // 0x20
	private readonly IBlockCipher cipher; // 0x28
	private readonly Int32 blockSize; // 0x30
	private Int32 count; // 0x34
	private Boolean forEncryption; // 0x38

	public String AlgorithmName { get; }
	public Boolean IsPartialBlockOkay { get; }

	// RVA: 0x652a538 VA: 0x7598b42538
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x652a664 VA: 0x7598b42664
	public IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x652a66c VA: 0x7598b4266c
	public String get_AlgorithmName() { }
	// RVA: 0x652a72c VA: 0x7598b4272c
	public Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x652a734 VA: 0x7598b42734
	public Int32 GetBlockSize() { }
	// RVA: 0x652a7d8 VA: 0x7598b427d8
	public Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x652b434 VA: 0x7598b43434
	public Void Reset() { }
	// RVA: 0x652b4fc VA: 0x7598b434fc
	public Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x652b6a0 VA: 0x7598b436a0
	private Byte EncryptByte(Byte data, Int32 blockOff) { }
	// RVA: 0x652ae34 VA: 0x7598b42e34
	private Int32 EncryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x652a7e8 VA: 0x7598b427e8
	private Int32 DecryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
}
```