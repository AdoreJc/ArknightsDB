# CbcBlockCipherMac

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Fields

- `Int32 bufOff`

- `IBlockCipher cipher`

- `IBlockCipherPadding padding`

- `Int32 macSize`


## Properties

- `String AlgorithmName`


## Methods

- `String get_AlgorithmName()`

- `Void Init(ICipherParameters)`

- `Int32 GetMacSize()`

- `Void Update(Byte)`

- `Void BlockUpdate(Byte[], Int32, Int32)`

- `Int32 DoFinal(Byte[], Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Macs
public class CbcBlockCipherMac : IMac
{
	private Byte[] buf; // 0x10
	private Int32 bufOff; // 0x18
	private IBlockCipher cipher; // 0x20
	private IBlockCipherPadding padding; // 0x28
	private Int32 macSize; // 0x30

	public String AlgorithmName { get; }

	// RVA: 0x652db5c VA: 0x7598b45b5c
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x652dddc VA: 0x7598b45ddc
	public Void .ctor(IBlockCipher cipher, IBlockCipherPadding padding) { }
	// RVA: 0x652290c VA: 0x7598b3a90c
	public Void .ctor(IBlockCipher cipher, Int32 macSizeInBits) { }
	// RVA: 0x652dc28 VA: 0x7598b45c28
	public Void .ctor(IBlockCipher cipher, Int32 macSizeInBits, IBlockCipherPadding padding) { }
	// RVA: 0x652deb4 VA: 0x7598b45eb4
	public String get_AlgorithmName() { }
	// RVA: 0x652df54 VA: 0x7598b45f54
	public Void Init(ICipherParameters parameters) { }
	// RVA: 0x652e0cc VA: 0x7598b460cc
	public Int32 GetMacSize() { }
	// RVA: 0x652e0d4 VA: 0x7598b460d4
	public Void Update(Byte input) { }
	// RVA: 0x652e1e8 VA: 0x7598b461e8
	public Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x652e474 VA: 0x7598b46474
	public Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x652e00c VA: 0x7598b4600c
	public Void Reset() { }
}
```