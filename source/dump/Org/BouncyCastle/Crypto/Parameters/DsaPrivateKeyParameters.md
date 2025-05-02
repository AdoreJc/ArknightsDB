# DsaPrivateKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `BigInteger X`


## Methods

- `BigInteger get_X()`

- `Boolean Equals(DsaPrivateKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DsaPrivateKeyParameters : DsaKeyParameters
{
	private readonly BigInteger x; // 0x20

	public BigInteger X { get; }

	// RVA: 0x6516608 VA: 0x7598b2e608
	public Void .ctor(BigInteger x, DsaParameters parameters) { }
	// RVA: 0x651668c VA: 0x7598b2e68c
	public BigInteger get_X() { }
	// RVA: 0x6516694 VA: 0x7598b2e694
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6516730 VA: 0x7598b2e730
	protected Boolean Equals(DsaPrivateKeyParameters other) { }
	// RVA: 0x651678c VA: 0x7598b2e78c
	public override Int32 GetHashCode() { }
}
```