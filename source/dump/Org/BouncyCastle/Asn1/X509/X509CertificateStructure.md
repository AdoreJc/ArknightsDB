# X509CertificateStructure

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `TbsCertificateStructure TbsCertificate`

- `Int32 Version`

- `DerInteger SerialNumber`

- `X509Name Issuer`

- `Time StartDate`

- `Time EndDate`

- `X509Name Subject`

- `SubjectPublicKeyInfo SubjectPublicKeyInfo`

- `AlgorithmIdentifier SignatureAlgorithm`

- `DerBitString Signature`


## Methods

- `TbsCertificateStructure get_TbsCertificate()`

- `Int32 get_Version()`

- `DerInteger get_SerialNumber()`

- `X509Name get_Issuer()`

- `Time get_StartDate()`

- `Time get_EndDate()`

- `X509Name get_Subject()`

- `SubjectPublicKeyInfo get_SubjectPublicKeyInfo()`

- `AlgorithmIdentifier get_SignatureAlgorithm()`

- `DerBitString get_Signature()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class X509CertificateStructure : Asn1Encodable
{
	private readonly TbsCertificateStructure tbsCert; // 0x10
	private readonly AlgorithmIdentifier sigAlgID; // 0x18
	private readonly DerBitString sig; // 0x20

	public TbsCertificateStructure TbsCertificate { get; }
	public Int32 Version { get; }
	public DerInteger SerialNumber { get; }
	public X509Name Issuer { get; }
	public Time StartDate { get; }
	public Time EndDate { get; }
	public X509Name Subject { get; }
	public SubjectPublicKeyInfo SubjectPublicKeyInfo { get; }
	public AlgorithmIdentifier SignatureAlgorithm { get; }
	public DerBitString Signature { get; }

	// RVA: 0x65b7e0c VA: 0x7598bcfe0c
	public static X509CertificateStructure GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b7e24 VA: 0x7598bcfe24
	public static X509CertificateStructure GetInstance(Object obj) { }
	// RVA: 0x65b8030 VA: 0x7598bd0030
	public Void .ctor(TbsCertificateStructure tbsCert, AlgorithmIdentifier sigAlgID, DerBitString sig) { }
	// RVA: 0x65b7ec8 VA: 0x7598bcfec8
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b8130 VA: 0x7598bd0130
	public TbsCertificateStructure get_TbsCertificate() { }
	// RVA: 0x65b8138 VA: 0x7598bd0138
	public Int32 get_Version() { }
	// RVA: 0x65b8150 VA: 0x7598bd0150
	public DerInteger get_SerialNumber() { }
	// RVA: 0x65b816c VA: 0x7598bd016c
	public X509Name get_Issuer() { }
	// RVA: 0x65b8188 VA: 0x7598bd0188
	public Time get_StartDate() { }
	// RVA: 0x65b81a4 VA: 0x7598bd01a4
	public Time get_EndDate() { }
	// RVA: 0x65b81c0 VA: 0x7598bd01c0
	public X509Name get_Subject() { }
	// RVA: 0x65b81dc VA: 0x7598bd01dc
	public SubjectPublicKeyInfo get_SubjectPublicKeyInfo() { }
	// RVA: 0x65b81f8 VA: 0x7598bd01f8
	public AlgorithmIdentifier get_SignatureAlgorithm() { }
	// RVA: 0x65b8200 VA: 0x7598bd0200
	public DerBitString get_Signature() { }
	// RVA: 0x65b8208 VA: 0x7598bd0208
	public Byte[] GetSignatureOctets() { }
	// RVA: 0x65b8228 VA: 0x7598bd0228
	public override Asn1Object ToAsn1Object() { }
}
```