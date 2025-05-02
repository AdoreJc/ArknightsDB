# CertificateStatus

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class CertificateStatus
{
	protected readonly Byte mStatusType; // 0x10
	protected readonly Object mResponse; // 0x18

	public virtual Byte StatusType { get; }
	public virtual Object Response { get; }

	// RVA: 0x64dd3e4 VA: 0x7598af53e4
	public Void .ctor(Byte statusType, Object response) { }
	// RVA: 0x64dd574 VA: 0x7598af5574
	public virtual Byte get_StatusType() { }
	// RVA: 0x64dd57c VA: 0x7598af557c
	public virtual Object get_Response() { }
	// RVA: 0x64dd584 VA: 0x7598af5584
	public virtual OcspResponse GetOcspResponse() { }
	// RVA: 0x64dd658 VA: 0x7598af5658
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64dd7a4 VA: 0x7598af57a4
	public static CertificateStatus Parse(Stream input) { }
	// RVA: 0x64dd48c VA: 0x7598af548c
	protected static Boolean IsCorrectType(Byte statusType, Object response) { }
}
```