# X509Certificate2

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `Oid lazySignatureAlgorithm`

- `Int32 lazyVersion`

- `X500DistinguishedName lazySubjectName`

- `X500DistinguishedName lazyIssuerName`

- `PublicKey lazyPublicKey`

- `AsymmetricAlgorithm lazyPrivateKey`

- `X509ExtensionCollection lazyExtensions`


## Properties

- `X509ExtensionCollection Extensions`

- `Boolean HasPrivateKey`

- `AsymmetricAlgorithm PrivateKey`

- `X500DistinguishedName IssuerName`

- `DateTime NotAfter`

- `DateTime NotBefore`

- `PublicKey PublicKey`

- `String SerialNumber`

- `Oid SignatureAlgorithm`

- `X500DistinguishedName SubjectName`

- `String Thumbprint`

- `Int32 Version`


## Methods

- `X509ExtensionCollection get_Extensions()`

- `Boolean get_HasPrivateKey()`

- `AsymmetricAlgorithm get_PrivateKey()`

- `X500DistinguishedName get_IssuerName()`

- `DateTime get_NotAfter()`

- `DateTime get_NotBefore()`

- `PublicKey get_PublicKey()`

- `String get_SerialNumber()`

- `Oid get_SignatureAlgorithm()`

- `X500DistinguishedName get_SubjectName()`

- `String get_Thumbprint()`

- `Int32 get_Version()`

- `String GetNameInfo(X509NameType, Boolean)`

- `Boolean Verify()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public class X509Certificate2 : X509Certificate
{
	private Byte[] lazyRawData; // 0x60
	private Oid lazySignatureAlgorithm; // 0x68
	private Int32 lazyVersion; // 0x70
	private X500DistinguishedName lazySubjectName; // 0x78
	private X500DistinguishedName lazyIssuerName; // 0x80
	private PublicKey lazyPublicKey; // 0x88
	private AsymmetricAlgorithm lazyPrivateKey; // 0x90
	private X509ExtensionCollection lazyExtensions; // 0x98

	public X509ExtensionCollection Extensions { get; }
	public Boolean HasPrivateKey { get; }
	public AsymmetricAlgorithm PrivateKey { get; }
	public X500DistinguishedName IssuerName { get; }
	public DateTime NotAfter { get; }
	public DateTime NotBefore { get; }
	public PublicKey PublicKey { get; }
	public Byte[] RawData { get; }
	public String SerialNumber { get; }
	public Oid SignatureAlgorithm { get; }
	public X500DistinguishedName SubjectName { get; }
	public String Thumbprint { get; }
	public Int32 Version { get; }
	internal X509Certificate2Impl Impl { get; }

	// RVA: 0x63a0314 VA: 0x75989b8314
	public override Void Reset() { }
	// RVA: 0x63a03c0 VA: 0x75989b83c0
	public Void .ctor() { }
	// RVA: 0x63a03c8 VA: 0x75989b83c8
	public Void .ctor(Byte[] rawData) { }
	// RVA: 0x63a0590 VA: 0x75989b8590
	public Void .ctor(X509Certificate certificate) { }
	// RVA: 0x63a0598 VA: 0x75989b8598
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x63a05e0 VA: 0x75989b85e0
	public X509ExtensionCollection get_Extensions() { }
	// RVA: 0x63a0cec VA: 0x75989b8cec
	public Boolean get_HasPrivateKey() { }
	// RVA: 0x63a0d20 VA: 0x75989b8d20
	public AsymmetricAlgorithm get_PrivateKey() { }
	// RVA: 0x63a0e88 VA: 0x75989b8e88
	public X500DistinguishedName get_IssuerName() { }
	// RVA: 0x63a0ef4 VA: 0x75989b8ef4
	public DateTime get_NotAfter() { }
	// RVA: 0x63a0efc VA: 0x75989b8efc
	public DateTime get_NotBefore() { }
	// RVA: 0x63a0f04 VA: 0x75989b8f04
	public PublicKey get_PublicKey() { }
	// RVA: 0x63a1070 VA: 0x75989b9070
	public Byte[] get_RawData() { }
	// RVA: 0x63a10dc VA: 0x75989b90dc
	public String get_SerialNumber() { }
	// RVA: 0x63a10ec VA: 0x75989b90ec
	public Oid get_SignatureAlgorithm() { }
	// RVA: 0x63a1160 VA: 0x75989b9160
	public X500DistinguishedName get_SubjectName() { }
	// RVA: 0x63a11cc VA: 0x75989b91cc
	public String get_Thumbprint() { }
	// RVA: 0x63a11e8 VA: 0x75989b91e8
	public Int32 get_Version() { }
	// RVA: 0x63a1244 VA: 0x75989b9244
	public static X509ContentType GetCertContentType(Byte[] rawData) { }
	// RVA: 0x63a12e0 VA: 0x75989b92e0
	public String GetNameInfo(X509NameType nameType, Boolean forIssuer) { }
	// RVA: 0x63a131c VA: 0x75989b931c
	public override String ToString() { }
	// RVA: 0x63a1328 VA: 0x75989b9328
	public override String ToString(Boolean verbose) { }
	// RVA: 0x63a23b4 VA: 0x75989ba3b4
	public Boolean Verify() { }
	// RVA: 0x63a0aa4 VA: 0x75989b8aa4
	private static X509Extension CreateCustomExtensionIfAny(Oid oid) { }
	// RVA: 0x63a0a18 VA: 0x75989b8a18
	internal X509Certificate2Impl get_Impl() { }
}
```