# ASN1

**Namespace:** `Mono.Security`


## Fields

- `Byte m_nTag`

- `ArrayList elist`


## Properties

- `Int32 Count`

- `Byte Tag`

- `Int32 Length`

- `ASN1 Item`


## Methods

- `Int32 get_Count()`

- `Byte get_Tag()`

- `Int32 get_Length()`

- `Void set_Value(Byte[])`

- `Boolean CompareArray(Byte[], Byte[])`

- `Boolean CompareValue(Byte[])`

- `ASN1 Add(ASN1)`

- `Void Decode(Byte[], ref, Int32)`

- `Void DecodeTLV(Byte[], ref, out, out, out)`

- `ASN1 get_Item(Int32)`

- `ASN1 Element(Int32, Byte)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security
public class ASN1
{
	private Byte m_nTag; // 0x10
	private Byte[] m_aValue; // 0x18
	private ArrayList elist; // 0x20

	public Int32 Count { get; }
	public Byte Tag { get; }
	public Int32 Length { get; }
	public Byte[] Value { get; set; }
	public ASN1 Item { get; }

	// RVA: 0x5ed2e34 VA: 0x75984eae34
	public Void .ctor(Byte tag) { }
	// RVA: 0x5ed2e68 VA: 0x75984eae68
	public Void .ctor(Byte tag, Byte[] data) { }
	// RVA: 0x5ed2ea0 VA: 0x75984eaea0
	public Void .ctor(Byte[] data) { }
	// RVA: 0x5ed3160 VA: 0x75984eb160
	public Int32 get_Count() { }
	// RVA: 0x5ed317c VA: 0x75984eb17c
	public Byte get_Tag() { }
	// RVA: 0x5ed3184 VA: 0x75984eb184
	public Int32 get_Length() { }
	// RVA: 0x5ed319c VA: 0x75984eb19c
	public Byte[] get_Value() { }
	// RVA: 0x5ed322c VA: 0x75984eb22c
	public Void set_Value(Byte[] value) { }
	// RVA: 0x5ed32e8 VA: 0x75984eb2e8
	private Boolean CompareArray(Byte[] array1, Byte[] array2) { }
	// RVA: 0x5ed335c VA: 0x75984eb35c
	public Boolean CompareValue(Byte[] value) { }
	// RVA: 0x5ed336c VA: 0x75984eb36c
	public ASN1 Add(ASN1 asn1) { }
	// RVA: 0x5ed3408 VA: 0x75984eb408
	public virtual Byte[] GetBytes() { }
	// RVA: 0x5ed3030 VA: 0x75984eb030
	protected Void Decode(Byte[] asn1, ref Int32 anPos, Int32 anLength) { }
	// RVA: 0x5ed3aac VA: 0x75984ebaac
	protected Void DecodeTLV(Byte[] asn1, ref Int32 pos, out Byte tag, out Int32 length, out Byte[] content) { }
	// RVA: 0x5ed3bdc VA: 0x75984ebbdc
	public ASN1 get_Item(Int32 index) { }
	// RVA: 0x5ed3d0c VA: 0x75984ebd0c
	public ASN1 Element(Int32 index, Byte anTag) { }
	// RVA: 0x5ed3e60 VA: 0x75984ebe60
	public override String ToString() { }
}
```