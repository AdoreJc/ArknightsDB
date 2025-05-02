# Asn1SignatureFactory

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
public class Asn1SignatureFactory : ISignatureFactory
{
	private readonly AlgorithmIdentifier algID; // 0x10
	private readonly String algorithm; // 0x18
	private readonly AsymmetricKeyParameter privateKey; // 0x20
	private readonly SecureRandom random; // 0x28

	public Object AlgorithmDetails { get; }
	public static IEnumerable SignatureAlgNames { get; }

	// RVA: 0x651f808 VA: 0x7598b37808
	public Void .ctor(String algorithm, AsymmetricKeyParameter privateKey) { }
	// RVA: 0x651f810 VA: 0x7598b37810
	public Void .ctor(String algorithm, AsymmetricKeyParameter privateKey, SecureRandom random) { }
	// RVA: 0x651f8dc VA: 0x7598b378dc
	public Object get_AlgorithmDetails() { }
	// RVA: 0x651f8e4 VA: 0x7598b378e4
	public IStreamCalculator CreateCalculator() { }
	// RVA: 0x651fb30 VA: 0x7598b37b30
	public static IEnumerable get_SignatureAlgNames() { }
}
```