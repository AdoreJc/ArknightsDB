# RL03RewardTotemView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RoguelikeRewardShowType _showType`

- `Image _totemBg`

- `Image _totemIcon`

- `Text _totemName`

- `Text _description`

- `GameObject _panelCombine`

- `Text _textCombine`

- `UIPageFinder m_pageFinder`

- `UIIntEvent <onClickEvent>k__BackingField`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03RewardTotemView : RoguelikeRewardItem
{
	private RoguelikeRewardShowType _showType; // 0x48
	private Image _totemBg; // 0x50
	private Image _totemIcon; // 0x58
	private Text _totemName; // 0x60
	private Text _description; // 0x68
	private GameObject _panelCombine; // 0x70
	private Text _textCombine; // 0x78
	private List`1 m_cachedTotemModels; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private UIIntEvent <onClickEvent>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2bb70ac VA: 0x75951cf0ac
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2bb7114 VA: 0x75951cf114
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2bb7198 VA: 0x75951cf198
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2bb7200 VA: 0x75951cf200
	public override Void OnClick() { }
	// RVA: 0x2bb72c8 VA: 0x75951cf2c8
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2bb75d0 VA: 0x75951cf5d0
	public Void .ctor() { }
}
```