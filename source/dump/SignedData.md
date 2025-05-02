# SignedData

**Namespace:** ` `


## Fields

- `Byte version`

- `String hashAlgorithm`

- `ContentInfo contentInfo`

- `X509CertificateCollection certs`

- `ArrayList crls`

- `SignerInfo signerInfo`

- `Boolean mda`


## Properties

- `X509CertificateCollection Certificates`

- `ContentInfo ContentInfo`

- `String HashName`

- `SignerInfo SignerInfo`


## Methods

- `X509CertificateCollection get_Certificates()`

- `ContentInfo get_ContentInfo()`

- `Void set_HashName(String)`

- `SignerInfo get_SignerInfo()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class SignedData
{
	private Byte version; // 0x10
	private String hashAlgorithm; // 0x18
	private ContentInfo contentInfo; // 0x20
	private X509CertificateCollection certs; // 0x28
	private ArrayList crls; // 0x30
	private SignerInfo signerInfo; // 0x38
	private Boolean mda; // 0x40

	public X509CertificateCollection Certificates { get; }
	public ContentInfo ContentInfo { get; }
	public String HashName { set; }
	public SignerInfo SignerInfo { get; }

	// RVA: 0x5ed5a88 VA: 0x75984eda88
	public Void .ctor(ASN1 asn1) { }
	// RVA: 0x5ed680c VA: 0x75984ee80c
	public X509CertificateCollection get_Certificates() { }
	// RVA: 0x5ed6814 VA: 0x75984ee814
	public ContentInfo get_ContentInfo() { }
	// RVA: 0x5ed67d0 VA: 0x75984ee7d0
	public Void set_HashName(String value) { }
	// RVA: 0x5ed681c VA: 0x75984ee81c
	public SignerInfo get_SignerInfo() { }
	// RVA: 0x5ed661c VA: 0x75984ee61c
	internal String OidToName(String oid) { }
}
```