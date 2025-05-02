# TripleDESTransform

**Namespace:** `System.Security.Cryptography`


## Fields

- `DESTransform E1`

- `DESTransform D2`

- `DESTransform E3`

- `DESTransform D1`

- `DESTransform E2`

- `DESTransform D3`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
internal class TripleDESTransform : SymmetricTransform
{
	private DESTransform E1; // 0x58
	private DESTransform D2; // 0x60
	private DESTransform E3; // 0x68
	private DESTransform D1; // 0x70
	private DESTransform E2; // 0x78
	private DESTransform D3; // 0x80


	// RVA: 0x5f75e60 VA: 0x759858de60
	public Void .ctor(TripleDES algo, Boolean encryption, Byte[] key, Byte[] iv) { }
	// RVA: 0x5f76278 VA: 0x759858e278
	protected override Void ECB(Byte[] input, Byte[] output) { }
	// RVA: 0x5f761d0 VA: 0x759858e1d0
	internal static Byte[] GetStrongKey() { }
}
```