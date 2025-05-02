# ISO9797Alg3Mac

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Fields

- `Int32 bufOff`

- `IBlockCipher cipher`

- `IBlockCipherPadding padding`

- `Int32 macSize`

- `KeyParameter lastKey2`

- `KeyParameter lastKey3`


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
public class ISO9797Alg3Mac : IMac
{
	private Byte[] mac; // 0x10
	private Byte[] buf; // 0x18
	private Int32 bufOff; // 0x20
	private IBlockCipher cipher; // 0x28
	private IBlockCipherPadding padding; // 0x30
	private Int32 macSize; // 0x38
	private KeyParameter lastKey2; // 0x40
	private KeyParameter lastKey3; // 0x48

	public String AlgorithmName { get; }

	// RVA: 0x6533234 VA: 0x7598b4b234
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x653358c VA: 0x7598b4b58c
	public Void .ctor(IBlockCipher cipher, IBlockCipherPadding padding) { }
	// RVA: 0x6533650 VA: 0x7598b4b650
	public Void .ctor(IBlockCipher cipher, Int32 macSizeInBits) { }
	// RVA: 0x65332ec VA: 0x7598b4b2ec
	public Void .ctor(IBlockCipher cipher, Int32 macSizeInBits, IBlockCipherPadding padding) { }
	// RVA: 0x6533658 VA: 0x7598b4b658
	public String get_AlgorithmName() { }
	// RVA: 0x6533698 VA: 0x7598b4b698
	public Void Init(ICipherParameters parameters) { }
	// RVA: 0x6533b5c VA: 0x7598b4bb5c
	public Int32 GetMacSize() { }
	// RVA: 0x6533b64 VA: 0x7598b4bb64
	public Void Update(Byte input) { }
	// RVA: 0x6533c7c VA: 0x7598b4bc7c
	public Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x6533f10 VA: 0x7598b4bf10
	public Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6533a9c VA: 0x7598b4ba9c
	public Void Reset() { }
}
```