# Tile

**Namespace:** `Torappu.Battle`


## Fields

- `String _tileKey`

- `Single _height`

- `Single _locateHeightOffset`

- `Boolean _forceBoxCollider`

- `TileGraphic _graphic`

- `String _effect`

- `TileData _data`

- `MapLayer _mapLayer`

- `Boolean _injectEnvDmgFlagToBlackboard`

- `Int32 m_triggerCnt`

- `Blackboard m_blackboard`

- `TileData m_data`

- `Options m_originOptions`

- `Options m_cachedOptions`

- `Single m_height`

- `TileAppendInfo m_tileAppendInfo`

- `TileInfoMask m_tileInfo`

- `Boolean m_enableOverlap`

- `Boolean m_onlyManuallyOverlap`

- `Boolean m_blockManuallySpawn`

- `Single m_additionalFriction`

- `SortedDoubleBufferedBuildSlots m_buildSlots`

- `UInt32 <instanceUid>k__BackingField`


## Properties

- `UInt32 instanceUid`

- `Single height`

- `Boolean enableOverlap`

- `Boolean onlyManuallyOverlap`

- `Boolean blockManuallySpawn`

- `Single locateHeight`

- `Single additionalFriction`

- `Boolean isEndPosTile`

- `Boolean isStartPosTile`

- `String tileKey`

- `String tileName`

- `String tileDescription`

- `Boolean isFunctional`

- `TileGraphic graphic`

- `BuildableType buildableType`

- `MotionMask passableMask`

- `HeightType heightType`

- `HeightType originHeightType`

- `PlayerSideMask playerSideMask`

- `MapLayer mapLayer`

- `AdvancedBuildableMask advancedBuildableMask`

- `Options options`

- `Boolean isHighland`

- `Boolean isLowland`

- `Boolean isHidden`

- `Boolean isBlockable`

- `HighlightType highlightType`

- `TileGraphic extraTileGraphic`

- `TileInfoMask tileInfo`

- `TileData data`

- `Blackboard blackboard`


