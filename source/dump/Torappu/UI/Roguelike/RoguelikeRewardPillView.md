# RoguelikeRewardPillView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _pillIcon`

- `Image _pillBg`

- `Text _name`

- `Text _desc`

- `GameObject _objReceiptBtn`

- `UIPageFinder m_pageFinder`

- `UIIntEvent <onClickEvent>k__BackingField`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardPillView : RoguelikeRewardItem
{
	private Image _pillIcon; // 0x48
	private Image _pillBg; // 0x50
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

	// RVA: 0x2a9f284 VA: 0x75950b7284
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2a9f2ec VA: 0x75950b72ec
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2a9f370 VA: 0x75950b7370
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2a9f3d8 VA: 0x75950b73d8
	public override Void OnClick() { }
	// RVA: 0x2a9f4a0 VA: 0x75950b74a0
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2a9f710 VA: 0x75950b7710
	public Void .ctor() { }
}
```