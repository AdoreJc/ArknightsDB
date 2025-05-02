# ISO7816d4Padding

**Namespace:** `Org.BouncyCastle.Crypto.Paddings`


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
public class ISO7816d4Padding : IBlockCipherPadding
{

	public String PaddingName { get; }

	// RVA: 0x651af04 VA: 0x7598b32f04
	public Void Init(SecureRandom random) { }
	// RVA: 0x651af08 VA: 0x7598b32f08
	public String get_PaddingName() { }
	// RVA: 0x651af48 VA: 0x7598b32f48
	public Int32 AddPadding(Byte[] input, Int32 inOff) { }
	// RVA: 0x651afac VA: 0x7598b32fac
	public Int32 PadCount(Byte[] input) { }
	// RVA: 0x651b05c VA: 0x7598b3305c
	public Void .ctor() { }
}
```