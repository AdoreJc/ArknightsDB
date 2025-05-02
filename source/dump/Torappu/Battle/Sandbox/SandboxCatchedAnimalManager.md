# SandboxCatchedAnimalManager

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `Single _animalAppearRandomOffset`

- `Single _animalCapPerTile`

- `String _trapAnimalCageKey`

- `BuffData _shinyAnimalBuff`

- `BuffData _newShinyAnimalBuff`

- `Vector2 _animalMoveInterval`

- `SandboxGameMode m_gameMode`

- `PhaseData m_catchedAnimalPhase`

- `Boolean m_cachedLastSpawnCage`

- `Boolean m_cachedLastEnemy`

- `Boolean m_cachedLastEnemyIsShiny`

- `SandboxCatchedAnimalTileBuildableChecker m_tileBuildableChecker`

- `Int32 m_mapWidth`

- `Int32 m_mapHeight`

- `String m_defaultFenceId`

- `String m_rareFenceId`

- `Int32 m_unitFenceLimit`

- `Int32 m_unitRareFenceLimit`


## Properties

- `SandboxInput input`

- `SandboxOutput output`

- `SandboxV2Data configData`

- `String trapAnimalCageKey`

- `Boolean inBuildMode`

- `PlayerSide playerSide`


## Methods

- `SandboxInput get_input()`

- `SandboxOutput get_output()`

- `SandboxV2Data get_configData()`

- `String get_trapAnimalCageKey()`

- `Boolean get_inBuildMode()`

- `PlayerSide get_playerSide()`

- `Void _OnGameStart(Object)`

- `Void _OnUnitBorn(Object)`

- `Void _OnEnemyBorn(Enemy)`

- `Void _OnCharacterBorn(Character)`

- `Void _OnUnitFinish(Object)`

- `Void _OnFenceFinishInBuild(Character)`

- `Void _OnFenceFinishInNormal(Character)`

- `Void _OnGameReady(Object)`

- `Void _OnBeforeSaveMapRequest(Object)`

