# GeneralNames

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class GeneralNames : Asn1Encodable
{
	private readonly GeneralName[] names; // 0x10


	// RVA: 0x65b41b0 VA: 0x7598bcc1b0
	public static GeneralNames GetInstance(Object obj) { }
	// RVA: 0x65b1ca4 VA: 0x7598bc9ca4
	public static GeneralNames GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b4470 VA: 0x7598bcc470
	public Void .ctor(GeneralName name) { }
	// RVA: 0x65b452c VA: 0x7598bcc52c
	public Void .ctor(GeneralName[] names) { }
	// RVA: 0x65b4338 VA: 0x7598bcc338
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65b45e8 VA: 0x7598bcc5e8
	public GeneralName[] GetNames() { }
	// RVA: 0x65b4660 VA: 0x7598bcc660
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65b46c8 VA: 0x7598bcc6c8
	public override String ToString() { }
}
```