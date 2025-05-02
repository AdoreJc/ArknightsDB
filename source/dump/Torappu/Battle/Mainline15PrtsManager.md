# Mainline15PrtsManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _prtsEnemyKey`

- `String _prtsEnemyDragTileKey`

- `Single _prtsSpawnCheckDistance`

- `BuffData _buffToPrtsWhenActionFinish`

- `BuffData _buffToPrtsWhenStartSubActionFailed`

- `String _effectOnDragTile`

- `String _effectMarkDragTargetPos`

- `String _prtsErrorBattleEvent`

- `String _prtsErrorUIPlugin`

- `Single _prtsWriterInterval`

- `Int32 _prtsWriterMaxLine`

- `EnemyPrts m_prts`

- `Boolean m_forceBattleSpeed`

- `Vector2 m_prtsDragPos`

- `Int32 m_mapHeight`

- `Int32 m_mapWidth`

- `PrtsErrorMetaController m_prtsErrorMetaController`


## Methods

- `Void CreateBuffToPrts(BuffData, Blackboard)`

- `Boolean SkipPrtsAction(PrtsActionType)`

- `Boolean FilterCurrenSubAction(PrtsSubActionType)`

- `Boolean FilterCurrentAction(PrtsActionType)`

- `Boolean TryNextSubAction(Boolean, Boolean)`

- `Boolean TryPickNextAction()`

- `Void _ParseMoveCreateBuffAction(PrtsAction)`

- `Void _ParseMoveAndSpawnEnemyAction(PrtsAction)`

- `Void _ParseMoveAndDragSourceAction(PrtsAction)`

- `Void _OnActionStart(PrtsAction)`

- `Void _OnActionFinish()`

- `Void _OnSubActionStartFailed()`

- `Void _OnPrtsFree()`

- `Boolean TrySpawnEnemyOnMostSurround(Tile, Int32, String, String, String)`

- `Void TryMoveAndCreateBuff(Int32, Vector2, BuffData, Blackboard)`

- `Void TryMoveAndDragSource(Int32, Entity, Vector2, BuffData, Blackboard)`

- `Tile FindMostCharacterSurroundTile()`

- `Tile FindMostEnemySurroundTile()`

- `Boolean _GetTileViaMaxDataMapFilter(Tile, Boolean)`

- `Tile _GetTileViaMaxDataMap(Int32[, ], Boolean, Boolean)`

- `Void _InitPrtsHookedAction()`

- `Void Update()`

- `Void SetForceBattleSpeed(Boolean)`

- `Void _OnUnitBorn(Object)`

- `Void _OnGameOver(Object)`

