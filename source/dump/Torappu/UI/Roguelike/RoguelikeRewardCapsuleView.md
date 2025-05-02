# RoguelikeRewardCapsuleView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIIntEvent <onClickEvent>k__BackingField`

- `Image _capsuleBg`

- `GameObject _panelReplaceText`

- `GameObject _panelReplaceCheck`

- `CanvasGroup _canvasReplaceCheck`

- `GameObject _objReceiptBtn`

- `RoguelikeRewardCapsuleSwitch m_switchTween`

- `Boolean m_isInited`


## Methods

- `Void OnCancelClick()`

- `Void OnConfirmClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardCapsuleView : RoguelikeRewardItem
{
	private UIIntEvent <onClickEvent>k__BackingField; // 0x48
	private Image _capsuleBg; // 0x50
	private GameObject _panelReplaceText; // 0x58
	private GameObject _panelReplaceCheck; // 0x60
	private CanvasGroup _canvasReplaceCheck; // 0x68
	private GameObject _objReceiptBtn; // 0x70
	private RoguelikeRewardCapsuleSwitch m_switchTween; // 0x78
	private Boolean m_isInited; // 0x80
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

	// RVA: 0x2a9442c VA: 0x75950ac42c
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2a94494 VA: 0x75950ac494
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2a94518 VA: 0x75950ac518
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2a94580 VA: 0x75950ac580
	public override Void OnClick() { }
	// RVA: 0x2a94700 VA: 0x75950ac700
	public Void OnCancelClick() { }
	// RVA: 0x2a94638 VA: 0x75950ac638
	public Void OnConfirmClick() { }
	// RVA: 0x2a94774 VA: 0x75950ac774
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2a94884 VA: 0x75950ac884
	private Void _InitIfNot() { }
	// RVA: 0x2a949d4 VA: 0x75950ac9d4
	public Void .ctor() { }
}
```