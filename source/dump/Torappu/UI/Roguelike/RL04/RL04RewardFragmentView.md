# RL04RewardFragmentView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04FragmentItemCard _fragmentCardPrefab`

- `Transform _fragmentCardContainer`

- `UIColorGraphic _graphicColor`

- `Image _fragmentBg`

- `Image _typeIcon`

- `Text _fragmentName`

- `Text _description`

- `GameObject _panelCombine`

- `Text _textCombine`

- `GameObject _objReceiptBtn`

- `Single _fragmentCardScale`

- `UIPageFinder m_pagefd`

- `RL04FragmentItemCard m_fragmentCard`

- `UIIntEvent <onClickEvent>k__BackingField`


## Methods

- `Void _EnsureFragmentCard()`

- `Void _RenderCombineInfo(Boolean, RoguelikeFragmentModuleData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04RewardFragmentView : RoguelikeRewardItem
{
	private RL04FragmentItemCard _fragmentCardPrefab; // 0x48
	private Transform _fragmentCardContainer; // 0x50
	private UIColorGraphic _graphicColor; // 0x58
	private Image _fragmentBg; // 0x60
	private Image _typeIcon; // 0x68
	private Text _fragmentName; // 0x70
	private Text _description; // 0x78
	private GameObject _panelCombine; // 0x80
	private Text _textCombine; // 0x88
	private GameObject _objReceiptBtn; // 0x90
	private Single _fragmentCardScale; // 0x98
	private UIPageFinder m_pagefd; // 0xa0
	private RL04FragmentItemCard m_fragmentCard; // 0xb0
	private UIIntEvent <onClickEvent>k__BackingField; // 0xb8
	private static DelegateBridge __Hotfix0_get_showType; // 0x0
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__EnsureFragmentCard; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__RenderCombineInfo; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override RoguelikeRewardShowType showType { get; }
	protected override UIIntEvent onClickEvent { get; set; }

	// RVA: 0x2b56c10 VA: 0x759516ec10
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2b56c78 VA: 0x759516ec78
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2b56ce0 VA: 0x759516ece0
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2b56d64 VA: 0x759516ed64
	public override Void OnClick() { }
	// RVA: 0x2b56e2c VA: 0x759516ee2c
	private Void _EnsureFragmentCard() { }
	// RVA: 0x2b56ff8 VA: 0x759516eff8
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2b57408 VA: 0x759516f408
	private Void _RenderCombineInfo(Boolean needShow, RoguelikeFragmentModuleData fragmentData) { }
	// RVA: 0x2b575f0 VA: 0x759516f5f0
	public Void .ctor() { }
}
```