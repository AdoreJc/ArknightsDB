# BossRushBattleFinishViewModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String m_actId`

- `String m_stageId`

- `BattleFinishIllust m_illust`

- `Int32 m_completedWave`

- `Int32 m_totalWave`

- `BattleInfoViewModel m_battleInfoModel`

- `MilestoneStruct m_milestoneStruct`

- `Int32 m_firstPassMilestoneCount`

- `Int32 m_firstPassTokenCount`

- `Int32 m_milestoneCount`

- `Int32 m_tokenCount`

- `Boolean m_isMilestoneLevelUp`

- `Boolean m_isMilestoneMax`

- `Boolean m_isTokenMax`

- `String m_milestoneItemId`

- `String m_tokenItemId`

- `BossRushStageType m_bossRushStageType`


## Properties

- `BattleFinishIllust illust`

- `Int32 completedWave`

- `Int32 totalWave`

- `BattleInfoViewModel battleInfoModel`

- `String statusDes`

- `Int32 currentExp`

- `Int32 totalExp`

- `Int32 milestoneLv`

- `Single expProgress`

- `Int32 milestoneCount`

- `Int32 firstPassMilestoneCount`

- `Int32 tokenCount`

- `Int32 firstPassTokenCount`

- `Boolean isMilestoneLevelUp`

- `Boolean isMilestoneMax`

- `Boolean isTokenMax`

- `String milestoneId`

- `String tokenId`

- `BossRushStageType bossRushStageType`


## Methods

- `BattleFinishIllust get_illust()`

- `Int32 get_completedWave()`

- `Int32 get_totalWave()`

- `BattleInfoViewModel get_battleInfoModel()`

- `String get_statusDes()`

- `Int32 get_currentExp()`

- `Int32 get_totalExp()`

- `Int32 get_milestoneLv()`

- `Single get_expProgress()`

- `Int32 get_milestoneCount()`

- `Int32 get_firstPassMilestoneCount()`

- `Int32 get_tokenCount()`

- `Int32 get_firstPassTokenCount()`

- `Boolean get_isMilestoneLevelUp()`

- `Boolean get_isMilestoneMax()`

- `Boolean get_isTokenMax()`

- `String get_milestoneId()`

- `String get_tokenId()`

- `BossRushStageType get_bossRushStageType()`

- `Void LoadData()`

- `Void _LoadNewStageInfo(ActivityBossRushData, String[])`

- `Int32 _GetTotalWave(ActivityBossRushData, String)`

- `BattleInfoViewModel _LoadBattleInfo(String)`

