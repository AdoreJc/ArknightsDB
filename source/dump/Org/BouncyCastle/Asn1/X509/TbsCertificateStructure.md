# TbsCertificateStructure

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `Int32 Version`

- `DerInteger VersionNumber`

- `DerInteger SerialNumber`

- `AlgorithmIdentifier Signature`

- `X509Name Issuer`

- `Time StartDate`

- `Time EndDate`

- `X509Name Subject`

- `SubjectPublicKeyInfo SubjectPublicKeyInfo`

- `DerBitString IssuerUniqueID`

- `DerBitString SubjectUniqueID`

- `X509Extensions Extensions`


## Methods

- `Int32 get_Version()`

- `DerInteger get_VersionNumber()`

- `DerInteger get_SerialNumber()`

- `AlgorithmIdentifier get_Signature()`

- `X509Name get_Issuer()`

- `Time get_StartDate()`

- `Time get_EndDate()`

- `X509Name get_Subject()`

- `SubjectPublicKeyInfo get_SubjectPublicKeyInfo()`

- `DerBitString get_IssuerUniqueID()`

- `DerBitString get_SubjectUniqueID()`

- `X509Extensions get_Extensions()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class TbsCertificateStructure : Asn1Encodable
{
	internal Asn1Sequence seq; // 0x10
	internal DerInteger version; // 0x18
	internal DerInteger serialNumber; // 0x20
	internal AlgorithmIdentifier signature; // 0x28
	internal X509Name issuer; // 0x30
	internal Time startDate; // 0x38
	internal Time endDate; // 0x40
	internal X509Name subject; // 0x48
	internal SubjectPublicKeyInfo subjectPublicKeyInfo; // 0x50
	internal DerBitString issuerUniqueID; // 0x58
	internal DerBitString subjectUniqueID; // 0x60
	internal X509Extensions extensions; // 0x68

	public Int32 Version { get; }
	public DerInteger VersionNumber { get; }
	public DerInteger SerialNumber { get; }
	public AlgorithmIdentifier Signature { get; }
	public X509Name Issuer { get; }
	public Time StartDate { get; }
	public Time EndDate { get; }
	public X509Name Subject { get; }
	public SubjectPublicKeyInfo SubjectPublicKeyInfo { get; }
	public DerBitString IssuerUniqueID { get; }
	public DerBitString SubjectUniqueID { get; }
	public X509Extensions Extensions { get; }

	// RVA: 0x65b6344 VA: 0x7598bce344
	public static TbsCertificateStructure GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b635c VA: 0x7598bce35c
	public static TbsCertificateStructure GetInstance(Object obj) { }
	// RVA: 0x65b6400 VA: 0x7598bce400
	internal Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b6c50 VA: 0x7598bcec50
	public Int32 get_Version() { }
	// RVA: 0x65b6c80 VA: 0x7598bcec80
	public DerInteger get_VersionNumber() { }
	// RVA: 0x65b6c88 VA: 0x7598bcec88
	public DerInteger get_SerialNumber() { }
	// RVA: 0x65b6c90 VA: 0x7598bcec90
	public AlgorithmIdentifier get_Signature() { }
	// RVA: 0x65b6c98 VA: 0x7598bcec98
	public X509Name get_Issuer() { }
	// RVA: 0x65b6ca0 VA: 0x7598bceca0
	public Time get_StartDate() { }
	// RVA: 0x65b6ca8 VA: 0x7598bceca8
	public Time get_EndDate() { }
	// RVA: 0x65b6cb0 VA: 0x7598bcecb0
	public X509Name get_Subject() { }
	// RVA: 0x65b6cb8 VA: 0x7598bcecb8
	public SubjectPublicKeyInfo get_SubjectPublicKeyInfo() { }
	// RVA: 0x65b6cc0 VA: 0x7598bcecc0
	public DerBitString get_IssuerUniqueID() { }
	// RVA: 0x65b6cc8 VA: 0x7598bcecc8
	public DerBitString get_SubjectUniqueID() { }
	// RVA: 0x65b6cd0 VA: 0x7598bcecd0
	public X509Extensions get_Extensions() { }
	// RVA: 0x65b6cd8 VA: 0x7598bcecd8
	public override Asn1Object ToAsn1Object() { }
}
```