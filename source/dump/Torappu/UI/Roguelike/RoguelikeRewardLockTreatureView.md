# RoguelikeRewardLockTreatureView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _treasureIcon`

- `Image _treasureBg`

- `Text _name`

- `Text _desc`

- `GameObject _objReceiptBtn`

- `UIPageFinder m_pageFinder`

- `UIIntEvent <onClickEvent>k__BackingField`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardLockTreatureView : RoguelikeRewardItem
{
	private Image _treasureIcon; // 0x48
	private Image _treasureBg; // 0x50
	private Text _name; // 0x58
	private Text _desc; // 0x60
	private GameObject _objReceiptBtn; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private UIIntEvent <onClickEvent>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2a9ed1c VA: 0x75950b6d1c
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2a9ed84 VA: 0x75950b6d84
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2a9ee08 VA: 0x75950b6e08
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2a9ee70 VA: 0x75950b6e70
	public override Void OnClick() { }
	// RVA: 0x2a9ef38 VA: 0x75950b6f38
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2a9f1a8 VA: 0x75950b71a8
	public Void .ctor() { }
}
```