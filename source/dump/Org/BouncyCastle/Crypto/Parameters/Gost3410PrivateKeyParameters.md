# Gost3410PrivateKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger X`


## Methods

- `BigInteger get_X()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class Gost3410PrivateKeyParameters : Gost3410KeyParameters
{
	private readonly BigInteger x; // 0x28

	public BigInteger X { get; }

	// RVA: 0x651908c VA: 0x7598b3108c
	public Void .ctor(BigInteger x, Gost3410Parameters parameters) { }
	// RVA: 0x6519184 VA: 0x7598b31184
	public Void .ctor(BigInteger x, DerObjectIdentifier publicKeyParamSet) { }
	// RVA: 0x6519258 VA: 0x7598b31258
	public BigInteger get_X() { }
}
```