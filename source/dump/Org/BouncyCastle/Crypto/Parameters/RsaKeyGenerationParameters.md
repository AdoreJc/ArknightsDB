# RsaKeyGenerationParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger PublicExponent`

- `Int32 Certainty`


## Methods

- `BigInteger get_PublicExponent()`

- `Int32 get_Certainty()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class RsaKeyGenerationParameters : KeyGenerationParameters
{
	private readonly BigInteger publicExponent; // 0x20
	private readonly Int32 certainty; // 0x28

	public BigInteger PublicExponent { get; }
	public Int32 Certainty { get; }

	// RVA: 0x651a2f8 VA: 0x7598b322f8
	public Void .ctor(BigInteger publicExponent, SecureRandom random, Int32 strength, Int32 certainty) { }
	// RVA: 0x651a33c VA: 0x7598b3233c
	public BigInteger get_PublicExponent() { }
	// RVA: 0x651a344 VA: 0x7598b32344
	public Int32 get_Certainty() { }
	// RVA: 0x651a34c VA: 0x7598b3234c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x651a400 VA: 0x7598b32400
	public override Int32 GetHashCode() { }
}
```