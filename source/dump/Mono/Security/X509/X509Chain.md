# X509Chain

**Namespace:** `Mono.Security.X509`


## Fields

- `X509CertificateCollection roots`

- `X509CertificateCollection certs`

- `X509Certificate _root`

- `X509CertificateCollection _chain`

- `X509ChainStatusFlags _status`


## Properties

- `X509CertificateCollection TrustAnchors`


## Methods

- `X509CertificateCollection get_TrustAnchors()`

- `Void LoadCertificates(X509CertificateCollection)`

- `Boolean Build(X509Certificate)`

- `Void Reset()`

- `Boolean IsValid(X509Certificate)`

- `X509Certificate FindCertificateParent(X509Certificate)`

- `X509Certificate FindCertificateRoot(X509Certificate)`

- `Boolean IsTrusted(X509Certificate)`

- `Boolean IsParent(X509Certificate, X509Certificate)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public class X509Chain
{
	private X509CertificateCollection roots; // 0x10
	private X509CertificateCollection certs; // 0x18
	private X509Certificate _root; // 0x20
	private X509CertificateCollection _chain; // 0x28
	private X509ChainStatusFlags _status; // 0x30

	public X509CertificateCollection TrustAnchors { get; }

	// RVA: 0x5ee29e4 VA: 0x75984fa9e4
	public Void .ctor() { }
	// RVA: 0x5ee2a58 VA: 0x75984faa58
	public X509CertificateCollection get_TrustAnchors() { }
	// RVA: 0x5ee2b84 VA: 0x75984fab84
	public Void LoadCertificates(X509CertificateCollection collection) { }
	// RVA: 0x5ee2b9c VA: 0x75984fab9c
	public Boolean Build(X509Certificate leaf) { }
	// RVA: 0x5ee3580 VA: 0x75984fb580
	public Void Reset() { }
	// RVA: 0x5ee34d4 VA: 0x75984fb4d4
	private Boolean IsValid(X509Certificate cert) { }
	// RVA: 0x5ee2f60 VA: 0x75984faf60
	private X509Certificate FindCertificateParent(X509Certificate child) { }
	// RVA: 0x5ee3150 VA: 0x75984fb150
	private X509Certificate FindCertificateRoot(X509Certificate potentialRoot) { }
	// RVA: 0x5ee35dc VA: 0x75984fb5dc
	private Boolean IsTrusted(X509Certificate potentialTrusted) { }
	// RVA: 0x5ee3390 VA: 0x75984fb390
	private Boolean IsParent(X509Certificate child, X509Certificate parent) { }
}
```