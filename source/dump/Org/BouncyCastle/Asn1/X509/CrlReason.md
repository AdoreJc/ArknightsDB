# CrlReason

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class CrlReason : DerEnumerated
{
	public const Int32 Unspecified; // 0x0
	public const Int32 KeyCompromise; // 0x0
	public const Int32 CACompromise; // 0x0
	public const Int32 AffiliationChanged; // 0x0
	public const Int32 Superseded; // 0x0
	public const Int32 CessationOfOperation; // 0x0
	public const Int32 CertificateHold; // 0x0
	public const Int32 RemoveFromCrl; // 0x0
	public const Int32 PrivilegeWithdrawn; // 0x0
	public const Int32 AACompromise; // 0x0
	private static readonly String[] ReasonString; // 0x0


	// RVA: 0x65b0fc8 VA: 0x7598bc8fc8
	public Void .ctor(Int32 reason) { }
	// RVA: 0x65b1030 VA: 0x7598bc9030
	public Void .ctor(DerEnumerated reason) { }
	// RVA: 0x65b10b0 VA: 0x7598bc90b0
	public override String ToString() { }
	// RVA: 0x65b1188 VA: 0x7598bc9188
	private static Void .cctor() { }
}
```