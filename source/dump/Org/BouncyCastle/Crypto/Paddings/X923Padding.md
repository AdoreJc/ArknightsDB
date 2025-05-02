# X923Padding

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
public class X923Padding : IBlockCipherPadding
{
	private SecureRandom random; // 0x10

	public String PaddingName { get; }

	// RVA: 0x651bf60 VA: 0x7598b33f60
	public Void Init(SecureRandom random) { }
	// RVA: 0x651bf68 VA: 0x7598b33f68
	public String get_PaddingName() { }
	// RVA: 0x651bfa8 VA: 0x7598b33fa8
	public Int32 AddPadding(Byte[] input, Int32 inOff) { }
	// RVA: 0x651c074 VA: 0x7598b34074
	public Int32 PadCount(Byte[] input) { }
	// RVA: 0x651c0f8 VA: 0x7598b340f8
	public Void .ctor() { }
}
```