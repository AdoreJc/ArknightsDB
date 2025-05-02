# SystemCertificateProvider

**Namespace:** `Mono`


## Properties

- `X509PalImpl X509Pal`


## Methods

- `X509PalImpl get_X509Pal()`

- `X509CertificateImpl Import(Byte[], CertificateImportFlags)`

- `X509Certificate2Impl Import(Byte[], SafePasswordHandle, X509KeyStorageFlags, CertificateImportFlags)`

- `X509Certificate2Impl Import(X509Certificate, CertificateImportFlags)`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono
internal class SystemCertificateProvider : ISystemCertificateProvider
{
	private static Int32 initialized; // 0x0
	private static X509PalImpl x509pal; // 0x8
	private static Object syncRoot; // 0x10

	public X509PalImpl X509Pal { get; }

	// RVA: 0x6251e08 VA: 0x7598869e08
	private static X509PalImpl GetX509Pal() { }
	// RVA: 0x6251eb8 VA: 0x7598869eb8
	private static Void EnsureInitialized() { }
	// RVA: 0x625200c VA: 0x759886a00c
	public X509PalImpl get_X509Pal() { }
	// RVA: 0x6252068 VA: 0x759886a068
	public X509CertificateImpl Import(Byte[] data, CertificateImportFlags importFlags) { }
	// RVA: 0x62522d0 VA: 0x759886a2d0
	private X509CertificateImpl Mono.ISystemCertificateProvider.Import(Byte[] data, SafePasswordHandle password, X509KeyStorageFlags keyStorageFlags, CertificateImportFlags importFlags) { }
	// RVA: 0x62522d4 VA: 0x759886a2d4
	public X509Certificate2Impl Import(Byte[] data, SafePasswordHandle password, X509KeyStorageFlags keyStorageFlags, CertificateImportFlags importFlags) { }
	// RVA: 0x62523e0 VA: 0x759886a3e0
	private X509CertificateImpl Mono.ISystemCertificateProvider.Import(X509Certificate cert, CertificateImportFlags importFlags) { }
	// RVA: 0x62523e4 VA: 0x759886a3e4
	public X509Certificate2Impl Import(X509Certificate cert, CertificateImportFlags importFlags) { }
	// RVA: 0x62524f8 VA: 0x759886a4f8
	public Void .ctor() { }
	// RVA: 0x6252500 VA: 0x759886a500
	private static Void .cctor() { }
}
```