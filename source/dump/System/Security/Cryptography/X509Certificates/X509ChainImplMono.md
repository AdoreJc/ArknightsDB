# X509ChainImplMono

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `StoreLocation location`

- `X509ChainElementCollection elements`

- `X509ChainPolicy policy`

- `Int32 max_path_length`

- `X500DistinguishedName working_issuer_name`

- `AsymmetricAlgorithm working_public_key`

- `X509ChainElement bce_restriction`

- `X509Certificate2Collection roots`

- `X509Certificate2Collection cas`

- `X509Store root_store`

- `X509Store ca_store`

- `X509Store user_root_store`

- `X509Store user_ca_store`

- `X509Certificate2Collection collection`


## Properties

- `X509Certificate2Collection Roots`

- `X509Certificate2Collection CertificateAuthorities`

- `X509Store LMRootStore`

- `X509Store UserRootStore`

- `X509Store LMCAStore`

- `X509Store UserCAStore`

- `X509Certificate2Collection CertificateCollection`


## Methods

- `X509Certificate2Collection get_Roots()`

- `X509Certificate2Collection get_CertificateAuthorities()`

- `X509Store get_LMRootStore()`

- `X509Store get_UserRootStore()`

- `X509Store get_LMCAStore()`

- `X509Store get_UserCAStore()`

- `X509Certificate2Collection get_CertificateCollection()`

- `X509ChainStatusFlags BuildChainFrom(X509Certificate2)`

- `X509Certificate2 SelectBestFromCollection(X509Certificate2, X509Certificate2Collection)`

- `X509Certificate2 FindParent(X509Certificate2)`

- `Boolean IsChainComplete(X509Certificate2)`

- `Boolean IsSelfIssued(X509Certificate2)`

- `Void ValidateChain(X509ChainStatusFlags)`

- `Void Process(Int32)`

- `Void PrepareForNextCertificate(Int32)`

- `Void WrapUp()`

- `Void ProcessCertificateExtensions(X509ChainElement)`

- `Boolean IsSignedWith(X509Certificate2, AsymmetricAlgorithm)`

- `String GetSubjectKeyIdentifier(X509Certificate2)`

- `Void CheckRevocationOnChain(X509ChainStatusFlags)`

- `X509ChainStatusFlags CheckRevocation(X509Certificate2, Int32, Boolean)`

- `X509ChainStatusFlags CheckRevocation(X509Certificate2, X509Certificate2, Boolean)`

- `X509Crl FindCrl(X509Certificate2)`

- `Boolean ProcessCrlExtensions(X509Crl)`

