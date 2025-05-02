# UIRoguelikePluginRL04

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIRoguelikeBattleFailedMask _battleFailedMaskPrefab`

- `UIGoldStealBattleToastPanelRL04 _goldStealBattleToastPrefab`

- `UIDisasterContinueBattleToastPanelRL04 _disasterContinueBattleToastPrefab`

- `UISkzddPreachBattleToastPanelRL04 _skzddPreachBattleToastPrefab`

- `UIGoldStealBattleToastPanelRL04 m_goldStealToast`

- `UIDisasterContinueBattleToastPanelRL04 m_disasterContinueToast`

- `UISkzddPreachBattleToastPanelRL04 m_skzddPreachToast`

- `UIRoguelikeBattleFailedMask m_failedPanel`


## Methods

- `Void _InitFailedPanel()`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch()`

- `Boolean <>xLuaBaseProxy_HookConfirmFinish(Action)`

- `RectTransform <>xLuaBaseProxy_HookBattleFailedPanelInit()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedPanelShow()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedPanelHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIRoguelikePluginRL04 : Plugin
{
	public static readonly UIStateEnum UI_STATE_MOVE_CAMERA; // 0x0
	private UIRoguelikeBattleFailedMask _battleFailedMaskPrefab; // 0x28
	private UIGoldStealBattleToastPanelRL04 _goldStealBattleToastPrefab; // 0x30
	private UIDisasterContinueBattleToastPanelRL04 _disasterContinueBattleToastPrefab; // 0x38
	private UISkzddPreachBattleToastPanelRL04 _skzddPreachBattleToastPrefab; // 0x40
	private UIStateNode[] _states; // 0x48
	private UIGoldStealBattleToastPanelRL04 m_goldStealToast; // 0x50
	private UIDisasterContinueBattleToastPanelRL04 m_disasterContinueToast; // 0x58
	private UISkzddPreachBattleToastPanelRL04 m_skzddPreachToast; // 0x60
	private UIRoguelikeBattleFailedMask m_failedPanel; // 0x68
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x10
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x18
	private static DelegateBridge __Hotfix0_HookGameReadyStateSwitch; // 0x20
	private static DelegateBridge __Hotfix0_HookConfirmFinish; // 0x28
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelInit; // 0x30
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelShow; // 0x38
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelHide; // 0x40
	private static DelegateBridge __Hotfix0__InitFailedPanel; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2075130 VA: 0x759468d130
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x2075480 VA: 0x759468d480
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x2075630 VA: 0x759468d630
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x2075860 VA: 0x759468d860
	public override Boolean HookGameReadyStateSwitch() { }
	// RVA: 0x2075a1c VA: 0x759468da1c
	public override Boolean HookConfirmFinish(Action finishCallback) { }
	// RVA: 0x2075bb0 VA: 0x759468dbb0
	public override RectTransform HookBattleFailedPanelInit() { }
	// RVA: 0x2075c38 VA: 0x759468dc38
	public override Boolean HookBattleFailedPanelShow() { }
	// RVA: 0x2075ce4 VA: 0x759468dce4
	public override Boolean HookBattleFailedPanelHide() { }
	// RVA: 0x20753e0 VA: 0x759468d3e0
	private Void _InitFailedPanel() { }
	// RVA: 0x2075d6c VA: 0x759468dd6c
	public Void .ctor() { }
	// RVA: 0x2075e28 VA: 0x759468de28
	private static Void .cctor() { }
	// RVA: 0x2075e74 VA: 0x759468de74
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x2075e7c VA: 0x759468de7c
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x2075e84 VA: 0x759468de84
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x2075e8c VA: 0x759468de8c
	private Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch() { }
	// RVA: 0x2075e94 VA: 0x759468de94
	private Boolean <>xLuaBaseProxy_HookConfirmFinish(Action P0) { }
	// RVA: 0x2075e9c VA: 0x759468de9c
	private RectTransform <>xLuaBaseProxy_HookBattleFailedPanelInit() { }
	// RVA: 0x2075ea4 VA: 0x759468dea4
	private Boolean <>xLuaBaseProxy_HookBattleFailedPanelShow() { }
	// RVA: 0x2075eac VA: 0x759468deac
	private Boolean <>xLuaBaseProxy_HookBattleFailedPanelHide() { }
}
```