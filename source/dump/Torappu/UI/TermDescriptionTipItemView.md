# TermDescriptionTipItemView

**Namespace:** `Torappu.UI`


## Fields

- `UICommentedText _textDesc`

- `Boolean _darkColorComment`

- `Text _textName`

- `Transform _rangeContainer`

- `LayoutElement _layoutElement`

- `Transform _uiContainer`

- `CanvasGroup _uiCanvasGroup`

- `UICharacterAttackRangeWidget _attackRange`

- `Button _btn`

- `Tween m_showTween`

- `Int32 m_cachedIdx`

- `Tween m_showUITween`

- `Action clickEvent`


## Methods

- `Void RenderTermTip(UITermDescViewModel, Int32, Boolean)`

- `Void _SetLayoutState(Boolean)`

- `Void _SetContainerState(Single)`

- `Void _StartShowTween()`

- `Void _StartHideTween()`

- `Void _ResetContainerPos()`

- `Void _SetContainerPosToTop()`

- `Void _PlayShowAnimation(Boolean, Boolean)`

- `Void _PlayHideAnimation(Boolean, Boolean)`

- `Void _InitTerm(String, InfoType, Boolean, Boolean)`

- `Void _RenderRange(AttackRangeDescModel)`

- `Void _RenderText(TermDescriptionData)`

- `Void OnClickEvent()`

- `Void <_StartShowTween>b__21_1(Single)`

- `Void <_StartHideTween>b__22_1(Single)`

- `Void <_StartHideTween>b__22_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TermDescriptionTipItemView : MonoBehaviour, IHotfixable
{
	private UICommentedText _textDesc; // 0x18
	private Boolean _darkColorComment; // 0x20
	private Text _textName; // 0x28
	private Transform _rangeContainer; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private Transform _uiContainer; // 0x40
	private CanvasGroup _uiCanvasGroup; // 0x48
	private UICharacterAttackRangeWidget _attackRange; // 0x50
	private Button _btn; // 0x58
	private Tween m_showTween; // 0x60
	private Int32 m_cachedIdx; // 0x68
	private Tween m_showUITween; // 0x70
	private const Single TWEEN_DURATION; // 0x0
	private const Single TWEEN_FADEIN_DURATION; // 0x0
	private const Single CONST_HEIGHT; // 0x0
	private const Single TERM_DESC_OFFSET_Y; // 0x0
	private const Single TERM_DESC_ORIGIN_Y; // 0x0
	public Action clickEvent; // 0x78
	private static DelegateBridge __Hotfix0_RenderTermTip; // 0x0
	private static DelegateBridge __Hotfix0__SetLayoutState; // 0x8
	private static DelegateBridge __Hotfix0__SetContainerState; // 0x10
	private static DelegateBridge __Hotfix0__StartShowTween; // 0x18
	private static DelegateBridge __Hotfix0__StartHideTween; // 0x20
	private static DelegateBridge __Hotfix0__ResetContainerPos; // 0x28
	private static DelegateBridge __Hotfix0__SetContainerPosToTop; // 0x30
	private static DelegateBridge __Hotfix0__PlayShowAnimation; // 0x38
	private static DelegateBridge __Hotfix0__PlayHideAnimation; // 0x40
	private static DelegateBridge __Hotfix0__InitTerm; // 0x48
	private static DelegateBridge __Hotfix0__RenderRange; // 0x50
	private static DelegateBridge __Hotfix0__RenderText; // 0x58
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x228c740 VA: 0x75948a4740
	public Void RenderTermTip(UITermDescViewModel viewModel, Int32 termCount, Boolean isFlow) { }
	// RVA: 0x228d2cc VA: 0x75948a52cc
	private Void _SetLayoutState(Boolean isHide) { }
	// RVA: 0x228d440 VA: 0x75948a5440
	private Void _SetContainerState(Single endPosY) { }
	// RVA: 0x228cb88 VA: 0x75948a4b88
	private Void _StartShowTween() { }
	// RVA: 0x228cf30 VA: 0x75948a4f30
	private Void _StartHideTween() { }
	// RVA: 0x228d3c8 VA: 0x75948a53c8
	private Void _ResetContainerPos() { }
	// RVA: 0x228cdb0 VA: 0x75948a4db0
	private Void _SetContainerPosToTop() { }
	// RVA: 0x228ce2c VA: 0x75948a4e2c
	private Void _PlayShowAnimation(Boolean isSublinTop, Boolean isFlow) { }
	// RVA: 0x228d1b8 VA: 0x75948a51b8
	private Void _PlayHideAnimation(Boolean isSublinTop, Boolean isFlow) { }
	// RVA: 0x228c978 VA: 0x75948a4978
	private Void _InitTerm(String termId, InfoType termType, Boolean isFlow, Boolean isSublinTop) { }
	// RVA: 0x228d574 VA: 0x75948a5574
	private Void _RenderRange(AttackRangeDescModel atkRange) { }
	// RVA: 0x228d4dc VA: 0x75948a54dc
	private Void _RenderText(TermDescriptionData viewData) { }
	// RVA: 0x228d60c VA: 0x75948a560c
	public Void OnClickEvent() { }
	// RVA: 0x228d690 VA: 0x75948a5690
	public Void .ctor() { }
	// RVA: 0x228d708 VA: 0x75948a5708
	private Void <_StartShowTween>b__21_1(Single val) { }
	// RVA: 0x228d750 VA: 0x75948a5750
	private Void <_StartHideTween>b__22_1(Single val) { }
	// RVA: 0x228d7b8 VA: 0x75948a57b8
	private Void <_StartHideTween>b__22_2() { }
}
```