- `Void GetCatchedAnimalInfo(Dictionary`2)`

- `Void _DoSaveCache(Object)`

- `Void _DoSaveCache()`

- `Void DoResetFromCache()`

- `String _GetEnemyIdByItem(String, out)`

- `String _GetItemIdByEnemy(String, Boolean)`

- `String _GetTargetFenceIdByEnemyId(String)`

- `String _GetItemIdByEnemy(Enemy)`

- `Int32 _CatchedAnimalRoomId(Int32, Int32)`

- `Int32 _GetCatchedAnimalRoomId(Tile)`

- `Int32 GetCatchedAnimalRoomId(Tile)`

- `Boolean CheckAnimalRelatedTileReachable(Tile, Tile)`

- `Void _ParseCatchedAnimalCards()`

- `Boolean _PreloadAnimalCards(String, Dictionary`2, List`1)`

- `Void _ParseCatchedAnimals(Dictionary`2)`

- `Void _ParseCatchedAnimalsInBuildMode(Dictionary`2)`

- `Void _RefreshCatchAnimalMapStatus()`

- `Boolean IsCageValidTile(Tile)`

- `Boolean _IsFenceTile(Int32, Int32)`

- `Boolean _IsRareFenceTile(Int32, Int32)`

- `Boolean _IsFenceTileId(String)`

- `Void _RefreshCatchAnimalMap()`

- `Void _SolveCatchedAnimalFlagViaDFS(Int32[, ], Int32, Int32, Int32, Int32, Int32, Int32)`

- `Void _RefreshAnimalRoomCapacity()`

- `Void _RefreshAnimalCountInRoom()`

- `Int32 _RegisterAnimalInRoom(Int32, Int32)`

- `Boolean _IsRoomOverflow(Int32)`

- `Int32 _GetRoomRestCap(Int32)`

- `Void _RecycleCatchedAnimal(Enemy)`

- `Void _SaveAnimalCardCount()`

- `Void _RecycleCatchedAnimalCard(String)`

- `Void _ForceChargeCatchedAnimalCard(UInt32, Int32)`

- `Void _DoEnemyMove(Enemy)`

- `Void _OnPlaceAniamlFull()`

- `Void _RefreshTrapFenceAnimatorSurround(Int32, Int32)`

- `Void _RefreshTrapFenceAnimator(Int32, Int32)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxCatchedAnimalManager : EnvManager
{
	private Single _animalAppearRandomOffset; // 0x28
	private Single _animalCapPerTile; // 0x2c
	private String _trapAnimalCageKey; // 0x30
	private BuffData _shinyAnimalBuff; // 0x38
	private List`1 _newShinyAnimalId; // 0x40
	private BuffData _newShinyAnimalBuff; // 0x48
	private Vector2 _animalMoveInterval; // 0x50
	private SandboxGameMode m_gameMode; // 0x58
	private const Int32 CATCHED_ANIMAL_ROOM_ID_PARAM; // 0x0
	private const Single CATCHED_ANIMAL_APPEAR_MOVE_DELAY; // 0x0
	private const Int32 FENCE_AREA_FLAG; // 0x0
	private List`1 m_catchedAnimalActions; // 0x60
	private PhaseData m_catchedAnimalPhase; // 0x68
	private Int32[,] m_catchedAnimalFlagMap; // 0x70
	private ListDict`2 m_catchedAnimals; // 0x78
	private Dictionary`2 m_catchedAnimalFenceId; // 0x80
	private Dictionary`2 m_animalRoomCapacity; // 0x88
	private Dictionary`2 m_animalCountInRoom; // 0x90
	private ListDict`2 m_animalCardInfos; // 0x98
	private Boolean m_cachedLastSpawnCage; // 0xa0
	private Boolean m_cachedLastEnemy; // 0xa1
	private Boolean m_cachedLastEnemyIsShiny; // 0xa2
	private ListDict`2 m_animalCardUids; // 0xa8
	private ListDict`2 m_catchedAnimalCardCount; // 0xb0
	private Dictionary`2 m_catchedAnimalCache; // 0xb8
	private ListDict`2 m_roomAnimalCountTmp; // 0xc0
	private ListDict`2 m_roomTilesCache; // 0xc8
	private ListDict`2 m_roomDiff; // 0xd0
	private SandboxCatchedAnimalTileBuildableChecker m_tileBuildableChecker; // 0xd8
	private Int32 m_mapWidth; // 0xe0
	private Int32 m_mapHeight; // 0xe4
	private String m_defaultFenceId; // 0xe8
	private String m_rareFenceId; // 0xf0
	private Int32 m_unitFenceLimit; // 0xf8
	private Int32 m_unitRareFenceLimit; // 0xfc
	private static DelegateBridge __Hotfix0_get_input; // 0x0
	private static DelegateBridge __Hotfix0_get_output; // 0x8
	private static DelegateBridge __Hotfix0_get_configData; // 0x10
	private static DelegateBridge __Hotfix0_get_trapAnimalCageKey; // 0x18
	private static DelegateBridge __Hotfix0_get_inBuildMode; // 0x20
	private static DelegateBridge __Hotfix0_get_playerSide; // 0x28
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0__OnGameStart; // 0x40
	private static DelegateBridge __Hotfix0_OnTick; // 0x48
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x50
	private static DelegateBridge __Hotfix0__OnEnemyBorn; // 0x58
	private static DelegateBridge __Hotfix0__OnCharacterBorn; // 0x60
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x68
	private static DelegateBridge __Hotfix0__OnFenceFinishInBuild; // 0x70
	private static DelegateBridge __Hotfix0__OnFenceFinishInNormal; // 0x78
	private static DelegateBridge __Hotfix0__OnGameReady; // 0x80
	private static DelegateBridge __Hotfix0__OnBeforeSaveMapRequest; // 0x88
	private static DelegateBridge __Hotfix0_GetCatchedAnimalInfo; // 0x90
	private static DelegateBridge __Hotfix0__DoSaveCache; // 0x98
	private static DelegateBridge __Hotfix1__DoSaveCache; // 0xa0
	private static DelegateBridge __Hotfix0_DoResetFromCache; // 0xa8
	private static DelegateBridge __Hotfix0__GetEnemyIdByItem; // 0xb0
	private static DelegateBridge __Hotfix0__GetItemIdByEnemy; // 0xb8
	private static DelegateBridge __Hotfix0__GetTargetFenceIdByEnemyId; // 0xc0
	private static DelegateBridge __Hotfix1__GetItemIdByEnemy; // 0xc8
	private static DelegateBridge __Hotfix0__CatchedAnimalRoomId; // 0xd0
	private static DelegateBridge __Hotfix0__GetCatchedAnimalRoomId; // 0xd8
	private static DelegateBridge __Hotfix0_GetCatchedAnimalRoomId; // 0xe0
	private static DelegateBridge __Hotfix0_CheckAnimalRelatedTileReachable; // 0xe8
	private static DelegateBridge __Hotfix0_CheckAnimalRelatedTileReachableForRareFence; // 0xf0
	private static DelegateBridge __Hotfix0__ParseCatchedAnimalCards; // 0xf8
	private static DelegateBridge __Hotfix0__PreloadAnimalCards; // 0x100
	private static DelegateBridge __Hotfix0__ParseCatchedAnimals; // 0x108
	private static DelegateBridge __Hotfix0__ParseCatchedAnimalsInBuildMode; // 0x110
	private static DelegateBridge __Hotfix0__RefreshCatchAnimalMapStatus; // 0x118
	private static DelegateBridge __Hotfix0_IsCageValidTile; // 0x120
	private static DelegateBridge __Hotfix0__IsFenceTile; // 0x128
	private static DelegateBridge __Hotfix0__IsRareFenceTile; // 0x130
	private static DelegateBridge __Hotfix0__IsFenceTileId; // 0x138
	private static DelegateBridge __Hotfix0__RefreshCatchAnimalMap; // 0x140
	private static DelegateBridge __Hotfix0__SolveCatchedAnimalFlagViaDFS; // 0x148
	private static DelegateBridge __Hotfix0__RefreshAnimalRoomCapacity; // 0x150
	private static DelegateBridge __Hotfix0__RefreshAnimalCountInRoom; // 0x158
	private static DelegateBridge __Hotfix0__RegisterAnimalInRoom; // 0x160
	private static DelegateBridge __Hotfix0__IsRoomOverflow; // 0x168
	private static DelegateBridge __Hotfix0__GetRoomRestCap; // 0x170
	private static DelegateBridge __Hotfix0__RecycleCatchedAnimal; // 0x178
	private static DelegateBridge __Hotfix0__SaveAnimalCardCount; // 0x180
	private static DelegateBridge __Hotfix0__RecycleCatchedAnimalCard; // 0x188
	private static DelegateBridge __Hotfix0__ForceChargeCatchedAnimalCard; // 0x190
	private static DelegateBridge __Hotfix0__DoEnemyMove; // 0x198
	private static DelegateBridge __Hotfix0__OnPlaceAniamlFull; // 0x1a0
	private static DelegateBridge __Hotfix0__RefreshTrapFenceAnimatorSurround; // 0x1a8
	private static DelegateBridge __Hotfix0__RefreshTrapFenceAnimator; // 0x1b0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1b8

	public SandboxInput input { get; }
	public SandboxOutput output { get; }
	public SandboxV2Data configData { get; }
	public String trapAnimalCageKey { get; }
	public Boolean inBuildMode { get; }
	private PlayerSide playerSide { get; }
	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x1dd9e34 VA: 0x75943f1e34
	public SandboxInput get_input() { }
	// RVA: 0x1dd9ea8 VA: 0x75943f1ea8
	public SandboxOutput get_output() { }
	// RVA: 0x1dd9f1c VA: 0x75943f1f1c
	public SandboxV2Data get_configData() { }
	// RVA: 0x1dd9f90 VA: 0x75943f1f90
	public String get_trapAnimalCageKey() { }
	// RVA: 0x1dd9ff8 VA: 0x75943f1ff8
	public Boolean get_inBuildMode() { }
	// RVA: 0x1dda06c VA: 0x75943f206c
	private PlayerSide get_playerSide() { }
	// RVA: 0x1dda0d0 VA: 0x75943f20d0
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x1dda400 VA: 0x75943f2400
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x1ddae8c VA: 0x75943f2e8c
	private Void _OnGameStart(Object arg) { }
	// RVA: 0x1ddb530 VA: 0x75943f3530
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ddb988 VA: 0x75943f3988
	public Void _OnUnitBorn(Object arg) { }
	// RVA: 0x1ddbb24 VA: 0x75943f3b24
	private Void _OnEnemyBorn(Enemy enemy) { }
	// RVA: 0x1ddc344 VA: 0x75943f4344
	private Void _OnCharacterBorn(Character character) { }
	// RVA: 0x1ddd554 VA: 0x75943f5554
	public Void _OnUnitFinish(Object arg) { }
	// RVA: 0x1ddd780 VA: 0x75943f5780
	public Void _OnFenceFinishInBuild(Character character) { }
	// RVA: 0x1dddd60 VA: 0x75943f5d60
	public Void _OnFenceFinishInNormal(Character character) { }
	// RVA: 0x1ddec20 VA: 0x75943f6c20
	private Void _OnGameReady(Object arg) { }
	// RVA: 0x1ddedf4 VA: 0x75943f6df4
	private Void _OnBeforeSaveMapRequest(Object arg) { }
	// RVA: 0x1ddee8c VA: 0x75943f6e8c
	public Void GetCatchedAnimalInfo(Dictionary`2 data) { }
	// RVA: 0x1ddf18c VA: 0x75943f718c
	private Void _DoSaveCache(Object arg) { }
	// RVA: 0x1ddf208 VA: 0x75943f7208
	private Void _DoSaveCache() { }
	// RVA: 0x1ddf410 VA: 0x75943f7410
	public Void DoResetFromCache() { }
	// RVA: 0x1ddf910 VA: 0x75943f7910
	private String _GetEnemyIdByItem(String itemId, out Boolean isShiny) { }
	// RVA: 0x1ddce70 VA: 0x75943f4e70
	private String _GetItemIdByEnemy(String enemyId, Boolean isShiny) { }
	// RVA: 0x1ddc6b8 VA: 0x75943f46b8
	private String _GetTargetFenceIdByEnemyId(String enemyId) { }
	// RVA: 0x1ddc79c VA: 0x75943f479c
	private String _GetItemIdByEnemy(Enemy enemy) { }
	// RVA: 0x1ddeb98 VA: 0x75943f6b98
	private Int32 _CatchedAnimalRoomId(Int32 row, Int32 col) { }
	// RVA: 0x1ddcbe8 VA: 0x75943f4be8
	private Int32 _GetCatchedAnimalRoomId(Tile tile) { }
	// RVA: 0x1ddfb3c VA: 0x75943f7b3c
	public Int32 GetCatchedAnimalRoomId(Tile tile) { }
	// RVA: 0x1ddfbbc VA: 0x75943f7bbc
	public Boolean CheckAnimalRelatedTileReachable(Tile tileA, Tile tileB) { }
	// RVA: 0x1ddfd98 VA: 0x75943f7d98
	public static Boolean CheckAnimalRelatedTileReachableForRareFence(Tile tileA, Tile tileB) { }
	// RVA: 0x1dda86c VA: 0x75943f286c
	private Void _ParseCatchedAnimalCards() { }
	// RVA: 0x1ddfe94 VA: 0x75943f7e94
	private Boolean _PreloadAnimalCards(String itemId, Dictionary`2 animalCardCount, List`1 tokenPreloads) { }
	// RVA: 0x1ddb1f4 VA: 0x75943f31f4
	private Void _ParseCatchedAnimals(Dictionary`2 animals) { }
	// RVA: 0x1de01e0 VA: 0x75943f81e0
	private Void _ParseCatchedAnimalsInBuildMode(Dictionary`2 animals) { }
	// RVA: 0x1ddd3b0 VA: 0x75943f53b0
	private Void _RefreshCatchAnimalMapStatus() { }
	// RVA: 0x1de110c VA: 0x75943f910c
	public Boolean IsCageValidTile(Tile tile) { }
	// RVA: 0x1ddeaa4 VA: 0x75943f6aa4
	private Boolean _IsFenceTile(Int32 row, Int32 col) { }
	// RVA: 0x1de11b4 VA: 0x75943f91b4
	private Boolean _IsRareFenceTile(Int32 row, Int32 col) { }
	// RVA: 0x1ddb148 VA: 0x75943f3148
	private Boolean _IsFenceTileId(String id) { }
	// RVA: 0x1ddd200 VA: 0x75943f5200
	private Void _RefreshCatchAnimalMap() { }
	// RVA: 0x1de1334 VA: 0x75943f9334
	private Void _SolveCatchedAnimalFlagViaDFS(Int32[,] map, Int32 row, Int32 col, Int32 i, Int32 j, Int32 new_flag, Int32 old_flag) { }
	// RVA: 0x1de0c74 VA: 0x75943f8c74
	private Void _RefreshAnimalRoomCapacity() { }
	// RVA: 0x1de0eb4 VA: 0x75943f8eb4
	private Void _RefreshAnimalCountInRoom() { }
	// RVA: 0x1ddccc0 VA: 0x75943f4cc0
	private Int32 _RegisterAnimalInRoom(Int32 roomId, Int32 count) { }
	// RVA: 0x1ddd070 VA: 0x75943f5070
	private Boolean _IsRoomOverflow(Int32 roomId) { }
	// RVA: 0x1de14d4 VA: 0x75943f94d4
	private Int32 _GetRoomRestCap(Int32 roomId) { }
	// RVA: 0x1ddc9ec VA: 0x75943f49ec
	private Void _RecycleCatchedAnimal(Enemy enemy) { }
	// RVA: 0x1ddb2a0 VA: 0x75943f32a0
	private Void _SaveAnimalCardCount() { }
	// RVA: 0x1ddc88c VA: 0x75943f488c
	private Void _RecycleCatchedAnimalCard(String itemId) { }
	// RVA: 0x1ddf838 VA: 0x75943f7838
	private Void _ForceChargeCatchedAnimalCard(UInt32 uid, Int32 count) { }
	// RVA: 0x1ddb714 VA: 0x75943f3714
	private Void _DoEnemyMove(Enemy enemy) { }
	// RVA: 0x1ddd0fc VA: 0x75943f50fc
	private Void _OnPlaceAniamlFull() { }
	// RVA: 0x1ddd438 VA: 0x75943f5438
	private Void _RefreshTrapFenceAnimatorSurround(Int32 row, Int32 col) { }
	// RVA: 0x1de15d4 VA: 0x75943f95d4
	private Void _RefreshTrapFenceAnimator(Int32 row, Int32 col) { }
	// RVA: 0x1de198c VA: 0x75943f998c
	public Void .ctor() { }
	// RVA: 0x1de1e20 VA: 0x75943f9e20
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x1de1e28 VA: 0x75943f9e28
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x1de1e30 VA: 0x75943f9e30
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```