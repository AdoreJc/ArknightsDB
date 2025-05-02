# StageMixStoryOverallState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageMixStoryOverallView _view`

- `CanvasGroup _rootCanvasGroup`

- `UIAnimationLocation _inAnimation`

- `RectTransform _topMenuContainer`

- `GameObject _tutorialSwitches`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `StageStateBean m_stageStateBean`

- `AnimationSwitchTween m_inTween`

- `MixStoryGroupViewProperty m_mixStoryProperty`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSelectZone(String, String)`

- `Void _JumpToZone(String, String)`

- `Void _OnSelectRetro(String)`

- `Void _OnSwitchSortMode()`

- `Void _OnSwitchDisplayFeature(OverallDisplayFeature)`

- `Void _InitIfNot()`

- `Void _EventOnBackBtnClicked()`

- `Void _TutorialIfNeed()`

- `IEnumerator _Tutorial_WaitToTriggerSignal()`

- `Void _Tutorial_TriggerRetroTutorialIfNeed()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMixStoryOverallState : UIPopupState, IValueMsgReceiver
{
	private const Single FADE_DURATION; // 0x0
	public const Int32 MSG_SELECT_ZONE; // 0x0
	public const Int32 MSG_SELECT_RETRO; // 0x0
	public const Int32 MSG_SWITCH_SORT_MODE; // 0x0
	public const Int32 MSG_SWITCH_DISPLAY_FEATURE; // 0x0
	private StageMixStoryOverallView _view; // 0x60
	private CanvasGroup _rootCanvasGroup; // 0x68
	private UIAnimationLocation _inAnimation; // 0x70
	private RectTransform _topMenuContainer; // 0x80
	private GameObject _tutorialSwitches; // 0x88
	private Boolean m_hasInited; // 0x90
	private UIPageFinder m_pageFinder; // 0x98
	private StageStateBean m_stageStateBean; // 0xa8
	private AnimationSwitchTween m_inTween; // 0xb0
	private MixStoryGroupViewProperty m_mixStoryProperty; // 0xb8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0__OnSelectZone; // 0x10
	private static DelegateBridge __Hotfix0__JumpToZone; // 0x18
	private static DelegateBridge __Hotfix0__OnSelectRetro; // 0x20
	private static DelegateBridge __Hotfix0__OnSwitchSortMode; // 0x28
	private static DelegateBridge __Hotfix0__OnSwitchDisplayFeature; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnPause; // 0x40
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x48
	private static DelegateBridge __Hotfix0_OnResume; // 0x50
	private static DelegateBridge __Hotfix0_OnExit; // 0x58
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x68
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x70
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x80
	private static DelegateBridge __Hotfix0__EventOnBackBtnClicked; // 0x88
	private static DelegateBridge __Hotfix0__TutorialIfNeed; // 0x90
	private static DelegateBridge __Hotfix0__Tutorial_WaitToTriggerSignal; // 0x98
	private static DelegateBridge __Hotfix0__Tutorial_TriggerRetroTutorialIfNeed; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x2f64f6c VA: 0x759557cf6c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f64fd4 VA: 0x759557cfd4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f6515c VA: 0x759557d15c
	private Void _OnSelectZone(String storySetId, String zoneId) { }
	// RVA: 0x2f658d8 VA: 0x759557d8d8
	private Void _JumpToZone(String storySetId, String zoneId) { }
	// RVA: 0x2f65450 VA: 0x759557d450
	private Void _OnSelectRetro(String storySetId) { }
	// RVA: 0x2f65690 VA: 0x759557d690
	private Void _OnSwitchSortMode() { }
	// RVA: 0x2f65794 VA: 0x759557d794
	private Void _OnSwitchDisplayFeature(OverallDisplayFeature displayFeature) { }
	// RVA: 0x2f65ce8 VA: 0x759557dce8
	protected override Void OnEnter() { }
	// RVA: 0x2f6618c VA: 0x759557e18c
	protected override Void OnPause() { }
	// RVA: 0x2f662a4 VA: 0x759557e2a4
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x2f66350 VA: 0x759557e350
	protected override Void OnResume() { }
	// RVA: 0x2f66464 VA: 0x759557e464
	protected override Void OnExit() { }
	// RVA: 0x2f66504 VA: 0x759557e504
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2f6667c VA: 0x759557e67c
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2f667f4 VA: 0x759557e7f4
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2f66924 VA: 0x759557e924
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2f65e30 VA: 0x759557de30
	private Void _InitIfNot() { }
	// RVA: 0x2f66a54 VA: 0x759557ea54
	private Void _EventOnBackBtnClicked() { }
	// RVA: 0x2f66af8 VA: 0x759557eaf8
	private Void _TutorialIfNeed() { }
	// RVA: 0x2f66c2c VA: 0x759557ec2c
	private IEnumerator _Tutorial_WaitToTriggerSignal() { }
	// RVA: 0x2f65c2c VA: 0x759557dc2c
	private Void _Tutorial_TriggerRetroTutorialIfNeed() { }
	// RVA: 0x2f66d00 VA: 0x759557ed00
	public Void .ctor() { }
	// RVA: 0x2f66d70 VA: 0x759557ed70
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f66d78 VA: 0x759557ed78
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2f66d80 VA: 0x759557ed80
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x2f66d8c VA: 0x759557ed8c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2f66d94 VA: 0x759557ed94
	private Void <>xLuaBaseProxy_OnExit() { }
}
```