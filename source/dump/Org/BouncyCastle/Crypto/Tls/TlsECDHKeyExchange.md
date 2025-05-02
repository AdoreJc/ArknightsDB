# TlsECDHKeyExchange

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `TlsSigner mTlsSigner`

- `AsymmetricKeyParameter mServerPublicKey`

- `TlsAgreementCredentials mAgreementCredentials`

- `ECPrivateKeyParameters mECAgreePrivateKey`

- `ECPublicKeyParameters mECAgreePublicKey`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsECDHKeyExchange : AbstractTlsKeyExchange
{
	protected TlsSigner mTlsSigner; // 0x28
	protected Int32[] mNamedCurves; // 0x30
	protected Byte[] mClientECPointFormats; // 0x38
	protected Byte[] mServerECPointFormats; // 0x40
	protected AsymmetricKeyParameter mServerPublicKey; // 0x48
	protected TlsAgreementCredentials mAgreementCredentials; // 0x50
	protected ECPrivateKeyParameters mECAgreePrivateKey; // 0x58
	protected ECPublicKeyParameters mECAgreePublicKey; // 0x60

	public override Boolean RequiresServerKeyExchange { get; }

	// RVA: 0x64e293c VA: 0x7598afa93c
	public Void .ctor(Int32 keyExchange, IList supportedSignatureAlgorithms, Int32[] namedCurves, Byte[] clientECPointFormats, Byte[] serverECPointFormats) { }
	// RVA: 0x64f6b98 VA: 0x7598b0eb98
	public override Void Init(TlsContext context) { }
	// RVA: 0x64f6c58 VA: 0x7598b0ec58
	public override Void SkipServerCredentials() { }
	// RVA: 0x64f6cac VA: 0x7598b0ecac
	public override Void ProcessServerCertificate(Certificate serverCertificate) { }
	// RVA: 0x64f7070 VA: 0x7598b0f070
	public override Boolean get_RequiresServerKeyExchange() { }
	// RVA: 0x64f7094 VA: 0x7598b0f094
	public override Byte[] GenerateServerKeyExchange() { }
	// RVA: 0x64f7200 VA: 0x7598b0f200
	public override Void ProcessServerKeyExchange(Stream input) { }
	// RVA: 0x64f731c VA: 0x7598b0f31c
	public override Void ValidateCertificateRequest(CertificateRequest certificateRequest) { }
	// RVA: 0x64f73d0 VA: 0x7598b0f3d0
	public override Void ProcessClientCredentials(TlsCredentials clientCredentials) { }
	// RVA: 0x64f74f8 VA: 0x7598b0f4f8
	public override Void GenerateClientKeyExchange(Stream output) { }
	// RVA: 0x64f761c VA: 0x7598b0f61c
	public override Void ProcessClientCertificate(Certificate clientCertificate) { }
	// RVA: 0x64f7670 VA: 0x7598b0f670
	public override Void ProcessClientKeyExchange(Stream input) { }
	// RVA: 0x64f774c VA: 0x7598b0f74c
	public override Byte[] GeneratePremasterSecret() { }
}
```