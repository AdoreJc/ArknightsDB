# LegacyTlsAuthentication

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `ICertificateVerifyer verifyer`

- `IClientCredentialsProvider credProvider`

- `Uri TargetUri`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class LegacyTlsAuthentication : TlsAuthentication
{
	protected ICertificateVerifyer verifyer; // 0x10
	protected IClientCredentialsProvider credProvider; // 0x18
	protected Uri TargetUri; // 0x20


	// RVA: 0x64e5340 VA: 0x7598afd340
	public Void .ctor(Uri targetUri, ICertificateVerifyer verifyer, IClientCredentialsProvider prov) { }
	// RVA: 0x64e53a0 VA: 0x7598afd3a0
	public virtual Void NotifyServerCertificate(Certificate serverCertificate) { }
	// RVA: 0x64e54ac VA: 0x7598afd4ac
	public virtual TlsCredentials GetClientCredentials(TlsContext context, CertificateRequest certificateRequest) { }
}
```