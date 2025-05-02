# StrifeUIPlugin

**Namespace:** `Torappu.Battle.Strife`


## Fields

- `BasicStatus _basicStatus`

- `UIBattleStrifeLastWavePanel _lastWavePanel`

- `UIBattleStrifeTopBar _topBarWaveInfo`

- `UIBattleBlurPanel _blurPanel`

- `StrifeGameMode m_gameMode`

- `UIBattleStrifeLastWavePanel m_lastWavePanel`

- `Int32 m_curWave`

- `Int32 m_totalWave`


## Properties

- `Int32 finishWave`

- `Int32 totalWave`


## Methods

- `Int32 get_finishWave()`

- `Int32 get_totalWave()`

- `Void UpdateRemainingDuration(Single, Int32)`

- `Void UpdateWaveInfo(Int32, Int32)`

- `Void _PreloadAssets()`

- `Void _OnCurWaveWillFinish(Single)`

- `Void _HookUITopBar()`

- `Void CloseSystemMenuPanel()`

- `Void FinishGameDirectly()`

- `Void <OnGameReset>b__14_0(Object)`

- `Void <>xLuaBaseProxy_OnGameReset(BattleController)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch()`

- `Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Strife
public class StrifeUIPlugin : Plugin
{
	public static readonly UIStateEnum UI_STATE_SYSTEM_MENU; // 0x0
	private BasicStatus _basicStatus; // 0x28
	private UIStateNode[] _states; // 0x30
	private UIBattleStrifeLastWavePanel _lastWavePanel; // 0x38
	private UIBattleStrifeTopBar _topBarWaveInfo; // 0x40
	private UIBattleBlurPanel _blurPanel; // 0x48
	private StrifeGameMode m_gameMode; // 0x50
	private UIBattleStrifeLastWavePanel m_lastWavePanel; // 0x58
	private Int32 m_curWave; // 0x60
	private Int32 m_totalWave; // 0x64
	private static DelegateBridge __Hotfix0_get_finishWave; // 0x8
	private static DelegateBridge __Hotfix0_get_totalWave; // 0x10
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x18
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x20
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x28
	private static DelegateBridge __Hotfix0_OnCreate; // 0x30
	private static DelegateBridge __Hotfix0_UpdateRemainingDuration; // 0x38
	private static DelegateBridge __Hotfix0_UpdateWaveInfo; // 0x40
	private static DelegateBridge __Hotfix0__PreloadAssets; // 0x48
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x50
	private static DelegateBridge __Hotfix0__OnCurWaveWillFinish; // 0x58
	private static DelegateBridge __Hotfix0_HookBattleSystemMenuSwitch; // 0x60
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x68
	private static DelegateBridge __Hotfix0__HookUITopBar; // 0x70
	private static DelegateBridge __Hotfix0_CloseSystemMenuPanel; // 0x78
	private static DelegateBridge __Hotfix0_FinishGameDirectly; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Int32 finishWave { get; }
	public Int32 totalWave { get; }

	// RVA: 0x1c594ac VA: 0x75942714ac
	public Int32 get_finishWave() { }
	// RVA: 0x1c59524 VA: 0x7594271524
	public Int32 get_totalWave() { }
	// RVA: 0x1c59b98 VA: 0x7594271b98
	public override Void OnGameReset(BattleController battleController) { }
	// RVA: 0x1c59cbc VA: 0x7594271cbc
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x1c59f80 VA: 0x7594271f80
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x1c5a0c4 VA: 0x75942720c4
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x1c5a344 VA: 0x7594272344
	public Void UpdateRemainingDuration(Single remainingDuration, Int32 totalDuration) { }
	// RVA: 0x1c5a408 VA: 0x7594272408
	public Void UpdateWaveInfo(Int32 curWave, Int32 totalWave) { }
	// RVA: 0x1c5a1b0 VA: 0x75942721b0
	private Void _PreloadAssets() { }
	// RVA: 0x1c5a4b0 VA: 0x75942724b0
	public override Void UpdateGameInfo() { }
	// RVA: 0x1c5a53c VA: 0x759427253c
	private Void _OnCurWaveWillFinish(Single showTime) { }
	// RVA: 0x1c5a5d4 VA: 0x75942725d4
	public override Boolean HookBattleSystemMenuSwitch() { }
	// RVA: 0x1c5a708 VA: 0x7594272708
	public override Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x1c59e28 VA: 0x7594271e28
	private Void _HookUITopBar() { }
	// RVA: 0x1c59694 VA: 0x7594271694
	public Void CloseSystemMenuPanel() { }
	// RVA: 0x1c59744 VA: 0x7594271744
	public Void FinishGameDirectly() { }
	// RVA: 0x1c5a860 VA: 0x7594272860
	public Void .ctor() { }
	// RVA: 0x1c5a924 VA: 0x7594272924
	private static Void .cctor() { }
	// RVA: 0x1c5a970 VA: 0x7594272970
	private Void <OnGameReset>b__14_0(Object arg) { }
	// RVA: 0x1c5a9e4 VA: 0x75942729e4
	private Void <>xLuaBaseProxy_OnGameReset(BattleController P0) { }
	// RVA: 0x1c5a9ec VA: 0x75942729ec
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x1c5a9f4 VA: 0x75942729f4
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x1c5a9fc VA: 0x75942729fc
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x1c5aa04 VA: 0x7594272a04
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x1c5aa0c VA: 0x7594272a0c
	private Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch() { }
	// RVA: 0x1c5aa14 VA: 0x7594272a14
	private Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode P0) { }
}
```