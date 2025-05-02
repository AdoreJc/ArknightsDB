# AuthorityKeyIdentifierExtension

**Namespace:** `Mono.Security.X509.Extensions`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509.Extensions
public class AuthorityKeyIdentifierExtension : X509Extension
{
	private Byte[] aki; // 0x28

	public Byte[] Identifier { get; }

	// RVA: 0x5ee4fbc VA: 0x75984fcfbc
	public Void .ctor(X509Extension extension) { }
	// RVA: 0x5ee4fc0 VA: 0x75984fcfc0
	protected override Void Decode() { }
	// RVA: 0x5ee50e8 VA: 0x75984fd0e8
	protected override Void Encode() { }
	// RVA: 0x5ee5240 VA: 0x75984fd240
	public Byte[] get_Identifier() { }
	// RVA: 0x5ee52b4 VA: 0x75984fd2b4
	public override String ToString() { }
}
```