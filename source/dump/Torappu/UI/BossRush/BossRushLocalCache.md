# BossRushLocalCache

**Namespace:** `Torappu.UI.BossRush`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `BossRushStageType LoadStageGroupModeCache(String, String)`

- `String LoadSquadSelectTeamIdCache(String, String)`

- `Boolean LoadSquadTeamPredefineChangedFlag(String)`

- `Void SaveStageGroupModeCache(String, String, BossRushStageType)`

- `Void SaveSquadSelectTeamCache(String, String, String)`

- `Void SaveSquadTeamPredefineChanged(String)`

- `Void SaveInitSquadCacheDict(String, String, Dictionary`2, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureActCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInAct; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_LoadFixedPartMemberCache; // 0x28
	private static DelegateBridge __Hotfix0_LoadStageGroupModeCache; // 0x30
	private static DelegateBridge __Hotfix0_LoadSquadSelectTeamIdCache; // 0x38
	private static DelegateBridge __Hotfix0_LoadCustomPartSquadCache; // 0x40
	private static DelegateBridge __Hotfix0_LoadSquadTeamPredefineChangedFlag; // 0x48
	private static DelegateBridge __Hotfix0_SaveStageGroupModeCache; // 0x50
	private static DelegateBridge __Hotfix0_SaveSquadSelectTeamCache; // 0x58
	private static DelegateBridge __Hotfix0_SaveSquadTeamPredefineChanged; // 0x60
	private static DelegateBridge __Hotfix0_SaveInitSquadCacheDict; // 0x68


	// RVA: 0x2e57a2c VA: 0x759546fa2c
	private Void .ctor() { }
	// RVA: 0x2e57abc VA: 0x759546fabc
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x2e57c20 VA: 0x759546fc20
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x2e57e00 VA: 0x759546fe00
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x2e57f44 VA: 0x759546ff44
	private Void _SaveData(ActData data) { }
	// RVA: 0x2e57ff0 VA: 0x759546fff0
	public Dictionary`2 LoadFixedPartMemberCache(String actId, String teamId) { }
	// RVA: 0x2e580e4 VA: 0x75954700e4
	public BossRushStageType LoadStageGroupModeCache(String actId, String stageGroupId) { }
	// RVA: 0x2e581d0 VA: 0x75954701d0
	public String LoadSquadSelectTeamIdCache(String actId, String stageId) { }
	// RVA: 0x2e582b4 VA: 0x75954702b4
	public List`1 LoadCustomPartSquadCache(String actId, String teamId) { }
	// RVA: 0x2e583a8 VA: 0x75954703a8
	public Boolean LoadSquadTeamPredefineChangedFlag(String actId) { }
	// RVA: 0x2e5843c VA: 0x759547043c
	public Void SaveStageGroupModeCache(String actId, String stageGroupId, BossRushStageType mode) { }
	// RVA: 0x2e585a0 VA: 0x75954705a0
	public Void SaveSquadSelectTeamCache(String actId, String stageId, String teamId) { }
	// RVA: 0x2e58704 VA: 0x7595470704
	public Void SaveSquadTeamPredefineChanged(String actId) { }
	// RVA: 0x2e587b8 VA: 0x75954707b8
	public Void SaveInitSquadCacheDict(String actId, String teamId, Dictionary`2 memberCache, List`1 slotList) { }
}
```