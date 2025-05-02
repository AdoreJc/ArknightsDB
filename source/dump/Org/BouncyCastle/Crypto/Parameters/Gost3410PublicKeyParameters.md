# Gost3410PublicKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger Y`


## Methods

- `BigInteger get_Y()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class Gost3410PublicKeyParameters : Gost3410KeyParameters
{
	private readonly BigInteger y; // 0x28

	public BigInteger Y { get; }

	// RVA: 0x6519260 VA: 0x7598b31260
	public Void .ctor(BigInteger y, Gost3410Parameters parameters) { }
	// RVA: 0x6519344 VA: 0x7598b31344
	public Void .ctor(BigInteger y, DerObjectIdentifier publicKeyParamSet) { }
	// RVA: 0x6519404 VA: 0x7598b31404
	public BigInteger get_Y() { }
}
```