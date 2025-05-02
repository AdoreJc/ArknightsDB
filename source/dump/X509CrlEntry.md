# X509CrlEntry

**Namespace:** ` `


## Fields

- `DateTime revocationDate`

- `X509ExtensionCollection extensions`


## Properties

- `DateTime RevocationDate`

- `X509ExtensionCollection Extensions`


## Methods

- `DateTime get_RevocationDate()`

- `X509ExtensionCollection get_Extensions()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class X509CrlEntry
{
	private Byte[] sn; // 0x10
	private DateTime revocationDate; // 0x18
	private X509ExtensionCollection extensions; // 0x20

	public Byte[] SerialNumber { get; }
	public DateTime RevocationDate { get; }
	public X509ExtensionCollection Extensions { get; }

	// RVA: 0x5edf9ac VA: 0x75984f79ac
	internal Void .ctor(ASN1 entry) { }
	// RVA: 0x5ee005c VA: 0x75984f805c
	public Byte[] get_SerialNumber() { }
	// RVA: 0x5ee0600 VA: 0x75984f8600
	public DateTime get_RevocationDate() { }
	// RVA: 0x5ee0608 VA: 0x75984f8608
	public X509ExtensionCollection get_Extensions() { }
}
```