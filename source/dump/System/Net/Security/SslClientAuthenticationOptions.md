# SslClientAuthenticationOptions

**Namespace:** `System.Net.Security`


## Fields

- `EncryptionPolicy _encryptionPolicy`

- `X509RevocationMode _checkCertificateRevocation`

- `SslProtocols _enabledSslProtocols`

- `Boolean _allowRenegotiation`

- `String <TargetHost>k__BackingField`

- `X509CertificateCollection <ClientCertificates>k__BackingField`


## Properties

- `String TargetHost`

- `X509CertificateCollection ClientCertificates`

- `X509RevocationMode CertificateRevocationCheckMode`

- `EncryptionPolicy EncryptionPolicy`

- `SslProtocols EnabledSslProtocols`


## Methods

- `String get_TargetHost()`

- `Void set_TargetHost(String)`

- `X509CertificateCollection get_ClientCertificates()`

- `Void set_ClientCertificates(X509CertificateCollection)`

- `Void set_CertificateRevocationCheckMode(X509RevocationMode)`

- `Void set_EncryptionPolicy(EncryptionPolicy)`

- `SslProtocols get_EnabledSslProtocols()`

- `Void set_EnabledSslProtocols(SslProtocols)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Security
public class SslClientAuthenticationOptions
{
	private EncryptionPolicy _encryptionPolicy; // 0x10
	private X509RevocationMode _checkCertificateRevocation; // 0x14
	private SslProtocols _enabledSslProtocols; // 0x18
	private Boolean _allowRenegotiation; // 0x1c
	private String <TargetHost>k__BackingField; // 0x20
	private X509CertificateCollection <ClientCertificates>k__BackingField; // 0x28

	public String TargetHost { get; set; }
	public X509CertificateCollection ClientCertificates { get; set; }
	public X509RevocationMode CertificateRevocationCheckMode { set; }
	public EncryptionPolicy EncryptionPolicy { set; }
	public SslProtocols EnabledSslProtocols { get; set; }

	// RVA: 0x63627f4 VA: 0x759897a7f4
	public String get_TargetHost() { }
	// RVA: 0x63627fc VA: 0x759897a7fc
	public Void set_TargetHost(String value) { }
	// RVA: 0x6362804 VA: 0x759897a804
	public X509CertificateCollection get_ClientCertificates() { }
	// RVA: 0x636280c VA: 0x759897a80c
	public Void set_ClientCertificates(X509CertificateCollection value) { }
	// RVA: 0x6362814 VA: 0x759897a814
	public Void set_CertificateRevocationCheckMode(X509RevocationMode value) { }
	// RVA: 0x63628b4 VA: 0x759897a8b4
	public Void set_EncryptionPolicy(EncryptionPolicy value) { }
	// RVA: 0x6362954 VA: 0x759897a954
	public SslProtocols get_EnabledSslProtocols() { }
	// RVA: 0x636295c VA: 0x759897a95c
	public Void set_EnabledSslProtocols(SslProtocols value) { }
	// RVA: 0x6362964 VA: 0x759897a964
	public Void .ctor() { }
}
```