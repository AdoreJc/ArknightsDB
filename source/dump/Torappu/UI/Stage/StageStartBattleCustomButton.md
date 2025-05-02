# StageStartBattleCustomButton

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Button _btnStartBattle`

- `Image _bkgCost`

- `Image _imgStartBattle`

- `Text _textCost`

- `GameObject _diffGroupObj`

- `Color _groupApCostColor`

- `Color _commonApCostColor`

- `String m_styleId`


## Methods

- `Void SetStartBattleEvent(ButtonClickedEvent)`

- `Void Render(PreviewConfigViewModel, UIPage)`

- `String _PickConstStyleId(PreviewConfigViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageStartBattleCustomButton : MonoBehaviour, IHotfixable
{
	private Button _btnStartBattle; // 0x18
	private Image _bkgCost; // 0x20
	private Image _imgStartBattle; // 0x28
	private Text _textCost; // 0x30
	private GameObject _diffGroupObj; // 0x38
	private Color _groupApCostColor; // 0x40
	private Color _commonApCostColor; // 0x50
	private String m_styleId; // 0x60
	private static DelegateBridge __Hotfix0_SetStartBattleEvent; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__PickConstStyleId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fa896c VA: 0x75955c096c
	public Void SetStartBattleEvent(ButtonClickedEvent clickEvent) { }
	// RVA: 0x2fa89f8 VA: 0x75955c09f8
	public Void Render(PreviewConfigViewModel stageModel, UIPage page) { }
	// RVA: 0x2fad194 VA: 0x75955c5194
	private String _PickConstStyleId(PreviewConfigViewModel stageModel) { }
	// RVA: 0x2fad278 VA: 0x75955c5278
	public Void .ctor() { }
}
```