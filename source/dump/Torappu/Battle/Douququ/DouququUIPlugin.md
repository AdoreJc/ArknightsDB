# DouququUIPlugin

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `UIBattleDouququBetPanel _betPanel`

- `DouququGameMode m_gameMode`

- `UIBattleDouququBetPanel m_betPanel`

- `SpeedLevel m_cacheSpeedLevel`

- `Boolean m_isInBet`


## Methods

- `Void OnAnnounceEnd(Boolean)`

- `Void OnBetEnd()`

- `Void OnRoundEndOver(Boolean)`

- `Void _ShowBetPanel()`

- `Void _HideBetPanel()`

- `Void _HookUITopBar()`

- `Void _OnCurWaveWillFinish(Single)`

- `Void _OnCurWaveWillStart(Single)`

- `Void <OnGameReset>b__9_0(Object)`

- `Void <OnGameReset>b__9_1(Object)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnGameReset(BattleController)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Boolean <>xLuaBaseProxy_HookPauseMask(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class DouququUIPlugin : Plugin
{
	public static readonly UIStateEnum UI_STATE_ANNOUNCE; // 0x0
	public static readonly UIStateEnum UI_STATE_ROUND_END; // 0x4
	private UIStateNode[] _states; // 0x28
	private UIBattleDouququBetPanel _betPanel; // 0x30
	private DouququGameMode m_gameMode; // 0x38
	private UIBattleDouququBetPanel m_betPanel; // 0x40
	private SpeedLevel m_cacheSpeedLevel; // 0x48
	private Boolean m_isInBet; // 0x4c
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x8
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x10
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x18
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x20
	private static DelegateBridge __Hotfix0_OnCreate; // 0x28
	private static DelegateBridge __Hotfix0_HookPauseMask; // 0x30
	private static DelegateBridge __Hotfix0_OnAnnounceEnd; // 0x38
	private static DelegateBridge __Hotfix0_OnBetEnd; // 0x40
	private static DelegateBridge __Hotfix0_OnRoundEndOver; // 0x48
	private static DelegateBridge __Hotfix0__ShowBetPanel; // 0x50
	private static DelegateBridge __Hotfix0__HideBetPanel; // 0x58
	private static DelegateBridge __Hotfix0__HookUITopBar; // 0x60
	private static DelegateBridge __Hotfix0__OnCurWaveWillFinish; // 0x68
	private static DelegateBridge __Hotfix0__OnCurWaveWillStart; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x1dd5f6c VA: 0x75943edf6c
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x1dd6184 VA: 0x75943ee184
	public override Void OnGameReset(BattleController battleController) { }
	// RVA: 0x1dd6314 VA: 0x75943ee314
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x1dd6458 VA: 0x75943ee458
	public override Void OnGameStart() { }
	// RVA: 0x1dd654c VA: 0x75943ee54c
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x1dd66f8 VA: 0x75943ee6f8
	public override Boolean HookPauseMask(Boolean isPause) { }
	// RVA: 0x1dd6784 VA: 0x75943ee784
	public Void OnAnnounceEnd(Boolean isFirst) { }
	// RVA: 0x1dd6950 VA: 0x75943ee950
	public Void OnBetEnd() { }
	// RVA: 0x1dd5d04 VA: 0x75943edd04
	public Void OnRoundEndOver(Boolean isFinish) { }
	// RVA: 0x1dd6878 VA: 0x75943ee878
	private Void _ShowBetPanel() { }
	// RVA: 0x1dd6a48 VA: 0x75943eea48
	private Void _HideBetPanel() { }
	// RVA: 0x1dd60e4 VA: 0x75943ee0e4
	private Void _HookUITopBar() { }
	// RVA: 0x1dd6b5c VA: 0x75943eeb5c
	private Void _OnCurWaveWillFinish(Single postDelay) { }
	// RVA: 0x1dd6c68 VA: 0x75943eec68
	private Void _OnCurWaveWillStart(Single preDelay) { }
	// RVA: 0x1dd6db4 VA: 0x75943eedb4
	public Void .ctor() { }
	// RVA: 0x1dd6e78 VA: 0x75943eee78
	private static Void .cctor() { }
	// RVA: 0x1dd6ec8 VA: 0x75943eeec8
	private Void <OnGameReset>b__9_0(Object arg) { }
	// RVA: 0x1dd6f3c VA: 0x75943eef3c
	private Void <OnGameReset>b__9_1(Object arg) { }
	// RVA: 0x1dd6fb0 VA: 0x75943eefb0
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x1dd6fb8 VA: 0x75943eefb8
	private Void <>xLuaBaseProxy_OnGameReset(BattleController P0) { }
	// RVA: 0x1dd6fc0 VA: 0x75943eefc0
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x1dd6fc8 VA: 0x75943eefc8
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x1dd6fd0 VA: 0x75943eefd0
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x1dd6fd8 VA: 0x75943eefd8
	private Boolean <>xLuaBaseProxy_HookPauseMask(Boolean P0) { }
}
```