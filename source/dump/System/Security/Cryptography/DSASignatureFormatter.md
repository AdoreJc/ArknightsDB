# DSASignatureFormatter

**Namespace:** `System.Security.Cryptography`


## Fields

- `DSA _dsaKey`

- `String _oid`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class DSASignatureFormatter : AsymmetricSignatureFormatter
{
	private DSA _dsaKey; // 0x10
	private String _oid; // 0x18


	// RVA: 0x5f530e4 VA: 0x759856b0e4
	public Void .ctor() { }
	// RVA: 0x5f5316c VA: 0x759856b16c
	public Void .ctor(AsymmetricAlgorithm key) { }
	// RVA: 0x5f53268 VA: 0x759856b268
	public override Void SetKey(AsymmetricAlgorithm key) { }
	// RVA: 0x5f5335c VA: 0x759856b35c
	public override Void SetHashAlgorithm(String strName) { }
	// RVA: 0x5f53428 VA: 0x759856b428
	public override Byte[] CreateSignature(Byte[] rgbHash) { }
}
```