# ECKeyPairGenerator

**Namespace:** `Org.BouncyCastle.Crypto.Generators`


## Fields

- `ECDomainParameters parameters`

- `DerObjectIdentifier publicKeyParamSet`

- `SecureRandom random`


## Methods

- `Void Init(KeyGenerationParameters)`

- `AsymmetricCipherKeyPair GenerateKeyPair()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Generators
public class ECKeyPairGenerator : IAsymmetricCipherKeyPairGenerator
{
	private readonly String algorithm; // 0x10
	private ECDomainParameters parameters; // 0x18
	private DerObjectIdentifier publicKeyParamSet; // 0x20
	private SecureRandom random; // 0x28


	// RVA: 0x65373ec VA: 0x7598b4f3ec
	public Void .ctor() { }
	// RVA: 0x6537434 VA: 0x7598b4f434
	public Void .ctor(String algorithm) { }
	// RVA: 0x65374fc VA: 0x7598b4f4fc
	public Void Init(KeyGenerationParameters parameters) { }
	// RVA: 0x6537874 VA: 0x7598b4f874
	public AsymmetricCipherKeyPair GenerateKeyPair() { }
	// RVA: 0x6537b88 VA: 0x7598b4fb88
	protected virtual ECMultiplier CreateBasePointMultiplier() { }
	// RVA: 0x6537800 VA: 0x7598b4f800
	internal static X9ECParameters FindECCurveByOid(DerObjectIdentifier oid) { }
	// RVA: 0x6537be4 VA: 0x7598b4fbe4
	internal static ECPublicKeyParameters GetCorrespondingPublicKey(ECPrivateKeyParameters privKey) { }
}
```