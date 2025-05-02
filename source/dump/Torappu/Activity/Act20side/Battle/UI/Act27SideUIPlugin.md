# Act27SideUIPlugin

**Namespace:** `Torappu.Activity.Act20side.Battle.UI`


## Fields

- `Int32 m_maxPlayTime`

- `Int32 m_playTime`

- `Act27SideGameMode m_gameMode`

- `Int32 m_nervousCount`

- `Int32 m_angryCount`

- `Int32 m_highlightSeconds`

- `Text _timerText`

- `Text _countText`

- `Transform _countDownHighlight`

- `Transform _normalSheep`

- `Transform _nervousSheep`

- `Transform _angrySheep`

- `Slider _slider`


## Methods

- `Void _UpdateTimeInfo()`

- `Void _UpdateCountInfo()`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnGameReady()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam)`

- `Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side.Battle.UI
public class Act27SideUIPlugin : Plugin
{
	public static readonly UIStateEnum UI_STATE_BATTLE_ACCOMPLISHED; // 0x0
	public static readonly UIStateEnum UI_STATE_BATTLE_FAILED; // 0x4
	private Int32 m_maxPlayTime; // 0x28
	private Int32 m_playTime; // 0x2c
	private Act27SideGameMode m_gameMode; // 0x30
	private Int32 m_nervousCount; // 0x38
	private Int32 m_angryCount; // 0x3c
	private Int32 m_highlightSeconds; // 0x40
	private Text _timerText; // 0x48
	private Text _countText; // 0x50
	private List`1 _states; // 0x58
	private Transform _countDownHighlight; // 0x60
	private Transform _normalSheep; // 0x68
	private Transform _nervousSheep; // 0x70
	private Transform _angrySheep; // 0x78
	private Slider _slider; // 0x80
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x8
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x10
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x18
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x20
	private static DelegateBridge __Hotfix0__UpdateTimeInfo; // 0x28
	private static DelegateBridge __Hotfix0__UpdateCountInfo; // 0x30
	private static DelegateBridge __Hotfix0_HookBattleFailedStateSwitch; // 0x38
	private static DelegateBridge __Hotfix0_HookBattleAccomplishedStateSwitch; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3307630 VA: 0x759591f630
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x33076f0 VA: 0x759591f6f0
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x3307848 VA: 0x759591f848
	public override Void OnGameReady() { }
	// RVA: 0x3307a34 VA: 0x759591fa34
	public override Void UpdateGameInfo() { }
	// RVA: 0x3307ac0 VA: 0x759591fac0
	private Void _UpdateTimeInfo() { }
	// RVA: 0x3307ca4 VA: 0x759591fca4
	private Void _UpdateCountInfo() { }
	// RVA: 0x3307eac VA: 0x759591feac
	public override Boolean HookBattleFailedStateSwitch(BattleFailedStateParam param) { }
	// RVA: 0x3307ff8 VA: 0x759591fff8
	public override Boolean HookBattleAccomplishedStateSwitch() { }
	// RVA: 0x33080d4 VA: 0x75959200d4
	public Void .ctor() { }
	// RVA: 0x3308164 VA: 0x7595920164
	private static Void .cctor() { }
	// RVA: 0x33081b4 VA: 0x75959201b4
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x33081bc VA: 0x75959201bc
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x33081c4 VA: 0x75959201c4
	private Void <>xLuaBaseProxy_OnGameReady() { }
	// RVA: 0x33081cc VA: 0x75959201cc
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x33081d4 VA: 0x75959201d4
	private Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam P0) { }
	// RVA: 0x33081e0 VA: 0x75959201e0
	private Boolean <>xLuaBaseProxy_HookBattleAccomplishedStateSwitch() { }
}
```