# EnemyDuelService

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `EnemyDuelServicePhase m_curPhase`

- `Core m_coreImpl`

- `IEnemyDuelServiceMode m_mode`

- `EnemyDuelServiceParam <param>k__BackingField`


## Properties

- `EnemyDuelServiceParam param`

- `Setting setting`

- `Int32 ping`

- `DateTime currentTime`

- `EnemyDuelServiceBattleInfo battleInfo`

- `EnemyDuelServiceTeamInfo teamInfo`

- `Boolean isMulti`


## Methods

- `EnemyDuelServiceParam get_param()`

- `Void set_param(EnemyDuelServiceParam)`

- `Setting get_setting()`

- `Int32 get_ping()`

- `DateTime get_currentTime()`

- `EnemyDuelServiceBattleInfo get_battleInfo()`

- `EnemyDuelServiceTeamInfo get_teamInfo()`

- `Boolean get_isMulti()`

- `Void Dispose()`

- `Void _HandleSceneChanged(String, String)`

- `Void _RefreshStatus()`

- `Void _Update()`

- `Void _FixedUpdate()`

- `Void _OnGUI()`

- `T _ChangePhase()`

- `T _CheckMode()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelService : IDisposable, IHotfixable
{
	private static EnemyDuelService s_instance; // 0x0
	private EnemyDuelServicePhase m_curPhase; // 0x10
	private Core m_coreImpl; // 0x18
	private IEnemyDuelServiceMode m_mode; // 0x20
	private EventPool`1 m_eventPool; // 0x28
	private EnemyDuelServiceParam <param>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_status; // 0x8
	private static DelegateBridge __Hotfix0_get_started; // 0x10
	private static DelegateBridge __Hotfix0_StartMulti; // 0x18
	private static DelegateBridge __Hotfix0_StartSingle; // 0x20
	private static DelegateBridge __Hotfix0_Stop; // 0x28
	private static DelegateBridge __Hotfix0_RegisterListener; // 0x30
	private static DelegateBridge __Hotfix0_CancelListener; // 0x38
	private static DelegateBridge __Hotfix0_SendRequest; // 0x40
	private static DelegateBridge __Hotfix0__Setup; // 0x48
	private static DelegateBridge __Hotfix0_get_param; // 0x50
	private static DelegateBridge __Hotfix0_set_param; // 0x58
	private static DelegateBridge __Hotfix0_get_setting; // 0x60
	private static DelegateBridge __Hotfix0_get_ping; // 0x68
	private static DelegateBridge __Hotfix0_get_currentTime; // 0x70
	private static DelegateBridge __Hotfix0_get_battleInfo; // 0x78
	private static DelegateBridge __Hotfix0_get_teamInfo; // 0x80
	private static DelegateBridge __Hotfix0_get_isMulti; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90
	private static DelegateBridge __Hotfix0_Dispose; // 0x98
	private static DelegateBridge __Hotfix0__HandleSceneChanged; // 0xa0
	private static DelegateBridge __Hotfix0__RefreshStatus; // 0xa8
	private static DelegateBridge __Hotfix0__Update; // 0xb0
	private static DelegateBridge __Hotfix0__FixedUpdate; // 0xb8
	private static DelegateBridge __Hotfix0__OnGUI; // 0xc0
	private static DelegateBridge __Hotfix0__ChangePhase; // 0xc8
	private static DelegateBridge __Hotfix0__CheckMode; // 0xd0

	public static EnemyDuelService status { get; }
	public static Boolean started { get; }
	public EnemyDuelServiceParam param { get; set; }
	public Setting setting { get; }
	public Int32 ping { get; }
	public DateTime currentTime { get; }
	public EnemyDuelServiceBattleInfo battleInfo { get; }
	public EnemyDuelServiceTeamInfo teamInfo { get; }
	public Boolean isMulti { get; }

	// RVA: 0x29a1da8 VA: 0x7594fb9da8
	public static EnemyDuelService get_status() { }
	// RVA: 0x29a1278 VA: 0x7594fb9278
	public static Boolean get_started() { }
	// RVA: 0x29a47f8 VA: 0x7594fbc7f8
	public static Void StartMulti(TeamJoinEntry entry, EnemyDuelServiceParam param) { }
	// RVA: 0x29a4ad0 VA: 0x7594fbcad0
	public static Void StartSingle(SingleBattleEntry entry, EnemyDuelServiceParam param) { }
	// RVA: 0x29a2ce8 VA: 0x7594fbace8
	public static Void Stop() { }
	// RVA: 0x29a20a4 VA: 0x7594fba0a4
	public static Void RegisterListener(EnemyDuelServiceEvent evt, EventCallbackDelegate cb) { }
	// RVA: 0x29a2170 VA: 0x7594fba170
	public static Void CancelListener(EnemyDuelServiceEvent evt, EventCallbackDelegate cb) { }
	// RVA: 0x29a0c18 VA: 0x7594fb8c18
	public static Void SendRequest(EnemyDuelServiceRequest request) { }
	// RVA: 0x29a48e0 VA: 0x7594fbc8e0
	private static EnemyDuelService _Setup() { }
	// RVA: 0x29a54c4 VA: 0x7594fbd4c4
	public EnemyDuelServiceParam get_param() { }
	// RVA: 0x29a49a8 VA: 0x7594fbc9a8
	private Void set_param(EnemyDuelServiceParam value) { }
	// RVA: 0x29a552c VA: 0x7594fbd52c
	public Setting get_setting() { }
	// RVA: 0x29a1e58 VA: 0x7594fb9e58
	public Int32 get_ping() { }
	// RVA: 0x29a55c4 VA: 0x7594fbd5c4
	public DateTime get_currentTime() { }
	// RVA: 0x29a56a0 VA: 0x7594fbd6a0
	public EnemyDuelServiceBattleInfo get_battleInfo() { }
	// RVA: 0x29a23b4 VA: 0x7594fba3b4
	public EnemyDuelServiceTeamInfo get_teamInfo() { }
	// RVA: 0x29a577c VA: 0x7594fbd77c
	public Boolean get_isMulti() { }
	// RVA: 0x29a535c VA: 0x7594fbd35c
	private Void .ctor() { }
	// RVA: 0x29a518c VA: 0x7594fbd18c
	public Void Dispose() { }
	// RVA: 0x29a5c4c VA: 0x7594fbdc4c
	private Void _HandleSceneChanged(String from, String to) { }
	// RVA: 0x29a5d54 VA: 0x7594fbdd54
	private Void _RefreshStatus() { }
	// RVA: 0x29a5f98 VA: 0x7594fbdf98
	private Void _Update() { }
	// RVA: 0x29a607c VA: 0x7594fbe07c
	private Void _FixedUpdate() { }
	// RVA: 0x29a60fc VA: 0x7594fbe0fc
	private Void _OnGUI() { }
	// RVA: 0x VA: 0x0
	private T _ChangePhase() { }
	// RVA: 0x VA: 0x0
	private T _CheckMode() { }
}
```