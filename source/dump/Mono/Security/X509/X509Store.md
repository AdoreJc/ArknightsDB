# X509Store

**Namespace:** `Mono.Security.X509`


## Fields

- `String _storePath`

- `X509CertificateCollection _certificates`

- `ArrayList _crls`

- `Boolean _crl`

- `Boolean _newFormat`


## Properties

- `X509CertificateCollection Certificates`

- `ArrayList Crls`


## Methods

- `X509CertificateCollection get_Certificates()`

- `ArrayList get_Crls()`

- `X509Certificate LoadCertificate(String)`

- `X509Crl LoadCrl(String)`

- `Boolean CheckStore(String, Boolean)`

- `X509CertificateCollection BuildCertificatesCollection(String)`

- `ArrayList BuildCrlsCollection(String)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public class X509Store
{
	private String _storePath; // 0x10
	private X509CertificateCollection _certificates; // 0x18
	private ArrayList _crls; // 0x20
	private Boolean _crl; // 0x28
	private Boolean _newFormat; // 0x29

	public X509CertificateCollection Certificates { get; }
	public ArrayList Crls { get; }

	// RVA: 0x5ee4120 VA: 0x75984fc120
	internal Void .ctor(String path, Boolean crl, Boolean newFormat) { }
	// RVA: 0x5ee416c VA: 0x75984fc16c
	public X509CertificateCollection get_Certificates() { }
	// RVA: 0x5ee4384 VA: 0x75984fc384
	public ArrayList get_Crls() { }
	// RVA: 0x5ee45e4 VA: 0x75984fc5e4
	private Byte[] Load(String filename) { }
	// RVA: 0x5ee47f0 VA: 0x75984fc7f0
	private X509Certificate LoadCertificate(String filename) { }
	// RVA: 0x5ee4860 VA: 0x75984fc860
	private X509Crl LoadCrl(String filename) { }
	// RVA: 0x5ee48d0 VA: 0x75984fc8d0
	private Boolean CheckStore(String path, Boolean throwException) { }
	// RVA: 0x5ee41b0 VA: 0x75984fc1b0
	private X509CertificateCollection BuildCertificatesCollection(String storeName) { }
	// RVA: 0x5ee4424 VA: 0x75984fc424
	private ArrayList BuildCrlsCollection(String storeName) { }
}
```