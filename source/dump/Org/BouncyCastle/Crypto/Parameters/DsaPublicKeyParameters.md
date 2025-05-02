# DsaPublicKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger Y`


## Methods

- `BigInteger get_Y()`

- `Boolean Equals(DsaPublicKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DsaPublicKeyParameters : DsaKeyParameters
{
	private readonly BigInteger y; // 0x20

	public BigInteger Y { get; }

	// RVA: 0x65167d0 VA: 0x7598b2e7d0
	public Void .ctor(BigInteger y, DsaParameters parameters) { }
	// RVA: 0x6516854 VA: 0x7598b2e854
	public BigInteger get_Y() { }
	// RVA: 0x651685c VA: 0x7598b2e85c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x65168f8 VA: 0x7598b2e8f8
	protected Boolean Equals(DsaPublicKeyParameters other) { }
	// RVA: 0x6516954 VA: 0x7598b2e954
	public override Int32 GetHashCode() { }
}
```