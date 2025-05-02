# ClimbTowerBuffSelectState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerBuffSelectView _view`

- `RectTransform _backBtnRt`

- `ClimbTowerMenuButton _menuButtonPrefab`

- `ClimbTowerBuffSelectStateBean m_stateBean`

- `MenuAdapter m_menuAdapter`

- `Boolean m_hasInited`

- `Coroutine m_tutorialCoroutine`


## Methods

- `Void _InitIfNot()`

- `Void _OnBuffTabToggle(ProfessionCategory)`

- `Void _OpenCreateSquadState()`

- `TowerTactical _GenerateTactical()`

- `Void _NavToLayerState()`

- `Void _SendSettleGameRequest()`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitAndTrigTutorial()`

- `Void _OnBtnConfirm()`

- `Void OnOpenPlanState()`

- `Void OnBtnQuit()`

- `Void <_SendSettleGameRequest>b__17_0(ClimbTowerSettleGameResponse)`

- `Void <_OnBtnConfirm>b__21_0(ClimbTowerInitGameResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBuffSelectState : PopupFadeState
{
	private ClimbTowerBuffSelectView _view; // 0x70
	private RectTransform _backBtnRt; // 0x78
	private ClimbTowerMenuButton _menuButtonPrefab; // 0x80
	private ClimbTowerBuffSelectStateBean m_stateBean; // 0x88
	private MenuAdapter m_menuAdapter; // 0x90
	private Boolean m_hasInited; // 0x98
	private Coroutine m_tutorialCoroutine; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OnPause; // 0x20
	private static DelegateBridge __Hotfix0__OnBuffTabToggle; // 0x28
	private static DelegateBridge __Hotfix0__OpenCreateSquadState; // 0x30
	private static DelegateBridge __Hotfix0__GenerateTactical; // 0x38
	private static DelegateBridge __Hotfix0__NavToLayerState; // 0x40
	private static DelegateBridge __Hotfix0__SendSettleGameRequest; // 0x48
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0x50
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x58
	private static DelegateBridge __Hotfix0__WaitAndTrigTutorial; // 0x60
	private static DelegateBridge __Hotfix0__OnBtnConfirm; // 0x68
	private static DelegateBridge __Hotfix0_OnOpenPlanState; // 0x70
	private static DelegateBridge __Hotfix0_OnBtnQuit; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x2c894a4 VA: 0x75952a14a4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c8950c VA: 0x75952a150c
	protected override Void OnEnter() { }
	// RVA: 0x2c89740 VA: 0x75952a1740
	private Void _InitIfNot() { }
	// RVA: 0x2c89d1c VA: 0x75952a1d1c
	protected override Void OnResume() { }
	// RVA: 0x2c89e88 VA: 0x75952a1e88
	protected override Void OnPause() { }
	// RVA: 0x2c89fa4 VA: 0x75952a1fa4
	private Void _OnBuffTabToggle(ProfessionCategory profession) { }
	// RVA: 0x2c8a250 VA: 0x75952a2250
	private Void _OpenCreateSquadState() { }
	// RVA: 0x2c8a358 VA: 0x75952a2358
	private TowerTactical _GenerateTactical() { }
	// RVA: 0x2c8a730 VA: 0x75952a2730
	private Void _NavToLayerState() { }
	// RVA: 0x2c8a8ac VA: 0x75952a28ac
	private Void _SendSettleGameRequest() { }
	// RVA: 0x2c89de0 VA: 0x75952a1de0
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x2c89efc VA: 0x75952a1efc
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2c8aa7c VA: 0x75952a2a7c
	private IEnumerator _WaitAndTrigTutorial() { }
	// RVA: 0x2c8ab50 VA: 0x75952a2b50
	private Void _OnBtnConfirm() { }
	// RVA: 0x2c8ae74 VA: 0x75952a2e74
	public Void OnOpenPlanState() { }
	// RVA: 0x2c8af7c VA: 0x75952a2f7c
	public Void OnBtnQuit() { }
	// RVA: 0x2c8b200 VA: 0x75952a3200
	public Void .ctor() { }
	// RVA: 0x2c8b358 VA: 0x75952a3358
	private Void <_SendSettleGameRequest>b__17_0(ClimbTowerSettleGameResponse response) { }
	// RVA: 0x2c8b35c VA: 0x75952a335c
	private Void <_OnBtnConfirm>b__21_0(ClimbTowerInitGameResponse response) { }
	// RVA: 0x2c8b360 VA: 0x75952a3360
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c8b368 VA: 0x75952a3368
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2c8b370 VA: 0x75952a3370
	private Void <>xLuaBaseProxy_OnPause() { }
}
```