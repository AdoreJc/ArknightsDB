# DHPrivateKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger X`


## Methods

- `BigInteger get_X()`

- `Boolean Equals(DHPrivateKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DHPrivateKeyParameters : DHKeyParameters
{
	private readonly BigInteger x; // 0x28

	public BigInteger X { get; }

	// RVA: 0x6515ae0 VA: 0x7598b2dae0
	public Void .ctor(BigInteger x, DHParameters parameters) { }
	// RVA: 0x6515b10 VA: 0x7598b2db10
	public Void .ctor(BigInteger x, DHParameters parameters, DerObjectIdentifier algorithmOid) { }
	// RVA: 0x6515b40 VA: 0x7598b2db40
	public BigInteger get_X() { }
	// RVA: 0x6515b48 VA: 0x7598b2db48
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6515be4 VA: 0x7598b2dbe4
	protected Boolean Equals(DHPrivateKeyParameters other) { }
	// RVA: 0x6515c3c VA: 0x7598b2dc3c
	public override Int32 GetHashCode() { }
}
```