# X509Crl

**Namespace:** `Org.BouncyCastle.X509`


## Methods

- `ISet LoadCrlEntries()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.X509
public class X509Crl : X509ExtensionBase
{
	private readonly CertificateList c; // 0x10
	private readonly String sigAlgName; // 0x18
	private readonly Byte[] sigAlgParams; // 0x20
	private readonly Boolean isIndirect; // 0x28

	public virtual Int32 Version { get; }
	public virtual X509Name IssuerDN { get; }
	public virtual DateTime ThisUpdate { get; }
	public virtual DateTimeObject NextUpdate { get; }
	public virtual String SigAlgName { get; }
	public virtual String SigAlgOid { get; }
	protected virtual Boolean IsIndirectCrl { get; }

	// RVA: 0x66e3a14 VA: 0x7598cfba14
	public Void .ctor(CertificateList c) { }
	// RVA: 0x66e3ef4 VA: 0x7598cfbef4
	protected override X509Extensions GetX509Extensions() { }
	// RVA: 0x66e3f38 VA: 0x7598cfbf38
	public virtual Byte[] GetEncoded() { }
	// RVA: 0x66e4030 VA: 0x7598cfc030
	public virtual Void Verify(AsymmetricKeyParameter publicKey) { }
	// RVA: 0x66e40b0 VA: 0x7598cfc0b0
	public virtual Void Verify(IVerifierFactoryProvider verifierProvider) { }
	// RVA: 0x66e4178 VA: 0x7598cfc178
	protected virtual Void CheckSignature(IVerifierFactory verifier) { }
	// RVA: 0x66e4558 VA: 0x7598cfc558
	public virtual Int32 get_Version() { }
	// RVA: 0x66e4574 VA: 0x7598cfc574
	public virtual X509Name get_IssuerDN() { }
	// RVA: 0x66e4590 VA: 0x7598cfc590
	public virtual DateTime get_ThisUpdate() { }
	// RVA: 0x66e45b8 VA: 0x7598cfc5b8
	public virtual DateTimeObject get_NextUpdate() { }
	// RVA: 0x66e465c VA: 0x7598cfc65c
	private ISet LoadCrlEntries() { }
	// RVA: 0x66e4b24 VA: 0x7598cfcb24
	public virtual X509CrlEntry GetRevokedCertificate(BigInteger serialNumber) { }
	// RVA: 0x66e4f50 VA: 0x7598cfcf50
	public virtual ISet GetRevokedCertificates() { }
	// RVA: 0x66e5008 VA: 0x7598cfd008
	public virtual Byte[] GetTbsCertList() { }
	// RVA: 0x66e5110 VA: 0x7598cfd110
	public virtual Byte[] GetSignature() { }
	// RVA: 0x66e512c VA: 0x7598cfd12c
	public virtual String get_SigAlgName() { }
	// RVA: 0x66e5134 VA: 0x7598cfd134
	public virtual String get_SigAlgOid() { }
	// RVA: 0x66e5168 VA: 0x7598cfd168
	public virtual Byte[] GetSigAlgParams() { }
	// RVA: 0x66e51e8 VA: 0x7598cfd1e8
	public override Boolean Equals(Object obj) { }
	// RVA: 0x66e529c VA: 0x7598cfd29c
	public override Int32 GetHashCode() { }
	// RVA: 0x66e52bc VA: 0x7598cfd2bc
	public override String ToString() { }
	// RVA: 0x66e62c8 VA: 0x7598cfe2c8
	public virtual Boolean IsRevoked(X509Certificate cert) { }
	// RVA: 0x66e638c VA: 0x7598cfe38c
	protected virtual Boolean get_IsIndirectCrl() { }
}
```