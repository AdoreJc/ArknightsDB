# SandboxBattleDataController

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `SandboxInput m_input`

- `SandboxOutput m_output`

- `SandboxGameMode m_gameMode`

- `SandboxBattleManager m_manager`


## Properties

- `SandboxOutput output`


## Methods

- `Void add_onItemCollect(Action`2)`

- `Void remove_onItemCollect(Action`2)`

- `SandboxOutput get_output()`

- `Void Init()`

- `Void _InitInputStatus()`

- `Void OnGameOver(GameResult)`

- `Void OnFetchGameOverOutput()`

- `Boolean FetchBossRecordedStatus(String, String, out)`

- `Boolean FetchUniEnemyRecordedStatus(String, out)`

- `Boolean FetchUnitRecordedStatus(SandboxEntityStatusKey, out)`

- `Boolean FetchPlacedItemRecordedStatus(SandboxPlacedItemStatusKey, out)`

- `Boolean FetchUniEnemyExtraInfo(String, out)`

- `Void RecordUnitState(SandboxLevelDataProcessor, SandboxEntityStatusKey, SandboxEntityStatusValue)`

- `Void RecordPlacedItemState(SandboxPlacedItemStatusKey, SandboxPlacedItemStatusValue)`

- `Void RecordBossState(String, String, SandboxRushBossStatus)`

- `Void RecordUniEnemyState(String, SandboxV2UniEnemyStatus)`

- `Boolean CheckSpecialUniEnemy(String)`

- `Void RecordUsingConstructItem(Character)`

- `Void MarkRushEnemyDead(RushEnemy)`

- `Void MarkRushEnemyReachExit(RushEnemy)`

- `Void MarkEnemyNeedRefreshDead(ActionID)`

- `Void ConstructSaveLevelRes()`

- `Int32 GetResCountByID(String, Boolean)`

- `UInt32 _PackedResDictKey(Entity)`

- `Void _SandboxEntityPackItem(Entity, ResPackType, Int32)`

- `Void _SandboxCollectItem(String, Int32, Boolean, Boolean)`

- `Void SandboxEntityDropItem(Entity, ResDropSourceType)`

- `Void SandboxEntityDropItem(Entity, String, Int32)`

- `Void SandboxCollectItem(String, Int32)`

- `Boolean CollectPackedRes(Entity)`

- `Boolean TransferAllPackedRes(Entity, Entity)`

- `Int32 _TransferPackedRes(Entity, Entity, ResPackType, Int32)`

- `Int32 GetPackedResMaxCount(Entity)`

- `Int32 GetPackedResMaxCount(Card)`

- `Int32 GetPackedResRestCount(Entity)`

- `Int32 GetTotalPackedResCount(Entity)`

- `Void SandboxAvgCollectItem(String, Int32, Boolean)`

- `Void SandboxAvgCollectItemList(List`1)`

- `Boolean CheckItemCount(String, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxBattleDataController : IHotfixable
{
	private SandboxInput m_input; // 0x10
	private SandboxOutput m_output; // 0x18
	private SandboxGameMode m_gameMode; // 0x20
	private SandboxBattleManager m_manager; // 0x28
	private Dictionary`2 m_resCollectedTotal; // 0x30
	private Dictionary`2 m_resCollectedThisLevel; // 0x38
	private Dictionary`2 m_resCollectedOnEnity; // 0x40
	private Dictionary`2 m_entityDroppedThisLevel; // 0x48
	private List`1 m_rushEnemyReachExit; // 0x50
	private ListDict`2 m_killedEnemies; // 0x58
	private Dictionary`2 m_entityStatus; // 0x60
	private Dictionary`2 m_placedItemStatus; // 0x68
	private Dictionary`2 m_outPlacedItemStatus; // 0x70
	private Dictionary`2 m_usedConstructItems; // 0x78
	private List`1 m_shinyUniEnemy; // 0x80
	private Action`2 onItemCollect; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_add_onItemCollect; // 0x8
	private static DelegateBridge __Hotfix0_remove_onItemCollect; // 0x10
	private static DelegateBridge __Hotfix0_get_output; // 0x18
	private static DelegateBridge __Hotfix0_get_entityStatus; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0__InitInputStatus; // 0x30
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x38
	private static DelegateBridge __Hotfix0_OnFetchGameOverOutput; // 0x40
	private static DelegateBridge __Hotfix0_FetchBossRecordedStatus; // 0x48
	private static DelegateBridge __Hotfix0_FetchUniEnemyRecordedStatus; // 0x50
	private static DelegateBridge __Hotfix0_FetchUnitRecordedStatus; // 0x58
	private static DelegateBridge __Hotfix0_FetchPlacedItemRecordedStatus; // 0x60
	private static DelegateBridge __Hotfix0_FetchUniEnemyExtraInfo; // 0x68
	private static DelegateBridge __Hotfix0_RecordUnitState; // 0x70
	private static DelegateBridge __Hotfix0_RecordPlacedItemState; // 0x78
	private static DelegateBridge __Hotfix0_RecordBossState; // 0x80
	private static DelegateBridge __Hotfix0_RecordUniEnemyState; // 0x88
	private static DelegateBridge __Hotfix0_CheckSpecialUniEnemy; // 0x90
	private static DelegateBridge __Hotfix0_RecordUsingConstructItem; // 0x98
	private static DelegateBridge __Hotfix0_MarkRushEnemyDead; // 0xa0
	private static DelegateBridge __Hotfix0_MarkRushEnemyReachExit; // 0xa8
	private static DelegateBridge __Hotfix0_MarkEnemyNeedRefreshDead; // 0xb0
	private static DelegateBridge __Hotfix0_ConstructSaveLevelRes; // 0xb8
	private static DelegateBridge __Hotfix0_GetResCountByID; // 0xc0
	private static DelegateBridge __Hotfix0__PackedResDictKey; // 0xc8
	private static DelegateBridge __Hotfix0_SandboxEntityPackedItems; // 0xd0
	private static DelegateBridge __Hotfix0__SandboxEntityPackItem; // 0xd8
	private static DelegateBridge __Hotfix0__SandboxCollectItem; // 0xe0
	private static DelegateBridge __Hotfix0_SandboxEntityDropItem; // 0xe8
	private static DelegateBridge __Hotfix1_SandboxEntityDropItem; // 0xf0
	private static DelegateBridge __Hotfix0_SandboxCollectItem; // 0xf8
	private static DelegateBridge __Hotfix0_CollectPackedRes; // 0x100
	private static DelegateBridge __Hotfix0_TransferAllPackedRes; // 0x108
	private static DelegateBridge __Hotfix0__TransferPackedRes; // 0x110
	private static DelegateBridge __Hotfix0_GetPackedResMaxCount; // 0x118
	private static DelegateBridge __Hotfix1_GetPackedResMaxCount; // 0x120
	private static DelegateBridge __Hotfix0_GetPackedResRestCount; // 0x128
	private static DelegateBridge __Hotfix0_GetTotalPackedResCount; // 0x130
	private static DelegateBridge __Hotfix0_SandboxAvgCollectItem; // 0x138
	private static DelegateBridge __Hotfix0_SandboxAvgCollectItemList; // 0x140
	private static DelegateBridge __Hotfix0_CheckItemCount; // 0x148

	public SandboxOutput output { get; }
	public Dictionary`2 entityStatus { get; }

	// RVA: 0x1de29c4 VA: 0x75943fa9c4
	public Void .ctor(SandboxGameMode gameMode, SandboxBattleManager manager) { }
	// RVA: 0x1de2df8 VA: 0x75943fadf8
	public Void add_onItemCollect(Action`2 value) { }
	// RVA: 0x1de2eec VA: 0x75943faeec
	public Void remove_onItemCollect(Action`2 value) { }
	// RVA: 0x1de2fe0 VA: 0x75943fafe0
	public SandboxOutput get_output() { }
	// RVA: 0x1de3054 VA: 0x75943fb054
	public Dictionary`2 get_entityStatus() { }
	// RVA: 0x1de30bc VA: 0x75943fb0bc
	public Void Init() { }
	// RVA: 0x1de3124 VA: 0x75943fb124
	private Void _InitInputStatus() { }
	// RVA: 0x1de35f0 VA: 0x75943fb5f0
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x1de378c VA: 0x75943fb78c
	public Void OnFetchGameOverOutput() { }
	// RVA: 0x1de43e0 VA: 0x75943fc3e0
	public Boolean FetchBossRecordedStatus(String rushEnemyUid, String targetKey, out SandboxRushBossStatus status) { }
	// RVA: 0x1de4580 VA: 0x75943fc580
	public Boolean FetchUniEnemyRecordedStatus(String targetKey, out SandboxV2UniEnemyStatus status) { }
	// RVA: 0x1de46e4 VA: 0x75943fc6e4
	public Boolean FetchUnitRecordedStatus(SandboxEntityStatusKey targetKey, out SandboxEntityStatusValue status) { }
	// RVA: 0x1de47a8 VA: 0x75943fc7a8
	public Boolean FetchPlacedItemRecordedStatus(SandboxPlacedItemStatusKey targetKey, out SandboxPlacedItemStatusValue status) { }
	// RVA: 0x1de4934 VA: 0x75943fc934
	public Boolean FetchUniEnemyExtraInfo(String targetKey, out RareAnimalExtraInfo extraInfo) { }
	// RVA: 0x1de4b34 VA: 0x75943fcb34
	public Void RecordUnitState(SandboxLevelDataProcessor levelDataProcessor, SandboxEntityStatusKey targetKey, SandboxEntityStatusValue newStatus) { }
	// RVA: 0x1de4d1c VA: 0x75943fcd1c
	public Void RecordPlacedItemState(SandboxPlacedItemStatusKey targetKey, SandboxPlacedItemStatusValue newStatus) { }
	// RVA: 0x1de4de0 VA: 0x75943fcde0
	public Void RecordBossState(String enemyUid, String targetKey, SandboxRushBossStatus newStatus) { }
	// RVA: 0x1de500c VA: 0x75943fd00c
	public Void RecordUniEnemyState(String targetKey, SandboxV2UniEnemyStatus newStatus) { }
	// RVA: 0x1de50c0 VA: 0x75943fd0c0
	public Boolean CheckSpecialUniEnemy(String enemyId) { }
	// RVA: 0x1de5198 VA: 0x75943fd198
	public Void RecordUsingConstructItem(Character character) { }
	// RVA: 0x1de5400 VA: 0x75943fd400
	public Void MarkRushEnemyDead(RushEnemy rushEnemy) { }
	// RVA: 0x1de552c VA: 0x75943fd52c
	public Void MarkRushEnemyReachExit(RushEnemy rushEnemy) { }
	// RVA: 0x1de5644 VA: 0x75943fd644
	public Void MarkEnemyNeedRefreshDead(ActionID actionId) { }
	// RVA: 0x1de5724 VA: 0x75943fd724
	public Void ConstructSaveLevelRes() { }
	// RVA: 0x1de57ac VA: 0x75943fd7ac
	public Int32 GetResCountByID(String resId, Boolean thisLevel) { }
	// RVA: 0x1de5878 VA: 0x75943fd878
	private UInt32 _PackedResDictKey(Entity entity) { }
	// RVA: 0x1de599c VA: 0x75943fd99c
	public Int32[] SandboxEntityPackedItems(Entity entity) { }
	// RVA: 0x1de5acc VA: 0x75943fdacc
	private Void _SandboxEntityPackItem(Entity entity, ResPackType type, Int32 count) { }
	// RVA: 0x1de5dd0 VA: 0x75943fddd0
	private Void _SandboxCollectItem(String itemId, Int32 count, Boolean withToast, Boolean withSound) { }
	// RVA: 0x1de60b0 VA: 0x75943fe0b0
	public Void SandboxEntityDropItem(Entity entity, ResDropSourceType type) { }
	// RVA: 0x1de6194 VA: 0x75943fe194
	public Void SandboxEntityDropItem(Entity entity, String itemId, Int32 count) { }
	// RVA: 0x1de641c VA: 0x75943fe41c
	public Void SandboxCollectItem(String itemId, Int32 count) { }
	// RVA: 0x1de64b0 VA: 0x75943fe4b0
	public Boolean CollectPackedRes(Entity entity) { }
	// RVA: 0x1de661c VA: 0x75943fe61c
	public Boolean TransferAllPackedRes(Entity fromTarget, Entity toTarget) { }
	// RVA: 0x1de678c VA: 0x75943fe78c
	private Int32 _TransferPackedRes(Entity fromTarget, Entity toTarget, ResPackType type, Int32 transferCount) { }
	// RVA: 0x1de68d4 VA: 0x75943fe8d4
	public Int32 GetPackedResMaxCount(Entity entity) { }
	// RVA: 0x1de69c0 VA: 0x75943fe9c0
	public Int32 GetPackedResMaxCount(Card card) { }
	// RVA: 0x1de66f4 VA: 0x75943fe6f4
	public Int32 GetPackedResRestCount(Entity entity) { }
	// RVA: 0x1de6b0c VA: 0x75943feb0c
	public Int32 GetTotalPackedResCount(Entity entity) { }
	// RVA: 0x1de6c14 VA: 0x75943fec14
	public Void SandboxAvgCollectItem(String itemId, Int32 count, Boolean withToast) { }
	// RVA: 0x1de6cd4 VA: 0x75943fecd4
	public Void SandboxAvgCollectItemList(List`1 models) { }
	// RVA: 0x1de6e70 VA: 0x75943fee70
	public Boolean CheckItemCount(String itemId, Int32 count, Boolean containsEq) { }
}
```