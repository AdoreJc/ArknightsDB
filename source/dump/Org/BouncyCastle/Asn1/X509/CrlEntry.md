# CrlEntry

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `DerInteger UserCertificate`

- `Time RevocationDate`

- `X509Extensions Extensions`


## Methods

- `DerInteger get_UserCertificate()`

- `Time get_RevocationDate()`

- `X509Extensions get_Extensions()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class CrlEntry : Asn1Encodable
{
	internal Asn1Sequence seq; // 0x10
	internal DerInteger userCertificate; // 0x18
	internal Time revocationDate; // 0x20
	internal X509Extensions crlEntryExtensions; // 0x28

	public DerInteger UserCertificate { get; }
	public Time RevocationDate { get; }
	public X509Extensions Extensions { get; }

	// RVA: 0x65b6ce0 VA: 0x7598bcece0
	public Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b6e34 VA: 0x7598bcee34
	public DerInteger get_UserCertificate() { }
	// RVA: 0x65b6e3c VA: 0x7598bcee3c
	public Time get_RevocationDate() { }
	// RVA: 0x65b6e44 VA: 0x7598bcee44
	public X509Extensions get_Extensions() { }
	// RVA: 0x65b6f00 VA: 0x7598bcef00
	public override Asn1Object ToAsn1Object() { }
}
```