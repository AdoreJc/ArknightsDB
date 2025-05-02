# SceneFontHolder

**Namespace:** `Torappu`


## Fields

- `FontSelect _fontSel`

- `FontSelect m_fontSelectPlugin`


## Methods

- `Void SetFontPlugin(FontSelect)`

- `Void UnRegisterFontPlugin()`

- `Boolean TryGetFont(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SceneFontHolder : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private FontSelect _fontSel; // 0x18
	private FontSelect m_fontSelectPlugin; // 0x20
	private static DelegateBridge __Hotfix0_SetFontPlugin; // 0x0
	private static DelegateBridge __Hotfix0_UnRegisterFontPlugin; // 0x8
	private static DelegateBridge __Hotfix0_TryGetFont; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31060c4 VA: 0x759571e0c4
	public Void SetFontPlugin(FontSelect fontSelect) { }
	// RVA: 0x3106148 VA: 0x759571e148
	public Void UnRegisterFontPlugin() { }
	// RVA: 0x31061b8 VA: 0x759571e1b8
	public Boolean TryGetFont(String name, out Font font) { }
	// RVA: 0x3106398 VA: 0x759571e398
	public Void .ctor() { }
}
```