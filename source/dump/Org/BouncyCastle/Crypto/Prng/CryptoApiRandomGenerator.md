# CryptoApiRandomGenerator

**Namespace:** `Org.BouncyCastle.Crypto.Prng`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Prng
public class CryptoApiRandomGenerator : IRandomGenerator
{
	private readonly RandomNumberGenerator rndProv; // 0x10


	// RVA: 0x6513bb4 VA: 0x7598b2bbb4
	public Void .ctor() { }
	// RVA: 0x6513c28 VA: 0x7598b2bc28
	public Void .ctor(RandomNumberGenerator rng) { }
	// RVA: 0x6513c58 VA: 0x7598b2bc58
	public virtual Void AddSeedMaterial(Byte[] seed) { }
	// RVA: 0x6513c5c VA: 0x7598b2bc5c
	public virtual Void AddSeedMaterial(Int64 seed) { }
	// RVA: 0x6513c60 VA: 0x7598b2bc60
	public virtual Void NextBytes(Byte[] bytes) { }
	// RVA: 0x6513c80 VA: 0x7598b2bc80
	public virtual Void NextBytes(Byte[] bytes, Int32 start, Int32 len) { }
}
```