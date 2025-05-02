# RSAPKCS1SignatureDeformatter

**Namespace:** `System.Security.Cryptography`


## Fields

- `RSA rsa`

- `String hashName`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class RSAPKCS1SignatureDeformatter : AsymmetricSignatureDeformatter
{
	private RSA rsa; // 0x10
	private String hashName; // 0x18


	// RVA: 0x5f74384 VA: 0x759858c384
	public Void .ctor() { }
	// RVA: 0x5f7438c VA: 0x759858c38c
	public Void .ctor(AsymmetricAlgorithm key) { }
	// RVA: 0x5f743c0 VA: 0x759858c3c0
	public override Void SetHashAlgorithm(String strName) { }
	// RVA: 0x5f74420 VA: 0x759858c420
	public override Void SetKey(AsymmetricAlgorithm key) { }
	// RVA: 0x5f74514 VA: 0x759858c514
	public override Boolean VerifySignature(Byte[] rgbHash, Byte[] rgbSignature) { }
}
```