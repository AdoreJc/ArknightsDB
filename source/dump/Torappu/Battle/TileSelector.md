# TileSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Options _options`

- `FilterType _filterType`

- `Boolean _limitTargetNum`

- `Int32 _maxNum`

- `TileSortType _tileSortType`

- `SideType _targetSide`

- `MotionMask _targetMotion`

- `EntityCategory _targetCategory`

- `Boolean _excludeAllCharacter`

- `Int32 _fixedDistance`

- `String _blackboardKey`

- `String _chrBuffKey`

- `String _enemyBuffKey`

- `Int32 _distValue`

- `CompareType _distCompareType`

- `Boolean _excludeCamouflagCharacter`

- `Boolean _alwaysSort`

- `Boolean _ignoreBlackList`

- `Int32 m_maxTileNum`

- `SideType m_sideType`


## Properties

- `Boolean limitTargetNum`

- `Boolean isCertainTileKeyListPreferred`

- `Boolean isFixedDistInFrontLineFallbackFarthest`

- `Boolean isAct37SideEquip`

- `Boolean isEnemyWithBuff`

- `Boolean isFilterDistRandom`

- `Int32 maxTileNum`


## Methods

- `Boolean get_limitTargetNum()`

- `Boolean get_isCertainTileKeyListPreferred()`

- `Boolean get_isFixedDistInFrontLineFallbackFarthest()`

- `Boolean get_isAct37SideEquip()`

- `Boolean get_isEnemyWithBuff()`

- `Boolean get_isFilterDistRandom()`

- `Int32 get_maxTileNum()`

- `Void set_maxTileNum(Int32)`

