# UnityTlsProvider

**Namespace:** `Mono.Unity`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono.Unity
internal class UnityTlsProvider : MobileTlsProvider
{

	public override String Name { get; }
	public override Guid ID { get; }
	public override Boolean SupportsSslStream { get; }
	public override Boolean SupportsMonoExtensions { get; }
	public override Boolean SupportsConnectionInfo { get; }
	internal override Boolean SupportsCleanShutdown { get; }
	public override SslProtocols SupportedProtocols { get; }

	// RVA: 0x6258a18 VA: 0x7598870a18
	public override String get_Name() { }
	// RVA: 0x6258a58 VA: 0x7598870a58
	public override Guid get_ID() { }
	// RVA: 0x6258ab0 VA: 0x7598870ab0
	public override Boolean get_SupportsSslStream() { }
	// RVA: 0x6258ab8 VA: 0x7598870ab8
	public override Boolean get_SupportsMonoExtensions() { }
	// RVA: 0x6258ac0 VA: 0x7598870ac0
	public override Boolean get_SupportsConnectionInfo() { }
	// RVA: 0x6258ac8 VA: 0x7598870ac8
	internal override Boolean get_SupportsCleanShutdown() { }
	// RVA: 0x6258ad0 VA: 0x7598870ad0
	public override SslProtocols get_SupportedProtocols() { }
	// RVA: 0x6258ad8 VA: 0x7598870ad8
	internal override MobileAuthenticatedStream CreateSslStream(SslStream sslStream, Stream innerStream, Boolean leaveInnerStreamOpen, MonoTlsSettings settings) { }
	// RVA: 0x62589b4 VA: 0x75988709b4
	private static unitytls_x509verify_result x509verify_callback(Void* userData, unitytls_x509_ref cert, unitytls_x509verify_result result, unitytls_errorstate* errorState) { }
	// RVA: 0x6258bfc VA: 0x7598870bfc
	internal override Boolean ValidateCertificate(ChainValidationHelper validator, String targetHost, Boolean serverMode, X509CertificateCollection certificates, Boolean wantsChain, ref X509Chain chain, ref SslPolicyErrors errors, ref Int32 status11) { }
	// RVA: 0x6259618 VA: 0x7598871618
	public Void .ctor() { }
}
```