# CfbBlockCipherMac

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Fields

- `Int32 bufOff`

- `MacCFBBlockCipher cipher`

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
public class CfbBlockCipherMac : IMac
{
	private Byte[] mac; // 0x10
	private Byte[] Buffer; // 0x18
	private Int32 bufOff; // 0x20
	private MacCFBBlockCipher cipher; // 0x28
	private IBlockCipherPadding padding; // 0x30
	private Int32 macSize; // 0x38

	public String AlgorithmName { get; }

	// RVA: 0x652ff40 VA: 0x7598b47f40
	public Void .ctor(IBlockCipher cipher) { }
	// RVA: 0x6530200 VA: 0x7598b48200
	public Void .ctor(IBlockCipher cipher, IBlockCipherPadding padding) { }
	// RVA: 0x65302dc VA: 0x7598b482dc
	public Void .ctor(IBlockCipher cipher, Int32 cfbBitSize, Int32 macSizeInBits) { }
	// RVA: 0x6530010 VA: 0x7598b48010
	public Void .ctor(IBlockCipher cipher, Int32 cfbBitSize, Int32 macSizeInBits, IBlockCipherPadding padding) { }
	// RVA: 0x65302e4 VA: 0x7598b482e4
	public String get_AlgorithmName() { }
	// RVA: 0x6530300 VA: 0x7598b48300
	public Void Init(ICipherParameters parameters) { }
	// RVA: 0x6530374 VA: 0x7598b48374
	public Int32 GetMacSize() { }
	// RVA: 0x653037c VA: 0x7598b4837c
	public Void Update(Byte input) { }
	// RVA: 0x653040c VA: 0x7598b4840c
	public Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x6530558 VA: 0x7598b48558
	public Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6530338 VA: 0x7598b48338
	public Void Reset() { }
}
```