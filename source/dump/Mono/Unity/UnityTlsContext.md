# UnityTlsContext

**Namespace:** `Mono.Unity`


## Fields

- `unitytls_tlsctx_read_callback readCallback`

- `unitytls_tlsctx_write_callback writeCallback`

- `unitytls_tlsctx_certificate_callback certificateCallback`

- `unitytls_tlsctx_x509verify_callback verifyCallback`

- `X509Certificate localClientCertificate`

- `X509Certificate2 remoteCertificate`

- `MonoTlsConnectionInfo connectioninfo`

- `Boolean isAuthenticated`

- `Boolean hasContext`

- `Boolean closedGraceful`

- `GCHandle handle`

- `Exception lastException`


## Methods

- `IntPtr WriteCallback(Byte*, IntPtr, unitytls_errorstate*)`

- `IntPtr ReadCallback(Byte*, IntPtr, unitytls_errorstate*)`

- `unitytls_x509verify_result VerifyCallback(unitytls_x509list_ref, unitytls_errorstate*)`

- `Void CertificateCallback(unitytls_tlsctx*, Byte*, IntPtr, unitytls_x509name*, IntPtr, unitytls_x509list_ref*, unitytls_key_ref*, unitytls_errorstate*)`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono.Unity
internal class UnityTlsContext : MobileTlsContext
{
	private unitytls_tlsctx* tlsContext; // 0x58
	private unitytls_x509list* requestedClientCertChain; // 0x60
	private unitytls_key* requestedClientKey; // 0x68
	private unitytls_tlsctx_read_callback readCallback; // 0x70
	private unitytls_tlsctx_write_callback writeCallback; // 0x78
	private unitytls_tlsctx_certificate_callback certificateCallback; // 0x80
	private unitytls_tlsctx_x509verify_callback verifyCallback; // 0x88
	private X509Certificate localClientCertificate; // 0x90
	private X509Certificate2 remoteCertificate; // 0x98
	private MonoTlsConnectionInfo connectioninfo; // 0xa0
	private Boolean isAuthenticated; // 0xa8
	private Boolean hasContext; // 0xa9
	private Boolean closedGraceful; // 0xaa
	private Byte[] writeBuffer; // 0xb0
	private Byte[] readBuffer; // 0xb8
	private GCHandle handle; // 0xc0
	private Exception lastException; // 0xc8

	public override Boolean IsAuthenticated { get; }
	internal override X509Certificate LocalClientCertificate { get; }
	public override X509Certificate2 RemoteCertificate { get; }

	// RVA: 0x6255c9c VA: 0x759886dc9c
	public Void .ctor(MobileAuthenticatedStream parent, MonoSslAuthenticationOptions options) { }
	// RVA: 0x625665c VA: 0x759886e65c
	private static Void ExtractNativeKeyAndChainFromManagedCertificate(X509Certificate cert, unitytls_errorstate* errorState, out unitytls_x509list* nativeCertChain, out unitytls_key* nativeKey) { }
	// RVA: 0x62569a4 VA: 0x759886e9a4
	public override Boolean get_IsAuthenticated() { }
	// RVA: 0x62569ac VA: 0x759886e9ac
	internal override X509Certificate get_LocalClientCertificate() { }
	// RVA: 0x62569b4 VA: 0x759886e9b4
	public override X509Certificate2 get_RemoteCertificate() { }
	// RVA: 0x62569bc VA: 0x759886e9bc
	public override ValueTuple`2 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6256b78 VA: 0x759886eb78
	public override ValueTuple`2 Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6256d28 VA: 0x759886ed28
	public override Void Renegotiate() { }
	// RVA: 0x6256d68 VA: 0x759886ed68
	public override Boolean PendingRenegotiation() { }
	// RVA: 0x6256d70 VA: 0x759886ed70
	public override Void Shutdown() { }
	// RVA: 0x6256e84 VA: 0x759886ee84
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6256f7c VA: 0x759886ef7c
	public override Void StartHandshake() { }
	// RVA: 0x62570fc VA: 0x759886f0fc
	public override Boolean ProcessHandshake() { }
	// RVA: 0x62572d8 VA: 0x759886f2d8
	public override Void FinishHandshake() { }
	// RVA: 0x6255994 VA: 0x759886d994
	private static IntPtr WriteCallback(Void* userData, Byte* data, IntPtr bufferLen, unitytls_errorstate* errorState) { }
	// RVA: 0x6257434 VA: 0x759886f434
	private IntPtr WriteCallback(Byte* data, IntPtr bufferLen, unitytls_errorstate* errorState) { }
	// RVA: 0x6255a5c VA: 0x759886da5c
	private static IntPtr ReadCallback(Void* userData, Byte* buffer, IntPtr bufferLen, unitytls_errorstate* errorState) { }
	// RVA: 0x62578a0 VA: 0x759886f8a0
	private IntPtr ReadCallback(Byte* buffer, IntPtr bufferLen, unitytls_errorstate* errorState) { }
	// RVA: 0x6255b24 VA: 0x759886db24
	private static unitytls_x509verify_result VerifyCallback(Void* userData, unitytls_x509list_ref chain, unitytls_errorstate* errorState) { }
	// RVA: 0x6257cc0 VA: 0x759886fcc0
	private unitytls_x509verify_result VerifyCallback(unitytls_x509list_ref chain, unitytls_errorstate* errorState) { }
	// RVA: 0x6255bd4 VA: 0x759886dbd4
	private static Void CertificateCallback(Void* userData, unitytls_tlsctx* ctx, Byte* cn, IntPtr cnLen, unitytls_x509name* caList, IntPtr caListLen, unitytls_x509list_ref* chain, unitytls_key_ref* key, unitytls_errorstate* errorState) { }
	// RVA: 0x6258164 VA: 0x7598870164
	private Void CertificateCallback(unitytls_tlsctx* ctx, Byte* cn, IntPtr cnLen, unitytls_x509name* caList, IntPtr caListLen, unitytls_x509list_ref* chain, unitytls_key_ref* key, unitytls_errorstate* errorState) { }
}
```