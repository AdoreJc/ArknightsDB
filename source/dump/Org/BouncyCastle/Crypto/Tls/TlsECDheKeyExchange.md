# TlsECDheKeyExchange

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `TlsSignerCredentials mServerCredentials`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsECDheKeyExchange : TlsECDHKeyExchange
{
	protected TlsSignerCredentials mServerCredentials; // 0x68


	// RVA: 0x64e2b48 VA: 0x7598afab48
	public Void .ctor(Int32 keyExchange, IList supportedSignatureAlgorithms, Int32[] namedCurves, Byte[] clientECPointFormats, Byte[] serverECPointFormats) { }
	// RVA: 0x64f6028 VA: 0x7598b0e028
	public override Void ProcessServerCredentials(TlsCredentials serverCredentials) { }
	// RVA: 0x64f618c VA: 0x7598b0e18c
	public override Byte[] GenerateServerKeyExchange() { }
	// RVA: 0x64f659c VA: 0x7598b0e59c
	public override Void ProcessServerKeyExchange(Stream input) { }
	// RVA: 0x64f6898 VA: 0x7598b0e898
	public override Void ValidateCertificateRequest(CertificateRequest certificateRequest) { }
	// RVA: 0x64f6934 VA: 0x7598b0e934
	public override Void ProcessClientCredentials(TlsCredentials clientCredentials) { }
	// RVA: 0x64f69c0 VA: 0x7598b0e9c0
	protected virtual ISigner InitVerifyer(TlsSigner tlsSigner, SignatureAndHashAlgorithm algorithm, SecurityParameters securityParameters) { }
}
```