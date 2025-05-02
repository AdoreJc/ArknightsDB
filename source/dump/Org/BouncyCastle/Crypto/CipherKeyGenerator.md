# CipherKeyGenerator

**Namespace:** `Org.BouncyCastle.Crypto`


## Fields

- `Boolean uninitialised`

- `Int32 defaultStrength`


## Properties

- `Int32 DefaultStrength`


## Methods

- `Int32 get_DefaultStrength()`

- `Void Init(KeyGenerationParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto
public class CipherKeyGenerator
{
	protected internal SecureRandom random; // 0x10
	protected internal Int32 strength; // 0x18
	private Boolean uninitialised; // 0x1c
	private Int32 defaultStrength; // 0x20

	public Int32 DefaultStrength { get; }

	// RVA: 0x64d6324 VA: 0x7598aee324
	public Void .ctor() { }
	// RVA: 0x64d6334 VA: 0x7598aee334
	internal Void .ctor(Int32 defaultStrength) { }
	// RVA: 0x64d63cc VA: 0x7598aee3cc
	public Int32 get_DefaultStrength() { }
	// RVA: 0x64d63d4 VA: 0x7598aee3d4
	public Void Init(KeyGenerationParameters parameters) { }
	// RVA: 0x64d643c VA: 0x7598aee43c
	protected virtual Void engineInit(KeyGenerationParameters parameters) { }
	// RVA: 0x64d648c VA: 0x7598aee48c
	public Byte[] GenerateKey() { }
	// RVA: 0x64d6688 VA: 0x7598aee688
	protected virtual Byte[] engineGenerateKey() { }
}
```