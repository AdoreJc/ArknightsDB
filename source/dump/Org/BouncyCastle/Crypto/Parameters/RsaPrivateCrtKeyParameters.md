# RsaPrivateCrtKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger PublicExponent`

- `BigInteger P`

- `BigInteger Q`

- `BigInteger DP`

- `BigInteger DQ`

- `BigInteger QInv`


## Methods

- `BigInteger get_PublicExponent()`

- `BigInteger get_P()`

- `BigInteger get_Q()`

- `BigInteger get_DP()`

- `BigInteger get_DQ()`

- `BigInteger get_QInv()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class RsaPrivateCrtKeyParameters : RsaKeyParameters
{
	private readonly BigInteger e; // 0x28
	private readonly BigInteger p; // 0x30
	private readonly BigInteger q; // 0x38
	private readonly BigInteger dP; // 0x40
	private readonly BigInteger dQ; // 0x48
	private readonly BigInteger qInv; // 0x50

	public BigInteger PublicExponent { get; }
	public BigInteger P { get; }
	public BigInteger Q { get; }
	public BigInteger DP { get; }
	public BigInteger DQ { get; }
	public BigInteger QInv { get; }

	// RVA: 0x651a74c VA: 0x7598b3274c
	public Void .ctor(BigInteger modulus, BigInteger publicExponent, BigInteger privateExponent, BigInteger p, BigInteger q, BigInteger dP, BigInteger dQ, BigInteger qInv) { }
	// RVA: 0x651aa48 VA: 0x7598b32a48
	public BigInteger get_PublicExponent() { }
	// RVA: 0x651aa50 VA: 0x7598b32a50
	public BigInteger get_P() { }
	// RVA: 0x651aa58 VA: 0x7598b32a58
	public BigInteger get_Q() { }
	// RVA: 0x651aa60 VA: 0x7598b32a60
	public BigInteger get_DP() { }
	// RVA: 0x651aa68 VA: 0x7598b32a68
	public BigInteger get_DQ() { }
	// RVA: 0x651aa70 VA: 0x7598b32a70
	public BigInteger get_QInv() { }
	// RVA: 0x651aa78 VA: 0x7598b32a78
	public override Boolean Equals(Object obj) { }
	// RVA: 0x651abf0 VA: 0x7598b32bf0
	public override Int32 GetHashCode() { }
	// RVA: 0x651a978 VA: 0x7598b32978
	private static Void ValidateValue(BigInteger x, String name, String desc) { }
}
```