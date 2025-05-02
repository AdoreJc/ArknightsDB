# Act38sideUIPlugin

**Namespace:** `Torappu.Activity.Act38side.Battle.UI`


## Fields

- `String _envSystemKey`

- `GameObject _carnivalPanel`

- `Text _allyKillCnt`

- `UIParticle _allyParticle`

- `Text _bossKillCnt`

- `UIParticle _bossParticle`

- `Single _keepTime`

- `AnimationWrapper _animWrapper`

- `Act38SideBattleManager m_envManager`

- `Act38sideUIPluginStateEnum m_state`

- `Boolean m_isDuringCarnival`

- `Boolean m_hasGameStarted`

- `Boolean m_isValid`

- `Int32 m_allyCnt`

- `Int32 m_bossCnt`

- `Tween m_animTween`


## Properties

- `Int32 allyKillCnt`

- `Int32 bossKillCnt`


## Methods

- `Int32 get_allyKillCnt()`

- `Int32 get_bossKillCnt()`

- `Boolean _CheckAllResourcesValid()`

- `Boolean _InitAllMembers()`

- `Void _OnCarnivalStateChanged()`

- `Boolean _SwitchState(Act38sideUIPluginStateEnum)`

- `Void _OnCarnivalStart()`

- `Void _OnAllyWin()`

- `Void _OnBossWin()`

- `Void _OnBossKilled()`

- `Void _SwitchToEndState()`

- `Void _OnCarnivalEnd()`

- `Void <_OnAllyWin>b__34_0()`

- `Void <_OnBossWin>b__35_0()`

- `Void <_OnBossKilled>b__36_0()`

- `Void <_OnCarnivalEnd>b__38_0()`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Void <>xLuaBaseProxy_OnGameOver(GameResult)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act38side.Battle.UI
public class Act38sideUIPlugin : Plugin
{
	private String _envSystemKey; // 0x28
	private GameObject _carnivalPanel; // 0x30
	private Text _allyKillCnt; // 0x38
	private UIParticle _allyParticle; // 0x40
	private Text _bossKillCnt; // 0x48
	private UIParticle _bossParticle; // 0x50
	private Single _keepTime; // 0x58
	private AnimationWrapper _animWrapper; // 0x60
	private Act38SideBattleManager m_envManager; // 0x68
	private Act38sideUIPluginStateEnum m_state; // 0x70
	private Boolean m_isDuringCarnival; // 0x74
	private Boolean m_hasGameStarted; // 0x75
	private Boolean m_isValid; // 0x76
	private Int32 m_allyCnt; // 0x78
	private Int32 m_bossCnt; // 0x7c
	private Tween m_animTween; // 0x80
	private const String START_ANIM; // 0x0
	private const String BOSS_WIN_ANIM; // 0x0
	private const String ALLY_WIN_ANIM; // 0x0
	private const String BOSS_KILLED_ANIM; // 0x0
	private const String END_ANIM; // 0x0
	private static DelegateBridge __Hotfix0_get_allyKillCnt; // 0x0
	private static DelegateBridge __Hotfix0_get_bossKillCnt; // 0x8
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x10
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x18
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x20
	private static DelegateBridge __Hotfix0__CheckAllResourcesValid; // 0x28
	private static DelegateBridge __Hotfix0__InitAllMembers; // 0x30
	private static DelegateBridge __Hotfix0__OnCarnivalStateChanged; // 0x38
	private static DelegateBridge __Hotfix0__SwitchState; // 0x40
	private static DelegateBridge __Hotfix0__OnCarnivalStart; // 0x48
	private static DelegateBridge __Hotfix0__OnAllyWin; // 0x50
	private static DelegateBridge __Hotfix0__OnBossWin; // 0x58
	private static DelegateBridge __Hotfix0__OnBossKilled; // 0x60
	private static DelegateBridge __Hotfix0__SwitchToEndState; // 0x68
	private static DelegateBridge __Hotfix0__OnCarnivalEnd; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private Int32 allyKillCnt { get; }
	private Int32 bossKillCnt { get; }

	// RVA: 0x3240ca4 VA: 0x7595858ca4
	private Int32 get_allyKillCnt() { }
	// RVA: 0x3240d18 VA: 0x7595858d18
	private Int32 get_bossKillCnt() { }
	// RVA: 0x3240d8c VA: 0x7595858d8c
	public override Void OnGameStart() { }
	// RVA: 0x3241188 VA: 0x7595859188
	public override Void UpdateGameInfo() { }
	// RVA: 0x32413dc VA: 0x75958593dc
	public override Void OnGameOver(GameResult result) { }
	// RVA: 0x3240e7c VA: 0x7595858e7c
	private Boolean _CheckAllResourcesValid() { }
	// RVA: 0x3240fec VA: 0x7595858fec
	private Boolean _InitAllMembers() { }
	// RVA: 0x3241320 VA: 0x7595859320
	private Void _OnCarnivalStateChanged() { }
	// RVA: 0x32414b0 VA: 0x75958594b0
	private Boolean _SwitchState(Act38sideUIPluginStateEnum nextState) { }
	// RVA: 0x3241678 VA: 0x7595859678
	private Void _OnCarnivalStart() { }
	// RVA: 0x3241790 VA: 0x7595859790
	private Void _OnAllyWin() { }
	// RVA: 0x32418e8 VA: 0x75958598e8
	private Void _OnBossWin() { }
	// RVA: 0x3241a40 VA: 0x7595859a40
	private Void _OnBossKilled() { }
	// RVA: 0x3241cf0 VA: 0x7595859cf0
	private Void _SwitchToEndState() { }
	// RVA: 0x3241b98 VA: 0x7595859b98
	private Void _OnCarnivalEnd() { }
	// RVA: 0x3241d5c VA: 0x7595859d5c
	public Void .ctor() { }
	// RVA: 0x3241e04 VA: 0x7595859e04
	private Void <_OnAllyWin>b__34_0() { }
	// RVA: 0x3241e88 VA: 0x7595859e88
	private Void <_OnBossWin>b__35_0() { }
	// RVA: 0x3241f0c VA: 0x7595859f0c
	private Void <_OnBossKilled>b__36_0() { }
	// RVA: 0x3241f90 VA: 0x7595859f90
	private Void <_OnCarnivalEnd>b__38_0() { }
	// RVA: 0x3242090 VA: 0x759585a090
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x3242098 VA: 0x759585a098
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x32420a0 VA: 0x759585a0a0
	private Void <>xLuaBaseProxy_OnGameOver(GameResult P0) { }
}
```