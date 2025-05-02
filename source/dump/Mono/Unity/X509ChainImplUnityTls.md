# X509ChainImplUnityTls

**Namespace:** `Mono.Unity`


## Fields

- `X509ChainElementCollection elements`

- `unitytls_x509list_ref nativeCertificateChain`

- `X509ChainPolicy policy`

- `Boolean reverseOrder`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono.Unity
internal class X509ChainImplUnityTls : X509ChainImpl
{
	private X509ChainElementCollection elements; // 0x10
	private unitytls_x509list* ownedList; // 0x18
	private unitytls_x509list_ref nativeCertificateChain; // 0x20
	private X509ChainPolicy policy; // 0x28
	private List`1 chainStatusList; // 0x30
	private Boolean reverseOrder; // 0x38

	public override Boolean IsValid { get; }
	internal unitytls_x509list_ref NativeCertificateChain { get; }
	public override X509ChainElementCollection ChainElements { get; }
	public override X509ChainPolicy ChainPolicy { get; }
	public override X509ChainStatus[] ChainStatus { get; }

	// RVA: 0x62580c0 VA: 0x75988700c0
	internal Void .ctor(unitytls_x509list_ref nativeCertificateChain, Boolean reverseOrder) { }
	// RVA: 0x6259538 VA: 0x7598871538
	internal Void .ctor(unitytls_x509list* ownedList, unitytls_errorstate* errorState, Boolean reverseOrder) { }
	// RVA: 0x6259818 VA: 0x7598871818
	public override Boolean get_IsValid() { }
	// RVA: 0x6259840 VA: 0x7598871840
	internal unitytls_x509list_ref get_NativeCertificateChain() { }
	// RVA: 0x6259848 VA: 0x7598871848
	public override X509ChainElementCollection get_ChainElements() { }
	// RVA: 0x6259b40 VA: 0x7598871b40
	public override Void AddStatus(X509ChainStatusFlags error) { }
	// RVA: 0x6259c68 VA: 0x7598871c68
	public override X509ChainPolicy get_ChainPolicy() { }
	// RVA: 0x6259c70 VA: 0x7598871c70
	public override X509ChainStatus[] get_ChainStatus() { }
	// RVA: 0x6259cec VA: 0x7598871cec
	public override Boolean Build(X509Certificate2 certificate) { }
	// RVA: 0x6259cf4 VA: 0x7598871cf4
	public override Void Reset() { }
	// RVA: 0x6259d7c VA: 0x7598871d7c
	protected override Void Dispose(Boolean disposing) { }
}
```