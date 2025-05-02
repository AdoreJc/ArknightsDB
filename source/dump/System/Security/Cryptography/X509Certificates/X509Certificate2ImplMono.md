# X509Certificate2ImplMono

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `X509CertificateImplCollection intermediateCerts`

- `X509Certificate _cert`


## Properties

- `X509Certificate Cert`


## Methods

- `X509Certificate get_Cert()`

- `X509Certificate ImportPkcs12(Byte[], SafePasswordHandle)`

- `X509Certificate ImportPkcs12(Byte[], String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
internal class X509Certificate2ImplMono : X509Certificate2ImplUnix
{
	private X509CertificateImplCollection intermediateCerts; // 0xb0
	private X509Certificate _cert; // 0xb8
	private static String empty_error; // 0x0
	private static Byte[] signedData; // 0x8

	public override Boolean IsValid { get; }
	private X509Certificate Cert { get; }
	public override Boolean HasPrivateKey { get; }
	public override AsymmetricAlgorithm PrivateKey { get; set; }
	internal override X509CertificateImplCollection IntermediateCertificates { get; }
	internal X509Certificate MonoCertificate { get; }

	// RVA: 0x63a4b88 VA: 0x75989bcb88
	public override Boolean get_IsValid() { }
	// RVA: 0x63a4b98 VA: 0x75989bcb98
	public Void .ctor(X509Certificate cert) { }
	// RVA: 0x63a4bd0 VA: 0x75989bcbd0
	private Void .ctor(X509Certificate2ImplMono other) { }
	// RVA: 0x63a4c90 VA: 0x75989bcc90
	public Void .ctor(Byte[] rawData, SafePasswordHandle password, X509KeyStorageFlags keyStorageFlags) { }
	// RVA: 0x63a4e6c VA: 0x75989bce6c
	public override X509CertificateImpl Clone() { }
	// RVA: 0x63a4ed8 VA: 0x75989bced8
	private X509Certificate get_Cert() { }
	// RVA: 0x63a4ef4 VA: 0x75989bcef4
	protected override Byte[] GetRawCertData() { }
	// RVA: 0x63a4f2c VA: 0x75989bcf2c
	public override Boolean get_HasPrivateKey() { }
	// RVA: 0x63a4f50 VA: 0x75989bcf50
	public override AsymmetricAlgorithm get_PrivateKey() { }
	// RVA: 0x63a5384 VA: 0x75989bd384
	public override Void set_PrivateKey(AsymmetricAlgorithm value) { }
	// RVA: 0x63a551c VA: 0x75989bd51c
	public override RSA GetRSAPrivateKey() { }
	// RVA: 0x63a55a8 VA: 0x75989bd5a8
	public override DSA GetDSAPrivateKey() { }
	// RVA: 0x63a4e14 VA: 0x75989bce14
	private X509Certificate ImportPkcs12(Byte[] rawData, SafePasswordHandle password) { }
	// RVA: 0x63a5634 VA: 0x75989bd634
	private X509Certificate ImportPkcs12(Byte[] rawData, String password) { }
	// RVA: 0x63a5f74 VA: 0x75989bdf74
	public override Boolean Verify(X509Certificate2 thisCertificate) { }
	// RVA: 0x63a60a0 VA: 0x75989be0a0
	internal override X509CertificateImplCollection get_IntermediateCertificates() { }
	// RVA: 0x63a60a8 VA: 0x75989be0a8
	internal X509Certificate get_MonoCertificate() { }
	// RVA: 0x63a60b0 VA: 0x75989be0b0
	private static Void .cctor() { }
}
```