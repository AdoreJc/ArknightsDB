# RoguelikeScrollReportItemView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _text`

- `UIAtlasImage _icon`

- `Single _paddings`

- `Single _minHeight`

- `TextGenerator m_textGenerator`

- `TextGenerationSettings m_textSettings`


## Methods

- `Single PrefabOnlyCalcHeight(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeScrollReportItemView : MonoBehaviour, IHotfixable
{
	private Text _text; // 0x18
	private UIAtlasImage _icon; // 0x20
	private Single _paddings; // 0x28
	private Single _minHeight; // 0x2c
	private TextGenerator m_textGenerator; // 0x30
	private TextGenerationSettings m_textSettings; // 0x38
	private static DelegateBridge __Hotfix0_PrefabOnlyCalcHeight; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2a8d704 VA: 0x75950a5704
	public Single PrefabOnlyCalcHeight(String content) { }
	// RVA: 0x2a8d8c0 VA: 0x75950a58c0
	public Void .ctor() { }
}
```