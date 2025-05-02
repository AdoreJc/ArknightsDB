# AsymmetricCipherKeyPair

**Namespace:** `Org.BouncyCastle.Crypto`


## Properties

- `AsymmetricKeyParameter Public`

- `AsymmetricKeyParameter Private`


## Methods

- `AsymmetricKeyParameter get_Public()`

- `AsymmetricKeyParameter get_Private()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto
public class AsymmetricCipherKeyPair
{
	private readonly AsymmetricKeyParameter publicParameter; // 0x10
	private readonly AsymmetricKeyParameter privateParameter; // 0x18

	public AsymmetricKeyParameter Public { get; }
	public AsymmetricKeyParameter Private { get; }

	// RVA: 0x64d2ac4 VA: 0x7598aeaac4
	public Void .ctor(AsymmetricKeyParameter publicParameter, AsymmetricKeyParameter privateParameter) { }
	// RVA: 0x64d2bb8 VA: 0x7598aeabb8
	public AsymmetricKeyParameter get_Public() { }
	// RVA: 0x64d2bc0 VA: 0x7598aeabc0
	public AsymmetricKeyParameter get_Private() { }
}
```