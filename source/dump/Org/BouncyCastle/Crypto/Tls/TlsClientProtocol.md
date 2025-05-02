# TlsClientProtocol

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `TlsClient mTlsClient`

- `TlsKeyExchange mKeyExchange`

- `TlsAuthentication mAuthentication`

- `CertificateStatus mCertificateStatus`

- `CertificateRequest mCertificateRequest`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class TlsClientProtocol : TlsProtocol
{
	protected TlsClient mTlsClient; // 0xa8
	internal TlsClientContextImpl mTlsClientContext; // 0xb0
	protected Byte[] mSelectedSessionID; // 0xb8
	protected TlsKeyExchange mKeyExchange; // 0xc0
	protected TlsAuthentication mAuthentication; // 0xc8
	protected CertificateStatus mCertificateStatus; // 0xd0
	protected CertificateRequest mCertificateRequest; // 0xd8

	protected override TlsContext Context { get; }
	internal override AbstractTlsContext ContextAdmin { get; }
	protected override TlsPeer Peer { get; }

	// RVA: 0x64ec114 VA: 0x7598b04114
	public Void .ctor(Stream stream, SecureRandom secureRandom) { }
	// RVA: 0x64ec190 VA: 0x7598b04190
	public Void .ctor(Stream input, Stream output, SecureRandom secureRandom) { }
	// RVA: 0x64ec350 VA: 0x7598b04350
	public Void .ctor(SecureRandom secureRandom) { }
	// RVA: 0x64ec558 VA: 0x7598b04558
	public virtual Void Connect(TlsClient tlsClient) { }
	// RVA: 0x64ecaf8 VA: 0x7598b04af8
	protected override Void CleanupHandshake() { }
	// RVA: 0x64ecc08 VA: 0x7598b04c08
	protected override TlsContext get_Context() { }
	// RVA: 0x64ecc10 VA: 0x7598b04c10
	internal override AbstractTlsContext get_ContextAdmin() { }
	// RVA: 0x64ecc18 VA: 0x7598b04c18
	protected override TlsPeer get_Peer() { }
	// RVA: 0x64ecc20 VA: 0x7598b04c20
	protected override Void HandleHandshakeMessage(Byte type, Byte[] data) { }
	// RVA: 0x64ee588 VA: 0x7598b06588
	protected virtual Void HandleSupplementalData(IList serverSupplementalData) { }
	// RVA: 0x64ee748 VA: 0x7598b06748
	protected virtual Void ReceiveNewSessionTicketMessage(MemoryStream buf) { }
	// RVA: 0x64ee838 VA: 0x7598b06838
	protected virtual Void ReceiveServerHelloMessage(MemoryStream buf) { }
	// RVA: 0x64ef7f4 VA: 0x7598b077f4
	protected virtual Void SendCertificateVerifyMessage(DigitallySigned certificateVerify) { }
	// RVA: 0x64ef884 VA: 0x7598b07884
	protected virtual Void SendClientHelloMessage() { }
	// RVA: 0x64efecc VA: 0x7598b07ecc
	protected virtual Void SendClientKeyExchangeMessage() { }
}
```