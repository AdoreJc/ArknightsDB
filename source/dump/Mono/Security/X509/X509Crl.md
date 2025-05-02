# X509Crl

**Namespace:** `Mono.Security.X509`


## Fields

- `String issuer`

- `Byte version`

- `DateTime thisUpdate`

- `DateTime nextUpdate`

- `ArrayList entries`

- `String signatureOID`

- `X509ExtensionCollection extensions`


## Properties

- `X509ExtensionCollection Extensions`

- `String IssuerName`

- `DateTime NextUpdate`


## Methods

- `Void Parse(Byte[])`

- `X509ExtensionCollection get_Extensions()`

- `String get_IssuerName()`

- `DateTime get_NextUpdate()`

- `Boolean Compare(Byte[], Byte[])`

- `X509CrlEntry GetCrlEntry(X509Certificate)`

- `X509CrlEntry GetCrlEntry(Byte[])`

- `Boolean VerifySignature(AsymmetricAlgorithm)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public class X509Crl
{
	private String issuer; // 0x10
	private Byte version; // 0x18
	private DateTime thisUpdate; // 0x20
	private DateTime nextUpdate; // 0x28
	private ArrayList entries; // 0x30
	private String signatureOID; // 0x38
	private Byte[] signature; // 0x40
	private X509ExtensionCollection extensions; // 0x48
	private Byte[] encoded; // 0x50
	private Byte[] hash_value; // 0x58

	public X509ExtensionCollection Extensions { get; }
	public Byte[] Hash { get; }
	public String IssuerName { get; }
	public DateTime NextUpdate { get; }

	// RVA: 0x5edf178 VA: 0x75984f7178
	public Void .ctor(Byte[] crl) { }
	// RVA: 0x5edf298 VA: 0x75984f7298
	private Void Parse(Byte[] crl) { }
	// RVA: 0x5edfbdc VA: 0x75984f7bdc
	public X509ExtensionCollection get_Extensions() { }
	// RVA: 0x5edfbe4 VA: 0x75984f7be4
	public Byte[] get_Hash() { }
	// RVA: 0x5edfe08 VA: 0x75984f7e08
	public String get_IssuerName() { }
	// RVA: 0x5edfe10 VA: 0x75984f7e10
	public DateTime get_NextUpdate() { }
	// RVA: 0x5edfe18 VA: 0x75984f7e18
	private Boolean Compare(Byte[] array1, Byte[] array2) { }
	// RVA: 0x5edfe94 VA: 0x75984f7e94
	public X509CrlEntry GetCrlEntry(X509Certificate x509) { }
	// RVA: 0x5edff14 VA: 0x75984f7f14
	public X509CrlEntry GetCrlEntry(Byte[] serialNumber) { }
	// RVA: 0x5ee00d4 VA: 0x75984f80d4
	internal Boolean VerifySignature(DSA dsa) { }
	// RVA: 0x5ee03a0 VA: 0x75984f83a0
	internal Boolean VerifySignature(RSA rsa) { }
	// RVA: 0x5ee0474 VA: 0x75984f8474
	public Boolean VerifySignature(AsymmetricAlgorithm aa) { }
}
```