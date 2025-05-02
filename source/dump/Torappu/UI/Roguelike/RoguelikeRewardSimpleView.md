# RoguelikeRewardSimpleView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _itemBg`

- `Image _itemIcon`

- `Text _itemName`

- `Text _itemCount`

- `RoguelikeRewardShowType _showType`

- `GameObject _objReceiptBtn`

- `UIPageFinder m_pageFinder`

- `UIIntEvent <onClickEvent>k__BackingField`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardSimpleView : RoguelikeRewardItem
{
	private Image _itemBg; // 0x48
	private Image _itemIcon; // 0x50
	private Text _itemName; // 0x58
	private Text _itemCount; // 0x60
	private RoguelikeRewardShowType _showType; // 0x68
	private GameObject _objReceiptBtn; // 0x70
	private UIPageFinder m_pageFinder; // 0x78
	private UIIntEvent <onClickEvent>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2aa1f90 VA: 0x75950b9f90
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2aa1ff8 VA: 0x75950b9ff8
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2aa207c VA: 0x75950ba07c
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2aa20e4 VA: 0x75950ba0e4
	public override Void OnClick() { }
	// RVA: 0x2aa21ac VA: 0x75950ba1ac
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2aa23f8 VA: 0x75950ba3f8
	public Void .ctor() { }
}
```