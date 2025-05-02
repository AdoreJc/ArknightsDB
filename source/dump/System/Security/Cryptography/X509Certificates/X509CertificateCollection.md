# X509CertificateCollection

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Properties

- `X509Certificate Item`


## Methods

- `X509Certificate get_Item(Int32)`

- `Void AddRange(X509CertificateCollection)`

- `X509CertificateEnumerator GetEnumerator()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public class X509CertificateCollection : CollectionBase
{

	public X509Certificate Item { get; }

	// RVA: 0x63a25c8 VA: 0x75989ba5c8
	public Void .ctor() { }
	// RVA: 0x63a667c VA: 0x75989be67c
	public Void .ctor(X509CertificateCollection value) { }
	// RVA: 0x63a677c VA: 0x75989be77c
	public X509Certificate get_Item(Int32 index) { }
	// RVA: 0x63a66a8 VA: 0x75989be6a8
	public Void AddRange(X509CertificateCollection value) { }
	// RVA: 0x63a6814 VA: 0x75989be814
	public X509CertificateEnumerator GetEnumerator() { }
	// RVA: 0x63a6930 VA: 0x75989be930
	public override Int32 GetHashCode() { }
}
```