# DHPublicKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger Y`


## Methods

- `BigInteger get_Y()`

- `Boolean Equals(DHPublicKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DHPublicKeyParameters : DHKeyParameters
{
	private readonly BigInteger y; // 0x28

	public BigInteger Y { get; }

	// RVA: 0x6515c7c VA: 0x7598b2dc7c
	public Void .ctor(BigInteger y, DHParameters parameters) { }
	// RVA: 0x6515cfc VA: 0x7598b2dcfc
	public Void .ctor(BigInteger y, DHParameters parameters, DerObjectIdentifier algorithmOid) { }
	// RVA: 0x6515d7c VA: 0x7598b2dd7c
	public BigInteger get_Y() { }
	// RVA: 0x6515d84 VA: 0x7598b2dd84
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6515e20 VA: 0x7598b2de20
	protected Boolean Equals(DHPublicKeyParameters other) { }
	// RVA: 0x6515e78 VA: 0x7598b2de78
	public override Int32 GetHashCode() { }
}
```