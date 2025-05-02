# Map

**Namespace:** `Torappu.Battle`


## Fields

- `Transform _anchorTransform`

- `Transform _tilesContainer`

- `Transform _graphicContainer`

- `Tiles2D _tiles`

- `DeathArea _deathArea`

- `MapGraphic _graphic`

- `MapData m_data`

- `Random m_random`

- `IPathFinding m_pathFinding`

- `MapThemeController m_themeController`


## Properties

- `Boolean isMultiLayerMap`

- `Boolean isMagicCircuitMap`

- `Int32 width`

- `Int32 height`

- `Boolean isValid`

- `CameraViewLevel cameraView`

- `Vector3 cameraFocusPos`

- `Int32 battleAreaStartCol`

- `Int32 battleAreaEndCol`

- `Transform anchorTransform`

- `Transform tilesContainer`

- `Transform graphicContainer`

- `Tile Item`

- `Tile Item`

- `MapGraphic graphic`

- `MapThemeController themeController`

- `NightMapController nightMapController`

- `MagicCircuitController magicCircuitController`

- `Random random`

- `String mapTheme`

- `MapData data`


## Methods

- `Boolean get_isMultiLayerMap()`

- `Boolean get_isMagicCircuitMap()`

- `Int32 get_width()`

- `Int32 get_height()`

- `Boolean get_isValid()`

- `CameraViewLevel get_cameraView()`

- `Vector3 get_cameraFocusPos()`

- `Int32 get_battleAreaStartCol()`

- `Int32 get_battleAreaEndCol()`

- `Transform get_anchorTransform()`

- `Transform get_tilesContainer()`

- `Transform get_graphicContainer()`

- `Tile get_Item(GridPosition)`

- `Tile get_Item(Int32, Int32)`

- `MapGraphic get_graphic()`

- `MapThemeController get_themeController()`

- `NightMapController get_nightMapController()`

- `MagicCircuitController get_magicCircuitController()`

- `Random get_random()`

- `String get_mapTheme()`

- `MapData get_data()`

