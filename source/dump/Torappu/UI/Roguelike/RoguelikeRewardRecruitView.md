# RoguelikeRewardRecruitView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIIntEvent <onClickEvent>k__BackingField`

- `Image _recruitBg`

- `Image _recruitIcon`

- `Text _recruitName`

- `Text _description`

- `GameObject _panelUpgrade`

- `Text _textUpgrade`

- `GameObject _objReceiptBtn`

- `UIPageFinder m_pageFinder`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardRecruitView : RoguelikeRewardItem
{
	private UIIntEvent <onClickEvent>k__BackingField; // 0x48
	private Image _recruitBg; // 0x50
	private Image _recruitIcon; // 0x58
	private Text _recruitName; // 0x60
	private Text _description; // 0x68
	private GameObject _panelUpgrade; // 0x70
	private Text _textUpgrade; // 0x78
	private GameObject _objReceiptBtn; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2a9f77c VA: 0x75950b777c
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2a9f7e4 VA: 0x75950b77e4
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2a9f868 VA: 0x75950b7868
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2a9f8d0 VA: 0x75950b78d0
	public override Void OnClick() { }
	// RVA: 0x2a9f998 VA: 0x75950b7998
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2a9fd24 VA: 0x75950b7d24
	public Void .ctor() { }
}
```