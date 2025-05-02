# ECKeyGenerationParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `ECDomainParameters DomainParameters`

- `DerObjectIdentifier PublicKeyParamSet`


## Methods

- `ECDomainParameters get_DomainParameters()`

- `DerObjectIdentifier get_PublicKeyParamSet()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ECKeyGenerationParameters : KeyGenerationParameters
{
	private readonly ECDomainParameters domainParams; // 0x20
	private readonly DerObjectIdentifier publicKeyParamSet; // 0x28

	public ECDomainParameters DomainParameters { get; }
	public DerObjectIdentifier PublicKeyParamSet { get; }

	// RVA: 0x651709c VA: 0x7598b2f09c
	public Void .ctor(ECDomainParameters domainParameters, SecureRandom random) { }
	// RVA: 0x65170f4 VA: 0x7598b2f0f4
	public Void .ctor(DerObjectIdentifier publicKeyParamSet, SecureRandom random) { }
	// RVA: 0x65172fc VA: 0x7598b2f2fc
	public ECDomainParameters get_DomainParameters() { }
	// RVA: 0x6517304 VA: 0x7598b2f304
	public DerObjectIdentifier get_PublicKeyParamSet() { }
}
```