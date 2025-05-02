# RoguelikeRewardGoldView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIIntEvent <onClickEvent>k__BackingField`

- `Image _goldBg`

- `Image _goldIcon`

- `Text _goldName`

- `Text _goldCount`

- `GameObject _objReceiptBtn`

- `UIPageFinder m_pageFinder`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardGoldView : RoguelikeRewardItem
{
	private UIIntEvent <onClickEvent>k__BackingField; // 0x48
	private Image _goldBg; // 0x50
	private Image _goldIcon; // 0x58
	private Text _goldName; // 0x60
	private Text _goldCount; // 0x68
	private GameObject _objReceiptBtn; // 0x70
	private UIPageFinder m_pageFinder; // 0x78
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2a99a54 VA: 0x75950b1a54
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2a99abc VA: 0x75950b1abc
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2a99b40 VA: 0x75950b1b40
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2a99ba8 VA: 0x75950b1ba8
	public override Void OnClick() { }
	// RVA: 0x2a99c70 VA: 0x75950b1c70
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2a99ebc VA: 0x75950b1ebc
	public Void .ctor() { }
}
```