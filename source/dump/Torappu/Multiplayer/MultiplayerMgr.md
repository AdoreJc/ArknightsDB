# MultiplayerMgr

**Namespace:** `Torappu.Multiplayer`


## Fields

- `MultiBattlePhase m_curPhase`

- `IMultiplayerMode m_mode`

- `String <partnerID>k__BackingField`

- `MultiplayerActParam <actParam>k__BackingField`

- `Boolean <battlePausing>k__BackingField`

- `Boolean <battleFastMode>k__BackingField`


## Properties

- `IMultiplayerMode mode`

- `String playerID`

- `String partnerID`

- `TeamInfo teamInfo`

- `BattleInfo battleInfo`

- `MultiplayerActParam actParam`

- `MultiplayerSetting setting`

- `Boolean battlePausing`

- `Boolean battleFastMode`

- `Boolean isReal`

- `Boolean isReplay`

- `Object cachedPlayerInfoForBattle`


## Methods

- `IMultiplayerMode get_mode()`

- `Void Dispose()`

- `Void _HandleSceneChanged(String, String)`

- `Void set_eventPool(EventPool`1)`

- `String get_playerID()`

- `String get_partnerID()`

- `Void set_partnerID(String)`

- `TeamInfo get_teamInfo()`

- `BattleInfo get_battleInfo()`

- `MultiplayerActParam get_actParam()`

- `Void set_actParam(MultiplayerActParam)`

- `MultiplayerSetting get_setting()`

- `Boolean get_battlePausing()`

- `Void set_battlePausing(Boolean)`

- `Boolean get_battleFastMode()`

- `Void set_battleFastMode(Boolean)`

- `Boolean get_isReal()`

- `Boolean get_isReplay()`

- `Object get_cachedPlayerInfoForBattle()`

- `Void UpdateStatus()`

- `Boolean SendRequest(RequestType, Object)`

- `Void RevStep(StepData)`

- `Void Update()`

- `Void FixedUpdate()`

- `Void OnGUI()`

- `Void Alert(String, ShowCondition, ProcWhenForbid)`

- `STPlayerStatus GetPlayerStatusByPlayerId(String)`

- `T _ChangeMode()`

- `T _ChangePhase()`

- `Void _CheckMySideAndStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class MultiplayerMgr : IDisposable, IHotfixable
{
	private static MultiplayerMgr s_instance; // 0x0
	private const String REPLAY_ACT_ID; // 0x0
	private MultiBattlePhase m_curPhase; // 0x10
	private IMultiplayerMode m_mode; // 0x18
	private EventPool`1 <eventPool>k__BackingField; // 0x20
	private String <partnerID>k__BackingField; // 0x28
	private MultiplayerActParam <actParam>k__BackingField; // 0x30
	private Boolean <battlePausing>k__BackingField; // 0xa0
	private Boolean <battleFastMode>k__BackingField; // 0xa1
	private static List`1 s_alerts; // 0x8
	private static DelegateBridge __Hotfix0_get_hasInstance; // 0x10
	private static DelegateBridge __Hotfix0_get_instance; // 0x18
	private static DelegateBridge __Hotfix0__Setup; // 0x20
	private static DelegateBridge __Hotfix0_get_started; // 0x28
	private static DelegateBridge __Hotfix0_Stop; // 0x30
	private static DelegateBridge __Hotfix0__StartImpl; // 0x38
	private static DelegateBridge __Hotfix0_StartWithLoadMask; // 0x40
	private static DelegateBridge __Hotfix0_Replay; // 0x48
	private static DelegateBridge __Hotfix1_Replay; // 0x50
	private static DelegateBridge __Hotfix0_get_curMode; // 0x58
	private static DelegateBridge __Hotfix0_get_mode; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68
	private static DelegateBridge __Hotfix0_Dispose; // 0x70
	private static DelegateBridge __Hotfix0__HandleSceneChanged; // 0x78
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x80
	private static DelegateBridge __Hotfix0_set_eventPool; // 0x88
	private static DelegateBridge __Hotfix0_get_playerID; // 0x90
	private static DelegateBridge __Hotfix0_get_partnerID; // 0x98
	private static DelegateBridge __Hotfix0_set_partnerID; // 0xa0
	private static DelegateBridge __Hotfix0_get_teamInfo; // 0xa8
	private static DelegateBridge __Hotfix0_get_battleInfo; // 0xb0
	private static DelegateBridge __Hotfix0_get_actParam; // 0xb8
	private static DelegateBridge __Hotfix0_set_actParam; // 0xc0
	private static DelegateBridge __Hotfix0_get_setting; // 0xc8
	private static DelegateBridge __Hotfix0_get_battlePausing; // 0xd0
	private static DelegateBridge __Hotfix0_set_battlePausing; // 0xd8
	private static DelegateBridge __Hotfix0_get_battleFastMode; // 0xe0
	private static DelegateBridge __Hotfix0_set_battleFastMode; // 0xe8
	private static DelegateBridge __Hotfix0_get_isReal; // 0xf0
	private static DelegateBridge __Hotfix0_get_isReplay; // 0xf8
	private static DelegateBridge __Hotfix0_get_cachedPlayerInfoForBattle; // 0x100
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x108
	private static DelegateBridge __Hotfix0_SendRequest; // 0x110
	private static DelegateBridge __Hotfix0_RevStep; // 0x118
	private static DelegateBridge __Hotfix0_Update; // 0x120
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x128
	private static DelegateBridge __Hotfix0_OnGUI; // 0x130
	private static DelegateBridge __Hotfix0_Alert; // 0x138
	private static DelegateBridge __Hotfix0_ProcessDelayedAlert; // 0x140
	private static DelegateBridge __Hotfix0_ClearDelayedAlert; // 0x148
	private static DelegateBridge __Hotfix0_GetPlayerStatusByPlayerId; // 0x150
	private static DelegateBridge __Hotfix0__ChangeMode; // 0x158
	private static DelegateBridge __Hotfix0__ChangePhase; // 0x160
	private static DelegateBridge __Hotfix0__CheckMySideAndStatus; // 0x168
	private static DelegateBridge __Hotfix1_SendRequest; // 0x170
	private static DelegateBridge __Hotfix0__ConstructTempActParam; // 0x178

	public static Boolean hasInstance { get; }
	public static MultiplayerMgr instance { get; }
	public static Boolean started { get; }
	public static IMultiplayerMode curMode { get; }
	public IMultiplayerMode mode { get; }
	public EventPool`1 eventPool { get; set; }
	public String playerID { get; }
	public String partnerID { get; set; }
	public TeamInfo teamInfo { get; }
	public BattleInfo battleInfo { get; }
	public MultiplayerActParam actParam { get; set; }
	public MultiplayerSetting setting { get; }
	public Boolean battlePausing { get; set; }
	public Boolean battleFastMode { get; set; }
	public Boolean isReal { get; }
	public Boolean isReplay { get; }
	public Object cachedPlayerInfoForBattle { get; }

	// RVA: 0x358e110 VA: 0x7595ba6110
	public static Boolean get_hasInstance() { }
	// RVA: 0x3588824 VA: 0x7595ba0824
	public static MultiplayerMgr get_instance() { }
	// RVA: 0x358e178 VA: 0x7595ba6178
	private static MultiplayerMgr _Setup() { }
	// RVA: 0x358e3c8 VA: 0x7595ba63c8
	public static Boolean get_started() { }
	// RVA: 0x35886a8 VA: 0x7595ba06a8
	public static Void Stop() { }
	// RVA: 0x358e518 VA: 0x7595ba6518
	private static Void _StartImpl(TeamInst team, MultiplayerActParam param, TeamJoinFollower follower) { }
	// RVA: 0x358e6e4 VA: 0x7595ba66e4
	public static Void StartWithLoadMask(TeamInst team, MultiplayerActParam param, TeamJoinFollower follower) { }
	// RVA: 0x358e86c VA: 0x7595ba686c
	public static Void Replay(IMultiplayerBattleVideo video, String uid) { }
	// RVA: 0x358ea00 VA: 0x7595ba6a00
	public static Void Replay(String[] videoUrls) { }
	// RVA: 0x358a920 VA: 0x7595ba2920
	public static IMultiplayerMode get_curMode() { }
	// RVA: 0x358eae4 VA: 0x7595ba6ae4
	public IMultiplayerMode get_mode() { }
	// RVA: 0x358e298 VA: 0x7595ba6298
	private Void .ctor() { }
	// RVA: 0x358f02c VA: 0x7595ba702c
	public Void Dispose() { }
	// RVA: 0x358f21c VA: 0x7595ba721c
	private Void _HandleSceneChanged(String from, String to) { }
	// RVA: 0x358b268 VA: 0x7595ba3268
	public EventPool`1 get_eventPool() { }
	// RVA: 0x358eea8 VA: 0x7595ba6ea8
	private Void set_eventPool(EventPool`1 value) { }
	// RVA: 0x3588b5c VA: 0x7595ba0b5c
	public String get_playerID() { }
	// RVA: 0x358f338 VA: 0x7595ba7338
	public String get_partnerID() { }
	// RVA: 0x358f3a0 VA: 0x7595ba73a0
	private Void set_partnerID(String value) { }
	// RVA: 0x358f424 VA: 0x7595ba7424
	public TeamInfo get_teamInfo() { }
	// RVA: 0x358896c VA: 0x7595ba096c
	public BattleInfo get_battleInfo() { }
	// RVA: 0x3588a48 VA: 0x7595ba0a48
	public MultiplayerActParam get_actParam() { }
	// RVA: 0x358e62c VA: 0x7595ba662c
	private Void set_actParam(MultiplayerActParam value) { }
	// RVA: 0x35888d4 VA: 0x7595ba08d4
	public MultiplayerSetting get_setting() { }
	// RVA: 0x358f500 VA: 0x7595ba7500
	public Boolean get_battlePausing() { }
	// RVA: 0x358ef2c VA: 0x7595ba6f2c
	private Void set_battlePausing(Boolean value) { }
	// RVA: 0x358f568 VA: 0x7595ba7568
	public Boolean get_battleFastMode() { }
	// RVA: 0x358efac VA: 0x7595ba6fac
	private Void set_battleFastMode(Boolean value) { }
	// RVA: 0x3588f60 VA: 0x7595ba0f60
	public Boolean get_isReal() { }
	// RVA: 0x358ab68 VA: 0x7595ba2b68
	public Boolean get_isReplay() { }
	// RVA: 0x3589014 VA: 0x7595ba1014
	public Object get_cachedPlayerInfoForBattle() { }
	// RVA: 0x358f5d0 VA: 0x7595ba75d0
	public Void UpdateStatus() { }
	// RVA: 0x3589fac VA: 0x7595ba1fac
	public Boolean SendRequest(RequestType request, Object param) { }
	// RVA: 0x358f934 VA: 0x7595ba7934
	public Void RevStep(StepData step) { }
	// RVA: 0x358fb78 VA: 0x7595ba7b78
	public Void Update() { }
	// RVA: 0x358fc5c VA: 0x7595ba7c5c
	public Void FixedUpdate() { }
	// RVA: 0x358fcdc VA: 0x7595ba7cdc
	public Void OnGUI() { }
	// RVA: 0x358fd5c VA: 0x7595ba7d5c
	public Void Alert(String content, ShowCondition condition, ProcWhenForbid proc) { }
	// RVA: 0x3590000 VA: 0x7595ba8000
	public static Boolean ProcessDelayedAlert(Action`2 proc) { }
	// RVA: 0x3590110 VA: 0x7595ba8110
	public static Void ClearDelayedAlert() { }
	// RVA: 0x35901c4 VA: 0x7595ba81c4
	public STPlayerStatus GetPlayerStatusByPlayerId(String playerID) { }
	// RVA: 0x VA: 0x0
	private T _ChangeMode() { }
	// RVA: 0x VA: 0x0
	private T _ChangePhase() { }
	// RVA: 0x358f7e4 VA: 0x7595ba77e4
	private Void _CheckMySideAndStatus() { }
	// RVA: 0x VA: 0x0
	public static Void SendRequest(String api, Req req, Action`1 onProceed, Boolean showMask, Func`2 onError) { }
	// RVA: 0x358e95c VA: 0x7595ba695c
	private static MultiplayerActParam _ConstructTempActParam() { }
}
```