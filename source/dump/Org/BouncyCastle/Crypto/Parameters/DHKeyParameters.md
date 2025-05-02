# DHKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `DHParameters Parameters`

- `DerObjectIdentifier AlgorithmOid`


## Methods

- `DHParameters get_Parameters()`

- `DerObjectIdentifier get_AlgorithmOid()`

- `Boolean Equals(DHKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DHKeyParameters : AsymmetricKeyParameter
{
	private readonly DHParameters parameters; // 0x18
	private readonly DerObjectIdentifier algorithmOid; // 0x20

	public DHParameters Parameters { get; }
	public DerObjectIdentifier AlgorithmOid { get; }

	// RVA: 0x6515148 VA: 0x7598b2d148
	protected Void .ctor(Boolean isPrivate, DHParameters parameters) { }
	// RVA: 0x65151c0 VA: 0x7598b2d1c0
	protected Void .ctor(Boolean isPrivate, DHParameters parameters, DerObjectIdentifier algorithmOid) { }
	// RVA: 0x6515208 VA: 0x7598b2d208
	public DHParameters get_Parameters() { }
	// RVA: 0x6515210 VA: 0x7598b2d210
	public DerObjectIdentifier get_AlgorithmOid() { }
	// RVA: 0x6515218 VA: 0x7598b2d218
	public override Boolean Equals(Object obj) { }
	// RVA: 0x65152b4 VA: 0x7598b2d2b4
	protected Boolean Equals(DHKeyParameters other) { }
	// RVA: 0x6515308 VA: 0x7598b2d308
	public override Int32 GetHashCode() { }
}
```