# CertificateStatusRequest

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class CertificateStatusRequest
{
	protected readonly Byte mStatusType; // 0x10
	protected readonly Object mRequest; // 0x18

	public virtual Byte StatusType { get; }
	public virtual Object Request { get; }

	// RVA: 0x64dd8b4 VA: 0x7598af58b4
	public Void .ctor(Byte statusType, Object request) { }
	// RVA: 0x64dda44 VA: 0x7598af5a44
	public virtual Byte get_StatusType() { }
	// RVA: 0x64dda4c VA: 0x7598af5a4c
	public virtual Object get_Request() { }
	// RVA: 0x64dda54 VA: 0x7598af5a54
	public virtual OcspStatusRequest GetOcspStatusRequest() { }
	// RVA: 0x64ddb28 VA: 0x7598af5b28
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64ddc60 VA: 0x7598af5c60
	public static CertificateStatusRequest Parse(Stream input) { }
	// RVA: 0x64dd95c VA: 0x7598af595c
	protected static Boolean IsCorrectType(Byte statusType, Object request) { }
}
```