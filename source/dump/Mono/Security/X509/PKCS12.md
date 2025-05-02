# PKCS12

**Namespace:** `Mono.Security.X509`


## Fields

- `ArrayList _keyBags`

- `ArrayList _secretBags`

- `X509CertificateCollection _certs`

- `Boolean _keyBagsChanged`

- `Boolean _secretBagsChanged`

- `Boolean _certsChanged`

- `Int32 _iterations`

- `ArrayList _safeBags`

- `RandomNumberGenerator _rng`


## Properties

- `String Password`

- `Int32 IterationCount`

- `ArrayList Keys`

- `X509CertificateCollection Certificates`


## Methods

- `Void Decode(Byte[])`

- `Void set_Password(String)`

- `Int32 get_IterationCount()`

- `Void set_IterationCount(Int32)`

- `ArrayList get_Keys()`

- `X509CertificateCollection get_Certificates()`

- `Boolean Compare(Byte[], Byte[])`

- `SymmetricAlgorithm GetSymmetricAlgorithm(String, Byte[], Int32)`

- `DSAParameters GetExistingParameters(out)`

- `Void AddPrivateKey(PrivateKeyInfo)`

- `Void ReadSafeBag(ASN1)`

- `ASN1 CertificateSafeBag(X509Certificate, IDictionary)`

- `ContentInfo EncryptedContentInfo(ASN1, String)`

- `Void AddCertificate(X509Certificate)`

- `Void AddCertificate(X509Certificate, IDictionary)`

- `Void RemoveCertificate(X509Certificate)`

- `Void RemoveCertificate(X509Certificate, IDictionary)`

- `Object Clone()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public class PKCS12 : ICloneable
{
	private Byte[] _password; // 0x10
	private ArrayList _keyBags; // 0x18
	private ArrayList _secretBags; // 0x20
	private X509CertificateCollection _certs; // 0x28
	private Boolean _keyBagsChanged; // 0x30
	private Boolean _secretBagsChanged; // 0x31
	private Boolean _certsChanged; // 0x32
	private Int32 _iterations; // 0x34
	private ArrayList _safeBags; // 0x38
	private RandomNumberGenerator _rng; // 0x40
	private static Int32 password_max_length; // 0x0

	public String Password { set; }
	public Int32 IterationCount { get; set; }
	public ArrayList Keys { get; }
	public X509CertificateCollection Certificates { get; }
	internal RandomNumberGenerator RNG { get; }
	public static Int32 MaximumPasswordLength { get; }

	// RVA: 0x5ed6ac8 VA: 0x75984eeac8
	public Void .ctor() { }
	// RVA: 0x5ed6be4 VA: 0x75984eebe4
	public Void .ctor(Byte[] data) { }
	// RVA: 0x5ed74c0 VA: 0x75984ef4c0
	public Void .ctor(Byte[] data, String password) { }
	// RVA: 0x5ed6e00 VA: 0x75984eee00
	private Void Decode(Byte[] data) { }
	// RVA: 0x5ed7e4c VA: 0x75984efe4c
	protected override Void Finalize() { }
	// RVA: 0x5ed6c18 VA: 0x75984eec18
	public Void set_Password(String value) { }
	// RVA: 0x5ed7f0c VA: 0x75984eff0c
	public Int32 get_IterationCount() { }
	// RVA: 0x5ed7f14 VA: 0x75984eff14
	public Void set_IterationCount(Int32 value) { }
	// RVA: 0x5ed7f1c VA: 0x75984eff1c
	public ArrayList get_Keys() { }
	// RVA: 0x5ed87d0 VA: 0x75984f07d0
	public X509CertificateCollection get_Certificates() { }
	// RVA: 0x5ed8c20 VA: 0x75984f0c20
	internal RandomNumberGenerator get_RNG() { }
	// RVA: 0x5ed7654 VA: 0x75984ef654
	private Boolean Compare(Byte[] expected, Byte[] actual) { }
	// RVA: 0x5ed8c50 VA: 0x75984f0c50
	private SymmetricAlgorithm GetSymmetricAlgorithm(String algorithmOid, Byte[] salt, Int32 iterationCount) { }
	// RVA: 0x5ed861c VA: 0x75984f061c
	public Byte[] Decrypt(String algorithmOid, Byte[] salt, Int32 iterationCount, Byte[] encryptedData) { }
	// RVA: 0x5ed7dbc VA: 0x75984efdbc
	public Byte[] Decrypt(EncryptedData ed) { }
	// RVA: 0x5ed9450 VA: 0x75984f1450
	public Byte[] Encrypt(String algorithmOid, Byte[] salt, Int32 iterationCount, Byte[] data) { }
	// RVA: 0x5ed96a4 VA: 0x75984f16a4
	private DSAParameters GetExistingParameters(out Boolean found) { }
	// RVA: 0x5ed9e24 VA: 0x75984f1e24
	private Void AddPrivateKey(PrivateKeyInfo pki) { }
	// RVA: 0x5ed76c8 VA: 0x75984ef6c8
	private Void ReadSafeBag(ASN1 safeBag) { }
	// RVA: 0x5eda0a0 VA: 0x75984f20a0
	private ASN1 CertificateSafeBag(X509Certificate x509, IDictionary attributes) { }
	// RVA: 0x5ed74f8 VA: 0x75984ef4f8
	private Byte[] MAC(Byte[] password, Byte[] salt, Int32 iterations, Byte[] data) { }
	// RVA: 0x5edad8c VA: 0x75984f2d8c
	public Byte[] GetBytes() { }
	// RVA: 0x5edd0c4 VA: 0x75984f50c4
	private ContentInfo EncryptedContentInfo(ASN1 safeBags, String algorithmOid) { }
	// RVA: 0x5edd0bc VA: 0x75984f50bc
	public Void AddCertificate(X509Certificate cert) { }
	// RVA: 0x5edd43c VA: 0x75984f543c
	public Void AddCertificate(X509Certificate cert, IDictionary attributes) { }
	// RVA: 0x5edd0b4 VA: 0x75984f50b4
	public Void RemoveCertificate(X509Certificate cert) { }
	// RVA: 0x5edd688 VA: 0x75984f5688
	public Void RemoveCertificate(X509Certificate cert, IDictionary attrs) { }
	// RVA: 0x5eddb94 VA: 0x75984f5b94
	public Object Clone() { }
	// RVA: 0x5eddc68 VA: 0x75984f5c68
	public static Int32 get_MaximumPasswordLength() { }
	// RVA: 0x5eddcc0 VA: 0x75984f5cc0
	private static Void .cctor() { }
}
```