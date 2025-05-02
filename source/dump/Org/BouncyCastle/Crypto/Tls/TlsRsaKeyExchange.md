# TlsRsaKeyExchange

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `AsymmetricKeyParameter mServerPublicKey`

- `RsaKeyParameters mRsaServerPublicKey`

- `TlsEncryptionCredentials mServerCredentials`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsRsaKeyExchange : AbstractTlsKeyExchange
{
	protected AsymmetricKeyParameter mServerPublicKey; // 0x28
	protected RsaKeyParameters mRsaServerPublicKey; // 0x30
	protected TlsEncryptionCredentials mServerCredentials; // 0x38
	protected Byte[] mPremasterSecret; // 0x40


	// RVA: 0x64fd638 VA: 0x7598b15638
	public Void .ctor(IList supportedSignatureAlgorithms) { }
	// RVA: 0x64fd648 VA: 0x7598b15648
	public override Void SkipServerCredentials() { }
	// RVA: 0x64fd68c VA: 0x7598b1568c
	public override Void ProcessServerCredentials(TlsCredentials serverCredentials) { }
	// RVA: 0x64fd7f4 VA: 0x7598b157f4
	public override Void ProcessServerCertificate(Certificate serverCertificate) { }
	// RVA: 0x64fdb54 VA: 0x7598b15b54
	public override Void ValidateCertificateRequest(CertificateRequest certificateRequest) { }
	// RVA: 0x64fdbf4 VA: 0x7598b15bf4
	public override Void ProcessClientCredentials(TlsCredentials clientCredentials) { }
	// RVA: 0x64fdc84 VA: 0x7598b15c84
	public override Void GenerateClientKeyExchange(Stream output) { }
	// RVA: 0x64fe0ac VA: 0x7598b160ac
	public override Void ProcessClientKeyExchange(Stream input) { }
	// RVA: 0x64fe304 VA: 0x7598b16304
	public override Byte[] GeneratePremasterSecret() { }
	// RVA: 0x64fe368 VA: 0x7598b16368
	protected virtual RsaKeyParameters ValidateRsaPublicKey(RsaKeyParameters key) { }
}
```