# Certificate

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class Certificate
{
	public static readonly Certificate EmptyChain; // 0x0
	protected readonly X509CertificateStructure[] mCertificateList; // 0x10

	public virtual Int32 Length { get; }
	public virtual Boolean IsEmpty { get; }

	// RVA: 0x64dbc28 VA: 0x7598af3c28
	public Void .ctor(X509CertificateStructure[] certificateList) { }
	// RVA: 0x64dbca8 VA: 0x7598af3ca8
	public virtual X509CertificateStructure[] GetCertificateList() { }
	// RVA: 0x64dbcb4 VA: 0x7598af3cb4
	public virtual X509CertificateStructure GetCertificateAt(Int32 index) { }
	// RVA: 0x64dbce4 VA: 0x7598af3ce4
	public virtual Int32 get_Length() { }
	// RVA: 0x64dbd00 VA: 0x7598af3d00
	public virtual Boolean get_IsEmpty() { }
	// RVA: 0x64dbd24 VA: 0x7598af3d24
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64dc1e0 VA: 0x7598af41e0
	public static Certificate Parse(Stream input) { }
	// RVA: 0x64dc644 VA: 0x7598af4644
	protected virtual X509CertificateStructure[] CloneCertificateList() { }
	// RVA: 0x64dc6bc VA: 0x7598af46bc
	private static Void .cctor() { }
}
```