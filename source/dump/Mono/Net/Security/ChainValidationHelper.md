# ChainValidationHelper

**Namespace:** `Mono.Net.Security`


## Properties

- `MonoTlsSettings Settings`


## Methods

- `MonoTlsSettings get_Settings()`

- `Boolean SelectClientCertificate(String, X509CertificateCollection, X509Certificate, String[], out)`

- `ValidationResult ValidateCertificate(String, Boolean, X509Certificate, X509Chain)`

- `ValidationResult ValidateChain(String, Boolean, X509Certificate, X509Chain, X509CertificateCollection, SslPolicyErrors)`

- `ValidationResult ValidateChain(String, Boolean, X509Certificate, ref, X509CertificateCollection, SslPolicyErrors)`

- `Boolean InvokeCallback(X509Certificate, X509Chain, SslPolicyErrors)`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono.Net.Security
internal class ChainValidationHelper : ICertificateValidator
{
	private readonly WeakReference`1 owner; // 0x10
	private readonly MonoTlsSettings settings; // 0x18
	private readonly MobileTlsProvider provider; // 0x20
	private readonly ServerCertValidationCallback certValidationCallback; // 0x28
	private readonly LocalCertSelectionCallback certSelectionCallback; // 0x30
	private readonly MonoTlsStream tlsStream; // 0x38
	private readonly HttpWebRequest request; // 0x40

	public MonoTlsSettings Settings { get; }

	// RVA: 0x625c2a4 VA: 0x75988742a4
	internal static ChainValidationHelper GetInternalValidator(SslStream owner, MobileTlsProvider provider, MonoTlsSettings settings) { }
	// RVA: 0x625c684 VA: 0x7598874684
	internal static ChainValidationHelper Create(MobileTlsProvider provider, ref MonoTlsSettings settings, MonoTlsStream stream) { }
	// RVA: 0x625c384 VA: 0x7598874384
	private Void .ctor(SslStream owner, MobileTlsProvider provider, MonoTlsSettings settings, Boolean cloneSettings, MonoTlsStream stream) { }
	// RVA: 0x625c834 VA: 0x7598874834
	private static ServerCertValidationCallback GetValidationCallback(MonoTlsSettings settings) { }
	// RVA: 0x625ca0c VA: 0x7598874a0c
	private static X509Certificate DefaultSelectionCallback(String targetHost, X509CertificateCollection localCertificates, X509Certificate remoteCertificate, String[] acceptableIssuers) { }
	// RVA: 0x625ca48 VA: 0x7598874a48
	public MonoTlsSettings get_Settings() { }
	// RVA: 0x625ca50 VA: 0x7598874a50
	public Boolean SelectClientCertificate(String targetHost, X509CertificateCollection localCertificates, X509Certificate remoteCertificate, String[] acceptableIssuers, out X509Certificate clientCertificate) { }
	// RVA: 0x625caa4 VA: 0x7598874aa4
	public ValidationResult ValidateCertificate(String host, Boolean serverMode, X509Certificate leaf, X509Chain chain) { }
	// RVA: 0x625cb78 VA: 0x7598874b78
	private ValidationResult ValidateChain(String host, Boolean server, X509Certificate leaf, X509Chain chain, X509CertificateCollection certs, SslPolicyErrors errors) { }
	// RVA: 0x625cc54 VA: 0x7598874c54
	private ValidationResult ValidateChain(String host, Boolean server, X509Certificate leaf, ref X509Chain chain, X509CertificateCollection certs, SslPolicyErrors errors) { }
	// RVA: 0x625d064 VA: 0x7598875064
	private Boolean InvokeCallback(X509Certificate leaf, X509Chain chain, SslPolicyErrors errors) { }
}
```