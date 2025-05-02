# ElGamalPublicKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger Y`


## Methods

- `BigInteger get_Y()`

- `Boolean Equals(ElGamalPublicKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ElGamalPublicKeyParameters : ElGamalKeyParameters
{
	private readonly BigInteger y; // 0x20

	public BigInteger Y { get; }

	// RVA: 0x65189e8 VA: 0x7598b309e8
	public Void .ctor(BigInteger y, ElGamalParameters parameters) { }
	// RVA: 0x6518a80 VA: 0x7598b30a80
	public BigInteger get_Y() { }
	// RVA: 0x6518a88 VA: 0x7598b30a88
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6518b24 VA: 0x7598b30b24
	protected Boolean Equals(ElGamalPublicKeyParameters other) { }
	// RVA: 0x6518b7c VA: 0x7598b30b7c
	public override Int32 GetHashCode() { }
}
```