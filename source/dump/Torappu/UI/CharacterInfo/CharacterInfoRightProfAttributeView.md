# CharacterInfoRightProfAttributeView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _attributeText`

- `String m_cacheText`

- `TextGenerator m_textGenerate`


## Methods

- `Void _RenderText(String)`

- `Void <>xLuaBaseProxy_Render(CharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightProfAttributeView : CharacterInfoRightProfObj
{
	private Text _attributeText; // 0x20
	private String m_cacheText; // 0x28
	private TextGenerator m_textGenerate; // 0x30
	private static DelegateBridge __Hotfix0_GetAndApplyHeight; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderText; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d86404 VA: 0x759539e404
	public override Single GetAndApplyHeight() { }
	// RVA: 0x2d864dc VA: 0x759539e4dc
	public override Void Render(CharViewModel viewModel) { }
	// RVA: 0x2d8666c VA: 0x759539e66c
	private Void _RenderText(String text) { }
	// RVA: 0x2d8676c VA: 0x759539e76c
	public Void .ctor() { }
	// RVA: 0x2d86810 VA: 0x759539e810
	private Void <>xLuaBaseProxy_Render(CharViewModel P0) { }
}
```