# ElGamalPrivateKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger X`


## Methods

- `BigInteger get_X()`

- `Boolean Equals(ElGamalPrivateKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ElGamalPrivateKeyParameters : ElGamalKeyParameters
{
	private readonly BigInteger x; // 0x20

	public BigInteger X { get; }

	// RVA: 0x6518814 VA: 0x7598b30814
	public Void .ctor(BigInteger x, ElGamalParameters parameters) { }
	// RVA: 0x65188ac VA: 0x7598b308ac
	public BigInteger get_X() { }
	// RVA: 0x65188b4 VA: 0x7598b308b4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6518950 VA: 0x7598b30950
	protected Boolean Equals(ElGamalPrivateKeyParameters other) { }
	// RVA: 0x65189a8 VA: 0x7598b309a8
	public override Int32 GetHashCode() { }
}
```