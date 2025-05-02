# KeyGenerationParameters

**Namespace:** `Org.BouncyCastle.Crypto`


## Fields

- `SecureRandom random`

- `Int32 strength`


## Properties

- `SecureRandom Random`

- `Int32 Strength`


## Methods

- `SecureRandom get_Random()`

- `Int32 get_Strength()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto
public class KeyGenerationParameters
{
	private SecureRandom random; // 0x10
	private Int32 strength; // 0x18

	public SecureRandom Random { get; }
	public Int32 Strength { get; }

	// RVA: 0x64d65a8 VA: 0x7598aee5a8
	public Void .ctor(SecureRandom random, Int32 strength) { }
	// RVA: 0x64d6830 VA: 0x7598aee830
	public SecureRandom get_Random() { }
	// RVA: 0x64d6838 VA: 0x7598aee838
	public Int32 get_Strength() { }
}
```