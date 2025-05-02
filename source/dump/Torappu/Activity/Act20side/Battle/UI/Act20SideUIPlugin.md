# Act20SideUIPlugin

**Namespace:** `Torappu.Activity.Act20side.Battle.UI`


## Fields

- `Transform _battleAccomplishedPanel`

- `TopBarStatus _topBar`

- `BattleController m_battleController`

- `UIController m_uiController`

- `Act20SideGameMode m_gameMode`


## Methods

- `Void _InitLayout()`

- `Void UpdateScore(Int32)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_OnGameReady()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam)`

- `Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch()`

- `Void <>xLuaBaseProxy_HookBattleData(BattleData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side.Battle.UI
public class Act20SideUIPlugin : Plugin
{
	public static readonly UIStateEnum UI_STATE_BATTLE_ACCOMPLISHED; // 0x0
	private List`1 _states; // 0x28
	private Transform _battleAccomplishedPanel; // 0x30
	private TopBarStatus _topBar; // 0x38
	private BattleController m_battleController; // 0x40
	private UIController m_uiController; // 0x48
	private Act20SideGameMode m_gameMode; // 0x50
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x8
	private static DelegateBridge __Hotfix0__InitLayout; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x20
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x28
	private static DelegateBridge __Hotfix0_UpdateScore; // 0x30
	private static DelegateBridge __Hotfix0_HookBattleFailedStateSwitch; // 0x38
	private static DelegateBridge __Hotfix0_HookBattleAccomplishedStateSwitch; // 0x40
	private static DelegateBridge __Hotfix0_HookBattleData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x33052c0 VA: 0x759591d2c0
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x3305418 VA: 0x759591d418
	private Void _InitLayout() { }
	// RVA: 0x33054bc VA: 0x759591d4bc
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x33055b0 VA: 0x759591d5b0
	public override Void OnGameReady() { }
	// RVA: 0x33058c4 VA: 0x759591d8c4
	public override Void UpdateGameInfo() { }
	// RVA: 0x3305954 VA: 0x759591d954
	public Void UpdateScore(Int32 value) { }
	// RVA: 0x3305c94 VA: 0x759591dc94
	public override Boolean HookBattleFailedStateSwitch(BattleFailedStateParam param) { }
	// RVA: 0x3305de0 VA: 0x759591dde0
	public override Boolean HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x3305ebc VA: 0x759591debc
	public override Void HookBattleData(BattleData battleData) { }
	// RVA: 0x3305fb4 VA: 0x759591dfb4
	public Void .ctor() { }
	// RVA: 0x3306034 VA: 0x759591e034
	private static Void .cctor() { }
	// RVA: 0x3306080 VA: 0x759591e080
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x3306088 VA: 0x759591e088
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x3306090 VA: 0x759591e090
	private Void <>xLuaBaseProxy_OnGameReady() { }
	// RVA: 0x3306098 VA: 0x759591e098
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x33060a0 VA: 0x759591e0a0
	private Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam P0) { }
	// RVA: 0x33060ac VA: 0x759591e0ac
	private Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x33060b4 VA: 0x759591e0b4
	private Void <>xLuaBaseProxy_HookBattleData(BattleData P0) { }
}
```