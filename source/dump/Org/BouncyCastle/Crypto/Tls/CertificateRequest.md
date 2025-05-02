# CertificateRequest

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class CertificateRequest
{
	protected readonly Byte[] mCertificateTypes; // 0x10
	protected readonly IList mSupportedSignatureAlgorithms; // 0x18
	protected readonly IList mCertificateAuthorities; // 0x20

	public virtual Byte[] CertificateTypes { get; }
	public virtual IList SupportedSignatureAlgorithms { get; }
	public virtual IList CertificateAuthorities { get; }

	// RVA: 0x64dc754 VA: 0x7598af4754
	public Void .ctor(Byte[] certificateTypes, IList supportedSignatureAlgorithms, IList certificateAuthorities) { }
	// RVA: 0x64dc7b4 VA: 0x7598af47b4
	public virtual Byte[] get_CertificateTypes() { }
	// RVA: 0x64dc7bc VA: 0x7598af47bc
	public virtual IList get_SupportedSignatureAlgorithms() { }
	// RVA: 0x64dc7c4 VA: 0x7598af47c4
	public virtual IList get_CertificateAuthorities() { }
	// RVA: 0x64dc7cc VA: 0x7598af47cc
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64dd0e0 VA: 0x7598af50e0
	public static CertificateRequest Parse(TlsContext context, Stream input) { }
}
```