# TlsDHKeyExchange

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `TlsSigner mTlsSigner`

- `DHParameters mDHParameters`

- `AsymmetricKeyParameter mServerPublicKey`

- `TlsAgreementCredentials mAgreementCredentials`

- `DHPrivateKeyParameters mDHAgreePrivateKey`

- `DHPublicKeyParameters mDHAgreePublicKey`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsDHKeyExchange : AbstractTlsKeyExchange
{
	protected TlsSigner mTlsSigner; // 0x28
	protected DHParameters mDHParameters; // 0x30
	protected AsymmetricKeyParameter mServerPublicKey; // 0x38
	protected TlsAgreementCredentials mAgreementCredentials; // 0x40
	protected DHPrivateKeyParameters mDHAgreePrivateKey; // 0x48
	protected DHPublicKeyParameters mDHAgreePublicKey; // 0x50

	public override Boolean RequiresServerKeyExchange { get; }
	protected virtual Int32 MinimumPrimeBits { get; }

	// RVA: 0x64e26e4 VA: 0x7598afa6e4
	public Void .ctor(Int32 keyExchange, IList supportedSignatureAlgorithms, DHParameters dhParameters) { }
	// RVA: 0x64f0dbc VA: 0x7598b08dbc
	public override Void Init(TlsContext context) { }
	// RVA: 0x64f0e7c VA: 0x7598b08e7c
	public override Void SkipServerCredentials() { }
	// RVA: 0x64f0ebc VA: 0x7598b08ebc
	public override Void ProcessServerCertificate(Certificate serverCertificate) { }
	// RVA: 0x64f129c VA: 0x7598b0929c
	public override Boolean get_RequiresServerKeyExchange() { }
	// RVA: 0x64f12c4 VA: 0x7598b092c4
	public override Void ValidateCertificateRequest(CertificateRequest certificateRequest) { }
	// RVA: 0x64f1360 VA: 0x7598b09360
	public override Void ProcessClientCredentials(TlsCredentials clientCredentials) { }
	// RVA: 0x64f147c VA: 0x7598b0947c
	public override Void GenerateClientKeyExchange(Stream output) { }
	// RVA: 0x64f16ac VA: 0x7598b096ac
	public override Void ProcessClientCertificate(Certificate clientCertificate) { }
	// RVA: 0x64f16b0 VA: 0x7598b096b0
	public override Void ProcessClientKeyExchange(Stream input) { }
	// RVA: 0x64f1788 VA: 0x7598b09788
	public override Byte[] GeneratePremasterSecret() { }
	// RVA: 0x64f1940 VA: 0x7598b09940
	protected virtual Int32 get_MinimumPrimeBits() { }
	// RVA: 0x64f1948 VA: 0x7598b09948
	protected virtual DHParameters ValidateDHParameters(DHParameters parameters) { }
}
```