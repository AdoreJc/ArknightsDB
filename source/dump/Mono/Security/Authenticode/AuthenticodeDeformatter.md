# AuthenticodeDeformatter

**Namespace:** `Mono.Security.Authenticode`


## Fields

- `String filename`

- `X509CertificateCollection coll`

- `ASN1 signedHash`

- `DateTime timestamp`

- `X509Certificate signingCertificate`

- `Int32 reason`

- `Boolean trustedRoot`

- `Boolean trustedTimestampRoot`

- `X509Chain signerChain`

- `X509Chain timestampChain`


## Properties

- `X509Certificate SigningCertificate`


## Methods

- `Void set_RawData(Byte[])`

- `X509Certificate get_SigningCertificate()`

- `Boolean CheckSignature()`

- `Boolean CompareIssuerSerial(String, Byte[], X509Certificate)`

- `Boolean VerifySignature(SignedData, Byte[], HashAlgorithm)`

- `Boolean VerifyCounterSignature(SignerInfo, Byte[])`

- `Void Reset()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Authenticode
public class AuthenticodeDeformatter : AuthenticodeBase
{
	private String filename; // 0x40
	private Byte[] rawdata; // 0x48
	private Byte[] hash; // 0x50
	private X509CertificateCollection coll; // 0x58
	private ASN1 signedHash; // 0x60
	private DateTime timestamp; // 0x68
	private X509Certificate signingCertificate; // 0x70
	private Int32 reason; // 0x78
	private Boolean trustedRoot; // 0x7c
	private Boolean trustedTimestampRoot; // 0x7d
	private Byte[] entry; // 0x80
	private X509Chain signerChain; // 0x88
	private X509Chain timestampChain; // 0x90

	public Byte[] RawData { set; }
	public X509Certificate SigningCertificate { get; }

	// RVA: 0x5ef1110 VA: 0x7598509110
	public Void .ctor() { }
	// RVA: 0x5ef11b0 VA: 0x75985091b0
	public Void .ctor(Byte[] rawData) { }
	// RVA: 0x5ef11d8 VA: 0x75985091d8
	public Void set_RawData(Byte[] value) { }
	// RVA: 0x5ef1690 VA: 0x7598509690
	public X509Certificate get_SigningCertificate() { }
	// RVA: 0x5ef13a8 VA: 0x75985093a8
	private Boolean CheckSignature() { }
	// RVA: 0x5ef20ec VA: 0x759850a0ec
	private Boolean CompareIssuerSerial(String issuer, Byte[] serial, X509Certificate x509) { }
	// RVA: 0x5ef1698 VA: 0x7598509698
	private Boolean VerifySignature(SignedData sd, Byte[] calculatedMessageDigest, HashAlgorithm ha) { }
	// RVA: 0x5ef21e0 VA: 0x759850a1e0
	private Boolean VerifyCounterSignature(SignerInfo cs, Byte[] signature) { }
	// RVA: 0x5ef12b4 VA: 0x75985092b4
	private Void Reset() { }
}
```