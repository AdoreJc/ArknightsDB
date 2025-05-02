# IesParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Fields

- `Int32 macKeySize`


## Properties

- `Int32 MacKeySize`


## Methods

- `Int32 get_MacKeySize()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class IesParameters : ICipherParameters
{
	private Byte[] derivation; // 0x10
	private Byte[] encoding; // 0x18
	private Int32 macKeySize; // 0x20

	public Int32 MacKeySize { get; }

	// RVA: 0x65195b4 VA: 0x7598b315b4
	public Void .ctor(Byte[] derivation, Byte[] encoding, Int32 macKeySize) { }
	// RVA: 0x651960c VA: 0x7598b3160c
	public Byte[] GetDerivationV() { }
	// RVA: 0x6519614 VA: 0x7598b31614
	public Byte[] GetEncodingV() { }
	// RVA: 0x651961c VA: 0x7598b3161c
	public Int32 get_MacKeySize() { }
}
```