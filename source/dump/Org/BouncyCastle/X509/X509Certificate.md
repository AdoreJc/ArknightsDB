# X509Certificate

**Namespace:** `Org.BouncyCastle.X509`


## Fields

- `Boolean hashValueSet`

- `Int32 hashValue`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.X509
public class X509Certificate : X509ExtensionBase
{
	private readonly X509CertificateStructure c; // 0x10
	private readonly BasicConstraints basicConstraints; // 0x18
	private readonly Boolean[] keyUsage; // 0x20
	private Boolean hashValueSet; // 0x28
	private Int32 hashValue; // 0x2c

	public virtual X509CertificateStructure CertificateStructure { get; }
	public virtual Boolean IsValidNow { get; }
	public virtual Int32 Version { get; }
	public virtual BigInteger SerialNumber { get; }
	public virtual X509Name IssuerDN { get; }
	public virtual X509Name SubjectDN { get; }
	public virtual DateTime NotBefore { get; }
	public virtual DateTime NotAfter { get; }
	public virtual String SigAlgName { get; }
	public virtual String SigAlgOid { get; }
	public virtual DerBitString IssuerUniqueID { get; }
	public virtual DerBitString SubjectUniqueID { get; }

	// RVA: 0x66e064c VA: 0x7598cf864c
	protected Void .ctor() { }
	// RVA: 0x66e065c VA: 0x7598cf865c
	public Void .ctor(X509CertificateStructure c) { }
	// RVA: 0x66e0aa8 VA: 0x7598cf8aa8
	public virtual X509CertificateStructure get_CertificateStructure() { }
	// RVA: 0x66e0ab0 VA: 0x7598cf8ab0
	public virtual Boolean get_IsValidNow() { }
	// RVA: 0x66e0b1c VA: 0x7598cf8b1c
	public virtual Boolean IsValid(DateTime time) { }
	// RVA: 0x66e0bf4 VA: 0x7598cf8bf4
	public virtual Void CheckValidity() { }
	// RVA: 0x66e0c60 VA: 0x7598cf8c60
	public virtual Void CheckValidity(DateTime time) { }
	// RVA: 0x66e0e34 VA: 0x7598cf8e34
	public virtual Int32 get_Version() { }
	// RVA: 0x66e0e50 VA: 0x7598cf8e50
	public virtual BigInteger get_SerialNumber() { }
	// RVA: 0x66e0e78 VA: 0x7598cf8e78
	public virtual X509Name get_IssuerDN() { }
	// RVA: 0x66e0e94 VA: 0x7598cf8e94
	public virtual X509Name get_SubjectDN() { }
	// RVA: 0x66e0eb0 VA: 0x7598cf8eb0
	public virtual DateTime get_NotBefore() { }
	// RVA: 0x66e0ed8 VA: 0x7598cf8ed8
	public virtual DateTime get_NotAfter() { }
	// RVA: 0x66e0f00 VA: 0x7598cf8f00
	public virtual Byte[] GetTbsCertificate() { }
	// RVA: 0x66e0f24 VA: 0x7598cf8f24
	public virtual Byte[] GetSignature() { }
	// RVA: 0x66e0f40 VA: 0x7598cf8f40
	public virtual String get_SigAlgName() { }
	// RVA: 0x66e0fc0 VA: 0x7598cf8fc0
	public virtual String get_SigAlgOid() { }
	// RVA: 0x66e0ff4 VA: 0x7598cf8ff4
	public virtual Byte[] GetSigAlgParams() { }
	// RVA: 0x66e1054 VA: 0x7598cf9054
	public virtual DerBitString get_IssuerUniqueID() { }
	// RVA: 0x66e1078 VA: 0x7598cf9078
	public virtual DerBitString get_SubjectUniqueID() { }
	// RVA: 0x66e109c VA: 0x7598cf909c
	public virtual Boolean[] GetKeyUsage() { }
	// RVA: 0x66e1110 VA: 0x7598cf9110
	public virtual IList GetExtendedKeyUsage() { }
	// RVA: 0x66e1634 VA: 0x7598cf9634
	public virtual Int32 GetBasicConstraints() { }
	// RVA: 0x66e169c VA: 0x7598cf969c
	public virtual ICollection GetSubjectAlternativeNames() { }
	// RVA: 0x66e16f0 VA: 0x7598cf96f0
	public virtual ICollection GetIssuerAlternativeNames() { }
	// RVA: 0x66e1744 VA: 0x7598cf9744
	protected virtual ICollection GetAlternativeNames(String oid) { }
	// RVA: 0x66e1a14 VA: 0x7598cf9a14
	protected override X509Extensions GetX509Extensions() { }
	// RVA: 0x66e1a58 VA: 0x7598cf9a58
	public virtual AsymmetricKeyParameter GetPublicKey() { }
	// RVA: 0x66e1a7c VA: 0x7598cf9a7c
	public virtual Byte[] GetEncoded() { }
	// RVA: 0x66e1a98 VA: 0x7598cf9a98
	public override Boolean Equals(Object obj) { }
	// RVA: 0x66e1b4c VA: 0x7598cf9b4c
	public override Int32 GetHashCode() { }
	// RVA: 0x66e1c50 VA: 0x7598cf9c50
	public override String ToString() { }
	// RVA: 0x66e29bc VA: 0x7598cfa9bc
	public virtual Void Verify(AsymmetricKeyParameter key) { }
	// RVA: 0x66e2a4c VA: 0x7598cfaa4c
	public virtual Void Verify(IVerifierFactoryProvider verifierProvider) { }
	// RVA: 0x66e2b14 VA: 0x7598cfab14
	protected virtual Void CheckSignature(IVerifierFactory verifier) { }
	// RVA: 0x66e2ee8 VA: 0x7598cfaee8
	private static Boolean IsAlgIDEqual(AlgorithmIdentifier id1, AlgorithmIdentifier id2) { }
}
```