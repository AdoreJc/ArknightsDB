# DSASignatureDeformatter

**Namespace:** `System.Security.Cryptography`


## Fields

- `DSA _dsaKey`

- `String _oid`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class DSASignatureDeformatter : AsymmetricSignatureDeformatter
{
	private DSA _dsaKey; // 0x10
	private String _oid; // 0x18


	// RVA: 0x5f52cac VA: 0x759856acac
	public Void .ctor() { }
	// RVA: 0x5f52d34 VA: 0x759856ad34
	public Void .ctor(AsymmetricAlgorithm key) { }
	// RVA: 0x5f52e30 VA: 0x759856ae30
	public override Void SetKey(AsymmetricAlgorithm key) { }
	// RVA: 0x5f52f24 VA: 0x759856af24
	public override Void SetHashAlgorithm(String strName) { }
	// RVA: 0x5f52ff0 VA: 0x759856aff0
	public override Boolean VerifySignature(Byte[] rgbHash, Byte[] rgbSignature) { }
}
```