# ElGamalKeyGenerationParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `ElGamalParameters Parameters`


## Methods

- `ElGamalParameters get_Parameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ElGamalKeyGenerationParameters : KeyGenerationParameters
{
	private readonly ElGamalParameters parameters; // 0x20

	public ElGamalParameters Parameters { get; }

	// RVA: 0x65183d0 VA: 0x7598b303d0
	public Void .ctor(SecureRandom random, ElGamalParameters parameters) { }
	// RVA: 0x651844c VA: 0x7598b3044c
	public ElGamalParameters get_Parameters() { }
	// RVA: 0x6518418 VA: 0x7598b30418
	internal static Int32 GetStrength(ElGamalParameters parameters) { }
}
```