- `Void _OnBeforeLevelActionExecute(Object)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Mainline15PrtsManager : EnvManager
{
	private String _prtsEnemyKey; // 0x28
	private String _prtsEnemyDragTileKey; // 0x30
	private Single _prtsSpawnCheckDistance; // 0x38
	private HighlandEnemyTrapPair[] _enemyTrapKeyPairs; // 0x40
	private BuffData _buffToPrtsWhenActionFinish; // 0x48
	private BuffData _buffToPrtsWhenStartSubActionFailed; // 0x50
	private String _effectOnDragTile; // 0x58
	private String _effectMarkDragTargetPos; // 0x60
	private String _prtsErrorBattleEvent; // 0x68
	private String _prtsErrorUIPlugin; // 0x70
	private Single _prtsWriterInterval; // 0x78
	private Int32 _prtsWriterMaxLine; // 0x7c
	public static readonly String EVENT_SYSTEM_KEY; // 0x0
	private EnemyPrts m_prts; // 0x80
	private Boolean m_forceBattleSpeed; // 0x88
	private Vector2 m_prtsDragPos; // 0x8c
	private HashSet`1 m_actionPrtsHooked; // 0x98
	private Queue`1 m_subActionsInDoing; // 0xa0
	private PriorityQueue`1 m_pendingPrtsActions; // 0xa8
	private Int32[,] m_charCountMap; // 0xb0
	private Int32[,] m_enemyCountMap; // 0xb8
	private Int32 m_mapHeight; // 0xc0
	private Int32 m_mapWidth; // 0xc4
	private List`1 m_sharedTileResults; // 0xc8
	private PrtsErrorMetaController m_prtsErrorMetaController; // 0xd0
	private static DelegateBridge __Hotfix0_CreateBuffToPrts; // 0x8
	private static DelegateBridge __Hotfix0_SkipPrtsAction; // 0x10
	private static DelegateBridge __Hotfix0_FilterCurrenSubAction; // 0x18
	private static DelegateBridge __Hotfix0_FilterCurrentAction; // 0x20
	private static DelegateBridge __Hotfix0_TryNextSubAction; // 0x28
	private static DelegateBridge __Hotfix0_TryPickNextAction; // 0x30
	private static DelegateBridge __Hotfix0__ParseMoveCreateBuffAction; // 0x38
	private static DelegateBridge __Hotfix0__ParseMoveAndSpawnEnemyAction; // 0x40
	private static DelegateBridge __Hotfix0__ParseMoveAndDragSourceAction; // 0x48
	private static DelegateBridge __Hotfix0__OnActionStart; // 0x50
	private static DelegateBridge __Hotfix0__OnActionFinish; // 0x58
	private static DelegateBridge __Hotfix0__OnSubActionStartFailed; // 0x60
	private static DelegateBridge __Hotfix0__OnPrtsFree; // 0x68
	private static DelegateBridge __Hotfix0_TrySpawnEnemyOnMostSurround; // 0x70
	private static DelegateBridge __Hotfix0_TryMoveAndCreateBuff; // 0x78
	private static DelegateBridge __Hotfix0_TryMoveAndDragSource; // 0x80
	private static DelegateBridge __Hotfix0_FindMostCharacterSurroundTile; // 0x88
	private static DelegateBridge __Hotfix0_FindMostEnemySurroundTile; // 0x90
	private static DelegateBridge __Hotfix0__GetTileViaMaxDataMapFilter; // 0x98
	private static DelegateBridge __Hotfix0__GetTileViaMaxDataMap; // 0xa0
	private static DelegateBridge __Hotfix0_Init; // 0xa8
	private static DelegateBridge __Hotfix0__InitPrtsHookedAction; // 0xb0
	private static DelegateBridge __Hotfix0_OnTick; // 0xb8
	private static DelegateBridge __Hotfix0_Update; // 0xc0
	private static DelegateBridge __Hotfix0_SetForceBattleSpeed; // 0xc8
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0xd0
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0xd8
	private static DelegateBridge __Hotfix0__OnGameOver; // 0xe0
	private static DelegateBridge __Hotfix0__OnBeforeLevelActionExecute; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4054390 VA: 0x759666c390
	public Void CreateBuffToPrts(BuffData buffData, Blackboard blackboard) { }
	// RVA: 0x4054460 VA: 0x759666c460
	public Boolean SkipPrtsAction(PrtsActionType actionType) { }
	// RVA: 0x4054718 VA: 0x759666c718
	public Boolean FilterCurrenSubAction(PrtsSubActionType actionType) { }
	// RVA: 0x4054868 VA: 0x759666c868
	public Boolean FilterCurrentAction(PrtsActionType actionType) { }
	// RVA: 0x40549b4 VA: 0x759666c9b4
	public Boolean TryNextSubAction(Boolean doNextWhenSuccess, Boolean forceNext) { }
	// RVA: 0x4054dc0 VA: 0x759666cdc0
	public Boolean TryPickNextAction() { }
	// RVA: 0x40551f8 VA: 0x759666d1f8
	private Void _ParseMoveCreateBuffAction(PrtsAction action) { }
	// RVA: 0x40553d4 VA: 0x759666d3d4
	private Void _ParseMoveAndSpawnEnemyAction(PrtsAction action) { }
	// RVA: 0x4055670 VA: 0x759666d670
	private Void _ParseMoveAndDragSourceAction(PrtsAction action) { }
	// RVA: 0x405584c VA: 0x759666d84c
	private Void _OnActionStart(PrtsAction action) { }
	// RVA: 0x4054d4c VA: 0x759666cd4c
	private Void _OnActionFinish() { }
	// RVA: 0x4054ca8 VA: 0x759666cca8
	private Void _OnSubActionStartFailed() { }
	// RVA: 0x4055118 VA: 0x759666d118
	private Void _OnPrtsFree() { }
	// RVA: 0x4055ebc VA: 0x759666debc
	public Boolean TrySpawnEnemyOnMostSurround(Tile targetTile, Int32 priority, String enemyKeyFly, String enemyKeyHL, String enemyKeyLL) { }
	// RVA: 0x40561bc VA: 0x759666e1bc
	public Void TryMoveAndCreateBuff(Int32 priority, Vector2 targetPos, BuffData buffData, Blackboard blackboard) { }
	// RVA: 0x4056340 VA: 0x759666e340
	public Void TryMoveAndDragSource(Int32 priority, Entity source, Vector2 targetPos, BuffData buffData, Blackboard blackboard) { }
	// RVA: 0x40564e4 VA: 0x759666e4e4
	public Tile FindMostCharacterSurroundTile() { }
	// RVA: 0x4056cac VA: 0x759666ecac
	public Tile FindMostEnemySurroundTile() { }
	// RVA: 0x405707c VA: 0x759666f07c
	private Boolean _GetTileViaMaxDataMapFilter(Tile tile, Boolean excludeTileHasChar) { }
	// RVA: 0x4056894 VA: 0x759666e894
	private Tile _GetTileViaMaxDataMap(Int32[,] dataMap, Boolean excludeTileHasChar, Boolean excludeStartEnd) { }
	// RVA: 0x40571c4 VA: 0x759666f1c4
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x40573d4 VA: 0x759666f3d4
	private Void _InitPrtsHookedAction() { }
	// RVA: 0x4057658 VA: 0x759666f658
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x405794c VA: 0x759666f94c
	private Void Update() { }
	// RVA: 0x4057aac VA: 0x759666faac
	public Void SetForceBattleSpeed(Boolean enable) { }
	// RVA: 0x4057b3c VA: 0x759666fb3c
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4057dec VA: 0x759666fdec
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x40580b8 VA: 0x75966700b8
	private Void _OnGameOver(Object arg) { }
	// RVA: 0x40581ac VA: 0x75966701ac
	private Void _OnBeforeLevelActionExecute(Object arg) { }
	// RVA: 0x4058ae0 VA: 0x7596670ae0
	public Void .ctor() { }
	// RVA: 0x4058d74 VA: 0x7596670d74
	private static Void .cctor() { }
	// RVA: 0x4058de0 VA: 0x7596670de0
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4058de8 VA: 0x7596670de8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x4058df0 VA: 0x7596670df0
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
}
```