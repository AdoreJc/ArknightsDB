# TbcPadding

**Namespace:** `Org.BouncyCastle.Crypto.Paddings`


## Properties

- `String PaddingName`


## Methods

- `String get_PaddingName()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Paddings
public class TbcPadding : IBlockCipherPadding
{

	public String PaddingName { get; }

	// RVA: 0x651be30 VA: 0x7598b33e30
	public String get_PaddingName() { }
	// RVA: 0x651be70 VA: 0x7598b33e70
	public virtual Void Init(SecureRandom random) { }
	// RVA: 0x651be74 VA: 0x7598b33e74
	public virtual Int32 AddPadding(Byte[] input, Int32 inOff) { }
	// RVA: 0x651befc VA: 0x7598b33efc
	public virtual Int32 PadCount(Byte[] input) { }
	// RVA: 0x651bf58 VA: 0x7598b33f58
	public Void .ctor() { }
}
```