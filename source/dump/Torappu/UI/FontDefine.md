# FontDefine

**Namespace:** `Torappu.UI`


## Methods

- `String GetFontGUID(String, ResLanguage)`

- `LanFonts _GetLanFont(ResLanguage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class FontDefine : ScriptableObject
{
	private String[] _fontTypes; // 0x18
	private LanFonts[] _lanFonts; // 0x20


	// RVA: 0x2172d54 VA: 0x759478ad54
	public String GetFontGUID(String fontName, ResLanguage lan) { }
	// RVA: 0x2172e24 VA: 0x759478ae24
	private LanFonts _GetLanFont(ResLanguage lan) { }
	// RVA: 0x2172ed8 VA: 0x759478aed8
	public Void .ctor() { }
}
```