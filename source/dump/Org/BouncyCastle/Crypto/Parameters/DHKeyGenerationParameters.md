# DHKeyGenerationParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `DHParameters Parameters`


## Methods

- `DHParameters get_Parameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DHKeyGenerationParameters : KeyGenerationParameters
{
	private readonly DHParameters parameters; // 0x20

	public DHParameters Parameters { get; }

	// RVA: 0x65150c4 VA: 0x7598b2d0c4
	public Void .ctor(SecureRandom random, DHParameters parameters) { }
	// RVA: 0x6515140 VA: 0x7598b2d140
	public DHParameters get_Parameters() { }
	// RVA: 0x651510c VA: 0x7598b2d10c
	internal static Int32 GetStrength(DHParameters parameters) { }
}
```