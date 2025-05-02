# TbsCertificateList

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `Int32 Version`

- `DerInteger VersionNumber`

- `AlgorithmIdentifier Signature`

- `X509Name Issuer`

- `Time ThisUpdate`

- `Time NextUpdate`

- `X509Extensions Extensions`


## Methods

- `Int32 get_Version()`

- `DerInteger get_VersionNumber()`

- `AlgorithmIdentifier get_Signature()`

- `X509Name get_Issuer()`

- `Time get_ThisUpdate()`

- `Time get_NextUpdate()`

- `IEnumerable GetRevokedCertificateEnumeration()`

- `X509Extensions get_Extensions()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class TbsCertificateList : Asn1Encodable
{
	internal Asn1Sequence seq; // 0x10
	internal DerInteger version; // 0x18
	internal AlgorithmIdentifier signature; // 0x20
	internal X509Name issuer; // 0x28
	internal Time thisUpdate; // 0x30
	internal Time nextUpdate; // 0x38
	internal Asn1Sequence revokedCertificates; // 0x40
	internal X509Extensions crlExtensions; // 0x48

	public Int32 Version { get; }
	public DerInteger VersionNumber { get; }
	public AlgorithmIdentifier Signature { get; }
	public X509Name Issuer { get; }
	public Time ThisUpdate { get; }
	public Time NextUpdate { get; }
	public X509Extensions Extensions { get; }

	// RVA: 0x65b6f08 VA: 0x7598bcef08
	public static TbsCertificateList GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b0308 VA: 0x7598bc8308
	public static TbsCertificateList GetInstance(Object obj) { }
	// RVA: 0x65b6f20 VA: 0x7598bcef20
	internal Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b072c VA: 0x7598bc872c
	public Int32 get_Version() { }
	// RVA: 0x65b7470 VA: 0x7598bcf470
	public DerInteger get_VersionNumber() { }
	// RVA: 0x65b7478 VA: 0x7598bcf478
	public AlgorithmIdentifier get_Signature() { }
	// RVA: 0x65b7480 VA: 0x7598bcf480
	public X509Name get_Issuer() { }
	// RVA: 0x65b7488 VA: 0x7598bcf488
	public Time get_ThisUpdate() { }
	// RVA: 0x65b7490 VA: 0x7598bcf490
	public Time get_NextUpdate() { }
	// RVA: 0x65b04b0 VA: 0x7598bc84b0
	public CrlEntry[] GetRevokedCertificates() { }
	// RVA: 0x65b0638 VA: 0x7598bc8638
	public IEnumerable GetRevokedCertificateEnumeration() { }
	// RVA: 0x65b74c8 VA: 0x7598bcf4c8
	public X509Extensions get_Extensions() { }
	// RVA: 0x65b74d0 VA: 0x7598bcf4d0
	public override Asn1Object ToAsn1Object() { }
}
```