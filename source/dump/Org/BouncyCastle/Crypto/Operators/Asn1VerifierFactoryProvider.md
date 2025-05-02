# Asn1VerifierFactoryProvider

**Namespace:** `Org.BouncyCastle.Crypto.Operators`


## Properties

- `IEnumerable SignatureAlgNames`


## Methods

- `IVerifierFactory CreateVerifierFactory(Object)`

- `IEnumerable get_SignatureAlgNames()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Operators
public class Asn1VerifierFactoryProvider : IVerifierFactoryProvider
{
	private readonly AsymmetricKeyParameter publicKey; // 0x10

	public IEnumerable SignatureAlgNames { get; }

	// RVA: 0x6520238 VA: 0x7598b38238
	public Void .ctor(AsymmetricKeyParameter publicKey) { }
	// RVA: 0x6520268 VA: 0x7598b38268
	public IVerifierFactory CreateVerifierFactory(Object algorithmDetails) { }
	// RVA: 0x652032c VA: 0x7598b3832c
	public IEnumerable get_SignatureAlgNames() { }
}
```