- `Void _FilterDistRandom(List`1)`

- `Void _ExcludeOwnerRootTile(ref)`

- `Tile _GetNearestTile(Entity, List`1)`

- `Void _CollectSurroundTile(Tile, List`1, List`1, Single)`

- `Void _CollectSurroundingTilesWithin3x3(Tile, List`1)`

- `Boolean _CheckHatredEnemyOnTile(Tile, out)`

- `Boolean _CheckHatredEntityOnTile(Tile, out)`

- `Boolean _FilterCharOnTileHatredDes(Tile, out)`

- `Boolean _CheckMostCrowedThenHatredCharacterOnTile(Tile, out, out)`

- `Boolean _CheckLeastCrowedThenHatredCharacterOnTile(Tile, out, out)`

- `Boolean _CheckCharacter(Character)`

- `Boolean CheckEnemies(DoubleBufferedList`1)`

- `Boolean _CheckEntities(ReusableList`1)`

- `Void _SortTiles(List`1)`

- `Void _SortTiles_DistToOwnerAsc(List`1)`

- `Void _SortTiles_DistToOwnerAscFixed(List`1)`

- `Int32 _GetTileClockWiseWeight(Tile)`

- `Void _SortTiles_ClockwisePartRandom(List`1)`

- `Void _SortTiles_DistToOwnerDesStable(List`1)`

- `Void _SortTiles_DistDesFrontFirst(List`1)`

- `Int32 <_SortTiles_DistToOwnerAsc>b__73_0(Tile, Tile)`

- `Int32 <_SortTiles_DistToOwnerAscFixed>b__74_0(Tile, Tile)`

- `Int32 <_SortTiles_ClockwisePartRandom>b__76_0(Tile, Tile)`

- `Int32 <_SortTiles_DistToOwnerDesStable>b__77_0(Tile, Tile)`

- `Int32 <_SortTiles_DistDesFrontFirst>b__78_0(Tile, Tile)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_ValidateTile(Tile)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TileSelector : RangeSelector
{
	private const Single MAX_SURROUND_DISTANCE; // 0x0
	private static readonly String[] SPAWN_ON_TILE_BLACKLIST; // 0x0
	protected Options _options; // 0xa0
	private FilterType _filterType; // 0xd8
	private Boolean _limitTargetNum; // 0xdc
	private Int32 _maxNum; // 0xe0
	private String[] _tileOrTokenIdListPreferred; // 0xe8
	private TileSortType _tileSortType; // 0xf0
	private SideType _targetSide; // 0xf4
	private MotionMask _targetMotion; // 0xf8
	private EntityCategory _targetCategory; // 0xfc
	private Boolean _excludeAllCharacter; // 0x100
	private Int32 _fixedDistance; // 0x104
	private String _blackboardKey; // 0x108
	private String _chrBuffKey; // 0x110
	private String _enemyBuffKey; // 0x118
	private Int32 _distValue; // 0x120
	public CompareType _distCompareType; // 0x124
	private Boolean _excludeCamouflagCharacter; // 0x128
	private Boolean _alwaysSort; // 0x129
	private Boolean _ignoreBlackList; // 0x12a
	private FilterType[] _extraFilterTypeList; // 0x130
	protected Int32 m_maxTileNum; // 0x138
	private SideType m_sideType; // 0x13c
	private readonly List`1 m_reusableTileList; // 0x140
	private static DelegateBridge __Hotfix0_get_limitTargetNum; // 0x8
	private static DelegateBridge __Hotfix0_get_isCertainTileKeyListPreferred; // 0x10
	private static DelegateBridge __Hotfix0_get_isFixedDistInFrontLineFallbackFarthest; // 0x18
	private static DelegateBridge __Hotfix0_get_isAct37SideEquip; // 0x20
	private static DelegateBridge __Hotfix0_get_isEnemyWithBuff; // 0x28
	private static DelegateBridge __Hotfix0_get_isFilterDistRandom; // 0x30
	private static DelegateBridge __Hotfix0_get_filterType; // 0x38
	private static DelegateBridge __Hotfix0_get_maxTileNum; // 0x40
	private static DelegateBridge __Hotfix0_set_maxTileNum; // 0x48
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x50
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x58
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x60
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x68
	private static DelegateBridge __Hotfix0_Reset; // 0x70
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x78
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0x80
	private static DelegateBridge __Hotfix0_ValidateTile; // 0x88
	private static DelegateBridge __Hotfix0__DoFilter; // 0x90
	private static DelegateBridge __Hotfix0__FilterDistRandom; // 0x98
	private static DelegateBridge __Hotfix0__ExcludeOwnerRootTile; // 0xa0
	private static DelegateBridge __Hotfix0__GetNearestTile; // 0xa8
	private static DelegateBridge __Hotfix0__CollectSurroundTile; // 0xb0
	private static DelegateBridge __Hotfix0__CollectSurroundingTilesWithin3x3; // 0xb8
	private static DelegateBridge __Hotfix0__CheckHatredEnemyOnTile; // 0xc0
	private static DelegateBridge __Hotfix0__CheckHatredEntityOnTile; // 0xc8
	private static DelegateBridge __Hotfix0__FilterCharOnTileHatredDes; // 0xd0
	private static DelegateBridge __Hotfix0__CheckMostCrowedThenHatredCharacterOnTile; // 0xd8
	private static DelegateBridge __Hotfix0__CheckLeastCrowedThenHatredCharacterOnTile; // 0xe0
	private static DelegateBridge __Hotfix0__CheckCharacter; // 0xe8
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0xf0
	private static DelegateBridge __Hotfix0_CheckEnemies; // 0xf8
	private static DelegateBridge __Hotfix0__CheckEntities; // 0x100
	private static DelegateBridge __Hotfix0__SortTiles; // 0x108
	private static DelegateBridge __Hotfix0__SortTiles_DistToOwnerAsc; // 0x110
	private static DelegateBridge __Hotfix0__SortTiles_DistToOwnerAscFixed; // 0x118
	private static DelegateBridge __Hotfix0__GetTileClockWiseWeight; // 0x120
	private static DelegateBridge __Hotfix0__SortTiles_ClockwisePartRandom; // 0x128
	private static DelegateBridge __Hotfix0__SortTiles_DistToOwnerDesStable; // 0x130
	private static DelegateBridge __Hotfix0__SortTiles_DistDesFrontFirst; // 0x138
	private static DelegateBridge _c__Hotfix0_ctor; // 0x140

	public Boolean limitTargetNum { get; }
	protected Boolean isCertainTileKeyListPreferred { get; }
	protected Boolean isFixedDistInFrontLineFallbackFarthest { get; }
	protected Boolean isAct37SideEquip { get; }
	protected Boolean isEnemyWithBuff { get; }
	protected Boolean isFilterDistRandom { get; }
	protected virtual FilterType filterType { get; }
	protected Int32 maxTileNum { get; set; }
	public override EntityCategory targetCategory { get; }
	public override MotionMask targetMotion { get; }
	public override SideType targetSide { get; }
	public override Boolean ignoreTargetFree { get; }

	// RVA: 0x1bcda5c VA: 0x75941e5a5c
	public Boolean get_limitTargetNum() { }
	// RVA: 0x1bcdad4 VA: 0x75941e5ad4
	protected Boolean get_isCertainTileKeyListPreferred() { }
	// RVA: 0x1bcdb54 VA: 0x75941e5b54
	protected Boolean get_isFixedDistInFrontLineFallbackFarthest() { }
	// RVA: 0x1bcdbd4 VA: 0x75941e5bd4
	protected Boolean get_isAct37SideEquip() { }
	// RVA: 0x1bcdc54 VA: 0x75941e5c54
	protected Boolean get_isEnemyWithBuff() { }
	// RVA: 0x1bcdcd4 VA: 0x75941e5cd4
	protected Boolean get_isFilterDistRandom() { }
	// RVA: 0x1bc51e8 VA: 0x75941dd1e8
	protected virtual FilterType get_filterType() { }
	// RVA: 0x1bc490c VA: 0x75941dc90c
	protected Int32 get_maxTileNum() { }
	// RVA: 0x1bcd408 VA: 0x75941e5408
	protected Void set_maxTileNum(Int32 value) { }
	// RVA: 0x1bc52dc VA: 0x75941dd2dc
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1bcdd54 VA: 0x75941e5d54
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1bcddcc VA: 0x75941e5dcc
	public override SideType get_targetSide() { }
	// RVA: 0x1bc5264 VA: 0x75941dd264
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1bc39f0 VA: 0x75941db9f0
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bcde44 VA: 0x75941e5e44
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bcdf14 VA: 0x75941e5f14
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bce33c VA: 0x75941e633c
	public override Boolean ValidateTile(Tile tile) { }
	// RVA: 0x1bc535c VA: 0x75941dd35c
	protected virtual Void _DoFilter(List`1 candidates, FilterType tileFilterType) { }
	// RVA: 0x1bcefb8 VA: 0x75941e6fb8
	private Void _FilterDistRandom(List`1 candidates) { }
	// RVA: 0x1bcee3c VA: 0x75941e6e3c
	private Void _ExcludeOwnerRootTile(ref List`1 candidates) { }
	// RVA: 0x1bce67c VA: 0x75941e667c
	private Tile _GetNearestTile(Entity candidate, List`1 tiles) { }
	// RVA: 0x1bce8b4 VA: 0x75941e68b4
	private Void _CollectSurroundTile(Tile keyPoint, List`1 tiles, List`1 result, Single maxDistance) { }
	// RVA: 0x1bcf288 VA: 0x75941e7288
	private Void _CollectSurroundingTilesWithin3x3(Tile center, List`1 results) { }
	// RVA: 0x1bcf468 VA: 0x75941e7468
	private Boolean _CheckHatredEnemyOnTile(Tile tile, out FP weight) { }
	// RVA: 0x1bcf8e8 VA: 0x75941e78e8
	private Boolean _CheckHatredEntityOnTile(Tile tile, out FP weight) { }
	// RVA: 0x1bcfcac VA: 0x75941e7cac
	private Boolean _FilterCharOnTileHatredDes(Tile tile, out FP weight) { }
	// RVA: 0x1bcfe2c VA: 0x75941e7e2c
	private Boolean _CheckMostCrowedThenHatredCharacterOnTile(Tile tile, out FP weight, out FP priorWeight) { }
	// RVA: 0x1bd018c VA: 0x75941e818c
	private Boolean _CheckLeastCrowedThenHatredCharacterOnTile(Tile tile, out FP weight, out FP priorWeight) { }
	// RVA: 0x1bce570 VA: 0x75941e6570
	private Boolean _CheckCharacter(Character character) { }
	// RVA: 0x1bd04ec VA: 0x75941e84ec
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1bcc97c VA: 0x75941e497c
	protected Boolean CheckEnemies(DoubleBufferedList`1 enemies) { }
	// RVA: 0x1bceb48 VA: 0x75941e6b48
	private Boolean _CheckEntities(ReusableList`1 entities) { }
	// RVA: 0x1bce250 VA: 0x75941e6250
	private Void _SortTiles(List`1 candidates) { }
	// RVA: 0x1bd057c VA: 0x75941e857c
	private Void _SortTiles_DistToOwnerAsc(List`1 candidates) { }
	// RVA: 0x1bd0670 VA: 0x75941e8670
	private Void _SortTiles_DistToOwnerAscFixed(List`1 candidates) { }
	// RVA: 0x1bd08dc VA: 0x75941e88dc
	private Int32 _GetTileClockWiseWeight(Tile tile) { }
	// RVA: 0x1bd0768 VA: 0x75941e8768
	private Void _SortTiles_ClockwisePartRandom(List`1 candidates) { }
	// RVA: 0x1bced44 VA: 0x75941e6d44
	private Void _SortTiles_DistToOwnerDesStable(List`1 candidates) { }
	// RVA: 0x1bcec4c VA: 0x75941e6c4c
	private Void _SortTiles_DistDesFrontFirst(List`1 candidate) { }
	// RVA: 0x1bc5068 VA: 0x75941dd068
	public Void .ctor() { }
	// RVA: 0x1bd0aa8 VA: 0x75941e8aa8
	private static Void .cctor() { }
	// RVA: 0x1bd0ca4 VA: 0x75941e8ca4
	private Int32 <_SortTiles_DistToOwnerAsc>b__73_0(Tile tileX, Tile tileY) { }
	// RVA: 0x1bd0dc4 VA: 0x75941e8dc4
	private Int32 <_SortTiles_DistToOwnerAscFixed>b__74_0(Tile tileX, Tile tileY) { }
	// RVA: 0x1bd0f0c VA: 0x75941e8f0c
	private Int32 <_SortTiles_ClockwisePartRandom>b__76_0(Tile tileX, Tile tileY) { }
	// RVA: 0x1bd0f4c VA: 0x75941e8f4c
	private Int32 <_SortTiles_DistToOwnerDesStable>b__77_0(Tile tileX, Tile tileY) { }
	// RVA: 0x1bd1094 VA: 0x75941e9094
	private Int32 <_SortTiles_DistDesFrontFirst>b__78_0(Tile tileX, Tile tileY) { }
	// RVA: 0x1bd131c VA: 0x75941e931c
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bd1320 VA: 0x75941e9320
	private Boolean <>xLuaBaseProxy_ValidateTile(Tile P0) { }
	// RVA: 0x1bd1324 VA: 0x75941e9324
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```