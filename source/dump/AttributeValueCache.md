# AttributeValueCache

**Namespace:** ` `


## Fields

- `StringBuilder stringValue`

- `String singleStringValue`

- `Int32 firstItem`

- `Int32 lastItem`


## Methods

- `Void StartComplexValue()`

- `Void AddItem(ItemType, Object)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : 
private class AttributeValueCache
{
	private StringBuilder stringValue; // 0x10
	private String singleStringValue; // 0x18
	private Item[] items; // 0x20
	private Int32 firstItem; // 0x28
	private Int32 lastItem; // 0x2c

	internal String StringValue { get; }

	// RVA: 0x629fc4c VA: 0x75988b7c4c
	internal String get_StringValue() { }
	// RVA: 0x62a0f98 VA: 0x75988b8f98
	internal Void WriteEntityRef(String name) { }
	// RVA: 0x62a12e0 VA: 0x75988b92e0
	internal Void WriteCharEntity(Char ch) { }
	// RVA: 0x62a1518 VA: 0x75988b9518
	internal Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x62a179c VA: 0x75988b979c
	internal Void WriteWhitespace(String ws) { }
	// RVA: 0x62a18dc VA: 0x75988b98dc
	internal Void WriteString(String text) { }
	// RVA: 0x62a1bcc VA: 0x75988b9bcc
	internal Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x62a1f04 VA: 0x75988b9f04
	internal Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x62a20b0 VA: 0x75988ba0b0
	internal Void WriteRaw(String data) { }
	// RVA: 0x62a296c VA: 0x75988ba96c
	internal Void WriteValue(String value) { }
	// RVA: 0x62a015c VA: 0x75988b815c
	internal Void Replay(XmlWriter writer) { }
	// RVA: 0x62a0480 VA: 0x75988b8480
	internal Void Trim() { }
	// RVA: 0x62a091c VA: 0x75988b891c
	internal Void Clear() { }
	// RVA: 0x62a4598 VA: 0x75988bc598
	private Void StartComplexValue() { }
	// RVA: 0x62a45e8 VA: 0x75988bc5e8
	private Void AddItem(ItemType type, Object data) { }
	// RVA: 0x62a2b24 VA: 0x75988bab24
	public Void .ctor() { }
}
```