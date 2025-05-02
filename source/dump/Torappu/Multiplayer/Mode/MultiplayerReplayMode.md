# MultiplayerReplayMode

**Namespace:** `Torappu.Multiplayer.Mode`


## Fields

- `MultiplayerMgr m_mgr`

- `Boolean m_waitingTryNext`

- `IMultiplayerBattleVideo m_video`

- `String m_uid`

- `String m_vurl`

- `Int32 m_curStep`

- `HttpUpload m_uploader`

- `TeamInfo <teamInfo>k__BackingField`

- `BattleInfo <battleInfo>k__BackingField`

- `RequestHandlers m_reqHandlers`

- `Object <cachedUserInfoForBattle>k__BackingField`


## Properties

- `String playerUID`

- `TeamInfo teamInfo`

- `BattleInfo battleInfo`

- `Int32 ping`

- `DateTime currentTime`

- `Object cachedUserInfoForBattle`


## Methods

- `String get_playerUID()`

- `TeamInfo get_teamInfo()`

- `Void set_teamInfo(TeamInfo)`

- `BattleInfo get_battleInfo()`

- `Void set_battleInfo(BattleInfo)`

- `Int32 get_ping()`

- `DateTime get_currentTime()`

- `Object get_cachedUserInfoForBattle()`

- `Void set_cachedUserInfoForBattle(Object)`

- `Void Dispose()`

- `StepData _GetCurStep()`

- `Void Init(MultiplayerMgr)`

- `Void Update()`

- `Void Play(IMultiplayerBattleVideo, String)`

- `Void Play(String[])`

- `Boolean SendRequest(RequestType, Object)`

- `Void TeamSetting(RoomConfigKey, String)`

- `Boolean _GameReady()`

- `Boolean _GameSettle(GameSettleParam)`

- `Void _Reset(Boolean)`

- `Void _TryPlayNext()`

- `Void _VideoDownloaded(String, String)`

- `Void _SetLogUpload(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.Mode
public class MultiplayerReplayMode : IMultiplayerMode, IHotfixable
{
	private MultiplayerMgr m_mgr; // 0x10
	private Queue`1 m_waiteForPlay; // 0x18
	private Boolean m_waitingTryNext; // 0x20
	private IMultiplayerBattleVideo m_video; // 0x28
	private String m_uid; // 0x30
	private String m_vurl; // 0x38
	private Int32 m_curStep; // 0x40
	private HttpUpload m_uploader; // 0x48
	private TeamInfo <teamInfo>k__BackingField; // 0x50
	private BattleInfo <battleInfo>k__BackingField; // 0x58
	private RequestHandlers m_reqHandlers; // 0x60
	public static Single REPLAY_SPEED; // 0x0
	private Object <cachedUserInfoForBattle>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_playerUID; // 0x8
	private static DelegateBridge __Hotfix0_get_teamInfo; // 0x10
	private static DelegateBridge __Hotfix0_set_teamInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_battleInfo; // 0x20
	private static DelegateBridge __Hotfix0_set_battleInfo; // 0x28
	private static DelegateBridge __Hotfix0_get_ping; // 0x30
	private static DelegateBridge __Hotfix0_get_currentTime; // 0x38
	private static DelegateBridge __Hotfix0_get_cachedUserInfoForBattle; // 0x40
	private static DelegateBridge __Hotfix0_set_cachedUserInfoForBattle; // 0x48
	private static DelegateBridge __Hotfix0_Dispose; // 0x50
	private static DelegateBridge __Hotfix0__GetCurStep; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x60
	private static DelegateBridge __Hotfix0_Update; // 0x68
	private static DelegateBridge __Hotfix0_Play; // 0x70
	private static DelegateBridge __Hotfix1_Play; // 0x78
	private static DelegateBridge __Hotfix0_SendRequest; // 0x80
	private static DelegateBridge __Hotfix0_TeamSetting; // 0x88
	private static DelegateBridge __Hotfix0__GameReady; // 0x90
	private static DelegateBridge __Hotfix0__GameSettle; // 0x98
	private static DelegateBridge __Hotfix0__Reset; // 0xa0
	private static DelegateBridge __Hotfix0__TryPlayNext; // 0xa8
	private static DelegateBridge __Hotfix0__VideoDownloaded; // 0xb0
	private static DelegateBridge __Hotfix0__SetLogUpload; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public String playerUID { get; }
	public TeamInfo teamInfo { get; set; }
	public BattleInfo battleInfo { get; set; }
	public Int32 ping { get; }
	public DateTime currentTime { get; }
	public Object cachedUserInfoForBattle { get; set; }

	// RVA: 0x35a91f8 VA: 0x7595bc11f8
	public String get_playerUID() { }
	// RVA: 0x35a9270 VA: 0x7595bc1270
	public TeamInfo get_teamInfo() { }
	// RVA: 0x35a92e8 VA: 0x7595bc12e8
	private Void set_teamInfo(TeamInfo value) { }
	// RVA: 0x35a937c VA: 0x7595bc137c
	public BattleInfo get_battleInfo() { }
	// RVA: 0x35a93f4 VA: 0x7595bc13f4
	private Void set_battleInfo(BattleInfo value) { }
	// RVA: 0x35a9488 VA: 0x7595bc1488
	public Int32 get_ping() { }
	// RVA: 0x35a94fc VA: 0x7595bc14fc
	public DateTime get_currentTime() { }
	// RVA: 0x35a9598 VA: 0x7595bc1598
	public Object get_cachedUserInfoForBattle() { }
	// RVA: 0x35a9610 VA: 0x7595bc1610
	private Void set_cachedUserInfoForBattle(Object value) { }
	// RVA: 0x35a96a4 VA: 0x7595bc16a4
	public Void Dispose() { }
	// RVA: 0x35a9724 VA: 0x7595bc1724
	private StepData _GetCurStep() { }
	// RVA: 0x35a9818 VA: 0x7595bc1818
	public Void Init(MultiplayerMgr mgr) { }
	// RVA: 0x35a9b24 VA: 0x7595bc1b24
	public Void Update() { }
	// RVA: 0x35a9d5c VA: 0x7595bc1d5c
	public Void Play(IMultiplayerBattleVideo video, String uid) { }
	// RVA: 0x35aa01c VA: 0x7595bc201c
	public Void Play(String[] urls) { }
	// RVA: 0x35aa1ac VA: 0x7595bc21ac
	public Boolean SendRequest(RequestType request, Object param) { }
	// RVA: 0x35aa250 VA: 0x7595bc2250
	public Void TeamSetting(RoomConfigKey key, String value) { }
	// RVA: 0x35aa2e0 VA: 0x7595bc22e0
	private Boolean _GameReady() { }
	// RVA: 0x35aa740 VA: 0x7595bc2740
	private Boolean _GameSettle(GameSettleParam settle) { }
	// RVA: 0x35a99d4 VA: 0x7595bc19d4
	private Void _Reset(Boolean exitReplay) { }
	// RVA: 0x35a9bf8 VA: 0x7595bc1bf8
	private Void _TryPlayNext() { }
	// RVA: 0x35aa924 VA: 0x7595bc2924
	private Void _VideoDownloaded(String url, String content) { }
	// RVA: 0x35aa378 VA: 0x7595bc2378
	private Void _SetLogUpload(String url) { }
	// RVA: 0x35aab78 VA: 0x7595bc2b78
	public Void .ctor() { }
	// RVA: 0x35aabf8 VA: 0x7595bc2bf8
	private static Void .cctor() { }
}
```