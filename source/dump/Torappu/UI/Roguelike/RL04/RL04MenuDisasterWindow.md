# RL04MenuDisasterWindow

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _imgDisaster`

- `GameObject _prefabLevel`

- `RectTransform _levelContainer`

- `Text _txtDisasterName`

- `Text _txtStep`

- `Text _txtFuncDesc`

- `Text _txtDesc`

- `UIPageFinder m_pageFinder`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MenuDisasterWindow : RoguelikeMenuWindow`1
{
	private Image _imgDisaster; // 0x28
	private GameObject _prefabLevel; // 0x30
	private RectTransform _levelContainer; // 0x38
	private Text _txtDisasterName; // 0x40
	private Text _txtStep; // 0x48
	private Text _txtFuncDesc; // 0x50
	private Text _txtDesc; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private List`1 m_levelObjs; // 0x70
	private static DelegateBridge __Hotfix0_get_selectType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2b2d894 VA: 0x7595145894
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2b2d8fc VA: 0x75951458fc
	public override Void Render(RL04MenuDisasterViewModel viewModel) { }
	// RVA: 0x2b2de00 VA: 0x7595145e00
	public Void .ctor() { }
}
```