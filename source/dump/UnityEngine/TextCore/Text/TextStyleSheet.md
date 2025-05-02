# TextStyleSheet

**Namespace:** `UnityEngine.TextCore.Text`


## Methods

- `TextStyle GetStyle(Int32)`

- `TextStyle GetStyle(String)`

- `Void RefreshStyles()`

- `Void LoadStyleDictionaryInternal()`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
public class TextStyleSheet : ScriptableObject
{
	private List`1 m_StyleList; // 0x18
	private Dictionary`2 m_StyleLookupDictionary; // 0x20

	internal List`1 styles { get; }

	// RVA: 0x6910460 VA: 0x7598f28460
	internal List`1 get_styles() { }
	// RVA: 0x6910468 VA: 0x7598f28468
	public TextStyle GetStyle(Int32 hashCode) { }
	// RVA: 0x69106b0 VA: 0x7598f286b0
	public TextStyle GetStyle(String name) { }
	// RVA: 0x6910744 VA: 0x7598f28744
	public Void RefreshStyles() { }
	// RVA: 0x69104f0 VA: 0x7598f284f0
	private Void LoadStyleDictionaryInternal() { }
	// RVA: 0x6910748 VA: 0x7598f28748
	public Void .ctor() { }
}
```