# TextStyle

**Namespace:** `UnityEngine.TextCore.Text`


## Fields

- `String m_Name`

- `Int32 m_HashCode`

- `String m_OpeningDefinition`

- `String m_ClosingDefinition`


## Properties

- `Int32 hashCode`


## Methods

- `Int32 get_hashCode()`

- `Void RefreshStyle()`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
public class TextStyle
{
	internal static TextStyle k_NormalStyle; // 0x0
	private String m_Name; // 0x10
	private Int32 m_HashCode; // 0x18
	private String m_OpeningDefinition; // 0x20
	private String m_ClosingDefinition; // 0x28
	private Int32[] m_OpeningTagArray; // 0x30
	private Int32[] m_ClosingTagArray; // 0x38
	internal UInt32[] m_OpeningTagUnicodeArray; // 0x40
	internal UInt32[] m_ClosingTagUnicodeArray; // 0x48

	public Int32 hashCode { get; }
	public Int32[] styleOpeningTagArray { get; }
	public Int32[] styleClosingTagArray { get; }

	// RVA: 0x6910224 VA: 0x7598f28224
	public Int32 get_hashCode() { }
	// RVA: 0x691022c VA: 0x7598f2822c
	public Int32[] get_styleOpeningTagArray() { }
	// RVA: 0x6910234 VA: 0x7598f28234
	public Int32[] get_styleClosingTagArray() { }
	// RVA: 0x691023c VA: 0x7598f2823c
	public Void RefreshStyle() { }
}
```