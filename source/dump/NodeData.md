# NodeData

**Namespace:** ` `


## Fields

- `String value`

- `Int32 valueStartPos`

- `Int32 valueLength`

- `Boolean isEmptyOrDefault`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : 
private class NodeData : IComparable
{
	private static NodeData s_None; // 0x0
	internal XmlNodeType type; // 0x10
	internal String localName; // 0x18
	internal String prefix; // 0x20
	internal String ns; // 0x28
	internal String nameWPrefix; // 0x30
	private String value; // 0x38
	private Char[] chars; // 0x40
	private Int32 valueStartPos; // 0x48
	private Int32 valueLength; // 0x4c
	internal LineInfo lineInfo; // 0x50
	internal LineInfo lineInfo2; // 0x58
	internal Char quoteChar; // 0x60
	internal Int32 depth; // 0x64
	private Boolean isEmptyOrDefault; // 0x68
	internal Int32 entityId; // 0x6c
	internal Boolean xmlContextPushed; // 0x70
	internal NodeData nextAttrValueChunk; // 0x78
	internal Object schemaType; // 0x80
	internal Object typedValue; // 0x88

	internal static NodeData None { get; }
	internal Int32 LineNo { get; }
	internal Int32 LinePos { get; }
	internal Boolean IsEmptyElement { get; set; }
	internal Boolean IsDefaultAttribute { get; set; }
	internal Boolean ValueBuffered { get; }
	internal String StringValue { get; }

	// RVA: 0x6298204 VA: 0x75988b0204
	internal static NodeData get_None() { }
	// RVA: 0x62982b4 VA: 0x75988b02b4
	internal Void .ctor() { }
	// RVA: 0x6298388 VA: 0x75988b0388
	internal Int32 get_LineNo() { }
	// RVA: 0x6298390 VA: 0x75988b0390
	internal Int32 get_LinePos() { }
	// RVA: 0x6298398 VA: 0x75988b0398
	internal Boolean get_IsEmptyElement() { }
	// RVA: 0x62983bc VA: 0x75988b03bc
	internal Void set_IsEmptyElement(Boolean value) { }
	// RVA: 0x62983c8 VA: 0x75988b03c8
	internal Boolean get_IsDefaultAttribute() { }
	// RVA: 0x62983ec VA: 0x75988b03ec
	internal Void set_IsDefaultAttribute(Boolean value) { }
	// RVA: 0x62983f8 VA: 0x75988b03f8
	internal Boolean get_ValueBuffered() { }
	// RVA: 0x6298408 VA: 0x75988b0408
	internal String get_StringValue() { }
	// RVA: 0x6298450 VA: 0x75988b0450
	internal Void TrimSpacesInValue() { }
	// RVA: 0x62982dc VA: 0x75988b02dc
	internal Void Clear(XmlNodeType type) { }
	// RVA: 0x629849c VA: 0x75988b049c
	internal Void ClearName() { }
	// RVA: 0x6298538 VA: 0x75988b0538
	internal Void SetLineInfo(Int32 lineNo, Int32 linePos) { }
	// RVA: 0x6298544 VA: 0x75988b0544
	internal Void SetLineInfo2(Int32 lineNo, Int32 linePos) { }
	// RVA: 0x6298550 VA: 0x75988b0550
	internal Void SetValueNode(XmlNodeType type, String value) { }
	// RVA: 0x629858c VA: 0x75988b058c
	internal Void SetValueNode(XmlNodeType type, Char[] chars, Int32 startPos, Int32 len) { }
	// RVA: 0x62985e4 VA: 0x75988b05e4
	internal Void SetNamedNode(XmlNodeType type, String localName) { }
	// RVA: 0x6298650 VA: 0x75988b0650
	internal Void SetNamedNode(XmlNodeType type, String localName, String prefix, String nameWPrefix) { }
	// RVA: 0x629871c VA: 0x75988b071c
	internal Void SetValue(String value) { }
	// RVA: 0x629872c VA: 0x75988b072c
	internal Void SetValue(Char[] chars, Int32 startPos, Int32 len) { }
	// RVA: 0x6298778 VA: 0x75988b0778
	internal Void OnBufferInvalidated() { }
	// RVA: 0x62987c8 VA: 0x75988b07c8
	internal Void CopyTo(Int32 valueOffset, StringBuilder sb) { }
	// RVA: 0x6298848 VA: 0x75988b0848
	internal String GetNameWPrefix(XmlNameTable nt) { }
	// RVA: 0x629885c VA: 0x75988b085c
	internal String CreateNameWPrefix(XmlNameTable nt) { }
	// RVA: 0x62988f4 VA: 0x75988b08f4
	private Int32 System.IComparable.CompareTo(Object obj) { }
}
```