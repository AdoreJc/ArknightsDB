# SafeBag

**Namespace:** `Mono.Security.X509`


## Fields

- `String _bagOID`

- `ASN1 _asn1`


## Properties

- `String BagOID`

- `ASN1 ASN1`


## Methods

- `String get_BagOID()`

- `ASN1 get_ASN1()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
internal class SafeBag
{
	private String _bagOID; // 0x10
	private ASN1 _asn1; // 0x18

	public String BagOID { get; }
	public ASN1 ASN1 { get; }

	// RVA: 0x5ed6a74 VA: 0x75984eea74
	public Void .ctor(String bagOID, ASN1 asn1) { }
	// RVA: 0x5ed6ab8 VA: 0x75984eeab8
	public String get_BagOID() { }
	// RVA: 0x5ed6ac0 VA: 0x75984eeac0
	public ASN1 get_ASN1() { }
}
```