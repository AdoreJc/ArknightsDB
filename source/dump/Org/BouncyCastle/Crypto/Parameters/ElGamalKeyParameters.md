# ElGamalKeyParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `ElGamalParameters Parameters`


## Methods

- `ElGamalParameters get_Parameters()`

- `Boolean Equals(ElGamalKeyParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class ElGamalKeyParameters : AsymmetricKeyParameter
{
	private readonly ElGamalParameters parameters; // 0x18

	public ElGamalParameters Parameters { get; }

	// RVA: 0x6518454 VA: 0x7598b30454
	protected Void .ctor(Boolean isPrivate, ElGamalParameters parameters) { }
	// RVA: 0x6518488 VA: 0x7598b30488
	public ElGamalParameters get_Parameters() { }
	// RVA: 0x6518490 VA: 0x7598b30490
	public override Boolean Equals(Object obj) { }
	// RVA: 0x651852c VA: 0x7598b3052c
	protected Boolean Equals(ElGamalKeyParameters other) { }
	// RVA: 0x6518580 VA: 0x7598b30580
	public override Int32 GetHashCode() { }
}
```