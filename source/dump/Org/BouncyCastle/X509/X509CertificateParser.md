# X509CertificateParser

**Namespace:** `Org.BouncyCastle.X509`


## Fields

- `Asn1Set sData`

- `Int32 sDataObjectCount`

- `Stream currentStream`


## Methods

- `X509Certificate ReadDerCertificate(Asn1InputStream)`

- `X509Certificate GetCertificate()`

- `X509Certificate ReadPemCertificate(Stream)`

- `X509Certificate ReadCertificate(Byte[])`

- `ICollection ReadCertificates(Byte[])`

- `X509Certificate ReadCertificate(Stream)`

- `ICollection ReadCertificates(Stream)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.X509
public class X509CertificateParser
{
	private static readonly PemParser PemCertParser; // 0x0
	private Asn1Set sData; // 0x10
	private Int32 sDataObjectCount; // 0x18
	private Stream currentStream; // 0x20


	// RVA: 0x66e3058 VA: 0x7598cfb058
	private X509Certificate ReadDerCertificate(Asn1InputStream dIn) { }
	// RVA: 0x66e327c VA: 0x7598cfb27c
	private X509Certificate GetCertificate() { }
	// RVA: 0x66e3360 VA: 0x7598cfb360
	private X509Certificate ReadPemCertificate(Stream inStream) { }
	// RVA: 0x66e3404 VA: 0x7598cfb404
	protected virtual X509Certificate CreateX509Certificate(X509CertificateStructure c) { }
	// RVA: 0x66e3464 VA: 0x7598cfb464
	public X509Certificate ReadCertificate(Byte[] input) { }
	// RVA: 0x66e37f0 VA: 0x7598cfb7f0
	public ICollection ReadCertificates(Byte[] input) { }
	// RVA: 0x66e34dc VA: 0x7598cfb4dc
	public X509Certificate ReadCertificate(Stream inStream) { }
	// RVA: 0x66e3868 VA: 0x7598cfb868
	public ICollection ReadCertificates(Stream inStream) { }
	// RVA: 0x66e3974 VA: 0x7598cfb974
	public Void .ctor() { }
	// RVA: 0x66e397c VA: 0x7598cfb97c
	private static Void .cctor() { }
}
```