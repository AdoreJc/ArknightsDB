# RoguelikeRewardTrapView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIIntEvent <onClickEvent>k__BackingField`

- `Image _trapBg`

- `Image _trapIcon`

- `Text _trapName`

- `Text _description`

- `GameObject _panelReplaceText`

- `GameObject _panelReplaceCheck`

- `CanvasGroup _canvasReplaceCheck`

- `Text _btnName`

- `GameObject _objReceiptBtn`

- `RoguelikeRewardTrapSwitch m_switchTween`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnCancelClick()`

- `Void OnConfirmClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardTrapView : RoguelikeRewardItem
{
	private UIIntEvent <onClickEvent>k__BackingField; // 0x48
	private Image _trapBg; // 0x50
	private Image _trapIcon; // 0x58
	private Text _trapName; // 0x60
	private Text _description; // 0x68
	private GameObject _panelReplaceText; // 0x70
	private GameObject _panelReplaceCheck; // 0x78
	private CanvasGroup _canvasReplaceCheck; // 0x80
	private Text _btnName; // 0x88
	private GameObject _objReceiptBtn; // 0x90
	private RoguelikeRewardTrapSwitch m_switchTween; // 0x98
	private Boolean m_isInited; // 0xa0
	private UIPageFinder m_pageFinder; // 0xa8
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_OnCancelClick; // 0x20
	private static DelegateBridge __Hotfix0_OnConfirmClick; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2aa2898 VA: 0x75950ba898
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2aa2900 VA: 0x75950ba900
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2aa2984 VA: 0x75950ba984
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2aa29ec VA: 0x75950ba9ec
	public override Void OnClick() { }
	// RVA: 0x2aa2b6c VA: 0x75950bab6c
	public Void OnCancelClick() { }
	// RVA: 0x2aa2aa4 VA: 0x75950baaa4
	public Void OnConfirmClick() { }
	// RVA: 0x2aa2be0 VA: 0x75950babe0
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2aa2ef0 VA: 0x75950baef0
	private Void _InitIfNot() { }
	// RVA: 0x2aa3040 VA: 0x75950bb040
	public Void .ctor() { }
}
```