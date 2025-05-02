# ClimbTowerEntryState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerTowerEntryView _towerEntryView`

- `RectTransform _topMenuContainer`

- `RectTransform _transRewardHolder`

- `ClimbTowerItemRewardView _rewardPrefab`

- `Boolean m_inited`

- `ClimbTowerMenuAdapter m_menuAdapter`

- `Coroutine m_tutorialCoroutine`

- `ClimbTowerItemRewardView m_rewardView`

- `ClimbTowerSweepResponse m_cachedSweepRes`


## Methods

- `Void _InitIfNot()`

- `IEnumerator _RouteToProperState()`

- `Void _RouteToSweepEndingState(IStateBean)`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitAndTrigTutorial()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnBtnRewardClicked()`

- `Void OnBtnLevelPreviewClicked()`

- `Void OnBtnCreateGameClicked()`

- `Void _OnBtnCancelSweep()`

- `Void _OnBtnStartSweep()`

- `Void _OnSwitchMode()`

- `Void _OnSwitchSweep()`

- `Void _ShowRewardDetail()`

- `Void <_InitIfNot>b__11_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryState : PopupFadeState, IValueMsgReceiver
{
	private ClimbTowerTowerEntryView _towerEntryView; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private RectTransform _transRewardHolder; // 0x80
	private ClimbTowerItemRewardView _rewardPrefab; // 0x88
	private Boolean m_inited; // 0x90
	private ClimbTowerMenuAdapter m_menuAdapter; // 0x98
	private Coroutine m_tutorialCoroutine; // 0xa0
	private ClimbTowerItemRewardView m_rewardView; // 0xa8
	private ClimbTowerSweepResponse m_cachedSweepRes; // 0xb0
	public const Int32 START_SWEEP; // 0x0
	public const Int32 CANCEL_SWEEP; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x18
	private static DelegateBridge __Hotfix0_OnPause; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x30
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x38
	private static DelegateBridge __Hotfix0__RouteToSweepEndingState; // 0x40
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0x48
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x50
	private static DelegateBridge __Hotfix0__WaitAndTrigTutorial; // 0x58
	private static DelegateBridge __Hotfix0_OnMessage; // 0x60
	private static DelegateBridge __Hotfix0_OnBtnRewardClicked; // 0x68
	private static DelegateBridge __Hotfix0_OnBtnLevelPreviewClicked; // 0x70
	private static DelegateBridge __Hotfix0_OnBtnCreateGameClicked; // 0x78
	private static DelegateBridge __Hotfix0__OnBtnCancelSweep; // 0x80
	private static DelegateBridge __Hotfix0__OnBtnStartSweep; // 0x88
	private static DelegateBridge __Hotfix0__OnSwitchMode; // 0x90
	private static DelegateBridge __Hotfix0__OnSwitchSweep; // 0x98
	private static DelegateBridge __Hotfix0__ShowRewardDetail; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x2c914c4 VA: 0x75952a94c4
	private Void _InitIfNot() { }
	// RVA: 0x2c917b0 VA: 0x75952a97b0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c91814 VA: 0x75952a9814
	protected override Void OnEnter() { }
	// RVA: 0x2c91b94 VA: 0x75952a9b94
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x2c91f54 VA: 0x75952a9f54
	protected override Void OnPause() { }
	// RVA: 0x2c92070 VA: 0x75952aa070
	protected override Void OnExit() { }
	// RVA: 0x2c920f0 VA: 0x75952aa0f0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2c92268 VA: 0x75952aa268
	private IEnumerator _RouteToProperState() { }
	// RVA: 0x2c9233c VA: 0x75952aa33c
	private Void _RouteToSweepEndingState(IStateBean sb) { }
	// RVA: 0x2c91eac VA: 0x75952a9eac
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x2c91fc8 VA: 0x75952a9fc8
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2c9241c VA: 0x75952aa41c
	private IEnumerator _WaitAndTrigTutorial() { }
	// RVA: 0x2c924f0 VA: 0x75952aa4f0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2c92d40 VA: 0x75952aad40
	public Void OnBtnRewardClicked() { }
	// RVA: 0x2c92f48 VA: 0x75952aaf48
	public Void OnBtnLevelPreviewClicked() { }
	// RVA: 0x2c93150 VA: 0x75952ab150
	public Void OnBtnCreateGameClicked() { }
	// RVA: 0x2c92b88 VA: 0x75952aab88
	private Void _OnBtnCancelSweep() { }
	// RVA: 0x2c925b0 VA: 0x75952aa5b0
	private Void _OnBtnStartSweep() { }
	// RVA: 0x2c9377c VA: 0x75952ab77c
	private Void _OnSwitchMode() { }
	// RVA: 0x2c93ae4 VA: 0x75952abae4
	private Void _OnSwitchSweep() { }
	// RVA: 0x2c93d90 VA: 0x75952abd90
	private Void _ShowRewardDetail() { }
	// RVA: 0x2c93f10 VA: 0x75952abf10
	public Void .ctor() { }
	// RVA: 0x2c93f80 VA: 0x75952abf80
	private Void <_InitIfNot>b__11_0() { }
	// RVA: 0x2c940f8 VA: 0x75952ac0f8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c94100 VA: 0x75952ac100
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x2c9410c VA: 0x75952ac10c
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2c94114 VA: 0x75952ac114
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2c9411c VA: 0x75952ac11c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```