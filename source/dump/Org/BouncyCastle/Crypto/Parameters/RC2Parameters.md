# RC2Parameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `Int32 EffectiveKeyBits`


## Methods

- `Int32 get_EffectiveKeyBits()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class RC2Parameters : KeyParameter
{
	private readonly Int32 bits; // 0x18

	public Int32 EffectiveKeyBits { get; }

	// RVA: 0x651a0fc VA: 0x7598b320fc
	public Void .ctor(Byte[] key) { }
	// RVA: 0x651a15c VA: 0x7598b3215c
	public Void .ctor(Byte[] key, Int32 keyOff, Int32 keyLen) { }
	// RVA: 0x651a138 VA: 0x7598b32138
	public Void .ctor(Byte[] key, Int32 bits) { }
	// RVA: 0x651a18c VA: 0x7598b3218c
	public Void .ctor(Byte[] key, Int32 keyOff, Int32 keyLen, Int32 bits) { }
	// RVA: 0x651a1b0 VA: 0x7598b321b0
	public Int32 get_EffectiveKeyBits() { }
}
```