## Methods

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`

- `Single get_height()`

- `Void set_height(Single)`

- `Boolean get_enableOverlap()`

- `Void set_enableOverlap(Boolean)`

- `Boolean get_onlyManuallyOverlap()`

- `Void set_onlyManuallyOverlap(Boolean)`

- `Boolean get_blockManuallySpawn()`

- `Void set_blockManuallySpawn(Boolean)`

- `Single get_locateHeight()`

- `Single get_additionalFriction()`

- `Boolean get_isEndPosTile()`

- `Boolean get_isStartPosTile()`

- `String get_tileKey()`

- `String get_tileName()`

- `String get_tileDescription()`

- `Boolean get_isFunctional()`

- `TileGraphic get_graphic()`

- `BuildableType get_buildableType()`

- `MotionMask get_passableMask()`

- `HeightType get_heightType()`

- `HeightType get_originHeightType()`

- `PlayerSideMask get_playerSideMask()`

- `MapLayer get_mapLayer()`

- `AdvancedBuildableMask get_advancedBuildableMask()`

- `Options get_options()`

- `Boolean get_isHighland()`

- `Boolean get_isLowland()`

- `Boolean get_isHidden()`

- `Boolean get_isBlockable()`

- `HighlightType get_highlightType()`

- `Void set_highlightType(HighlightType)`

- `TileGraphic get_extraTileGraphic()`

- `TileInfoMask get_tileInfo()`

- `TileData get_data()`

- `Blackboard get_blackboard()`

- `Int32 CompareTo(Tile)`

- `Boolean ContainsInfoMask(TileInfoMask)`

- `Void EnsureBlackboard()`

- `Boolean AssignBlackboard(String, Single)`

- `Single GetBBFloatOrDefault(String, Single)`

- `Void AddListener(ITileListener)`

- `Void RemoveListener(ITileListener)`

- `Void AddBuildableChecker(ITileBuildableChecker)`

- `Void RemoveBuildableChecker(ITileBuildableChecker)`

- `Boolean IsPassable(MotionMode)`

- `Boolean IsPassableGoTo(MotionMode, Direction)`

- `Void OverwriteBuildableType(BuildableType)`

- `Boolean CheckBuildable(BattleCharacterData, Boolean)`

- `Void OverwriteAdvancedBuildableMask(AdvancedBuildableMask)`

- `Void OverwriteAdvancedBuildableMask(AdvancedBuildableMask, Boolean)`

- `Void OverwriteObstacleLikeMoveCost(Boolean)`

- `Character GetCharacter()`

- `Boolean HasWalkEnemy()`

- `Boolean RefreshExtraTileGraphic()`

- `Void ClearCharacterIfExists()`

- `Void ClearCharacterInBuildSlots(Character)`

- `Void ClearCharacterIfExistsBeforeReplace(Character)`

- `FixedPosition GetLocatePosition()`

- `Void OnCharacterFinished(Character, FinishReason)`

- `Boolean LocateCharacter(Character, Boolean)`

- `Void RegisterCharacter(Character)`

- `Void AddEnemy(Enemy)`

- `Void RemoveEnemy(Enemy)`

- `Void SetData(TileData, GridPosition, Map, MapLayer)`

- `Void ReplaceGraphicFromScene(IList`1)`

- `Void ClearAllGraphic()`

- `Boolean Trigger()`

- `Boolean TryUpdateOptions(Options, Boolean, Boolean)`

- `Boolean TryUpdateTileInfo(TileInfoMask)`

- `Void RestoreOptions()`

- `Void RefreshOptionsOnly(Options, Trap)`

- `Boolean VerifyOverlap(Boolean)`

- `MotionMask RewriteOptions(Options)`

- `Void _InitCollider()`

- `Boolean RefreshTileOptionsViaTrap(Trap)`

- `Void OnTrapFinished(Trap)`

- `Void RestoreOptionsOnlyViaTrap(Trap)`

- `Void HandleMapEffect(Effect)`

- `Void GenerateTileEffect()`

- `TileAppendInfo _EnsureAppendInfo(Boolean)`

- `Boolean CheckExtraBuildable(BattleCharacterData)`

- `Boolean OnEntityWillBuild(Entity, Direction, Boolean)`

- `Void Awake()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Tile : VisualObject, IHotfixable, IPtrObject, IComparable`1
{
	private static UInt32 s_tileInstCounter; // 0x0
	private String _tileKey; // 0x18
	private Single _height; // 0x20
	private Single _locateHeightOffset; // 0x24
	private Boolean _forceBoxCollider; // 0x28
	private TileGraphic _graphic; // 0x30
	private List`1 _allGraphicList; // 0x38
	private String _effect; // 0x40
	private TileData _data; // 0x48
	private MapLayer _mapLayer; // 0x50
	private Boolean _injectEnvDmgFlagToBlackboard; // 0x54
	private Int32 m_triggerCnt; // 0x58
	private Blackboard m_blackboard; // 0x60
	private TileData m_data; // 0x68
	private Options m_originOptions; // 0x70
	private Options m_cachedOptions; // 0x84
	private Single m_height; // 0x98
	private TileAppendInfo m_tileAppendInfo; // 0xa0
	private TileInfoMask m_tileInfo; // 0xa8
	private KeyValuePair`2 m_extraTileGraphic; // 0xb0
	private Boolean m_enableOverlap; // 0xc8
	private Boolean m_onlyManuallyOverlap; // 0xc9
	private Boolean m_blockManuallySpawn; // 0xca
	protected Single m_additionalFriction; // 0xcc
	protected List`1 m_tileEffectSpecs; // 0xd0
	protected SortedDoubleBufferedBuildSlots m_buildSlots; // 0xd8
	protected DoubleBufferedList`1 m_enemies; // 0xe0
	private List`1 m_listeners; // 0xe8
	private List`1 m_extraBuildableCheckers; // 0xf0
	private Int32[] m_gotoDirectionalPassableMask; // 0xf8
	private Behaviour[] m_behaviours; // 0x100
	private UInt32 <instanceUid>k__BackingField; // 0x108
	private static DelegateBridge __Hotfix0_get_buildSlot; // 0x8
	private static DelegateBridge __Hotfix0_get_slotEnumerator; // 0x10
	private static DelegateBridge __Hotfix0_get_instanceUid; // 0x18
	private static DelegateBridge __Hotfix0_set_instanceUid; // 0x20
	private static DelegateBridge __Hotfix0_get_height; // 0x28
	private static DelegateBridge __Hotfix0_set_height; // 0x30
	private static DelegateBridge __Hotfix0_get_enableOverlap; // 0x38
	private static DelegateBridge __Hotfix0_set_enableOverlap; // 0x40
	private static DelegateBridge __Hotfix0_get_onlyManuallyOverlap; // 0x48
	private static DelegateBridge __Hotfix0_set_onlyManuallyOverlap; // 0x50
	private static DelegateBridge __Hotfix0_get_blockManuallySpawn; // 0x58
	private static DelegateBridge __Hotfix0_set_blockManuallySpawn; // 0x60
	private static DelegateBridge __Hotfix0_get_locateHeight; // 0x68
	private static DelegateBridge __Hotfix0_get_additionalFriction; // 0x70
	private static DelegateBridge __Hotfix0_get_isEndPosTile; // 0x78
	private static DelegateBridge __Hotfix0_get_isStartPosTile; // 0x80
	private static DelegateBridge __Hotfix0_get_tileKey; // 0x88
	private static DelegateBridge __Hotfix0_get_tileName; // 0x90
	private static DelegateBridge __Hotfix0_get_tileDescription; // 0x98
	private static DelegateBridge __Hotfix0_get_isFunctional; // 0xa0
	private static DelegateBridge __Hotfix0_get_graphic; // 0xa8
	private static DelegateBridge __Hotfix0_get_buildableType; // 0xb0
	private static DelegateBridge __Hotfix0_get_passableMask; // 0xb8
	private static DelegateBridge __Hotfix0_get_heightType; // 0xc0
	private static DelegateBridge __Hotfix0_get_originHeightType; // 0xc8
	private static DelegateBridge __Hotfix0_get_playerSideMask; // 0xd0
	private static DelegateBridge __Hotfix0_get_mapLayer; // 0xd8
	private static DelegateBridge __Hotfix0_get_advancedBuildableMask; // 0xe0
	private static DelegateBridge __Hotfix0_get_options; // 0xe8
	private static DelegateBridge __Hotfix0_get_isHighland; // 0xf0
	private static DelegateBridge __Hotfix0_get_isLowland; // 0xf8
	private static DelegateBridge __Hotfix0_get_isHidden; // 0x100
	private static DelegateBridge __Hotfix0_get_isBlockable; // 0x108
	private static DelegateBridge __Hotfix0_get_highlightType; // 0x110
	private static DelegateBridge __Hotfix0_set_highlightType; // 0x118
	private static DelegateBridge __Hotfix0_get_extraTileGraphic; // 0x120
	private static DelegateBridge __Hotfix0_get_tileInfo; // 0x128
	private static DelegateBridge __Hotfix0_get_moveCost; // 0x130
	private static DelegateBridge __Hotfix0_get_isObstacleLike; // 0x138
	private static DelegateBridge __Hotfix0_get_triggerable; // 0x140
	private static DelegateBridge __Hotfix0_get_maxTriggerCnt; // 0x148
	private static DelegateBridge __Hotfix0_get_data; // 0x150
	private static DelegateBridge __Hotfix0_get_blackboard; // 0x158
	private static DelegateBridge __Hotfix0_get_effectHolder; // 0x160
	private static DelegateBridge __Hotfix0_CompareTo; // 0x168
	private static DelegateBridge __Hotfix0_Init; // 0x170
	private static DelegateBridge __Hotfix0_ContainsInfoMask; // 0x178
	private static DelegateBridge __Hotfix0_EnsureBlackboard; // 0x180
	private static DelegateBridge __Hotfix0_AssignBlackboard; // 0x188
	private static DelegateBridge __Hotfix0_GetBBFloatOrDefault; // 0x190
	private static DelegateBridge __Hotfix0_AddListener; // 0x198
	private static DelegateBridge __Hotfix0_RemoveListener; // 0x1a0
	private static DelegateBridge __Hotfix0_AddBuildableChecker; // 0x1a8
	private static DelegateBridge __Hotfix0_RemoveBuildableChecker; // 0x1b0
	private static DelegateBridge __Hotfix0_IsPassable; // 0x1b8
	private static DelegateBridge __Hotfix0_IsPassableGoTo; // 0x1c0
	private static DelegateBridge __Hotfix0_OverwriteBuildableType; // 0x1c8
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x1d0
	private static DelegateBridge __Hotfix0_OverwriteAdvancedBuildableMask; // 0x1d8
	private static DelegateBridge __Hotfix1_OverwriteAdvancedBuildableMask; // 0x1e0
	private static DelegateBridge __Hotfix0_OverwriteObstacleLikeMoveCost; // 0x1e8
	private static DelegateBridge __Hotfix0_GetCharacter; // 0x1f0
	private static DelegateBridge __Hotfix0_GetEnemies; // 0x1f8
	private static DelegateBridge __Hotfix0_GetEntities_DISPOSE; // 0x200
	private static DelegateBridge __Hotfix0_HasWalkEnemy; // 0x208
	private static DelegateBridge __Hotfix0_RefreshExtraTileGraphic; // 0x210
	private static DelegateBridge __Hotfix0_ClearCharacterIfExists; // 0x218
	private static DelegateBridge __Hotfix0_ClearCharacterInBuildSlots; // 0x220
	private static DelegateBridge __Hotfix0_ClearCharacterIfExistsBeforeReplace; // 0x228
	private static DelegateBridge __Hotfix0_GetLocatePosition; // 0x230
	private static DelegateBridge __Hotfix0_OnCharacterFinished; // 0x238
	private static DelegateBridge __Hotfix0_LocateCharacter; // 0x240
	private static DelegateBridge __Hotfix0_RegisterCharacter; // 0x248
	private static DelegateBridge __Hotfix0_AddEnemy; // 0x250
	private static DelegateBridge __Hotfix0_RemoveEnemy; // 0x258
	private static DelegateBridge __Hotfix0_SetData; // 0x260
	private static DelegateBridge __Hotfix0_ReplaceGraphicFromScene; // 0x268
	private static DelegateBridge __Hotfix0_ClearAllGraphic; // 0x270
	private static DelegateBridge __Hotfix0_Trigger; // 0x278
	private static DelegateBridge __Hotfix0_TryUpdateOptions; // 0x280
	private static DelegateBridge __Hotfix0_TryUpdateTileInfo; // 0x288
	private static DelegateBridge __Hotfix0_RestoreOptions; // 0x290
	private static DelegateBridge __Hotfix0_RefreshOptionsOnly; // 0x298
	private static DelegateBridge __Hotfix0_VerifyOverlap; // 0x2a0
	private static DelegateBridge __Hotfix0_RewriteOptions; // 0x2a8
	private static DelegateBridge __Hotfix0_PreprocessTileOptions; // 0x2b0
	private static DelegateBridge __Hotfix0_PreloadAssets; // 0x2b8
	private static DelegateBridge __Hotfix0__InitCollider; // 0x2c0
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x2c8
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x2d0
	private static DelegateBridge __Hotfix0_OnCharacterEnter; // 0x2d8
	private static DelegateBridge __Hotfix0_OnCharacterLeave; // 0x2e0
	private static DelegateBridge __Hotfix0_OnRallyPointLikeReborn; // 0x2e8
	private static DelegateBridge __Hotfix0_OnRallyPointLikeFakeDeath; // 0x2f0
	private static DelegateBridge __Hotfix0_OnEnemyEnter; // 0x2f8
	private static DelegateBridge __Hotfix0_OnEnemyLeave; // 0x300
	private static DelegateBridge __Hotfix0_HoldEffect; // 0x308
	private static DelegateBridge __Hotfix0_FinishHoldEffect; // 0x310
	private static DelegateBridge __Hotfix0_FinishSpecifiedHoldEffect; // 0x318
	private static DelegateBridge __Hotfix0_CheckHasHoldEffect; // 0x320
	private static DelegateBridge __Hotfix0_RefreshTileOptionsViaTrap; // 0x328
	private static DelegateBridge __Hotfix0_OnTrapFinished; // 0x330
	private static DelegateBridge __Hotfix0_RestoreOptionsOnlyViaTrap; // 0x338
	private static DelegateBridge __Hotfix0_OnEntityEnter; // 0x340
	private static DelegateBridge __Hotfix0_OnEntityLeave; // 0x348
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x350
	private static DelegateBridge __Hotfix0_HandleMapEffect; // 0x358
	private static DelegateBridge __Hotfix0_GenerateTileEffect; // 0x360
	private static DelegateBridge __Hotfix0__EnsureAppendInfo; // 0x368
	private static DelegateBridge __Hotfix0_CheckExtraBuildable; // 0x370
	private static DelegateBridge __Hotfix0_OnEntityWillBuild; // 0x378
	private static DelegateBridge __Hotfix0_Awake; // 0x380
	private static DelegateBridge __Hotfix0_Start; // 0x388
	private static DelegateBridge _c__Hotfix0_ctor; // 0x390

	protected ObjectPtr`1 buildSlot { get; }
	public IEnumerator`1 slotEnumerator { get; }
	public UInt32 instanceUid { get; set; }
	public Single height { get; set; }
	public Boolean enableOverlap { get; set; }
	public Boolean onlyManuallyOverlap { get; set; }
	public Boolean blockManuallySpawn { get; set; }
	public Single locateHeight { get; }
	public Single additionalFriction { get; }
	public Boolean isEndPosTile { get; }
	public Boolean isStartPosTile { get; }
	public String tileKey { get; }
	public String tileName { get; }
	public String tileDescription { get; }
	public Boolean isFunctional { get; }
	public TileGraphic graphic { get; }
	public BuildableType buildableType { get; }
	public MotionMask passableMask { get; }
	public HeightType heightType { get; }
	public HeightType originHeightType { get; }
	public PlayerSideMask playerSideMask { get; }
	public MapLayer mapLayer { get; }
	public AdvancedBuildableMask advancedBuildableMask { get; }
	public Options options { get; }
	public Boolean isHighland { get; }
	public Boolean isLowland { get; }
	public Boolean isHidden { get; }
	public Boolean isBlockable { get; }
	public HighlightType highlightType { get; set; }
	private TileGraphic extraTileGraphic { get; }
	public TileInfoMask tileInfo { get; }
	public virtual Int32 moveCost { get; }
	public virtual Boolean isObstacleLike { get; }
	public virtual Boolean triggerable { get; }
	protected virtual Int32 maxTriggerCnt { get; }
	protected TileData data { get; }
	public Blackboard blackboard { get; }
	public virtual Transform effectHolder { get; }

	// RVA: 0x408a42c VA: 0x75966a242c
	protected ObjectPtr`1 get_buildSlot() { }
	// RVA: 0x4092e8c VA: 0x75966aae8c
	public IEnumerator`1 get_slotEnumerator() { }
	// RVA: 0x4092f14 VA: 0x75966aaf14
	public UInt32 get_instanceUid() { }
	// RVA: 0x4092f7c VA: 0x75966aaf7c
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x4092ff8 VA: 0x75966aaff8
	public Single get_height() { }
	// RVA: 0x4093060 VA: 0x75966ab060
	public Void set_height(Single value) { }
	// RVA: 0x40930dc VA: 0x75966ab0dc
	public Boolean get_enableOverlap() { }
	// RVA: 0x4093144 VA: 0x75966ab144
	public Void set_enableOverlap(Boolean value) { }
	// RVA: 0x40931c4 VA: 0x75966ab1c4
	public Boolean get_onlyManuallyOverlap() { }
	// RVA: 0x409322c VA: 0x75966ab22c
	public Void set_onlyManuallyOverlap(Boolean value) { }
	// RVA: 0x40932ac VA: 0x75966ab2ac
	public Boolean get_blockManuallySpawn() { }
	// RVA: 0x4093314 VA: 0x75966ab314
	public Void set_blockManuallySpawn(Boolean value) { }
	// RVA: 0x4093394 VA: 0x75966ab394
	public Single get_locateHeight() { }
	// RVA: 0x4093404 VA: 0x75966ab404
	public Single get_additionalFriction() { }
	// RVA: 0x409346c VA: 0x75966ab46c
	public Boolean get_isEndPosTile() { }
	// RVA: 0x40934fc VA: 0x75966ab4fc
	public Boolean get_isStartPosTile() { }
	// RVA: 0x408acf8 VA: 0x75966a2cf8
	public String get_tileKey() { }
	// RVA: 0x409358c VA: 0x75966ab58c
	public String get_tileName() { }
	// RVA: 0x4093820 VA: 0x75966ab820
	public String get_tileDescription() { }
	// RVA: 0x40938dc VA: 0x75966ab8dc
	public Boolean get_isFunctional() { }
	// RVA: 0x4093a70 VA: 0x75966aba70
	public TileGraphic get_graphic() { }
	// RVA: 0x4093ad8 VA: 0x75966abad8
	public BuildableType get_buildableType() { }
	// RVA: 0x4093b40 VA: 0x75966abb40
	public MotionMask get_passableMask() { }
	// RVA: 0x4093ba8 VA: 0x75966abba8
	public HeightType get_heightType() { }
	// RVA: 0x4093c10 VA: 0x75966abc10
	public HeightType get_originHeightType() { }
	// RVA: 0x40883bc VA: 0x75966a03bc
	public PlayerSideMask get_playerSideMask() { }
	// RVA: 0x4093ce0 VA: 0x75966abce0
	public MapLayer get_mapLayer() { }
	// RVA: 0x4093d48 VA: 0x75966abd48
	public AdvancedBuildableMask get_advancedBuildableMask() { }
	// RVA: 0x4093db0 VA: 0x75966abdb0
	public Options get_options() { }
	// RVA: 0x4093e40 VA: 0x75966abe40
	public Boolean get_isHighland() { }
	// RVA: 0x4093ec0 VA: 0x75966abec0
	public Boolean get_isLowland() { }
	// RVA: 0x40939fc VA: 0x75966ab9fc
	public Boolean get_isHidden() { }
	// RVA: 0x4093f40 VA: 0x75966abf40
	public Boolean get_isBlockable() { }
	// RVA: 0x4093ffc VA: 0x75966abffc
	public HighlightType get_highlightType() { }
	// RVA: 0x4094130 VA: 0x75966ac130
	public Void set_highlightType(HighlightType value) { }
	// RVA: 0x4094310 VA: 0x75966ac310
	private TileGraphic get_extraTileGraphic() { }
	// RVA: 0x4094540 VA: 0x75966ac540
	public TileInfoMask get_tileInfo() { }
	// RVA: 0x4091310 VA: 0x75966a9310
	public virtual Int32 get_moveCost() { }
	// RVA: 0x4091388 VA: 0x75966a9388
	public virtual Boolean get_isObstacleLike() { }
	// RVA: 0x408f1dc VA: 0x75966a71dc
	public virtual Boolean get_triggerable() { }
	// RVA: 0x408b494 VA: 0x75966a3494
	protected virtual Int32 get_maxTriggerCnt() { }
	// RVA: 0x4093c78 VA: 0x75966abc78
	protected TileData get_data() { }
	// RVA: 0x40890c8 VA: 0x75966a10c8
	public Blackboard get_blackboard() { }
	// RVA: 0x40945a8 VA: 0x75966ac5a8
	public virtual Transform get_effectHolder() { }
	// RVA: 0x4094614 VA: 0x75966ac614
	public Int32 CompareTo(Tile another) { }
	// RVA: 0x4087e20 VA: 0x759669fe20
	public virtual Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x40946f4 VA: 0x75966ac6f4
	public Boolean ContainsInfoMask(TileInfoMask infoMask) { }
	// RVA: 0x4087508 VA: 0x759669f508
	public Void EnsureBlackboard() { }
	// RVA: 0x409477c VA: 0x75966ac77c
	public Boolean AssignBlackboard(String key, Single value) { }
	// RVA: 0x409486c VA: 0x75966ac86c
	public Single GetBBFloatOrDefault(String key, Single defaultvalue) { }
	// RVA: 0x4094928 VA: 0x75966ac928
	public Void AddListener(ITileListener listener) { }
	// RVA: 0x4094a24 VA: 0x75966aca24
	public Void RemoveListener(ITileListener listener) { }
	// RVA: 0x4094ac4 VA: 0x75966acac4
	public Void AddBuildableChecker(ITileBuildableChecker checker) { }
	// RVA: 0x4094bc0 VA: 0x75966acbc0
	public Void RemoveBuildableChecker(ITileBuildableChecker checker) { }
	// RVA: 0x4094c60 VA: 0x75966acc60
	public Boolean IsPassable(MotionMode mode) { }
	// RVA: 0x4085adc VA: 0x759669dadc
	public Boolean IsPassableGoTo(MotionMode mode, Direction direction) { }
	// RVA: 0x4087654 VA: 0x759669f654
	public Void OverwriteBuildableType(BuildableType buildableType) { }
	// RVA: 0x4094cf0 VA: 0x75966accf0
	public Boolean CheckBuildable(BattleCharacterData characterData, Boolean spawnManually) { }
	// RVA: 0x408e9f0 VA: 0x75966a69f0
	public Void OverwriteAdvancedBuildableMask(AdvancedBuildableMask advancedBuildMask) { }
	// RVA: 0x40875bc VA: 0x759669f5bc
	public Void OverwriteAdvancedBuildableMask(AdvancedBuildableMask advancedBuildMask, Boolean isAdd) { }
	// RVA: 0x408cf10 VA: 0x75966a4f10
	public Void OverwriteObstacleLikeMoveCost(Boolean flag) { }
	// RVA: 0x408d528 VA: 0x75966a5528
	public Character GetCharacter() { }
	// RVA: 0x4090370 VA: 0x75966a8370
	public DoubleBufferedList`1 GetEnemies() { }
	// RVA: 0x4094e48 VA: 0x75966ace48
	public ReusableList`1 GetEntities_DISPOSE() { }
	// RVA: 0x408f9d4 VA: 0x75966a79d4
	public Boolean HasWalkEnemy() { }
	// RVA: 0x40953d4 VA: 0x75966ad3d4
	public Boolean RefreshExtraTileGraphic() { }
	// RVA: 0x4095540 VA: 0x75966ad540
	public Void ClearCharacterIfExists() { }
	// RVA: 0x4095620 VA: 0x75966ad620
	public Void ClearCharacterInBuildSlots(Character character) { }
	// RVA: 0x4095a5c VA: 0x75966ada5c
	public Void ClearCharacterIfExistsBeforeReplace(Character character) { }
	// RVA: 0x4095b50 VA: 0x75966adb50
	public FixedPosition GetLocatePosition() { }
	// RVA: 0x4095c7c VA: 0x75966adc7c
	public Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x4095fcc VA: 0x75966adfcc
	public Boolean LocateCharacter(Character character, Boolean spawnManually) { }
	// RVA: 0x40962b8 VA: 0x75966ae2b8
	public Void RegisterCharacter(Character character) { }
	// RVA: 0x40966e0 VA: 0x75966ae6e0
	public Void AddEnemy(Enemy enemy) { }
	// RVA: 0x40967b8 VA: 0x75966ae7b8
	public Void RemoveEnemy(Enemy enemy) { }
	// RVA: 0x40968e0 VA: 0x75966ae8e0
	public Void SetData(TileData data, GridPosition pos, Map map, MapLayer layer) { }
	// RVA: 0x4096e44 VA: 0x75966aee44
	public Void ReplaceGraphicFromScene(IList`1 newGraphicList) { }
	// RVA: 0x40972a8 VA: 0x75966af2a8
	public Void ClearAllGraphic() { }
	// RVA: 0x4092cfc VA: 0x75966aacfc
	public Boolean Trigger() { }
	// RVA: 0x409748c VA: 0x75966af48c
	public Boolean TryUpdateOptions(Options newOptions, Boolean keepCurrentPassableMask, Boolean ignoreBlockAnyRoutes) { }
	// RVA: 0x4097750 VA: 0x75966af750
	public Boolean TryUpdateTileInfo(TileInfoMask info) { }
	// RVA: 0x4086d80 VA: 0x759669ed80
	public Void RestoreOptions() { }
	// RVA: 0x40977d0 VA: 0x75966af7d0
	public Void RefreshOptionsOnly(Options option, Trap trap) { }
	// RVA: 0x40978c4 VA: 0x75966af8c4
	public Boolean VerifyOverlap(Boolean spawnManually) { }
	// RVA: 0x4097608 VA: 0x75966af608
	protected MotionMask RewriteOptions(Options newOptions) { }
	// RVA: 0x408e5ec VA: 0x75966a65ec
	protected virtual Void PreprocessTileOptions(ref Options tileOptions) { }
	// RVA: 0x408b2ac VA: 0x75966a32ac
	protected virtual Void PreloadAssets() { }
	// RVA: 0x4096c58 VA: 0x75966aec58
	private Void _InitCollider() { }
	// RVA: 0x409795c VA: 0x75966af95c
	public virtual Void OnGameStart() { }
	// RVA: 0x4097a0c VA: 0x75966afa0c
	public virtual Void OnGameOver(GameResult result) { }
	// RVA: 0x40885c8 VA: 0x75966a05c8
	protected virtual Void OnCharacterEnter(Character newChar, Character oldChar) { }
	// RVA: 0x4088a6c VA: 0x75966a0a6c
	protected virtual Void OnCharacterLeave(Character character) { }
	// RVA: 0x4088da8 VA: 0x75966a0da8
	public virtual Void OnRallyPointLikeReborn(Unit unit) { }
	// RVA: 0x408dce0 VA: 0x75966a5ce0
	public virtual Void OnRallyPointLikeFakeDeath(Unit unit) { }
	// RVA: 0x4088eec VA: 0x75966a0eec
	protected virtual Void OnEnemyEnter(Enemy enemy) { }
	// RVA: 0x408903c VA: 0x75966a103c
	protected virtual Void OnEnemyLeave(Enemy enemy) { }
	// RVA: 0x4097ad4 VA: 0x75966afad4
	public virtual Void HoldEffect(String effectKey, Effect effect) { }
	// RVA: 0x4097cac VA: 0x75966afcac
	public virtual Void FinishHoldEffect() { }
	// RVA: 0x4097ed8 VA: 0x75966afed8
	public virtual Void FinishSpecifiedHoldEffect(String key) { }
	// RVA: 0x4098054 VA: 0x75966b0054
	public virtual Boolean CheckHasHoldEffect(String effectKey) { }
	// RVA: 0x40960dc VA: 0x75966ae0dc
	protected Boolean RefreshTileOptionsViaTrap(Trap trap) { }
	// RVA: 0x4095e0c VA: 0x75966ade0c
	protected Void OnTrapFinished(Trap trap) { }
	// RVA: 0x4098210 VA: 0x75966b0210
	public Void RestoreOptionsOnlyViaTrap(Trap trap) { }
	// RVA: 0x4098328 VA: 0x75966b0328
	protected virtual Void OnEntityEnter(Entity entity) { }
	// RVA: 0x40984d0 VA: 0x75966b04d0
	protected virtual Void OnEntityLeave(Entity entity) { }
	// RVA: 0x408a37c VA: 0x75966a237c
	protected virtual Void OnTrigger() { }
	// RVA: 0x408d938 VA: 0x75966a5938
	protected Void HandleMapEffect(Effect effect) { }
	// RVA: 0x4098678 VA: 0x75966b0678
	public Void GenerateTileEffect() { }
	// RVA: 0x4093608 VA: 0x75966ab608
	private TileAppendInfo _EnsureAppendInfo(Boolean forceReload) { }
	// RVA: 0x40989b4 VA: 0x75966b09b4
	public Boolean CheckExtraBuildable(BattleCharacterData sourceData) { }
	// RVA: 0x4098bc8 VA: 0x75966b0bc8
	public Boolean OnEntityWillBuild(Entity entity, Direction direction, Boolean spawnManually) { }
	// RVA: 0x4098ce0 VA: 0x75966b0ce0
	private Void Awake() { }
	// RVA: 0x4098d70 VA: 0x75966b0d70
	private Void Start() { }
	// RVA: 0x40896e4 VA: 0x75966a16e4
	public Void .ctor() { }
}
```