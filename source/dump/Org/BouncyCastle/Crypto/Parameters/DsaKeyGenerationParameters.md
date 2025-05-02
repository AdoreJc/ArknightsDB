# DsaKeyGenerationParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `DsaParameters Parameters`


## Methods

- `DsaParameters get_Parameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DsaKeyGenerationParameters : KeyGenerationParameters
{
	private readonly DsaParameters parameters; // 0x20

	public DsaParameters Parameters { get; }

	// RVA: 0x6516178 VA: 0x7598b2e178
	public Void .ctor(SecureRandom random, DsaParameters parameters) { }
	// RVA: 0x65161d0 VA: 0x7598b2e1d0
	public DsaParameters get_Parameters() { }
}
```