# KeyUsage

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class KeyUsage : DerBitString
{
	public const Int32 DigitalSignature; // 0x0
	public const Int32 NonRepudiation; // 0x0
	public const Int32 KeyEncipherment; // 0x0
	public const Int32 DataEncipherment; // 0x0
	public const Int32 KeyAgreement; // 0x0
	public const Int32 KeyCertSign; // 0x0
	public const Int32 CrlSign; // 0x0
	public const Int32 EncipherOnly; // 0x0
	public const Int32 DecipherOnly; // 0x0


	// RVA: 0x65b55e0 VA: 0x7598bcd5e0
	public static KeyUsage GetInstance(Object obj) { }
	// RVA: 0x65b5788 VA: 0x7598bcd788
	public Void .ctor(Int32 usage) { }
	// RVA: 0x65b56f4 VA: 0x7598bcd6f4
	private Void .ctor(DerBitString usage) { }
	// RVA: 0x65b57f0 VA: 0x7598bcd7f0
	public override String ToString() { }
}
```