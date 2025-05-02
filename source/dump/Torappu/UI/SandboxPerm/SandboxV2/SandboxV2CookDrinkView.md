# SandboxV2CookDrinkView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Single SWITCH_MID_INTERVAL`

- `Text _stockText`

- `Text _makeCountText`

- `GameObject _clearValidPanel`

- `GameObject _clearInvalidPanel`

- `GameObject _autoValidPanel`

- `GameObject _autoInvalidPanel`

- `GameObject _makeValidPanel`

- `GameObject _makeInvalidPanel`

- `SandboxV2CookDrinkWaterView _waterView`

- `SandboxV2CookDrinkItemLoopAdapter _itemAdapter`

- `LoopVerticalScrollRect _itemScrollRect`

- `CanvasGroup _itemContentGroup`

- `GameObject _itemsPanel`

- `GameObject _emptyPanel`

- `UIAnimationLocation _bottleAnimation`

- `CanvasGroup _leftBottleGroup`

- `CanvasGroup _rightNearBottleGroup`

- `CanvasGroup _rightFarBottleGroup`

- `UIAnimationLocation _matSwitchAnimation`

- `Single _itemContentSwitchHalfDuration`

- `UILongPressButtonEx _autoButton`

- `GameObject _tutorialOnly_autoButton`

- `GameObject _tutorialOnly_makeButton`

- `Boolean m_hasInited`

- `SelectMode m_cachedSelectMode`

- `Int32 m_cachedBottleCount`

- `BottleAnimator m_bottleAnimator`

- `UISwitchTween m_matSwitchTween`

- `Tween m_contentSwitchTween`

- `Boolean m_blockingItemsUpdate`

- `Action <switchModeEvent>k__BackingField`

- `Action <clearEvent>k__BackingField`

- `Action <makeEvent>k__BackingField`

- `SandboxV2AdminMainState <tutorialOnly_mainState>k__BackingField`

- `Coroutine m_tutorialRaisingCoroutine`


## Properties

- `Action switchModeEvent`

- `Action clearEvent`

- `Action makeEvent`

- `SandboxV2AdminMainState tutorialOnly_mainState`

- `Boolean tutorialOnly_isTransiting`


## Methods

- `Action get_switchModeEvent()`

- `Void set_switchModeEvent(Action)`

- `Action get_clearEvent()`

- `Void set_clearEvent(Action)`

