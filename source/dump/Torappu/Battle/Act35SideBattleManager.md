# Act35SideBattleManager

**Namespace:** `Torappu.Battle`


## Fields

- `BuffData _linkEffectKeyUp`

- `BuffData _linkEffectKeyDown`

- `BuffData _linkEffectKeyLeft`

- `BuffData _linkEffectKeyRight`

- `BuffData _transEffectKeyUp`

- `BuffData _transEffectKeyDown`

- `BuffData _transEffectKeyLeft`

- `BuffData _transEffectKeyRight`

- `String _gemsBornAudioKey`

- `Int32 _gemsEliminatedAudioLimit`

- `String _gemsBigEliminatedAudioKey`

- `String _gemsEliminatedAudioKey`

- `Int32 m_mapWidth`

- `Int32 m_mapHeight`

- `Boolean m_isGameStart`

- `Int32 m_eliminatedGemsCount`

- `Int32 m_linkedGemsCount`

- `Act35SideGemsTileBuildableChecker m_tileBuildableChecker`


## Methods

- `Void GatherAudio(List`1)`

- `Int32 GetGemsCount(Boolean)`

- `Boolean CheckIfOnGemsTile(GridPosition, Boolean)`

- `Void EliminateGemsByPositionAndDirection(Int32, Int32, Direction)`

- `Boolean SummonGemsEnemyOnTileWithoutRefresh(Int32, Int32, GemsType)`

- `Boolean SummonGemsEnemyOnTileAndRefresh(Int32, Int32, GemsType)`

- `Void SummonGemsEnemyOnLine(Int32, Int32, GemsType, Direction)`

- `Void RefreshAndCheckMap()`

- `Void RefreshAndCheckMapByPos(Int32, Int32)`

- `Void UpdateMaxLinkedGemsCount(Int32, Int32)`

- `Void _OnGameStart(Object)`

- `Void _OnGemsClear(Enemy)`

- `Void _OnClearGemsTakeDamage(Entity)`

- `Void _OnUnitBorn(Object)`

- `Void _OnEnemyBorn(Enemy)`

- `Void _OnCharacterBorn(Character)`

- `Void _OnGameOver(Object)`

- `Void _CountAndRemoveGems(GemsEnemy)`

- `Void _RemoveDeBuffsFromCharacter(Enemy)`

- `Void _AddLinkEffectBuff(Entity, Int32, Int32)`

- `Void _AddTransEffectBuff(Entity, SubClearArea, Int32, Int32)`

- `Int32 _GetAreaId(Int32, Int32)`

- `Void _RemoveInvalidAreasFromMap()`

- `Void _CheckAndEliminateGemsInMap()`

- `Void _CheckAndEliminateGemsByPos(Int32, Int32)`

- `Void _CheckAndEliminateGemsInArea(Area)`

- `Void _CheckAndEliminateGemsInSubArea(Area, SubClearArea)`

- `Void _ResetAreaIdMap()`

- `Void _ResetAreaIdMapByArea(Area)`

- `Void _ResetAreaIdMapByPos(Int32, Int32, Boolean)`

- `Void _UpdateAreaMap()`

- `Void _UpdateAreaMapByPos(Int32, Int32)`

- `Void _UpdateAllSubArea()`

- `Void _UpdateSubArea(Area)`

- `Void _PrintAreaMap()`

- `Int32 _GenerateSubAreaId(Int32)`

- `Boolean _CheckIfSubAreaIsUninitialized(Int32, Int32)`

- `Boolean _CheckIfTileIsSpecificGemsType(Int32, Int32, GemsType)`

- `Void _AssignAreaIdsInPrimaryMap(Int32, Int32, Int32)`

- `Void _AssignSubAreaIdsWithinArea(Int32, Int32, Area, Int32)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTrigger(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act35SideBattleManager : EnvManager, IAudioSource
{
	private List`1 _charNotLocatedBuffs; // 0x28
	private List`1 _charLocatedBuffs; // 0x30
	private List`1 _enemyBuffs; // 0x38
	private List`1 _linkBuffs; // 0x40
	private BuffData _linkEffectKeyUp; // 0x48
	private BuffData _linkEffectKeyDown; // 0x50
	private BuffData _linkEffectKeyLeft; // 0x58
	private BuffData _linkEffectKeyRight; // 0x60
	private BuffData _transEffectKeyUp; // 0x68
	private BuffData _transEffectKeyDown; // 0x70
	private BuffData _transEffectKeyLeft; // 0x78
	private BuffData _transEffectKeyRight; // 0x80
	private String _gemsBornAudioKey; // 0x88
	private Int32 _gemsEliminatedAudioLimit; // 0x90
	private String _gemsBigEliminatedAudioKey; // 0x98
	private String _gemsEliminatedAudioKey; // 0xa0
	private Int32[,] m_areaIdMap; // 0xa8
	private Int32[,] m_gemsTypeMap; // 0xb0
	private Int32 m_mapWidth; // 0xb8
	private Int32 m_mapHeight; // 0xbc
	private Boolean m_isGameStart; // 0xc0
	private Int32 m_eliminatedGemsCount; // 0xc4
	private Int32 m_linkedGemsCount; // 0xc8
	private Act35SideGemsTileBuildableChecker m_tileBuildableChecker; // 0xd0
	private readonly Dictionary`2 m_areaIdToArea; // 0xd8
	private readonly Dictionary`2 m_areaIdToSubAreaCount; // 0xe0
	private readonly Dictionary`2 m_gemsPosToEnemy; // 0xe8
	private readonly List`1 m_invalidAreas; // 0xf0
	private static readonly List`1 ExcludedTileKey; // 0x0
	public const String EVENT_SYSTEM_KEY; // 0x0
	private const Int32 AREA_ID_PARAM; // 0x0
	private const Int32 INIT_AREA_FLAG; // 0x0
	private const Single WAIT_TIME; // 0x0
	private const String GEMS_TYPE_KEY; // 0x0
	private const String GEMS_ENEMY_ID; // 0x0
	private const String LINK_TRAP_ID; // 0x0
	private const String EVENT_SWITCH_TO_CLEAR; // 0x0
	private const String EVENT_TAKE_DAMAGE_CLEAR; // 0x0
	private const Int32 CONDUCTED_DAMAGE; // 0x0
	private const String LOG_ELIMINATE; // 0x0
	private const String LOG_LINK; // 0x0
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x18
	private static DelegateBridge __Hotfix0_GatherAudio; // 0x20
	private static DelegateBridge __Hotfix0_GetGemsCount; // 0x28
	private static DelegateBridge __Hotfix0_CheckIfOnGemsTile; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfOnExcludedTile; // 0x38
	private static DelegateBridge __Hotfix0_EliminateGemsByPositionAndDirection; // 0x40
	private static DelegateBridge __Hotfix0_SummonGemsEnemyOnTileWithoutRefresh; // 0x48
	private static DelegateBridge __Hotfix0_SummonGemsEnemyOnTileAndRefresh; // 0x50
	private static DelegateBridge __Hotfix0_SummonGemsEnemyOnLine; // 0x58
	private static DelegateBridge __Hotfix0_RefreshAndCheckMap; // 0x60
	private static DelegateBridge __Hotfix0_RefreshAndCheckMapByPos; // 0x68
	private static DelegateBridge __Hotfix0_UpdateMaxLinkedGemsCount; // 0x70
	private static DelegateBridge __Hotfix0__OnGameStart; // 0x78
	private static DelegateBridge __Hotfix0__OnGemsClear; // 0x80
	private static DelegateBridge __Hotfix0__OnClearGemsTakeDamage; // 0x88
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x90
	private static DelegateBridge __Hotfix0__OnEnemyBorn; // 0x98
	private static DelegateBridge __Hotfix0__OnCharacterBorn; // 0xa0
	private static DelegateBridge __Hotfix0__OnGameOver; // 0xa8
	private static DelegateBridge __Hotfix0__CountAndRemoveGems; // 0xb0
	private static DelegateBridge __Hotfix0__RemoveDeBuffsFromCharacter; // 0xb8
	private static DelegateBridge __Hotfix0__AddLinkEffectBuff; // 0xc0
	private static DelegateBridge __Hotfix0__AddTransEffectBuff; // 0xc8
	private static DelegateBridge __Hotfix0__GetAreaId; // 0xd0
	private static DelegateBridge __Hotfix0__RemoveInvalidAreasFromMap; // 0xd8
	private static DelegateBridge __Hotfix0__CheckAndEliminateGemsInMap; // 0xe0
	private static DelegateBridge __Hotfix0__CheckAndEliminateGemsByPos; // 0xe8
	private static DelegateBridge __Hotfix0__CheckAndEliminateGemsInArea; // 0xf0
	private static DelegateBridge __Hotfix0__CheckAndEliminateGemsInSubArea; // 0xf8
	private static DelegateBridge __Hotfix0__ResetAreaIdMap; // 0x100
	private static DelegateBridge __Hotfix0__ResetAreaIdMapByArea; // 0x108
	private static DelegateBridge __Hotfix0__ResetAreaIdMapByPos; // 0x110
	private static DelegateBridge __Hotfix0__UpdateAreaMap; // 0x118
	private static DelegateBridge __Hotfix0__UpdateAreaMapByPos; // 0x120
	private static DelegateBridge __Hotfix0__UpdateAllSubArea; // 0x128
	private static DelegateBridge __Hotfix0__UpdateSubArea; // 0x130
	private static DelegateBridge __Hotfix0__PrintAreaMap; // 0x138
	private static DelegateBridge __Hotfix0__GenerateAreaId; // 0x140
	private static DelegateBridge __Hotfix0__GenerateSubAreaId; // 0x148
	private static DelegateBridge __Hotfix0__CheckIfSubAreaIsUninitialized; // 0x150
	private static DelegateBridge __Hotfix0__CheckIfTileIsSpecificGemsType; // 0x158
	private static DelegateBridge __Hotfix0__AssignAreaIdsInPrimaryMap; // 0x160
	private static DelegateBridge __Hotfix0__AssignSubAreaIdsWithinArea; // 0x168
	private static DelegateBridge _c__Hotfix0_ctor; // 0x170

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x40363d0 VA: 0x759664e3d0
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4036680 VA: 0x759664e680
	public override Void Init(GlobalEnvSystem envSystem) { }
	// RVA: 0x4036900 VA: 0x759664e900
	public override Void OnTrigger(Object param) { }
	// RVA: 0x403736c VA: 0x759664f36c
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x4037528 VA: 0x759664f528
	public Int32 GetGemsCount(Boolean excludeLinkGems) { }
	// RVA: 0x403770c VA: 0x759664f70c
	public Boolean CheckIfOnGemsTile(GridPosition gridPosition, Boolean excludeLinkGems) { }
	// RVA: 0x403781c VA: 0x759664f81c
	public static Boolean CheckIfOnExcludedTile(GridPosition gridPosition) { }
	// RVA: 0x403791c VA: 0x759664f91c
	public Void EliminateGemsByPositionAndDirection(Int32 row, Int32 col, Direction direction) { }
	// RVA: 0x4038490 VA: 0x7596650490
	public Boolean SummonGemsEnemyOnTileWithoutRefresh(Int32 row, Int32 col, GemsType type) { }
	// RVA: 0x4038e10 VA: 0x7596650e10
	public Boolean SummonGemsEnemyOnTileAndRefresh(Int32 row, Int32 col, GemsType type) { }
	// RVA: 0x4038fe8 VA: 0x7596650fe8
	public Void SummonGemsEnemyOnLine(Int32 row, Int32 col, GemsType type, Direction direction) { }
	// RVA: 0x40383b4 VA: 0x75966503b4
	public Void RefreshAndCheckMap() { }
	// RVA: 0x4038ee8 VA: 0x7596650ee8
	public Void RefreshAndCheckMapByPos(Int32 row, Int32 col) { }
	// RVA: 0x4039aa8 VA: 0x7596651aa8
	public Void UpdateMaxLinkedGemsCount(Int32 row, Int32 col) { }
	// RVA: 0x4039ca4 VA: 0x7596651ca4
	private Void _OnGameStart(Object arg) { }
	// RVA: 0x4036b08 VA: 0x759664eb08
	private Void _OnGemsClear(Enemy enemy) { }
	// RVA: 0x4036ebc VA: 0x759664eebc
	private Void _OnClearGemsTakeDamage(Entity entity) { }
	// RVA: 0x403a5d8 VA: 0x75966525d8
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x403a78c VA: 0x759665278c
	private Void _OnEnemyBorn(Enemy enemy) { }
	// RVA: 0x403a9f8 VA: 0x75966529f8
	private Void _OnCharacterBorn(Character character) { }
	// RVA: 0x403ac84 VA: 0x7596652c84
	private Void _OnGameOver(Object arg) { }
	// RVA: 0x4038198 VA: 0x7596650198
	private Void _CountAndRemoveGems(GemsEnemy gemsEnemy) { }
	// RVA: 0x4037e2c VA: 0x759664fe2c
	private Void _RemoveDeBuffsFromCharacter(Enemy enemy) { }
	// RVA: 0x4038bcc VA: 0x7596650bcc
	private Void _AddLinkEffectBuff(Entity owner, Int32 row, Int32 col) { }
	// RVA: 0x403a2c4 VA: 0x75966522c4
	private Void _AddTransEffectBuff(Entity owner, SubClearArea subClearArea, Int32 row, Int32 col) { }
	// RVA: 0x4039bb4 VA: 0x7596651bb4
	private Int32 _GetAreaId(Int32 row, Int32 col) { }
	// RVA: 0x40395c4 VA: 0x75966515c4
	private Void _RemoveInvalidAreasFromMap() { }
	// RVA: 0x4039440 VA: 0x7596651440
	private Void _CheckAndEliminateGemsInMap() { }
	// RVA: 0x403998c VA: 0x759665198c
	private Void _CheckAndEliminateGemsByPos(Int32 row, Int32 col) { }
	// RVA: 0x403a128 VA: 0x7596652128
	private Void _CheckAndEliminateGemsInArea(Area area) { }
	// RVA: 0x403adc0 VA: 0x7596652dc0
	private Void _CheckAndEliminateGemsInSubArea(Area area, SubClearArea subClearArea) { }
	// RVA: 0x403824c VA: 0x759665024c
	private Void _ResetAreaIdMap() { }
	// RVA: 0x403b28c VA: 0x759665328c
	private Void _ResetAreaIdMapByArea(Area area) { }
	// RVA: 0x403b4d0 VA: 0x75966534d0
	private Void _ResetAreaIdMapByPos(Int32 row, Int32 col, Boolean checkNear) { }
	// RVA: 0x403918c VA: 0x759665118c
	private Void _UpdateAreaMap() { }
	// RVA: 0x40398e4 VA: 0x75966518e4
	private Void _UpdateAreaMapByPos(Int32 row, Int32 col) { }
	// RVA: 0x40392bc VA: 0x75966512bc
	private Void _UpdateAllSubArea() { }
	// RVA: 0x4039ee8 VA: 0x7596651ee8
	private Void _UpdateSubArea(Area area) { }
	// RVA: 0x4039870 VA: 0x7596651870
	private Void _PrintAreaMap() { }
	// RVA: 0x403b6c0 VA: 0x75966536c0
	private static Int32 _GenerateAreaId(Int32 row, Int32 col) { }
	// RVA: 0x403bce4 VA: 0x7596653ce4
	private Int32 _GenerateSubAreaId(Int32 id) { }
	// RVA: 0x403bbb0 VA: 0x7596653bb0
	private Boolean _CheckIfSubAreaIsUninitialized(Int32 row, Int32 col) { }
	// RVA: 0x403ba88 VA: 0x7596653a88
	private Boolean _CheckIfTileIsSpecificGemsType(Int32 row, Int32 col, GemsType type) { }
	// RVA: 0x403b75c VA: 0x759665375c
	private Void _AssignAreaIdsInPrimaryMap(Int32 i, Int32 j, Int32 newId) { }
	// RVA: 0x403be08 VA: 0x7596653e08
	private Void _AssignSubAreaIdsWithinArea(Int32 i, Int32 j, Area area, Int32 subId) { }
	// RVA: 0x403c1e4 VA: 0x75966541e4
	public Void .ctor() { }
	// RVA: 0x403c430 VA: 0x7596654430
	private static Void .cctor() { }
	// RVA: 0x403c70c VA: 0x759665470c
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x403c710 VA: 0x7596654710
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x403c714 VA: 0x7596654714
	private Void <>xLuaBaseProxy_OnTrigger(Object P0) { }
}
```