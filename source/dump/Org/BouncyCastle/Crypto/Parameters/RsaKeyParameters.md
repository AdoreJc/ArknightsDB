# RsaKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger Modulus`

- `BigInteger Exponent`


## Methods

- `BigInteger get_Modulus()`

- `BigInteger get_Exponent()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class RsaKeyParameters : AsymmetricKeyParameter
{
	private readonly BigInteger modulus; // 0x18
	private readonly BigInteger exponent; // 0x20

	public BigInteger Modulus { get; }
	public BigInteger Exponent { get; }

	// RVA: 0x651a450 VA: 0x7598b32450
	public Void .ctor(Boolean isPrivate, BigInteger modulus, BigInteger exponent) { }
	// RVA: 0x651a5a8 VA: 0x7598b325a8
	public BigInteger get_Modulus() { }
	// RVA: 0x651a5b0 VA: 0x7598b325b0
	public BigInteger get_Exponent() { }
	// RVA: 0x651a5b8 VA: 0x7598b325b8
	public override Boolean Equals(Object obj) { }
	// RVA: 0x651a698 VA: 0x7598b32698
	public override Int32 GetHashCode() { }
}
```