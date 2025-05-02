# RoguelikeRewardLeaveView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIIntEvent <onClickEvent>k__BackingField`

- `GameObject _panelLeaveCheck`

- `CanvasGroup _canvasLeaveCheck`

- `RoguelikeRewardLeaveSwitch m_switchTween`

- `Boolean m_isInited`


## Methods

- `Void OnCancelClick()`

- `Void OnConfirmClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardLeaveView : RoguelikeRewardItem
{
	private UIIntEvent <onClickEvent>k__BackingField; // 0x48
	private GameObject _panelLeaveCheck; // 0x50
	private CanvasGroup _canvasLeaveCheck; // 0x58
	private RoguelikeRewardLeaveSwitch m_switchTween; // 0x60
	private Boolean m_isInited; // 0x68
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

	// RVA: 0x2a9af68 VA: 0x75950b2f68
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2a9afd0 VA: 0x75950b2fd0
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2a9b054 VA: 0x75950b3054
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2a9b0bc VA: 0x75950b30bc
	public override Void OnClick() { }
	// RVA: 0x2a9b154 VA: 0x75950b3154
	public Void OnCancelClick() { }
	// RVA: 0x2a9b1c8 VA: 0x75950b31c8
	public Void OnConfirmClick() { }
	// RVA: 0x2a9b290 VA: 0x75950b3290
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2a9b33c VA: 0x75950b333c
	private Void _InitIfNot() { }
	// RVA: 0x2a9b48c VA: 0x75950b348c
	public Void .ctor() { }
}
```