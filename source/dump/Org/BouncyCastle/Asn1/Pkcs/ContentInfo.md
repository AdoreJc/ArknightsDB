# ContentInfo

**Namespace:** `Org.BouncyCastle.Asn1.Pkcs`


## Properties

- `DerObjectIdentifier ContentType`

- `Asn1Encodable Content`


## Methods

- `DerObjectIdentifier get_ContentType()`

- `Asn1Encodable get_Content()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Pkcs
public class ContentInfo : Asn1Encodable
{
	private readonly DerObjectIdentifier contentType; // 0x10
	private readonly Asn1Encodable content; // 0x18

	public DerObjectIdentifier ContentType { get; }
	public Asn1Encodable Content { get; }

	// RVA: 0x65d46fc VA: 0x7598bec6fc
	public static ContentInfo GetInstance(Object obj) { }
	// RVA: 0x65d47a0 VA: 0x7598bec7a0
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65d4914 VA: 0x7598bec914
	public Void .ctor(DerObjectIdentifier contentType, Asn1Encodable content) { }
	// RVA: 0x65d4958 VA: 0x7598bec958
	public DerObjectIdentifier get_ContentType() { }
	// RVA: 0x65d4960 VA: 0x7598bec960
	public Asn1Encodable get_Content() { }
	// RVA: 0x65d4968 VA: 0x7598bec968
	public override Asn1Object ToAsn1Object() { }
}
```