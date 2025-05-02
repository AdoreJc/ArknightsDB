# RSAPKCS1SignatureFormatter

**Namespace:** `System.Security.Cryptography`


## Fields

- `RSA rsa`

- `String hash`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class RSAPKCS1SignatureFormatter : AsymmetricSignatureFormatter
{
	private RSA rsa; // 0x10
	private String hash; // 0x18


	// RVA: 0x5f74674 VA: 0x759858c674
	public Void .ctor() { }
	// RVA: 0x5f7467c VA: 0x759858c67c
	public Void .ctor(AsymmetricAlgorithm key) { }
	// RVA: 0x5f746b0 VA: 0x759858c6b0
	public override Byte[] CreateSignature(Byte[] rgbHash) { }
	// RVA: 0x5f747d8 VA: 0x759858c7d8
	public override Void SetHashAlgorithm(String strName) { }
	// RVA: 0x5f74838 VA: 0x759858c838
	public override Void SetKey(AsymmetricAlgorithm key) { }
}
```