# Pkcs7Padding

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
public class Pkcs7Padding : IBlockCipherPadding
{

	public String PaddingName { get; }

	// RVA: 0x651bce0 VA: 0x7598b33ce0
	public Void Init(SecureRandom random) { }
	// RVA: 0x651bce4 VA: 0x7598b33ce4
	public String get_PaddingName() { }
	// RVA: 0x651bd24 VA: 0x7598b33d24
	public Int32 AddPadding(Byte[] input, Int32 inOff) { }
	// RVA: 0x651bd70 VA: 0x7598b33d70
	public Int32 PadCount(Byte[] input) { }
	// RVA: 0x651b1f0 VA: 0x7598b331f0
	public Void .ctor() { }
}
```