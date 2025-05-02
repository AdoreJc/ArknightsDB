# SignedData

**Namespace:** `Org.BouncyCastle.Asn1.Pkcs`


## Properties

- `DerInteger Version`

- `Asn1Set DigestAlgorithms`

- `ContentInfo ContentInfo`

- `Asn1Set Certificates`

- `Asn1Set Crls`

- `Asn1Set SignerInfos`


## Methods

- `DerInteger get_Version()`

- `Asn1Set get_DigestAlgorithms()`

- `ContentInfo get_ContentInfo()`

- `Asn1Set get_Certificates()`

- `Asn1Set get_Crls()`

- `Asn1Set get_SignerInfos()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Pkcs
public class SignedData : Asn1Encodable
{
	private readonly DerInteger version; // 0x10
	private readonly Asn1Set digestAlgorithms; // 0x18
	private readonly ContentInfo contentInfo; // 0x20
	private readonly Asn1Set certificates; // 0x28
	private readonly Asn1Set crls; // 0x30
	private readonly Asn1Set signerInfos; // 0x38

	public DerInteger Version { get; }
	public Asn1Set DigestAlgorithms { get; }
	public ContentInfo ContentInfo { get; }
	public Asn1Set Certificates { get; }
	public Asn1Set Crls { get; }
	public Asn1Set SignerInfos { get; }

	// RVA: 0x65d7dd8 VA: 0x7598befdd8
	public static SignedData GetInstance(Object obj) { }
	// RVA: 0x65d84b4 VA: 0x7598bf04b4
	public Void .ctor(DerInteger _version, Asn1Set _digestAlgorithms, ContentInfo _contentInfo, Asn1Set _certificates, Asn1Set _crls, Asn1Set _signerInfos) { }
	// RVA: 0x65d7e7c VA: 0x7598befe7c
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65d8558 VA: 0x7598bf0558
	public DerInteger get_Version() { }
	// RVA: 0x65d8560 VA: 0x7598bf0560
	public Asn1Set get_DigestAlgorithms() { }
	// RVA: 0x65d8568 VA: 0x7598bf0568
	public ContentInfo get_ContentInfo() { }
	// RVA: 0x65d8570 VA: 0x7598bf0570
	public Asn1Set get_Certificates() { }
	// RVA: 0x65d8578 VA: 0x7598bf0578
	public Asn1Set get_Crls() { }
	// RVA: 0x65d8580 VA: 0x7598bf0580
	public Asn1Set get_SignerInfos() { }
	// RVA: 0x65d8588 VA: 0x7598bf0588
	public override Asn1Object ToAsn1Object() { }
}
```