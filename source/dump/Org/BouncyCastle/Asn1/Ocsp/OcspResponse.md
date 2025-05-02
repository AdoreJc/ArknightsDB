# OcspResponse

**Namespace:** `Org.BouncyCastle.Asn1.Ocsp`


## Properties

- `OcspResponseStatus ResponseStatus`

- `ResponseBytes ResponseBytes`


## Methods

- `OcspResponseStatus get_ResponseStatus()`

- `ResponseBytes get_ResponseBytes()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Ocsp
public class OcspResponse : Asn1Encodable
{
	private readonly OcspResponseStatus responseStatus; // 0x10
	private readonly ResponseBytes responseBytes; // 0x18

	public OcspResponseStatus ResponseStatus { get; }
	public ResponseBytes ResponseBytes { get; }

	// RVA: 0x65d8efc VA: 0x7598bf0efc
	public static OcspResponse GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65d8f14 VA: 0x7598bf0f14
	public static OcspResponse GetInstance(Object obj) { }
	// RVA: 0x65d921c VA: 0x7598bf121c
	public Void .ctor(OcspResponseStatus responseStatus, ResponseBytes responseBytes) { }
	// RVA: 0x65d909c VA: 0x7598bf109c
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65d9348 VA: 0x7598bf1348
	public OcspResponseStatus get_ResponseStatus() { }
	// RVA: 0x65d9350 VA: 0x7598bf1350
	public ResponseBytes get_ResponseBytes() { }
	// RVA: 0x65d9358 VA: 0x7598bf1358
	public override Asn1Object ToAsn1Object() { }
}
```