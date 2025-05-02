# ContentInfo

**Namespace:** ` `


## Fields

- `String contentType`

- `ASN1 content`


## Properties

- `ASN1 ASN1`

- `ASN1 Content`

- `String ContentType`


## Methods

- `ASN1 get_ASN1()`

- `ASN1 get_Content()`

- `Void set_Content(ASN1)`

- `String get_ContentType()`

- `Void set_ContentType(String)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class ContentInfo
{
	private String contentType; // 0x10
	private ASN1 content; // 0x18

	public ASN1 ASN1 { get; }
	public ASN1 Content { get; set; }
	public String ContentType { get; set; }

	// RVA: 0x5ed5314 VA: 0x75984ed314
	public Void .ctor() { }
	// RVA: 0x5ed53a0 VA: 0x75984ed3a0
	public Void .ctor(String oid) { }
	// RVA: 0x5ed53cc VA: 0x75984ed3cc
	public Void .ctor(Byte[] data) { }
	// RVA: 0x5ed543c VA: 0x75984ed43c
	public Void .ctor(ASN1 asn1) { }
	// RVA: 0x5ed55e4 VA: 0x75984ed5e4
	public ASN1 get_ASN1() { }
	// RVA: 0x5ed56a8 VA: 0x75984ed6a8
	public ASN1 get_Content() { }
	// RVA: 0x5ed56b0 VA: 0x75984ed6b0
	public Void set_Content(ASN1 value) { }
	// RVA: 0x5ed56b8 VA: 0x75984ed6b8
	public String get_ContentType() { }
	// RVA: 0x5ed56c0 VA: 0x75984ed6c0
	public Void set_ContentType(String value) { }
	// RVA: 0x5ed55e8 VA: 0x75984ed5e8
	internal ASN1 GetASN1() { }
}
```