- `BossRushStageType _LoadStageType(ActivityBossRushData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushBattleFinishViewModel : IHotfixable
{
	private String m_actId; // 0x10
	private String m_stageId; // 0x18
	private BattleFinishIllust m_illust; // 0x20
	private Int32 m_completedWave; // 0x40
	private Int32 m_totalWave; // 0x44
	private BattleInfoViewModel m_battleInfoModel; // 0x48
	private MilestoneStruct m_milestoneStruct; // 0x50
	private Int32 m_firstPassMilestoneCount; // 0x60
	private Int32 m_firstPassTokenCount; // 0x64
	private Int32 m_milestoneCount; // 0x68
	private Int32 m_tokenCount; // 0x6c
	private Boolean m_isMilestoneLevelUp; // 0x70
	private Boolean m_isMilestoneMax; // 0x71
	private Boolean m_isTokenMax; // 0x72
	private String m_milestoneItemId; // 0x78
	private String m_tokenItemId; // 0x80
	private BossRushStageType m_bossRushStageType; // 0x88
	private List`1 m_stageInfoList; // 0x90
	private static DelegateBridge __Hotfix0_get_illust; // 0x0
	private static DelegateBridge __Hotfix0_get_completedWave; // 0x8
	private static DelegateBridge __Hotfix0_get_totalWave; // 0x10
	private static DelegateBridge __Hotfix0_get_battleInfoModel; // 0x18
	private static DelegateBridge __Hotfix0_get_statusDes; // 0x20
	private static DelegateBridge __Hotfix0_get_currentExp; // 0x28
	private static DelegateBridge __Hotfix0_get_totalExp; // 0x30
	private static DelegateBridge __Hotfix0_get_milestoneLv; // 0x38
	private static DelegateBridge __Hotfix0_get_expProgress; // 0x40
	private static DelegateBridge __Hotfix0_get_milestoneCount; // 0x48
	private static DelegateBridge __Hotfix0_get_firstPassMilestoneCount; // 0x50
	private static DelegateBridge __Hotfix0_get_tokenCount; // 0x58
	private static DelegateBridge __Hotfix0_get_firstPassTokenCount; // 0x60
	private static DelegateBridge __Hotfix0_get_isMilestoneLevelUp; // 0x68
	private static DelegateBridge __Hotfix0_get_isMilestoneMax; // 0x70
	private static DelegateBridge __Hotfix0_get_isTokenMax; // 0x78
	private static DelegateBridge __Hotfix0_get_milestoneId; // 0x80
	private static DelegateBridge __Hotfix0_get_tokenId; // 0x88
	private static DelegateBridge __Hotfix0_get_unlockStageInfoList; // 0x90
	private static DelegateBridge __Hotfix0_get_bossRushStageType; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0xa0
	private static DelegateBridge __Hotfix0__LoadNewStageInfo; // 0xa8
	private static DelegateBridge __Hotfix0__GetTotalWave; // 0xb0
	private static DelegateBridge __Hotfix0__LoadBattleInfo; // 0xb8
	private static DelegateBridge __Hotfix0__LoadStageType; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public BattleFinishIllust illust { get; }
	public Int32 completedWave { get; }
	public Int32 totalWave { get; }
	public BattleInfoViewModel battleInfoModel { get; }
	public String statusDes { get; }
	public Int32 currentExp { get; }
	public Int32 totalExp { get; }
	public Int32 milestoneLv { get; }
	public Single expProgress { get; }
	public Int32 milestoneCount { get; }
	public Int32 firstPassMilestoneCount { get; }
	public Int32 tokenCount { get; }
	public Int32 firstPassTokenCount { get; }
	public Boolean isMilestoneLevelUp { get; }
	public Boolean isMilestoneMax { get; }
	public Boolean isTokenMax { get; }
	public String milestoneId { get; }
	public String tokenId { get; }
	public List`1 unlockStageInfoList { get; }
	public BossRushStageType bossRushStageType { get; }

	// RVA: 0x2e56ba0 VA: 0x759546eba0
	public BattleFinishIllust get_illust() { }
	// RVA: 0x2e55c30 VA: 0x759546dc30
	public Int32 get_completedWave() { }
	// RVA: 0x2e564dc VA: 0x759546e4dc
	public Int32 get_totalWave() { }
	// RVA: 0x2e55b20 VA: 0x759546db20
	public BattleInfoViewModel get_battleInfoModel() { }
	// RVA: 0x2e55b88 VA: 0x759546db88
	public String get_statusDes() { }
	// RVA: 0x2e55d00 VA: 0x759546dd00
	public Int32 get_currentExp() { }
	// RVA: 0x2e55d68 VA: 0x759546dd68
	public Int32 get_totalExp() { }
	// RVA: 0x2e55dd0 VA: 0x759546ddd0
	public Int32 get_milestoneLv() { }
	// RVA: 0x2e55e38 VA: 0x759546de38
	public Single get_expProgress() { }
	// RVA: 0x2e55fc0 VA: 0x759546dfc0
	public Int32 get_milestoneCount() { }
	// RVA: 0x2e56028 VA: 0x759546e028
	public Int32 get_firstPassMilestoneCount() { }
	// RVA: 0x2e56160 VA: 0x759546e160
	public Int32 get_tokenCount() { }
	// RVA: 0x2e561c8 VA: 0x759546e1c8
	public Int32 get_firstPassTokenCount() { }
	// RVA: 0x2e55ef0 VA: 0x759546def0
	public Boolean get_isMilestoneLevelUp() { }
	// RVA: 0x2e55c98 VA: 0x759546dc98
	public Boolean get_isMilestoneMax() { }
	// RVA: 0x2e560f8 VA: 0x759546e0f8
	public Boolean get_isTokenMax() { }
	// RVA: 0x2e55f58 VA: 0x759546df58
	public String get_milestoneId() { }
	// RVA: 0x2e56090 VA: 0x759546e090
	public String get_tokenId() { }
	// RVA: 0x2e562c4 VA: 0x759546e2c4
	public List`1 get_unlockStageInfoList() { }
	// RVA: 0x2e56544 VA: 0x759546e544
	public BossRushStageType get_bossRushStageType() { }
	// RVA: 0x2e54d38 VA: 0x759546cd38
	public Void LoadData() { }
	// RVA: 0x2e5721c VA: 0x759546f21c
	private Void _LoadNewStageInfo(ActivityBossRushData actData, String[] unlockStages) { }
	// RVA: 0x2e56c4c VA: 0x759546ec4c
	private Int32 _GetTotalWave(ActivityBossRushData bossRushData, String stageId) { }
	// RVA: 0x2e56e30 VA: 0x759546ee30
	private BattleInfoViewModel _LoadBattleInfo(String stageId) { }
	// RVA: 0x2e56d70 VA: 0x759546ed70
	private BossRushStageType _LoadStageType(ActivityBossRushData actData) { }
	// RVA: 0x2e54cc8 VA: 0x759546ccc8
	public Void .ctor() { }
}
```