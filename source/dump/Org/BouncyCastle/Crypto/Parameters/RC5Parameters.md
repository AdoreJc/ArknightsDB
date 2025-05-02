# RC5Parameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `Int32 Rounds`


## Methods

- `Int32 get_Rounds()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class RC5Parameters : KeyParameter
{
	private readonly Int32 rounds; // 0x18

	public Int32 Rounds { get; }

	// RVA: 0x651a1b8 VA: 0x7598b321b8
	public Void .ctor(Byte[] key, Int32 rounds) { }
	// RVA: 0x651a240 VA: 0x7598b32240
	public Int32 get_Rounds() { }
}
```