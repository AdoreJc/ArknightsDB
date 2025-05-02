# SystemDependencyProvider

**Namespace:** `Mono`


## Properties

- `SystemCertificateProvider CertificateProvider`

- `X509PalImpl X509Pal`


## Methods

- `SystemCertificateProvider get_CertificateProvider()`

- `X509PalImpl get_X509Pal()`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono
internal class SystemDependencyProvider : ISystemDependencyProvider
{
	private static SystemDependencyProvider instance; // 0x0
	private static Object syncRoot; // 0x8
	private readonly SystemCertificateProvider <CertificateProvider>k__BackingField; // 0x10

	public static SystemDependencyProvider Instance { get; }
	private ISystemCertificateProvider Mono.ISystemDependencyProvider.CertificateProvider { get; }
	public SystemCertificateProvider CertificateProvider { get; }
	public X509PalImpl X509Pal { get; }

	// RVA: 0x625257c VA: 0x759886a57c
	public static SystemDependencyProvider get_Instance() { }
	// RVA: 0x62525d8 VA: 0x759886a5d8
	internal static Void Initialize() { }
	// RVA: 0x62527d8 VA: 0x759886a7d8
	private ISystemCertificateProvider Mono.ISystemDependencyProvider.get_CertificateProvider() { }
	// RVA: 0x62527e0 VA: 0x759886a7e0
	public SystemCertificateProvider get_CertificateProvider() { }
	// RVA: 0x62527e8 VA: 0x759886a7e8
	public X509PalImpl get_X509Pal() { }
	// RVA: 0x6252734 VA: 0x759886a734
	private Void .ctor() { }
	// RVA: 0x6252800 VA: 0x759886a800
	private static Void .cctor() { }
}
```