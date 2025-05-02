# CertificateList

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `TbsCertificateList TbsCertList`

- `AlgorithmIdentifier SignatureAlgorithm`

- `DerBitString Signature`

- `Int32 Version`

- `X509Name Issuer`

- `Time ThisUpdate`

- `Time NextUpdate`


## Methods

- `TbsCertificateList get_TbsCertList()`

- `IEnumerable GetRevokedCertificateEnumeration()`

- `AlgorithmIdentifier get_SignatureAlgorithm()`

- `DerBitString get_Signature()`

- `Int32 get_Version()`

- `X509Name get_Issuer()`

- `Time get_ThisUpdate()`

- `Time get_NextUpdate()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class CertificateList : Asn1Encodable
{
	private readonly TbsCertificateList tbsCertList; // 0x10
	private readonly AlgorithmIdentifier sigAlgID; // 0x18
	private readonly DerBitString sig; // 0x20

	public TbsCertificateList TbsCertList { get; }
	public AlgorithmIdentifier SignatureAlgorithm { get; }
	public DerBitString Signature { get; }
	public Int32 Version { get; }
	public X509Name Issuer { get; }
	public Time ThisUpdate { get; }
	public Time NextUpdate { get; }

	// RVA: 0x65b00e4 VA: 0x7598bc80e4
	public static CertificateList GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b00fc VA: 0x7598bc80fc
	public static CertificateList GetInstance(Object obj) { }
	// RVA: 0x65b01a0 VA: 0x7598bc81a0
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b0490 VA: 0x7598bc8490
	public TbsCertificateList get_TbsCertList() { }
	// RVA: 0x65b0498 VA: 0x7598bc8498
	public CrlEntry[] GetRevokedCertificates() { }
	// RVA: 0x65b0620 VA: 0x7598bc8620
	public IEnumerable GetRevokedCertificateEnumeration() { }
	// RVA: 0x65b06e4 VA: 0x7598bc86e4
	public AlgorithmIdentifier get_SignatureAlgorithm() { }
	// RVA: 0x65b06ec VA: 0x7598bc86ec
	public DerBitString get_Signature() { }
	// RVA: 0x65b06f4 VA: 0x7598bc86f4
	public Byte[] GetSignatureOctets() { }
	// RVA: 0x65b0714 VA: 0x7598bc8714
	public Int32 get_Version() { }
	// RVA: 0x65b075c VA: 0x7598bc875c
	public X509Name get_Issuer() { }
	// RVA: 0x65b0778 VA: 0x7598bc8778
	public Time get_ThisUpdate() { }
	// RVA: 0x65b0794 VA: 0x7598bc8794
	public Time get_NextUpdate() { }
	// RVA: 0x65b07b0 VA: 0x7598bc87b0
	public override Asn1Object ToAsn1Object() { }
}
```