- `Void Init(MapData, LevelData, IList`1, String)`

- `Void ResetSeed(Int32)`

- `Void InitRouteAndPassableMap(LevelData)`

- `Void ReplaceAllRoutes(RouteData[])`

- `Void UpdateAllRoutes()`

- `Void UpdateRoutes(MotionMode)`

- `Boolean CheckAllRoutesReachable(Boolean)`

- `Boolean CheckReachable(MotionMode, GridPosition, GridPosition, Boolean)`

- `Boolean CheckPassable(MotionMode, GridPosition)`

- `Boolean CheckObstacleLikeOrUnpassable(MotionMode, GridPosition)`

- `Void UpdatePassableMap(Tile)`

- `Boolean TryGetInitialLOrR(GridPosition, out)`

- `Void ImportData(MapData, BattleFactory, Boolean, Boolean, Boolean, Boolean)`

- `Int32 FilterTiles(IDrawableRange, Action`1)`

- `Int32 FilterTiles(IList`1, Action`1)`

- `Single GetTileHeight(HeightType)`

- `Boolean TryGetCameraView(out)`

- `Boolean CheckHasTag(String)`

- `Boolean CheckOneOfTags(IList`1)`

- `Int32 GetMapLayerCount()`

- `Void _InitMapLayers()`

- `Void _InitSceneEffects()`

- `Void _ProcessSpineShaderReplace(BaseSceneEffect)`

- `Void _InitControllerByTags()`

- `BaseSceneEffect GetFirstSceneEffect(Predicate`1)`

- `Vector3 GetLayerCenters(MapLayer)`

- `Vector3 GetLayerCenters(PlayerSide)`

- `PlayerSide GetPlayerSide(MapLayer)`

- `MapLayer GetPlayerLayer(PlayerSide)`

- `Boolean TryGetNextLayersTile(Tile, out)`

- `Void OnFixedUpdate(FP)`

- `Void Reset()`

- `Void _InitTilesAndWidgets(MapData, IList`1)`

- `Void _InitRoutesAndPassableMaps(RouteData[], RouteData[])`

- `Boolean _VerifyData(MapData)`

- `Void RefreshMeshThemeConfig()`

- `Route GenerateRuntimeRoute(UInt32, RouteData)`

- `Route GenerateRuntimeRoute(RouteData)`

- `Void TryRemoveRuntimeRoute(UInt32)`

- `Route GenerateRuntimeTraceRoute(GridPosition, MotionMode)`

- `Route GenerateRuntimeExtraRoute(GridPosition, RouteData)`

- `Boolean RemoveRuntimeExtraRoute(GridPosition)`

- `Boolean TryCalculatePathFindingDistance(MotionMode, GridPosition, GridPosition, out)`

- `Vector3 MapToWorldPosition(Vector2)`

- `Vector2 WorldToMapPosition(Vector3)`

- `Vector3 MapToWorldPositionV3(Vector3)`

- `Vector3 GetTilesCenterWorldPosition(IList`1)`

- `Boolean TryGetWorldPositionByGridPosition(GridPosition, out)`

- `Boolean TryGetGridPosByWorldPosition(Vector3, out)`

- `Vector3 WorldToMapPositionV3(Vector3)`

- `Tile GetTileByScreenPos(Vector2, out)`

- `Boolean GetMapPosByScreenPos(Vector2, out)`

- `Boolean IsPosOutOfScreen(Vector2)`

- `Boolean GetWorldPosByScreenPos(Vector2, out)`

- `Void RegisterTileBind(String, Tile)`

- `Void _ProcessTileBind()`

- `Boolean CheckGridValid(GridPosition)`

- `Boolean CheckTileValid(Int32, Int32)`

- `Boolean CheckWithinLayerRect(Tile)`

- `Boolean TryGetTile(GridPosition, out)`

- `Boolean TryGetTiles(IDrawableRange, List`1)`

- `Boolean TryGetCharacterByPos(GridPosition, out)`

- `Tile GetTile(Int32, Int32)`

- `Tile GetTile(GridPosition)`

- `Boolean TryGetTargetBehindTile(Entity, out)`

- `Boolean TryGetAroundTileByDirection(Vector2, Direction, out)`

- `Route GetRouteOrNull(Int32, Boolean)`

- `Int32 GetRouteIndex(Route)`

- `Int32 GetExtraRouteIndex(Route)`

- `Int32 GetGotoDirectionalPassableMask(GridPosition, MotionMode)`

- `ControllerT GetMapController(MapTags)`

- `Vector2 GetDirectionToGoBackFromInvalidPos(GridPosition)`

- `Void _UpdateAnchorToCenter()`

- `Tile _CreateTile(TileData, BattleFactory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Map : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, ILuaCallCSharp, IHotfixable
{
	private Transform _anchorTransform; // 0x18
	private Transform _tilesContainer; // 0x20
	private Transform _graphicContainer; // 0x28
	private Tiles2D _tiles; // 0x30
	private Edge[] _blockedEdges; // 0x38
	private DeathArea _deathArea; // 0x40
	private MapGraphic _graphic; // 0x48
	private MapData m_data; // 0x50
	private MapWidget[] m_widgets; // 0x58
	private Boolean[,][] m_passableMaps; // 0x60
	private Route[] m_routes; // 0x68
	private Route[] m_extraRoutes; // 0x70
	private ListDict`2 m_runtimeRoutes; // 0x78
	private ListDict`2 m_runtimeTraceRoutes; // 0x80
	private readonly ListDict`2 m_runtimeExtraRoutes; // 0x88
	private RaycastHit[] m_hitResults; // 0x90
	private List`1 m_updateableTiles; // 0x98
	private Random m_random; // 0xa0
	private IPathFinding m_pathFinding; // 0xa8
	private MapThemeController m_themeController; // 0xb0
	private ListDict`2 m_mapControllers; // 0xb8
	private readonly ListDict`2 m_bindKeyToTilesDict; // 0xc0
	private readonly ListDict`2 m_tileToBindingTilesDict; // 0xc8
	private readonly List`1 m_mapLayerRects; // 0xd0
	private readonly List`1 m_mapLayerCenters; // 0xd8
	private BaseSceneEffect[] m_sceneEffects; // 0xe0
	private readonly List`1 m_endTiles; // 0xe8
	private const String BLOCKED_EDGE_PREFAB; // 0x0
	private static DelegateBridge __Hotfix0_get_isMultiLayerMap; // 0x0
	private static DelegateBridge __Hotfix0_get_isMagicCircuitMap; // 0x8
	private static DelegateBridge __Hotfix0_get_tiles; // 0x10
	private static DelegateBridge __Hotfix0_get_endPosTiles; // 0x18
	private static DelegateBridge __Hotfix0_get_width; // 0x20
	private static DelegateBridge __Hotfix0_get_height; // 0x28
	private static DelegateBridge __Hotfix0_get_isValid; // 0x30
	private static DelegateBridge __Hotfix0_get_cameraView; // 0x38
	private static DelegateBridge __Hotfix0_get_cameraWorldPos; // 0x40
	private static DelegateBridge __Hotfix0_get_cameraFocusPos; // 0x48
	private static DelegateBridge __Hotfix0_get_battleAreaStartCol; // 0x50
	private static DelegateBridge __Hotfix0_get_battleAreaEndCol; // 0x58
	private static DelegateBridge __Hotfix0_get_anchorTransform; // 0x60
	private static DelegateBridge __Hotfix0_get_tilesContainer; // 0x68
	private static DelegateBridge __Hotfix0_get_graphicContainer; // 0x70
	private static DelegateBridge __Hotfix0_get_Item; // 0x78
	private static DelegateBridge __Hotfix1_get_Item; // 0x80
	private static DelegateBridge __Hotfix0_get_graphic; // 0x88
	private static DelegateBridge __Hotfix0_get_themeController; // 0x90
	private static DelegateBridge __Hotfix0_get_nightMapController; // 0x98
	private static DelegateBridge __Hotfix0_get_magicCircuitController; // 0xa0
	private static DelegateBridge __Hotfix0_get_random; // 0xa8
	private static DelegateBridge __Hotfix0_get_mapTheme; // 0xb0
	private static DelegateBridge __Hotfix0_get_data; // 0xb8
	private static DelegateBridge __Hotfix0_Init; // 0xc0
	private static DelegateBridge __Hotfix0_ResetSeed; // 0xc8
	private static DelegateBridge __Hotfix0_InitRouteAndPassableMap; // 0xd0
	private static DelegateBridge __Hotfix0_ReplaceAllRoutes; // 0xd8
	private static DelegateBridge __Hotfix0_UpdateAllRoutes; // 0xe0
	private static DelegateBridge __Hotfix0_UpdateRoutes; // 0xe8
	private static DelegateBridge __Hotfix0_CheckAllRoutesReachable; // 0xf0
	private static DelegateBridge __Hotfix0_CheckReachable; // 0xf8
	private static DelegateBridge __Hotfix0_GetPassableMap; // 0x100
	private static DelegateBridge __Hotfix0_CheckPassable; // 0x108
	private static DelegateBridge __Hotfix0_CheckObstacleLikeOrUnpassable; // 0x110
	private static DelegateBridge __Hotfix0_UpdatePassableMap; // 0x118
	private static DelegateBridge __Hotfix0_TryGetInitialLOrR; // 0x120
	private static DelegateBridge __Hotfix0_ImportData; // 0x128
	private static DelegateBridge __Hotfix0_FilterTiles; // 0x130
	private static DelegateBridge __Hotfix1_FilterTiles; // 0x138
	private static DelegateBridge __Hotfix0_GetTileHeight; // 0x140
	private static DelegateBridge __Hotfix0_TryGetCameraView; // 0x148
	private static DelegateBridge __Hotfix0_CheckHasTag; // 0x150
	private static DelegateBridge __Hotfix0_CheckOneOfTags; // 0x158
	private static DelegateBridge __Hotfix0_GetMapLayerCount; // 0x160
	private static DelegateBridge __Hotfix0__InitMapLayers; // 0x168
	private static DelegateBridge __Hotfix0__InitSceneEffects; // 0x170
	private static DelegateBridge __Hotfix0__ProcessSpineShaderReplace; // 0x178
	private static DelegateBridge __Hotfix0__InitControllerByTags; // 0x180
	private static DelegateBridge __Hotfix0__CreateController; // 0x188
	private static DelegateBridge __Hotfix0_GetFirstSceneEffect; // 0x190
	private static DelegateBridge __Hotfix0_GetLayerCenters; // 0x198
	private static DelegateBridge __Hotfix1_GetLayerCenters; // 0x1a0
	private static DelegateBridge __Hotfix0_GetPlayerSide; // 0x1a8
	private static DelegateBridge __Hotfix0_GetPlayerLayer; // 0x1b0
	private static DelegateBridge __Hotfix0_TryGetNextLayersTile; // 0x1b8
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x1c0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x1c8
	private static DelegateBridge __Hotfix0_Reset; // 0x1d0
	private static DelegateBridge __Hotfix0__InitTilesAndWidgets; // 0x1d8
	private static DelegateBridge __Hotfix0__InitRoutesAndPassableMaps; // 0x1e0
	private static DelegateBridge __Hotfix0__VerifyData; // 0x1e8
	private static DelegateBridge __Hotfix0_RefreshMeshThemeConfig; // 0x1f0
	private static DelegateBridge __Hotfix0_GenerateRuntimeRoute; // 0x1f8
	private static DelegateBridge __Hotfix1_GenerateRuntimeRoute; // 0x200
	private static DelegateBridge __Hotfix0_TryRemoveRuntimeRoute; // 0x208
	private static DelegateBridge __Hotfix0_GenerateRuntimeTraceRoute; // 0x210
	private static DelegateBridge __Hotfix0_GenerateRuntimeExtraRoute; // 0x218
	private static DelegateBridge __Hotfix0_RemoveRuntimeExtraRoute; // 0x220
	private static DelegateBridge __Hotfix0_TryCalculatePathFindingDistance; // 0x228
	private static DelegateBridge __Hotfix0_MapToWorldPosition; // 0x230
	private static DelegateBridge __Hotfix0_WorldToMapPosition; // 0x238
	private static DelegateBridge __Hotfix0_MapToWorldPositionV3; // 0x240
	private static DelegateBridge __Hotfix0_GetTilesCenterWorldPosition; // 0x248
	private static DelegateBridge __Hotfix0_TryGetWorldPositionByGridPosition; // 0x250
	private static DelegateBridge __Hotfix0_TryGetGridPosByWorldPosition; // 0x258
	private static DelegateBridge __Hotfix0_WorldToMapPositionV3; // 0x260
	private static DelegateBridge __Hotfix0_GetTileByScreenPos; // 0x268
	private static DelegateBridge __Hotfix0_GetMapPosByScreenPos; // 0x270
	private static DelegateBridge __Hotfix0_IsPosOutOfScreen; // 0x278
	private static DelegateBridge __Hotfix0_GetWorldPosByScreenPos; // 0x280
	private static DelegateBridge __Hotfix0_RegisterTileBind; // 0x288
	private static DelegateBridge __Hotfix0__ProcessTileBind; // 0x290
	private static DelegateBridge __Hotfix0_GetBindingTiles; // 0x298
	private static DelegateBridge __Hotfix0_CheckGridValid; // 0x2a0
	private static DelegateBridge __Hotfix0_CheckTileValid; // 0x2a8
	private static DelegateBridge __Hotfix0_CheckWithinLayerRect; // 0x2b0
	private static DelegateBridge __Hotfix0_TryGetTile; // 0x2b8
	private static DelegateBridge __Hotfix0_TryGetTiles; // 0x2c0
	private static DelegateBridge __Hotfix0_TryGetCharacterByPos; // 0x2c8
	private static DelegateBridge __Hotfix0_GetTile; // 0x2d0
	private static DelegateBridge __Hotfix1_GetTile; // 0x2d8
	private static DelegateBridge __Hotfix0_TryGetTargetBehindTile; // 0x2e0
	private static DelegateBridge __Hotfix0_TryGetAroundTileByDirection; // 0x2e8
	private static DelegateBridge __Hotfix0_GetRouteOrNull; // 0x2f0
	private static DelegateBridge __Hotfix0_GetRouteIndex; // 0x2f8
	private static DelegateBridge __Hotfix0_GetExtraRouteIndex; // 0x300
	private static DelegateBridge __Hotfix0_GetGotoDirectionalPassableMask; // 0x308
	private static DelegateBridge __Hotfix0_GetMapController; // 0x310
	private static DelegateBridge __Hotfix0_GetDirectionToGoBackFromInvalidPos; // 0x318
	private static DelegateBridge __Hotfix0_GetNearestEndPointTile; // 0x320
	private static DelegateBridge __Hotfix0_GetAdjacentTilesEnemies; // 0x328
	private static DelegateBridge __Hotfix0__UpdateAnchorToCenter; // 0x330
	private static DelegateBridge __Hotfix0__CreateTile; // 0x338
	private static DelegateBridge _c__Hotfix0_ctor; // 0x340

	public Boolean isMultiLayerMap { get; }
	public Boolean isMagicCircuitMap { get; }
	public Tile[] tiles { get; }
	public List`1 endPosTiles { get; }
	public Int32 width { get; }
	public Int32 height { get; }
	public Boolean isValid { get; }
	public CameraViewLevel cameraView { get; }
	public Nullable`1 cameraWorldPos { get; }
	public Vector3 cameraFocusPos { get; }
	public Int32 battleAreaStartCol { get; }
	public Int32 battleAreaEndCol { get; }
	public Transform anchorTransform { get; }
	protected Transform tilesContainer { get; }
	public Transform graphicContainer { get; }
	public Tile Item { get; }
	public Tile Item { get; }
	public MapGraphic graphic { get; }
	public MapThemeController themeController { get; }
	public NightMapController nightMapController { get; }
	public MagicCircuitController magicCircuitController { get; }
	public Random random { get; }
	public String mapTheme { get; }
	public MapData data { get; }

	// RVA: 0x406e33c VA: 0x759668633c
	public Boolean get_isMultiLayerMap() { }
	// RVA: 0x406e3c8 VA: 0x75966863c8
	public Boolean get_isMagicCircuitMap() { }
	// RVA: 0x406e540 VA: 0x7596686540
	public Tile[] get_tiles() { }
	// RVA: 0x406e5b4 VA: 0x75966865b4
	public List`1 get_endPosTiles() { }
	// RVA: 0x406e804 VA: 0x7596686804
	public Int32 get_width() { }
	// RVA: 0x406e878 VA: 0x7596686878
	public Int32 get_height() { }
	// RVA: 0x406e8ec VA: 0x75966868ec
	public Boolean get_isValid() { }
	// RVA: 0x406e978 VA: 0x7596686978
	public CameraViewLevel get_cameraView() { }
	// RVA: 0x406eaa0 VA: 0x7596686aa0
	public Nullable`1 get_cameraWorldPos() { }
	// RVA: 0x406ed70 VA: 0x7596686d70
	public Vector3 get_cameraFocusPos() { }
	// RVA: 0x406ee9c VA: 0x7596686e9c
	public Int32 get_battleAreaStartCol() { }
	// RVA: 0x406f01c VA: 0x759668701c
	public Int32 get_battleAreaEndCol() { }
	// RVA: 0x406f1a4 VA: 0x75966871a4
	public Transform get_anchorTransform() { }
	// RVA: 0x406f25c VA: 0x759668725c
	protected Transform get_tilesContainer() { }
	// RVA: 0x406f314 VA: 0x7596687314
	public Transform get_graphicContainer() { }
	// RVA: 0x406f3cc VA: 0x75966873cc
	public Tile get_Item(GridPosition pos) { }
	// RVA: 0x406e0f4 VA: 0x75966860f4
	public Tile get_Item(Int32 row, Int32 col) { }
	// RVA: 0x406f458 VA: 0x7596687458
	public MapGraphic get_graphic() { }
	// RVA: 0x406f4c0 VA: 0x75966874c0
	public MapThemeController get_themeController() { }
	// RVA: 0x406f528 VA: 0x7596687528
	public NightMapController get_nightMapController() { }
	// RVA: 0x406f5ac VA: 0x75966875ac
	public MagicCircuitController get_magicCircuitController() { }
	// RVA: 0x406f630 VA: 0x7596687630
	public Random get_random() { }
	// RVA: 0x406f698 VA: 0x7596687698
	public String get_mapTheme() { }
	// RVA: 0x406f758 VA: 0x7596687758
	public MapData get_data() { }
	// RVA: 0x406f7c0 VA: 0x75966877c0
	public Void Init(MapData mapData, LevelData levelData, IList`1 tilesDisallowToLocate, String themeId) { }
	// RVA: 0x4070ef8 VA: 0x7596688ef8
	public Void ResetSeed(Int32 newSeed) { }
	// RVA: 0x4070f8c VA: 0x7596688f8c
	public Void InitRouteAndPassableMap(LevelData levelData) { }
	// RVA: 0x4071014 VA: 0x7596689014
	public Void ReplaceAllRoutes(RouteData[] newRoutes) { }
	// RVA: 0x4071210 VA: 0x7596689210
	public Void UpdateAllRoutes() { }
	// RVA: 0x407156c VA: 0x759668956c
	public Void UpdateRoutes(MotionMode motionMode) { }
	// RVA: 0x40719bc VA: 0x75966899bc
	public Boolean CheckAllRoutesReachable(Boolean avoidObstacleLike) { }
	// RVA: 0x4071bc4 VA: 0x7596689bc4
	public Boolean CheckReachable(MotionMode motionMode, GridPosition posFrom, GridPosition posTo, Boolean avoidObstacleLike) { }
	// RVA: 0x4071cf0 VA: 0x7596689cf0
	public Boolean[,] GetPassableMap(MotionMode motionMode) { }
	// RVA: 0x4071d8c VA: 0x7596689d8c
	public Boolean CheckPassable(MotionMode motionMode, GridPosition pos) { }
	// RVA: 0x4071f3c VA: 0x7596689f3c
	public Boolean CheckObstacleLikeOrUnpassable(MotionMode motionMode, GridPosition pos) { }
	// RVA: 0x4072018 VA: 0x759668a018
	public Void UpdatePassableMap(Tile tile) { }
	// RVA: 0x407213c VA: 0x759668a13c
	public Boolean TryGetInitialLOrR(GridPosition pos, out Direction direction) { }
	// RVA: 0x407227c VA: 0x759668a27c
	public Void ImportData(MapData mapData, BattleFactory factory, Boolean force, Boolean includeGraphic, Boolean updateAnchor, Boolean attachGraphic) { }
	// RVA: 0x40734bc VA: 0x759668b4bc
	public Int32 FilterTiles(IDrawableRange range, Action`1 cb) { }
	// RVA: 0x4073664 VA: 0x759668b664
	public Int32 FilterTiles(IList`1 ranges, Action`1 cb) { }
	// RVA: 0x4073920 VA: 0x759668b920
	public Single GetTileHeight(HeightType heightTile) { }
	// RVA: 0x4073b1c VA: 0x759668bb1c
	public Boolean TryGetCameraView(out Vector3 pos) { }
	// RVA: 0x406e48c VA: 0x759668648c
	public Boolean CheckHasTag(String tag) { }
	// RVA: 0x4073cc0 VA: 0x759668bcc0
	public Boolean CheckOneOfTags(IList`1 tags) { }
	// RVA: 0x4073e08 VA: 0x759668be08
	public Int32 GetMapLayerCount() { }
	// RVA: 0x40705c0 VA: 0x75966885c0
	private Void _InitMapLayers() { }
	// RVA: 0x40707ec VA: 0x75966887ec
	private Void _InitSceneEffects() { }
	// RVA: 0x4073e88 VA: 0x759668be88
	private Void _ProcessSpineShaderReplace(BaseSceneEffect sceneEffect) { }
	// RVA: 0x40709ac VA: 0x75966889ac
	private Void _InitControllerByTags() { }
	// RVA: 0x4074090 VA: 0x759668c090
	private static MapController _CreateController(MapTags tag) { }
	// RVA: 0x4074170 VA: 0x759668c170
	public BaseSceneEffect GetFirstSceneEffect(Predicate`1 predicate) { }
	// RVA: 0x40742b0 VA: 0x759668c2b0
	public Vector3 GetLayerCenters(MapLayer layer) { }
	// RVA: 0x4074484 VA: 0x759668c484
	public Vector3 GetLayerCenters(PlayerSide playerSide) { }
	// RVA: 0x4074594 VA: 0x759668c594
	public PlayerSide GetPlayerSide(MapLayer mapLayer) { }
	// RVA: 0x4074510 VA: 0x759668c510
	public MapLayer GetPlayerLayer(PlayerSide playerSide) { }
	// RVA: 0x4074640 VA: 0x759668c640
	public Boolean TryGetNextLayersTile(Tile inTile, out Tile outTile) { }
	// RVA: 0x4074954 VA: 0x759668c954
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x4074aa4 VA: 0x759668caa4
	protected override Void OnDestroy() { }
	// RVA: 0x4074bf4 VA: 0x759668cbf4
	public Void Reset() { }
	// RVA: 0x406fbd8 VA: 0x7596687bd8
	private Void _InitTilesAndWidgets(MapData mapData, IList`1 tilesDisallowToLocate) { }
	// RVA: 0x407015c VA: 0x759668815c
	private Void _InitRoutesAndPassableMaps(RouteData[] routesData, RouteData[] extraRoutesData) { }
	// RVA: 0x406f9a4 VA: 0x75966879a4
	private Boolean _VerifyData(MapData mapData) { }
	// RVA: 0x4075454 VA: 0x759668d454
	public Void RefreshMeshThemeConfig() { }
	// RVA: 0x407560c VA: 0x759668d60c
	public Route GenerateRuntimeRoute(UInt32 key, RouteData data) { }
	// RVA: 0x407578c VA: 0x759668d78c
	public Route GenerateRuntimeRoute(RouteData data) { }
	// RVA: 0x4075854 VA: 0x759668d854
	public Void TryRemoveRuntimeRoute(UInt32 key) { }
	// RVA: 0x4075930 VA: 0x759668d930
	public Route GenerateRuntimeTraceRoute(GridPosition tracePosition, MotionMode motionMode) { }
	// RVA: 0x4075b5c VA: 0x759668db5c
	public Route GenerateRuntimeExtraRoute(GridPosition gridPosition, RouteData routeData) { }
	// RVA: 0x4075c58 VA: 0x759668dc58
	public Boolean RemoveRuntimeExtraRoute(GridPosition gridPosition) { }
	// RVA: 0x4075d38 VA: 0x759668dd38
	public Boolean TryCalculatePathFindingDistance(MotionMode motionMode, GridPosition targetPos, GridPosition startPos, out Int32 distance) { }
	// RVA: 0x4075e64 VA: 0x759668de64
	public Vector3 MapToWorldPosition(Vector2 mapPosition) { }
	// RVA: 0x4075f04 VA: 0x759668df04
	public Vector2 WorldToMapPosition(Vector3 worldPosition) { }
	// RVA: 0x4075fb0 VA: 0x759668dfb0
	public Vector3 MapToWorldPositionV3(Vector3 mapPosition) { }
	// RVA: 0x4076064 VA: 0x759668e064
	public Vector3 GetTilesCenterWorldPosition(IList`1 tiles) { }
	// RVA: 0x4076610 VA: 0x759668e610
	public Boolean TryGetWorldPositionByGridPosition(GridPosition gridPos, out Vector3 worldPos) { }
	// RVA: 0x4076718 VA: 0x759668e718
	public Boolean TryGetGridPosByWorldPosition(Vector3 worldPos, out GridPosition gridPos) { }
	// RVA: 0x4076888 VA: 0x759668e888
	public Vector3 WorldToMapPositionV3(Vector3 worldPosition) { }
	// RVA: 0x407693c VA: 0x759668e93c
	public Tile GetTileByScreenPos(Vector2 screenPos, out Vector2 mapPos) { }
	// RVA: 0x4076b90 VA: 0x759668eb90
	public Boolean GetMapPosByScreenPos(Vector2 screenPos, out Vector2 mapPos) { }
	// RVA: 0x4076fe4 VA: 0x759668efe4
	public Boolean IsPosOutOfScreen(Vector2 screenPos) { }
	// RVA: 0x4076c9c VA: 0x759668ec9c
	public Boolean GetWorldPosByScreenPos(Vector2 screenPos, out Vector3 worldPos) { }
	// RVA: 0x40770a8 VA: 0x759668f0a8
	public Void RegisterTileBind(String key, Tile tile) { }
	// RVA: 0x4074f30 VA: 0x759668cf30
	private Void _ProcessTileBind() { }
	// RVA: 0x40772dc VA: 0x759668f2dc
	public List`1 GetBindingTiles(Tile tile) { }
	// RVA: 0x4071e88 VA: 0x7596689e88
	public Boolean CheckGridValid(GridPosition pos) { }
	// RVA: 0x40773bc VA: 0x759668f3bc
	public Boolean CheckTileValid(Int32 row, Int32 col) { }
	// RVA: 0x4077570 VA: 0x759668f570
	public Boolean CheckWithinLayerRect(Tile tile) { }
	// RVA: 0x40751e0 VA: 0x759668d1e0
	public Boolean TryGetTile(GridPosition pos, out Tile tile) { }
	// RVA: 0x40777dc VA: 0x759668f7dc
	public Boolean TryGetTiles(IDrawableRange range, List`1 updateTiles) { }
	// RVA: 0x40779cc VA: 0x759668f9cc
	public Boolean TryGetCharacterByPos(GridPosition pos, out Character character) { }
	// RVA: 0x4077b00 VA: 0x759668fb00
	public Tile GetTile(Int32 row, Int32 col) { }
	// RVA: 0x40748d4 VA: 0x759668c8d4
	public Tile GetTile(GridPosition pos) { }
	// RVA: 0x4077b8c VA: 0x759668fb8c
	public Boolean TryGetTargetBehindTile(Entity entity, out Tile tile) { }
	// RVA: 0x4077e2c VA: 0x759668fe2c
	public Boolean TryGetAroundTileByDirection(Vector2 curMapPos, Direction direction, out Tile tile) { }
	// RVA: 0x4077f94 VA: 0x759668ff94
	public Route GetRouteOrNull(Int32 index, Boolean isExtraRoute) { }
	// RVA: 0x407808c VA: 0x759669008c
	public Int32 GetRouteIndex(Route route) { }
	// RVA: 0x4078160 VA: 0x7596690160
	public Int32 GetExtraRouteIndex(Route route) { }
	// RVA: 0x4078234 VA: 0x7596690234
	public Int32 GetGotoDirectionalPassableMask(GridPosition pos, MotionMode motion) { }
	// RVA: 0x VA: 0x0
	public ControllerT GetMapController(MapTags tag) { }
	// RVA: 0x407848c VA: 0x759669048c
	public Vector2 GetDirectionToGoBackFromInvalidPos(GridPosition pos) { }
	// RVA: 0x40786b8 VA: 0x75966906b8
	public Nullable`1 GetNearestEndPointTile(GridPosition sourcePos, MotionMode motionMode, out Route route) { }
	// RVA: 0x4078a1c VA: 0x7596690a1c
	public static Void GetAdjacentTilesEnemies(Tile tile, List`1 enemies) { }
	// RVA: 0x4072cb0 VA: 0x759668acb0
	private Void _UpdateAnchorToCenter() { }
	// RVA: 0x4072b48 VA: 0x759668ab48
	private Tile _CreateTile(TileData tileData, BattleFactory factory) { }
	// RVA: 0x4078c54 VA: 0x7596690c54
	public Void .ctor() { }
}
```