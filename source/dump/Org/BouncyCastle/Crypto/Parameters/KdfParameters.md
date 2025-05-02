# KdfParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class KdfParameters : IDerivationParameters
{
	private Byte[] iv; // 0x10
	private Byte[] shared; // 0x18


	// RVA: 0x6519688 VA: 0x7598b31688
	public Void .ctor(Byte[] shared, Byte[] iv) { }
	// RVA: 0x65196cc VA: 0x7598b316cc
	public Byte[] GetSharedSecret() { }
	// RVA: 0x65196d4 VA: 0x7598b316d4
	public Byte[] GetIV() { }
}
```