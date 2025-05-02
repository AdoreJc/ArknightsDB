# Act1VAutoChessEntryTeamInfoViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Boolean isEnemyTeam`

- `String selectedCharTeamId`

- `String selectedEnemyTeamId`

- `String teamName`

- `String leaderName`

- `String leaderIconId`

- `String teamLogoId`

- `Boolean isCurLocked`

- `Boolean isSwitchToLock`

- `Int32 teamHp`

- `String teamEffectDesc`

- `String unlockReqDesc`

- `String enemyIntroDesc`

- `Boolean m_isInit`

- `ActivityAutoChessVerify1Data m_cachedData`


## Properties

- `String actId`


## Methods

- `String get_actId()`

- `Void _InitIfNot()`

- `Void _RefreshCurrentBySelected(String)`

- `Void <>xLuaBaseProxy_LoadData(String, ActivityAutoChessVerify1Data)`

- `Void <>xLuaBaseProxy_RefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryTeamInfoViewModel : Act1VAutoChessEntryBaseSubViewModel
{
	public Boolean isEnemyTeam; // 0x24
	public String selectedCharTeamId; // 0x28
	public String selectedEnemyTeamId; // 0x30
	public String teamName; // 0x38
	public String leaderName; // 0x40
	public String leaderIconId; // 0x48
	public String teamLogoId; // 0x50
	public Boolean isCurLocked; // 0x58
	public Boolean isSwitchToLock; // 0x59
	public Int32 teamHp; // 0x5c
	public String teamEffectDesc; // 0x60
	public String unlockReqDesc; // 0x68
	public String enemyIntroDesc; // 0x70
	public List`1 charTeamDataList; // 0x78
	public List`1 enemyTeamDataList; // 0x80
	private Boolean m_isInit; // 0x88
	private ActivityAutoChessVerify1Data m_cachedData; // 0x90
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge __Hotfix0_GetEnemyListByForceId; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__RefreshCurrentBySelected; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String actId { get; }

	// RVA: 0x334e2ac VA: 0x75959662ac
	public String get_actId() { }
	// RVA: 0x33578cc VA: 0x759596f8cc
	public override Void LoadData(String actId, ActivityAutoChessVerify1Data actData) { }
	// RVA: 0x33581d0 VA: 0x75959701d0
	public override Void RefreshData() { }
	// RVA: 0x33584b0 VA: 0x75959704b0
	public List`1 GetEnemyListByForceId(String forceId, Dictionary`2 cachedEnemyDict) { }
	// RVA: 0x3357e94 VA: 0x759596fe94
	private Void _InitIfNot() { }
	// RVA: 0x3357f0c VA: 0x759596ff0c
	private Void _RefreshCurrentBySelected(String selectedTeamId) { }
	// RVA: 0x3358980 VA: 0x7595970980
	public Void .ctor() { }
	// RVA: 0x3358a74 VA: 0x7595970a74
	private Void <>xLuaBaseProxy_LoadData(String P0, ActivityAutoChessVerify1Data P1) { }
	// RVA: 0x3358a78 VA: 0x7595970a78
	private Void <>xLuaBaseProxy_RefreshData() { }
}
```