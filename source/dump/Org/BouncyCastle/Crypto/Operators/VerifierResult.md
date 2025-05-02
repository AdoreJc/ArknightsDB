# VerifierResult

**Namespace:** `Org.BouncyCastle.Crypto.Operators`


## Methods

- `Boolean IsVerified(Byte[])`

- `Boolean IsVerified(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Operators
internal class VerifierResult : IVerifier
{
	private readonly ISigner sig; // 0x10


	// RVA: 0x6520058 VA: 0x7598b38058
	internal Void .ctor(ISigner sig) { }
	// RVA: 0x6520088 VA: 0x7598b38088
	public Boolean IsVerified(Byte[] signature) { }
	// RVA: 0x6520134 VA: 0x7598b38134
	public Boolean IsVerified(Byte[] signature, Int32 off, Int32 length) { }
}
```