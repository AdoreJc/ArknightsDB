# DerSequenceReader

**Namespace:** `System.Security.Cryptography`


## Fields

- `Int32 _position`

- `Int32 <ContentLength>k__BackingField`


## Properties

- `Int32 ContentLength`


## Methods

- `Void set_ContentLength(Int32)`

- `DerSequenceReader ReadCollectionWithTag(DerTag)`

- `DateTime ReadTime(DerTag, String)`

- `Void EatTag(DerTag)`

- `Int32 EatLength()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography
internal class DerSequenceReader
{
	internal static DateTimeFormatInfo s_validityDateTimeFormatInfo; // 0x0
	private static Encoding s_utf8EncodingWithExceptionFallback; // 0x8
	private static Encoding s_latin1Encoding; // 0x10
	private readonly Byte[] _data; // 0x10
	private readonly Int32 _end; // 0x18
	private Int32 _position; // 0x1c
	private Int32 <ContentLength>k__BackingField; // 0x20

	private Int32 ContentLength { set; }
	internal Boolean HasData { get; }

	// RVA: 0x639ab64 VA: 0x75989b2b64
	private Void set_ContentLength(Int32 value) { }
	// RVA: 0x639ab6c VA: 0x75989b2b6c
	internal Void .ctor(Byte[] data) { }
	// RVA: 0x639ab90 VA: 0x75989b2b90
	internal Void .ctor(Byte[] data, Int32 offset, Int32 length) { }
	// RVA: 0x639aba4 VA: 0x75989b2ba4
	private Void .ctor(DerTag tagToEat, Byte[] data, Int32 offset, Int32 length) { }
	// RVA: 0x639ad64 VA: 0x75989b2d64
	internal Boolean get_HasData() { }
	// RVA: 0x639ad74 VA: 0x75989b2d74
	internal Byte PeekTag() { }
	// RVA: 0x639ae0c VA: 0x75989b2e0c
	internal Void SkipValue() { }
	// RVA: 0x639ae5c VA: 0x75989b2e5c
	internal Byte[] ReadNextEncodedValue() { }
	// RVA: 0x639b034 VA: 0x75989b3034
	internal Boolean ReadBoolean() { }
	// RVA: 0x639b100 VA: 0x75989b3100
	internal Int32 ReadInteger() { }
	// RVA: 0x639b1b4 VA: 0x75989b31b4
	internal Byte[] ReadIntegerBytes() { }
	// RVA: 0x639b284 VA: 0x75989b3284
	internal Byte[] ReadBitString() { }
	// RVA: 0x639b3cc VA: 0x75989b33cc
	internal Byte[] ReadOctetString() { }
	// RVA: 0x639b3e8 VA: 0x75989b33e8
	internal String ReadOidAsString() { }
	// RVA: 0x639b6b4 VA: 0x75989b36b4
	internal String ReadUtf8String() { }
	// RVA: 0x639b7ac VA: 0x75989b37ac
	private DerSequenceReader ReadCollectionWithTag(DerTag expected) { }
	// RVA: 0x639b91c VA: 0x75989b391c
	internal DerSequenceReader ReadSequence() { }
	// RVA: 0x639b924 VA: 0x75989b3924
	internal DerSequenceReader ReadSet() { }
	// RVA: 0x639b92c VA: 0x75989b392c
	internal String ReadPrintableString() { }
	// RVA: 0x639b9ac VA: 0x75989b39ac
	internal String ReadIA5String() { }
	// RVA: 0x639ba2c VA: 0x75989b3a2c
	internal String ReadT61String() { }
	// RVA: 0x639bd14 VA: 0x75989b3d14
	internal DateTime ReadX509Date() { }
	// RVA: 0x639bd98 VA: 0x75989b3d98
	internal DateTime ReadUtcTime() { }
	// RVA: 0x639bde4 VA: 0x75989b3de4
	internal DateTime ReadGeneralizedTime() { }
	// RVA: 0x639c078 VA: 0x75989b4078
	internal String ReadBMPString() { }
	// RVA: 0x639b734 VA: 0x75989b3734
	private static String TrimTrailingNulls(String value) { }
	// RVA: 0x639be30 VA: 0x75989b3e30
	private DateTime ReadTime(DerTag timeTag, String formatString) { }
	// RVA: 0x639b1d0 VA: 0x75989b31d0
	private Byte[] ReadContentAsBytes() { }
	// RVA: 0x639aca8 VA: 0x75989b2ca8
	private Void EatTag(DerTag expected) { }
	// RVA: 0x639b884 VA: 0x75989b3884
	private static Void CheckTag(DerTag expected, Byte[] data, Int32 position) { }
	// RVA: 0x639ad28 VA: 0x75989b2d28
	private Int32 EatLength() { }
	// RVA: 0x639af14 VA: 0x75989b2f14
	private static Int32 ScanContentLength(Byte[] data, Int32 offset, Int32 end, out Int32 bytesConsumed) { }
}
```