# Asn1VerifierFactory

**Namespace:** `Org.BouncyCastle.Crypto.Operators`


## Properties

- `Object AlgorithmDetails`


## Methods

- `Object get_AlgorithmDetails()`

- `IStreamCalculator CreateCalculator()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Operators
public class Asn1VerifierFactory : IVerifierFactory
{
	private readonly AlgorithmIdentifier algID; // 0x10
	private readonly AsymmetricKeyParameter publicKey; // 0x18

	public Object AlgorithmDetails { get; }

	// RVA: 0x651fd14 VA: 0x7598b37d14
	public Void .ctor(String algorithm, AsymmetricKeyParameter publicKey) { }
	// RVA: 0x651fdb4 VA: 0x7598b37db4
	public Void .ctor(AlgorithmIdentifier algorithm, AsymmetricKeyParameter publicKey) { }
	// RVA: 0x651fdf8 VA: 0x7598b37df8
	public Object get_AlgorithmDetails() { }
	// RVA: 0x651fe00 VA: 0x7598b37e00
	public IStreamCalculator CreateCalculator() { }
}
```