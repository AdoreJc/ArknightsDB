# CbcBlockCipher

**Namespace:** `Org.BouncyCastle.Crypto.Modes`


## Fields

- `Int32 blockSize`

- `IBlockCipher cipher`

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

- `Void Reset()`

- `Int32 EncryptBlock(Byte[], Int32, Byte[], Int32)`

- `Int32 DecryptBlock(Byte[], Int32, Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Modes
public class CbcBlockCipher : IBlockCipher
{
	private Byte[] IV; // 0x10
	private Byte[] cbcV; // 0x18
	private Byte[] cbcNextV; // 0x20
	private Int32 blockSize; // 0x28
	private IBlockCipher cipher; // 0x30
	private Boolean encrypting; // 0x38

	public String AlgorithmName { get; }
	public Boolean IsPartialBlockOkay { get; }

	// RVA: 0x6520378 VA: 0x7598b38378
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x65204a4 VA: 0x7598b384a4
	public IBlockCipher GetUnderlyingCipher() { }
	// RVA: 0x65204ac VA: 0x7598b384ac
	public Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x6520780 VA: 0x7598b38780
	public String get_AlgorithmName() { }
	// RVA: 0x6520840 VA: 0x7598b38840
	public Boolean get_IsPartialBlockOkay() { }
	// RVA: 0x6520848 VA: 0x7598b38848
	public Int32 GetBlockSize() { }
	// RVA: 0x65208ec VA: 0x7598b388ec
	public Int32 ProcessBlock(Byte[] input, Int32 inOff, Byte[] output, Int32 outOff) { }
	// RVA: 0x65206a4 VA: 0x7598b386a4
	public Void Reset() { }
	// RVA: 0x6520ae8 VA: 0x7598b38ae8
	private Int32 EncryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x65208fc VA: 0x7598b388fc
	private Int32 DecryptBlock(Byte[] input, Int32 inOff, Byte[] outBytes, Int32 outOff) { }
}
```