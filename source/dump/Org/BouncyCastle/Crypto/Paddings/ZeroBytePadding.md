# ZeroBytePadding

**Namespace:** `Org.BouncyCastle.Crypto.Paddings`


## Properties

- `String PaddingName`


## Methods

- `String get_PaddingName()`

- `Void Init(SecureRandom)`

- `Int32 AddPadding(Byte[], Int32)`

- `Int32 PadCount(Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Paddings
public class ZeroBytePadding : IBlockCipherPadding
{

	public String PaddingName { get; }

	// RVA: 0x651c100 VA: 0x7598b34100
	public String get_PaddingName() { }
	// RVA: 0x651c140 VA: 0x7598b34140
	public Void Init(SecureRandom random) { }
	// RVA: 0x651c144 VA: 0x7598b34144
	public Int32 AddPadding(Byte[] input, Int32 inOff) { }
	// RVA: 0x651c18c VA: 0x7598b3418c
	public Int32 PadCount(Byte[] input) { }
	// RVA: 0x651c1e0 VA: 0x7598b341e0
	public Void .ctor() { }
}
```