- `Boolean ProcessCrlEntryExtensions(X509CrlEntry)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
internal class X509ChainImplMono : X509ChainImpl
{
	private StoreLocation location; // 0x10
	private X509ChainElementCollection elements; // 0x18
	private X509ChainPolicy policy; // 0x20
	private X509ChainStatus[] status; // 0x28
	private static X509ChainStatus[] Empty; // 0x0
	private Int32 max_path_length; // 0x30
	private X500DistinguishedName working_issuer_name; // 0x38
	private AsymmetricAlgorithm working_public_key; // 0x40
	private X509ChainElement bce_restriction; // 0x48
	private X509Certificate2Collection roots; // 0x50
	private X509Certificate2Collection cas; // 0x58
	private X509Store root_store; // 0x60
	private X509Store ca_store; // 0x68
	private X509Store user_root_store; // 0x70
	private X509Store user_ca_store; // 0x78
	private X509Certificate2Collection collection; // 0x80

	public override Boolean IsValid { get; }
	public override X509ChainElementCollection ChainElements { get; }
	public override X509ChainPolicy ChainPolicy { get; }
	public override X509ChainStatus[] ChainStatus { get; }
	private X509Certificate2Collection Roots { get; }
	private X509Certificate2Collection CertificateAuthorities { get; }
	private X509Store LMRootStore { get; }
	private X509Store UserRootStore { get; }
	private X509Store LMCAStore { get; }
	private X509Store UserCAStore { get; }
	private X509Certificate2Collection CertificateCollection { get; }

	// RVA: 0x63a84fc VA: 0x75989c04fc
	public Void .ctor(Boolean useMachineContext) { }
	// RVA: 0x63a85e4 VA: 0x75989c05e4
	public override Boolean get_IsValid() { }
	// RVA: 0x63a85ec VA: 0x75989c05ec
	public override X509ChainElementCollection get_ChainElements() { }
	// RVA: 0x63a85f4 VA: 0x75989c05f4
	public override X509ChainPolicy get_ChainPolicy() { }
	// RVA: 0x63a85fc VA: 0x75989c05fc
	public override X509ChainStatus[] get_ChainStatus() { }
	// RVA: 0x63a8660 VA: 0x75989c0660
	public override Void AddStatus(X509ChainStatusFlags error) { }
	// RVA: 0x63a8664 VA: 0x75989c0664
	public override Boolean Build(X509Certificate2 certificate) { }
	// RVA: 0x63a8ea0 VA: 0x75989c0ea0
	public override Void Reset() { }
	// RVA: 0x63a9020 VA: 0x75989c1020
	private X509Certificate2Collection get_Roots() { }
	// RVA: 0x63a9380 VA: 0x75989c1380
	private X509Certificate2Collection get_CertificateAuthorities() { }
	// RVA: 0x63a90f0 VA: 0x75989c10f0
	private X509Store get_LMRootStore() { }
	// RVA: 0x63a91f0 VA: 0x75989c11f0
	private X509Store get_UserRootStore() { }
	// RVA: 0x63a9450 VA: 0x75989c1450
	private X509Store get_LMCAStore() { }
	// RVA: 0x63a9550 VA: 0x75989c1550
	private X509Store get_UserCAStore() { }
	// RVA: 0x63a9b94 VA: 0x75989c1b94
	private X509Certificate2Collection get_CertificateCollection() { }
	// RVA: 0x63a8c60 VA: 0x75989c0c60
	private X509ChainStatusFlags BuildChainFrom(X509Certificate2 certificate) { }
	// RVA: 0x63aa0d4 VA: 0x75989c20d4
	private X509Certificate2 SelectBestFromCollection(X509Certificate2 child, X509Certificate2Collection c) { }
	// RVA: 0x63a9ef8 VA: 0x75989c1ef8
	private X509Certificate2 FindParent(X509Certificate2 certificate) { }
	// RVA: 0x63aa00c VA: 0x75989c200c
	private Boolean IsChainComplete(X509Certificate2 certificate) { }
	// RVA: 0x63aa3a4 VA: 0x75989c23a4
	private Boolean IsSelfIssued(X509Certificate2 certificate) { }
	// RVA: 0x63a8d48 VA: 0x75989c0d48
	private Void ValidateChain(X509ChainStatusFlags flag) { }
	// RVA: 0x63aa3ec VA: 0x75989c23ec
	private Void Process(Int32 n) { }
	// RVA: 0x63aa68c VA: 0x75989c268c
	private Void PrepareForNextCertificate(Int32 n) { }
	// RVA: 0x63aaa94 VA: 0x75989c2a94
	private Void WrapUp() { }
	// RVA: 0x63aac24 VA: 0x75989c2c24
	private Void ProcessCertificateExtensions(X509ChainElement element) { }
	// RVA: 0x63aabec VA: 0x75989c2bec
	private Boolean IsSignedWith(X509Certificate2 signed, AsymmetricAlgorithm pubkey) { }
	// RVA: 0x63aa2f4 VA: 0x75989c22f4
	private String GetSubjectKeyIdentifier(X509Certificate2 certificate) { }
	// RVA: 0x63aa260 VA: 0x75989c2260
	private static String GetAuthorityKeyIdentifier(X509Certificate2 certificate) { }
	// RVA: 0x63aae68 VA: 0x75989c2e68
	private static String GetAuthorityKeyIdentifier(X509Crl crl) { }
	// RVA: 0x63aad0c VA: 0x75989c2d0c
	private static String GetAuthorityKeyIdentifier(X509Extension ext) { }
	// RVA: 0x63aa8a4 VA: 0x75989c28a4
	private Void CheckRevocationOnChain(X509ChainStatusFlags flag) { }
	// RVA: 0x63aaef4 VA: 0x75989c2ef4
	private X509ChainStatusFlags CheckRevocation(X509Certificate2 certificate, Int32 ca, Boolean online) { }
	// RVA: 0x63aafc0 VA: 0x75989c2fc0
	private X509ChainStatusFlags CheckRevocation(X509Certificate2 certificate, X509Certificate2 ca_cert, Boolean online) { }
	// RVA: 0x63ab958 VA: 0x75989c3958
	private static X509Crl CheckCrls(String subject, String ski, X509Store store) { }
	// RVA: 0x63ab18c VA: 0x75989c318c
	private X509Crl FindCrl(X509Certificate2 caCertificate) { }
	// RVA: 0x63ab610 VA: 0x75989c3610
	private Boolean ProcessCrlExtensions(X509Crl crl) { }
	// RVA: 0x63ab300 VA: 0x75989c3300
	private Boolean ProcessCrlEntryExtensions(X509CrlEntry entry) { }
	// RVA: 0x63abcec VA: 0x75989c3cec
	private static Void .cctor() { }
}
```