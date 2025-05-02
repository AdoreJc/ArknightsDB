# RoguelikeDuelUIPlugin

**Namespace:** `Torappu.Battle.Roguelike.Duel`


## Fields

- `RoguelikeDuelUIBattlePanel _duelBattlePanel`

- `RoguelikeDuelUIChosenPanel _duelChosenPanel`

- `GameObject _globalMask`

- `RoguelikeDuelUIBattlePanel m_battlePanel`

- `RoguelikeDuelUIChosenPanel m_chosenPanel`

- `RoguelikeDuelGameMode m_gameMode`


## Methods

- `Void OnDuelBattleStart()`

- `Void _HookBattleUIPanel()`

- `Void _DetachChosenUIPanel()`

- `Void _HideOriUIPanel()`

- `Void _ActiveChosenUIPanel()`

- `Void _OnDuelBattlePreStart(Object)`

- `Void _OnStartMoveCamera(Object)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam)`

- `Boolean <>xLuaBaseProxy_HookConfirmFinish(Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Duel
public class RoguelikeDuelUIPlugin : Plugin
{
	public static readonly Event ON_START_MOVE_CAMERA; // 0x0
	public static readonly Event ON_DUEL_BATTLE_PRE_START; // 0x4
	public static readonly Event ON_REAL_DUEL_START; // 0x8
	public static readonly UIStateEnum ON_MOVE_CAMERA_STATE; // 0xc
	public static readonly UIStateEnum ON_BATTLE_FINISH_STATE; // 0x10
	private UIStateNode[] _states; // 0x28
	private RoguelikeDuelUIBattlePanel _duelBattlePanel; // 0x30
	private RoguelikeDuelUIChosenPanel _duelChosenPanel; // 0x38
	private GameObject _globalMask; // 0x40
	private RoguelikeDuelUIBattlePanel m_battlePanel; // 0x48
	private RoguelikeDuelUIChosenPanel m_chosenPanel; // 0x50
	private RoguelikeDuelGameMode m_gameMode; // 0x58
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x18
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x20
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x28
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x30
	private static DelegateBridge __Hotfix0_HookBattleAccomplishedStateSwitch; // 0x38
	private static DelegateBridge __Hotfix0_HookBattleFailedStateSwitch; // 0x40
	private static DelegateBridge __Hotfix0_HookConfirmFinish; // 0x48
	private static DelegateBridge __Hotfix0_OnDuelBattleStart; // 0x50
	private static DelegateBridge __Hotfix0__HookBattleUIPanel; // 0x58
	private static DelegateBridge __Hotfix0__DetachChosenUIPanel; // 0x60
	private static DelegateBridge __Hotfix0__HideOriUIPanel; // 0x68
	private static DelegateBridge __Hotfix0__ActiveChosenUIPanel; // 0x70
	private static DelegateBridge __Hotfix0__OnDuelBattlePreStart; // 0x78
	private static DelegateBridge __Hotfix0__OnStartMoveCamera; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x1d4c90c VA: 0x759436490c
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x1d4cc70 VA: 0x7594364c70
	public override Void OnGameStart() { }
	// RVA: 0x1d4cde8 VA: 0x7594364de8
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x1d4cf2c VA: 0x7594364f2c
	public override Void UpdateGameInfo() { }
	// RVA: 0x1d4d03c VA: 0x759436503c
	public override Boolean HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x1d4d118 VA: 0x7594365118
	public override Boolean HookBattleFailedStateSwitch(BattleFailedStateParam param) { }
	// RVA: 0x1d4d208 VA: 0x7594365208
	public override Boolean HookConfirmFinish(Action finishCallback) { }
	// RVA: 0x1d4d39c VA: 0x759436539c
	public Void OnDuelBattleStart() { }
	// RVA: 0x1d4d470 VA: 0x7594365470
	private Void _HookBattleUIPanel() { }
	// RVA: 0x1d4d570 VA: 0x7594365570
	private Void _DetachChosenUIPanel() { }
	// RVA: 0x1d4cbb8 VA: 0x7594364bb8
	private Void _HideOriUIPanel() { }
	// RVA: 0x1d4cce8 VA: 0x7594364ce8
	private Void _ActiveChosenUIPanel() { }
	// RVA: 0x1d4d648 VA: 0x7594365648
	private Void _OnDuelBattlePreStart(Object args) { }
	// RVA: 0x1d4d734 VA: 0x7594365734
	private Void _OnStartMoveCamera(Object args) { }
	// RVA: 0x1d4d7d8 VA: 0x75943657d8
	public Void .ctor() { }
	// RVA: 0x1d4d894 VA: 0x7594365894
	private static Void .cctor() { }
	// RVA: 0x1d4d8ec VA: 0x75943658ec
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x1d4d8f4 VA: 0x75943658f4
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x1d4d8fc VA: 0x75943658fc
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x1d4d904 VA: 0x7594365904
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x1d4d90c VA: 0x759436590c
	private Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x1d4d914 VA: 0x7594365914
	private Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam P0) { }
	// RVA: 0x1d4d920 VA: 0x7594365920
	private Boolean <>xLuaBaseProxy_HookConfirmFinish(Action P0) { }
}
```