# DsaKeyPairGenerator

**Namespace:** `Org.BouncyCastle.Crypto.Generators`


## Fields

- `DsaKeyGenerationParameters param`


## Methods

- `Void Init(KeyGenerationParameters)`

- `AsymmetricCipherKeyPair GenerateKeyPair()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Generators
public class DsaKeyPairGenerator : IAsymmetricCipherKeyPairGenerator
{
	private static readonly BigInteger One; // 0x0
	private DsaKeyGenerationParameters param; // 0x10


	// RVA: 0x6537014 VA: 0x7598b4f014
	public Void Init(KeyGenerationParameters parameters) { }
	// RVA: 0x6537108 VA: 0x7598b4f108
	public AsymmetricCipherKeyPair GenerateKeyPair() { }
	// RVA: 0x6537250 VA: 0x7598b4f250
	private static BigInteger GeneratePrivateKey(BigInteger q, SecureRandom random) { }
	// RVA: 0x6537340 VA: 0x7598b4f340
	private static BigInteger CalculatePublicKey(BigInteger p, BigInteger g, BigInteger x) { }
	// RVA: 0x6537364 VA: 0x7598b4f364
	public Void .ctor() { }
	// RVA: 0x653736c VA: 0x7598b4f36c
	private static Void .cctor() { }
}
```