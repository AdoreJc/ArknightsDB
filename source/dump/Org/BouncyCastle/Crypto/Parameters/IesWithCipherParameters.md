# IesWithCipherParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Fields

- `Int32 cipherKeySize`


## Properties

- `Int32 CipherKeySize`


## Methods

- `Int32 get_CipherKeySize()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class IesWithCipherParameters : IesParameters
{
	private Int32 cipherKeySize; // 0x24

	public Int32 CipherKeySize { get; }

	// RVA: 0x6519624 VA: 0x7598b31624
	public Void .ctor(Byte[] derivation, Byte[] encoding, Int32 macKeySize, Int32 cipherKeySize) { }
	// RVA: 0x6519648 VA: 0x7598b31648
	public Int32 get_CipherKeySize() { }
}
```