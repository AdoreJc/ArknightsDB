# BerTaggedObjectParser

**Namespace:** `Org.BouncyCastle.Asn1`


## Fields

- `Boolean _constructed`

- `Int32 _tagNumber`

- `Asn1StreamParser _parser`


## Properties

- `Boolean IsConstructed`

- `Int32 TagNo`


## Methods

- `Boolean get_IsConstructed()`

- `Int32 get_TagNo()`

- `IAsn1Convertible GetObjectParser(Int32, Boolean)`

- `Asn1Object ToAsn1Object()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class BerTaggedObjectParser : Asn1TaggedObjectParser, IAsn1Convertible
{
	private Boolean _constructed; // 0x10
	private Int32 _tagNumber; // 0x14
	private Asn1StreamParser _parser; // 0x18

	public Boolean IsConstructed { get; }
	public Int32 TagNo { get; }

	// RVA: 0x6599b88 VA: 0x7598bb1b88
	internal Void .ctor(Int32 baseTag, Int32 tagNumber, Stream contentStream) { }
	// RVA: 0x658fc4c VA: 0x7598ba7c4c
	internal Void .ctor(Boolean constructed, Int32 tagNumber, Asn1StreamParser parser) { }
	// RVA: 0x6599c34 VA: 0x7598bb1c34
	public Boolean get_IsConstructed() { }
	// RVA: 0x6599c3c VA: 0x7598bb1c3c
	public Int32 get_TagNo() { }
	// RVA: 0x6599c44 VA: 0x7598bb1c44
	public IAsn1Convertible GetObjectParser(Int32 tag, Boolean isExplicit) { }
	// RVA: 0x658fc94 VA: 0x7598ba7c94
	public Asn1Object ToAsn1Object() { }
}
```