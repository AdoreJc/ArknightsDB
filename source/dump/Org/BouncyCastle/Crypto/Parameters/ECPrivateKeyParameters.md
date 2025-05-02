# ECPrivateKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger D`


## Methods

- `BigInteger get_D()`

- `Boolean Equals(ECPrivateKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ECPrivateKeyParameters : ECKeyParameters
{
	private readonly BigInteger d; // 0x30

	public BigInteger D { get; }

	// RVA: 0x6517b20 VA: 0x7598b2fb20
	public Void .ctor(BigInteger d, ECDomainParameters parameters) { }
	// RVA: 0x6517c5c VA: 0x7598b2fc5c
	public Void .ctor(BigInteger d, DerObjectIdentifier publicKeyParamSet) { }
	// RVA: 0x6517b80 VA: 0x7598b2fb80
	public Void .ctor(String algorithm, BigInteger d, ECDomainParameters parameters) { }
	// RVA: 0x6517d40 VA: 0x7598b2fd40
	public Void .ctor(String algorithm, BigInteger d, DerObjectIdentifier publicKeyParamSet) { }
	// RVA: 0x6517e1c VA: 0x7598b2fe1c
	public BigInteger get_D() { }
	// RVA: 0x6517e24 VA: 0x7598b2fe24
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6517ec0 VA: 0x7598b2fec0
	protected Boolean Equals(ECPrivateKeyParameters other) { }
	// RVA: 0x6517f18 VA: 0x7598b2ff18
	public override Int32 GetHashCode() { }
}
```