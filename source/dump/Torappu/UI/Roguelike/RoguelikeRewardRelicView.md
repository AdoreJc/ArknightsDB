# RoguelikeRewardRelicView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIIntEvent <onClickEvent>k__BackingField`

- `Image _relicBg`

- `Image _relicIcon`

- `Text _relicName`

- `Text _description`

- `GameObject _panelCurse`

- `GameObject _panelNormal`

- `GameObject _panelUpgrade`

- `Text _textUpgrade`

- `Text _textUpgradeDesc`

- `GameObject _objReceiptBtn`

- `UIPageFinder m_pageFinder`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardRelicView : RoguelikeRewardItem
{
	private UIIntEvent <onClickEvent>k__BackingField; // 0x48
	private Image _relicBg; // 0x50
	private Image _relicIcon; // 0x58
	private Text _relicName; // 0x60
	private Text _description; // 0x68
	private GameObject _panelCurse; // 0x70
	private GameObject _panelNormal; // 0x78
	private GameObject _panelUpgrade; // 0x80
	private Text _textUpgrade; // 0x88
	private Text _textUpgradeDesc; // 0x90
	private GameObject _objReceiptBtn; // 0x98
	private UIPageFinder m_pageFinder; // 0xa0
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2aa0288 VA: 0x75950b8288
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2aa02f0 VA: 0x75950b82f0
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2aa0374 VA: 0x75950b8374
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2aa03dc VA: 0x75950b83dc
	public override Void OnClick() { }
	// RVA: 0x2aa04a4 VA: 0x75950b84a4
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2aa08d4 VA: 0x75950b88d4
	public Void .ctor() { }
}
```