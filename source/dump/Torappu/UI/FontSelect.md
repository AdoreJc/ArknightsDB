# FontSelect

**Namespace:** `Torappu.UI`


## Fields

- `ResLanguage _lan`


## Properties

- `ResLanguage language`


## Methods

- `Font GetFont(String)`

- `ResLanguage get_language()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class FontSelect : ScriptableObject
{
	private ResLanguage _lan; // 0x18
	private TheFont[] _fonts; // 0x20
	private Dictionary`2 _fontdic; // 0x28

	public ResLanguage language { get; }

	// RVA: 0x2172ee0 VA: 0x759478aee0
	public Font GetFont(String fontName) { }
	// RVA: 0x217304c VA: 0x759478b04c
	public ResLanguage get_language() { }
	// RVA: 0x2173054 VA: 0x759478b054
	public Void .ctor() { }
}
```