- `Void set_autoFillEvent(Func`1)`

- `Action get_makeEvent()`

- `Void set_makeEvent(Action)`

- `Void set_itemSelectEvent(Func`3)`

- `Void OnSwitchModeEvent()`

- `Void OnClearEvent()`

- `Void OnMakeEvent()`

- `Void _InitIfNot()`

- `Void _SwitchContent(SelectMode)`

- `Sequence _SequenceOfSwitchContent(SelectMode)`

- `Void _OnAutoFillPress()`

- `Boolean _OnAutoFillLongPress()`

- `SandboxV2AdminMainState get_tutorialOnly_mainState()`

- `Void set_tutorialOnly_mainState(SandboxV2AdminMainState)`

- `Boolean get_tutorialOnly_isTransiting()`

- `GameObject TutorialOnly_GetAutoGO()`

- `GameObject TutorialOnly_GetMakeGO()`

- `Void _TutorialOnly_CheckSignalToRaise(Boolean)`

- `IEnumerator _TutorialOnly_RaiseSignalWhenFinishTransiting(Action)`

- `Void _StopCoroutineIfNeed()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookDrinkView : SandboxV2AdminMainContentViewBase`1
{
	private Single SWITCH_MID_INTERVAL; // 0x34
	private Text _stockText; // 0x38
	private Text _makeCountText; // 0x40
	private GameObject _clearValidPanel; // 0x48
	private GameObject _clearInvalidPanel; // 0x50
	private GameObject _autoValidPanel; // 0x58
	private GameObject _autoInvalidPanel; // 0x60
	private GameObject _makeValidPanel; // 0x68
	private GameObject _makeInvalidPanel; // 0x70
	private SandboxV2CookDrinkWaterView _waterView; // 0x78
	private SandboxV2CookDrinkItemLoopAdapter _itemAdapter; // 0x80
	private LoopVerticalScrollRect _itemScrollRect; // 0x88
	private CanvasGroup _itemContentGroup; // 0x90
	private GameObject _itemsPanel; // 0x98
	private GameObject _emptyPanel; // 0xa0
	private UIAnimationLocation _bottleAnimation; // 0xa8
	private CanvasGroup _leftBottleGroup; // 0xb8
	private CanvasGroup _rightNearBottleGroup; // 0xc0
	private CanvasGroup _rightFarBottleGroup; // 0xc8
	private UIAnimationLocation _matSwitchAnimation; // 0xd0
	private Single _itemContentSwitchHalfDuration; // 0xe0
	private UILongPressButtonEx _autoButton; // 0xe8
	private GameObject _tutorialOnly_autoButton; // 0xf0
	private GameObject _tutorialOnly_makeButton; // 0xf8
	private Boolean m_hasInited; // 0x100
	private SelectMode m_cachedSelectMode; // 0x104
	private List`1 m_cachedFoodmatItems; // 0x108
	private List`1 m_cachedFoodItems; // 0x110
	private Int32 m_cachedBottleCount; // 0x118
	private BottleAnimator m_bottleAnimator; // 0x120
	private UISwitchTween m_matSwitchTween; // 0x128
	private Tween m_contentSwitchTween; // 0x130
	private Boolean m_blockingItemsUpdate; // 0x138
	private Action <switchModeEvent>k__BackingField; // 0x140
	private Action <clearEvent>k__BackingField; // 0x148
	private Func`1 <autoFillEvent>k__BackingField; // 0x150
	private Action <makeEvent>k__BackingField; // 0x158
	private Func`3 <itemSelectEvent>k__BackingField; // 0x160
	private SandboxV2AdminMainState <tutorialOnly_mainState>k__BackingField; // 0x168
	private Coroutine m_tutorialRaisingCoroutine; // 0x170
	private static DelegateBridge __Hotfix0_get_switchModeEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_switchModeEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_clearEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_clearEvent; // 0x18
	private static DelegateBridge __Hotfix0_get_autoFillEvent; // 0x20
	private static DelegateBridge __Hotfix0_set_autoFillEvent; // 0x28
	private static DelegateBridge __Hotfix0_get_makeEvent; // 0x30
	private static DelegateBridge __Hotfix0_set_makeEvent; // 0x38
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x40
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0_OnShow; // 0x58
	private static DelegateBridge __Hotfix0_OnSwitchModeEvent; // 0x60
	private static DelegateBridge __Hotfix0_OnClearEvent; // 0x68
	private static DelegateBridge __Hotfix0_OnMakeEvent; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__SwitchContent; // 0x80
	private static DelegateBridge __Hotfix0__SequenceOfSwitchContent; // 0x88
	private static DelegateBridge __Hotfix0__OnAutoFillPress; // 0x90
	private static DelegateBridge __Hotfix0__OnAutoFillLongPress; // 0x98
	private static DelegateBridge __Hotfix0_get_tutorialOnly_mainState; // 0xa0
	private static DelegateBridge __Hotfix0_set_tutorialOnly_mainState; // 0xa8
	private static DelegateBridge __Hotfix0_get_tutorialOnly_isTransiting; // 0xb0
	private static DelegateBridge __Hotfix0_TutorialOnly_GetAutoGO; // 0xb8
	private static DelegateBridge __Hotfix0_TutorialOnly_GetMakeGO; // 0xc0
	private static DelegateBridge __Hotfix0__TutorialOnly_CheckSignalToRaise; // 0xc8
	private static DelegateBridge __Hotfix0__TutorialOnly_RaiseSignalWhenFinishTransiting; // 0xd0
	private static DelegateBridge __Hotfix0__StopCoroutineIfNeed; // 0xd8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	private Action switchModeEvent { get; set; }
	private Action clearEvent { get; set; }
	private Func`1 autoFillEvent { get; set; }
	private Action makeEvent { get; set; }
	private Func`3 itemSelectEvent { get; set; }
	private SandboxV2AdminMainState tutorialOnly_mainState { get; set; }
	protected Boolean tutorialOnly_isTransiting { get; }

	// RVA: 0x24c4ce4 VA: 0x7594adcce4
	private Action get_switchModeEvent() { }
	// RVA: 0x24c4d4c VA: 0x7594adcd4c
	public Void set_switchModeEvent(Action value) { }
	// RVA: 0x24c4dd0 VA: 0x7594adcdd0
	private Action get_clearEvent() { }
	// RVA: 0x24c4e38 VA: 0x7594adce38
	public Void set_clearEvent(Action value) { }
	// RVA: 0x24c4ebc VA: 0x7594adcebc
	private Func`1 get_autoFillEvent() { }
	// RVA: 0x24c4f24 VA: 0x7594adcf24
	public Void set_autoFillEvent(Func`1 value) { }
	// RVA: 0x24c4fa8 VA: 0x7594adcfa8
	private Action get_makeEvent() { }
	// RVA: 0x24c5010 VA: 0x7594add010
	public Void set_makeEvent(Action value) { }
	// RVA: 0x24c5094 VA: 0x7594add094
	private Func`3 get_itemSelectEvent() { }
	// RVA: 0x24c50fc VA: 0x7594add0fc
	public Void set_itemSelectEvent(Func`3 value) { }
	// RVA: 0x24c5180 VA: 0x7594add180
	public override Void OnValueChanged(SandboxV2AdminMainCookPanelModelProperty property) { }
	// RVA: 0x24c667c VA: 0x7594ade67c
	protected override Void OnShow() { }
	// RVA: 0x24c66f4 VA: 0x7594ade6f4
	public Void OnSwitchModeEvent() { }
	// RVA: 0x24c6790 VA: 0x7594ade790
	public Void OnClearEvent() { }
	// RVA: 0x24c682c VA: 0x7594ade82c
	public Void OnMakeEvent() { }
	// RVA: 0x24c55e0 VA: 0x7594add5e0
	private Void _InitIfNot() { }
	// RVA: 0x24c60ec VA: 0x7594ade0ec
	private Void _SwitchContent(SelectMode selectMode) { }
	// RVA: 0x24c64a4 VA: 0x7594ade4a4
	private Sequence _SequenceOfSwitchContent(SelectMode selectMode) { }
	// RVA: 0x24c6a94 VA: 0x7594adea94
	private Void _OnAutoFillPress() { }
	// RVA: 0x24c6b30 VA: 0x7594adeb30
	private Boolean _OnAutoFillLongPress() { }
	// RVA: 0x24c6bcc VA: 0x7594adebcc
	private SandboxV2AdminMainState get_tutorialOnly_mainState() { }
	// RVA: 0x24c6c34 VA: 0x7594adec34
	public Void set_tutorialOnly_mainState(SandboxV2AdminMainState value) { }
	// RVA: 0x24c6cb8 VA: 0x7594adecb8
	protected Boolean get_tutorialOnly_isTransiting() { }
	// RVA: 0x24c6e54 VA: 0x7594adee54
	public GameObject TutorialOnly_GetAutoGO() { }
	// RVA: 0x24c6ebc VA: 0x7594adeebc
	public GameObject TutorialOnly_GetMakeGO() { }
	// RVA: 0x24c5920 VA: 0x7594add920
	private Void _TutorialOnly_CheckSignalToRaise(Boolean isShow) { }
	// RVA: 0x24c7048 VA: 0x7594adf048
	private IEnumerator _TutorialOnly_RaiseSignalWhenFinishTransiting(Action signalAction) { }
	// RVA: 0x24c6f24 VA: 0x7594adef24
	private Void _StopCoroutineIfNeed() { }
	// RVA: 0x24c7140 VA: 0x7594adf140
	private Void OnDestroy() { }
	// RVA: 0x24c71a8 VA: 0x7594adf1a8
	public Void .ctor() { }
}
```