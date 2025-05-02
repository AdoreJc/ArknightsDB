# SignatureLoader

**Namespace:** `XLua`


## Fields

- `CustomLoader userLoader`

- `RSACryptoServiceProvider rsa`

- `SHA1 sha`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class SignatureLoader
{
	private CustomLoader userLoader; // 0x10
	private RSACryptoServiceProvider rsa; // 0x18
	private SHA1 sha; // 0x20


	// RVA: 0x3ff1e7c VA: 0x7596609e7c
	public Void .ctor(String publicKey, CustomLoader loader) { }
	// RVA: 0x3ff1fa0 VA: 0x7596609fa0
	private Byte[] load_and_verify(ref String filepath) { }
	// RVA: 0x3ff2114 VA: 0x759660a114
	public static CustomLoader op_Implicit(SignatureLoader signatureLoader) { }
}
```