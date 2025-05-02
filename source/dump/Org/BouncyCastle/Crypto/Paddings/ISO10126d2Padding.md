# ISO10126d2Padding

**Namespace:** `Org.BouncyCastle.Crypto.Paddings`


## Fields

- `SecureRandom random`


## Properties

- `String PaddingName`


## Methods

- `Void Init(SecureRandom)`

- `String get_PaddingName()`

- `Int32 AddPadding(Byte[], Int32)`

- `Int32 PadCount(Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Paddings
public class ISO10126d2Padding : IBlockCipherPadding
{
	private SecureRandom random; // 0x10

	public String PaddingName { get; }

	// RVA: 0x651ad10 VA: 0x7598b32d10
	public Void Init(SecureRandom random) { }
	// RVA: 0x651ad84 VA: 0x7598b32d84
	public String get_PaddingName() { }
	// RVA: 0x651adc4 VA: 0x7598b32dc4
	public Int32 AddPadding(Byte[] input, Int32 inOff) { }
	// RVA: 0x651ae78 VA: 0x7598b32e78
	public Int32 PadCount(Byte[] input) { }
	// RVA: 0x651aefc VA: 0x7598b32efc
	public Void .ctor() { }
}
```