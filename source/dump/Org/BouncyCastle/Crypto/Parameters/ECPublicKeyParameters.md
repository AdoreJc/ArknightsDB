# ECPublicKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `ECPoint Q`


## Methods

- `ECPoint get_Q()`

- `Boolean Equals(ECPublicKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ECPublicKeyParameters : ECKeyParameters
{
	private readonly ECPoint q; // 0x30

	public ECPoint Q { get; }

	// RVA: 0x6517f58 VA: 0x7598b2ff58
	public Void .ctor(ECPoint q, ECDomainParameters parameters) { }
	// RVA: 0x65180a8 VA: 0x7598b300a8
	public Void .ctor(ECPoint q, DerObjectIdentifier publicKeyParamSet) { }
	// RVA: 0x6517fb8 VA: 0x7598b2ffb8
	public Void .ctor(String algorithm, ECPoint q, ECDomainParameters parameters) { }
	// RVA: 0x65181a0 VA: 0x7598b301a0
	public Void .ctor(String algorithm, ECPoint q, DerObjectIdentifier publicKeyParamSet) { }
	// RVA: 0x6518290 VA: 0x7598b30290
	public ECPoint get_Q() { }
	// RVA: 0x6518298 VA: 0x7598b30298
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6518334 VA: 0x7598b30334
	protected Boolean Equals(ECPublicKeyParameters other) { }
	// RVA: 0x6518390 VA: 0x7598b30390
	public override Int32 GetHashCode() { }
}
```