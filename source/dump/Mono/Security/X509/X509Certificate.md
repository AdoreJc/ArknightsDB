# X509Certificate

**Namespace:** `Mono.Security.X509`


## Fields

- `ASN1 decoder`

- `DateTime m_from`

- `DateTime m_until`

- `ASN1 issuer`

- `String m_issuername`

- `String m_keyalgo`

- `ASN1 subject`

- `String m_subject`

- `String m_signaturealgo`

- `RSA _rsa`

- `DSA _dsa`

- `Int32 version`

- `X509ExtensionCollection extensions`


## Properties

- `DSA DSA`

- `X509ExtensionCollection Extensions`

- `Int32 Version`

- `Boolean IsCurrent`

- `Boolean IsSelfSigned`


## Methods

- `Void Parse(Byte[])`

- `DSA get_DSA()`

- `Void set_DSA(DSA)`

- `X509ExtensionCollection get_Extensions()`

- `Int32 get_Version()`

- `Boolean get_IsCurrent()`

- `Boolean WasCurrent(DateTime)`

- `Boolean VerifySignature(AsymmetricAlgorithm)`

- `Boolean get_IsSelfSigned()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public class X509Certificate : ISerializable
{
	private ASN1 decoder; // 0x10
	private Byte[] m_encodedcert; // 0x18
	private DateTime m_from; // 0x20
	private DateTime m_until; // 0x28
	private ASN1 issuer; // 0x30
	private String m_issuername; // 0x38
	private String m_keyalgo; // 0x40
	private Byte[] m_keyalgoparams; // 0x48
	private ASN1 subject; // 0x50
	private String m_subject; // 0x58
	private Byte[] m_publickey; // 0x60
	private Byte[] signature; // 0x68
	private String m_signaturealgo; // 0x70
	private Byte[] m_signaturealgoparams; // 0x78
	private Byte[] certhash; // 0x80
	private RSA _rsa; // 0x88
	private DSA _dsa; // 0x90
	private Int32 version; // 0x98
	private Byte[] serialnumber; // 0xa0
	private Byte[] issuerUniqueID; // 0xa8
	private Byte[] subjectUniqueID; // 0xb0
	private X509ExtensionCollection extensions; // 0xb8
	private static String encoding_error; // 0x0

	public DSA DSA { get; set; }
	public X509ExtensionCollection Extensions { get; }
	public Byte[] Hash { get; }
	public virtual String IssuerName { get; }
	public virtual String KeyAlgorithm { get; }
	public virtual Byte[] KeyAlgorithmParameters { get; set; }
	public virtual Byte[] PublicKey { get; }
	public virtual RSA RSA { get; set; }
	public virtual Byte[] RawData { get; }
	public virtual Byte[] SerialNumber { get; }
	public virtual Byte[] Signature { get; }
	public virtual String SubjectName { get; }
	public virtual DateTime ValidFrom { get; }
	public virtual DateTime ValidUntil { get; }
	public Int32 Version { get; }
	public Boolean IsCurrent { get; }
	public Boolean IsSelfSigned { get; }

	// RVA: 0x5ee0610 VA: 0x75984f8610
	private Void Parse(Byte[] data) { }
	// RVA: 0x5ed5fc0 VA: 0x75984edfc0
	public Void .ctor(Byte[] data) { }
	// RVA: 0x5ee116c VA: 0x75984f916c
	private Byte[] GetUnsignedBigInteger(Byte[] integer) { }
	// RVA: 0x5ed9a88 VA: 0x75984f1a88
	public DSA get_DSA() { }
	// RVA: 0x5ee1200 VA: 0x75984f9200
	public Void set_DSA(DSA value) { }
	// RVA: 0x5ee1240 VA: 0x75984f9240
	public X509ExtensionCollection get_Extensions() { }
	// RVA: 0x5ee1248 VA: 0x75984f9248
	public Byte[] get_Hash() { }
	// RVA: 0x5ee14ec VA: 0x75984f94ec
	public virtual String get_IssuerName() { }
	// RVA: 0x5ee14f4 VA: 0x75984f94f4
	public virtual String get_KeyAlgorithm() { }
	// RVA: 0x5ee14fc VA: 0x75984f94fc
	public virtual Byte[] get_KeyAlgorithmParameters() { }
	// RVA: 0x5ee1570 VA: 0x75984f9570
	public virtual Void set_KeyAlgorithmParameters(Byte[] value) { }
	// RVA: 0x5ee1578 VA: 0x75984f9578
	public virtual Byte[] get_PublicKey() { }
	// RVA: 0x5ee15ec VA: 0x75984f95ec
	public virtual RSA get_RSA() { }
	// RVA: 0x5ee17b0 VA: 0x75984f97b0
	public virtual Void set_RSA(RSA value) { }
	// RVA: 0x5ee17ec VA: 0x75984f97ec
	public virtual Byte[] get_RawData() { }
	// RVA: 0x5ee1860 VA: 0x75984f9860
	public virtual Byte[] get_SerialNumber() { }
	// RVA: 0x5ee18d4 VA: 0x75984f98d4
	public virtual Byte[] get_Signature() { }
	// RVA: 0x5ee1d10 VA: 0x75984f9d10
	public virtual String get_SubjectName() { }
	// RVA: 0x5ee1d18 VA: 0x75984f9d18
	public virtual DateTime get_ValidFrom() { }
	// RVA: 0x5ee1d20 VA: 0x75984f9d20
	public virtual DateTime get_ValidUntil() { }
	// RVA: 0x5ee1d28 VA: 0x75984f9d28
	public Int32 get_Version() { }
	// RVA: 0x5ee1d30 VA: 0x75984f9d30
	public Boolean get_IsCurrent() { }
	// RVA: 0x5ee1d90 VA: 0x75984f9d90
	public Boolean WasCurrent(DateTime instant) { }
	// RVA: 0x5ee1e68 VA: 0x75984f9e68
	internal Boolean VerifySignature(DSA dsa) { }
	// RVA: 0x5ee1f30 VA: 0x75984f9f30
	internal Boolean VerifySignature(RSA rsa) { }
	// RVA: 0x5ee2058 VA: 0x75984fa058
	public Boolean VerifySignature(AsymmetricAlgorithm aa) { }
	// RVA: 0x5ee21e4 VA: 0x75984fa1e4
	public Boolean get_IsSelfSigned() { }
	// RVA: 0x5ee22ec VA: 0x75984fa2ec
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ee1038 VA: 0x75984f9038
	private static Byte[] PEM(String type, Byte[] data) { }
	// RVA: 0x5ee2348 VA: 0x75984fa348
	private static Void .cctor() { }
}
```