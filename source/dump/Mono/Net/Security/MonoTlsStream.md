# MonoTlsStream

**Namespace:** `Mono.Net.Security`


## Fields

- `SslStream sslStream`

- `WebExceptionStatus status`

- `Boolean <CertificateValidationFailed>k__BackingField`


## Methods

- `Void Dispose()`

- `Void CloseSslStream()`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono.Net.Security
internal class MonoTlsStream : IDisposable
{
	private readonly MobileTlsProvider provider; // 0x10
	private readonly NetworkStream networkStream; // 0x18
	private readonly HttpWebRequest request; // 0x20
	private readonly MonoTlsSettings settings; // 0x28
	private SslStream sslStream; // 0x30
	private readonly Object sslStreamLock; // 0x38
	private WebExceptionStatus status; // 0x40
	private Boolean <CertificateValidationFailed>k__BackingField; // 0x44

	internal HttpWebRequest Request { get; }
	internal WebExceptionStatus ExceptionStatus { get; }
	internal Boolean CertificateValidationFailed { get; set; }

	// RVA: 0x62616fc VA: 0x75988796fc
	internal HttpWebRequest get_Request() { }
	// RVA: 0x6261704 VA: 0x7598879704
	internal WebExceptionStatus get_ExceptionStatus() { }
	// RVA: 0x626170c VA: 0x759887970c
	internal Boolean get_CertificateValidationFailed() { }
	// RVA: 0x6261714 VA: 0x7598879714
	internal Void set_CertificateValidationFailed(Boolean value) { }
	// RVA: 0x6261720 VA: 0x7598879720
	public Void .ctor(HttpWebRequest request, NetworkStream networkStream) { }
	// RVA: 0x6261954 VA: 0x7598879954
	internal Task`1 CreateStream(WebConnectionTunnel tunnel, CancellationToken cancellationToken) { }
	// RVA: 0x6261aa0 VA: 0x7598879aa0
	public Void Dispose() { }
	// RVA: 0x6261aa4 VA: 0x7598879aa4
	private Void CloseSslStream() { }
}
```