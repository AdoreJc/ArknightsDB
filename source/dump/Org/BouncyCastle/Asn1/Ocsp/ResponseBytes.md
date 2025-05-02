# ResponseBytes

**Namespace:** `Org.BouncyCastle.Asn1.Ocsp`


## Properties

- `DerObjectIdentifier ResponseType`

- `Asn1OctetString Response`


## Methods

- `DerObjectIdentifier get_ResponseType()`

- `Asn1OctetString get_Response()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Ocsp
public class ResponseBytes : Asn1Encodable
{
	private readonly DerObjectIdentifier responseType; // 0x10
	private readonly Asn1OctetString response; // 0x18

	public DerObjectIdentifier ResponseType { get; }
	public Asn1OctetString Response { get; }

	// RVA: 0x65d9330 VA: 0x7598bf1330
	public static ResponseBytes GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65d9a60 VA: 0x7598bf1a60
	public static ResponseBytes GetInstance(Object obj) { }
	// RVA: 0x65d9d2c VA: 0x7598bf1d2c
	public Void .ctor(DerObjectIdentifier responseType, Asn1OctetString response) { }
	// RVA: 0x65d9be8 VA: 0x7598bf1be8
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65d9de8 VA: 0x7598bf1de8
	public DerObjectIdentifier get_ResponseType() { }
	// RVA: 0x65d9df0 VA: 0x7598bf1df0
	public Asn1OctetString get_Response() { }
	// RVA: 0x65d9df8 VA: 0x7598bf1df8
	public override Asn1Object ToAsn1Object() { }
}
```