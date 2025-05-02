# PollutedAreaManager

**Namespace:** `Torappu.Battle`


## Fields

- `PeriodicTimer m_timer`

- `PillarCtrl m_pillarCtrl`

- `Int32 m_lateTimes`


## Methods

- `Void RebuildCurAreaWithTile(Tile)`

- `Boolean CheckTileIsWaterField(Tile)`

- `Void RemoveTilesInSameArea(List`1)`

- `Boolean CheckTileIsInPolluteArea(Tile)`

- `Int32 GetTilePolluteValue(Tile)`

- `Single GetTilePolluteValueRatio(Tile)`

- `Int32 GetAreaPolluteValueByTile(Tile)`

- `Single GetAreaPolluteVRatioByTile(Tile)`

- `Void AddAreaPolluteValue(Tile, Int32)`

- `Void AddTileExtraTgtPollute(Tile, Int32)`

- `Void FlushArea(List`1, Int32)`

- `PolluteTileData GetTilePolluteData(Tile)`

- `Int32 GetAreaIndex(PolluteAreaData)`

- `Void _OnUnitFinish(Object)`

- `Void _OnUnitBorn(Object)`

- `Void _OnGameOverLog(Object)`

- `PolluteAreaData _CreatePolluteAreaData(List`1)`

- `Void _RebuildAreas()`

- `Void _RebuildAreasWithRebuildTiles()`

- `Void _UpdateAreaTgtPolluteValue()`

- `Void _UpdateTilePolluteValueToTgt()`

- `Void _HandleFlushData()`

- `Int32 _GetUpdatePollute(Int32, Int32)`

- `Void _InitTileAndPolluteValue()`

- `Void _UpdateAreasPolluteValue(Boolean)`

- `Void _FindAreasRelatedToTile(Tile)`

- `Void Awake()`

- `Void <>xLuaBaseProxy_OnPostInit()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PollutedAreaManager : EnvManager
{
	public static readonly String EVENT_SYSTEM_KEY; // 0x0
	private static readonly String[] EXCLUDED_TILE_KEY; // 0x8
	private static readonly String OBJ_KEYWORD; // 0x10
	private static readonly String LOG_CLEAN_AREA_CNT; // 0x18
	private static readonly Int32 NEARBY_TILE_CNT; // 0x20
	private static MaterialPropertyBlock m_reusedPropertyBlock; // 0x28
	private const Int32 MAX_POLLUTE_V; // 0x0
	private const Int32 MIN_POLLUTE_V; // 0x0
	private const Int32 FLUSH_VELOCITY; // 0x0
	private const Int32 EXTRA_TGT_CHANGE_VELOCITY; // 0x0
	private readonly FP TIMER_INTERVAL; // 0x28
	private const Int32 POLLUTE_LATE_TIMES; // 0x0
	private const Int32 POLLUTE_V_STEP; // 0x0
	private readonly Int32[] m_pollutVelocity; // 0x30
	private const String TAG_TRAP_DHTL; // 0x0
	private const String INIT_POLLUTE_VALUE; // 0x0
	private readonly Char[] INIT_POLLUTE_SEPARATOR; // 0x38
	private readonly ListDict`2 m_polluteTiles; // 0x40
	private readonly List`1 m_areaDatas; // 0x48
	private readonly List`1 m_rebuildTiles; // 0x50
	private readonly Queue`1 m_areaDataReusePool; // 0x58
	private PeriodicTimer m_timer; // 0x60
	private PillarCtrl m_pillarCtrl; // 0x68
	private Int32 m_lateTimes; // 0x70
	private List`1 m_visited; // 0x78
	private List`1 m_curTiles; // 0x80
	private Queue`1 m_queue; // 0x88
	private readonly Vector2Int[] m_dirs; // 0x90
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x30
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_RebuildCurAreaWithTile; // 0x48
	private static DelegateBridge __Hotfix0_CheckTileIsWaterField; // 0x50
	private static DelegateBridge __Hotfix0_RemoveTilesInSameArea; // 0x58
	private static DelegateBridge __Hotfix0_CheckTileIsInPolluteArea; // 0x60
	private static DelegateBridge __Hotfix0_GetTilePolluteValue; // 0x68
	private static DelegateBridge __Hotfix0_GetTilePolluteValueRatio; // 0x70
	private static DelegateBridge __Hotfix0_GetAreaPolluteValueByTile; // 0x78
	private static DelegateBridge __Hotfix0_GetAreaPolluteVRatioByTile; // 0x80
	private static DelegateBridge __Hotfix0_AddAreaPolluteValue; // 0x88
	private static DelegateBridge __Hotfix0_AddTileExtraTgtPollute; // 0x90
	private static DelegateBridge __Hotfix0_FlushArea; // 0x98
	private static DelegateBridge __Hotfix0_GetTilePolluteData; // 0xa0
	private static DelegateBridge __Hotfix0_GetAreaIndex; // 0xa8
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0xb0
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0xb8
	private static DelegateBridge __Hotfix0__OnGameOverLog; // 0xc0
	private static DelegateBridge __Hotfix0__CreatePolluteAreaData; // 0xc8
	private static DelegateBridge __Hotfix0__RebuildAreas; // 0xd0
	private static DelegateBridge __Hotfix0__RebuildAreasWithRebuildTiles; // 0xd8
	private static DelegateBridge __Hotfix0__UpdateAreaTgtPolluteValue; // 0xe0
	private static DelegateBridge __Hotfix0__UpdateTilePolluteValueToTgt; // 0xe8
	private static DelegateBridge __Hotfix0__HandleFlushData; // 0xf0
	private static DelegateBridge __Hotfix0__GetUpdatePollute; // 0xf8
	private static DelegateBridge __Hotfix0__InitTileAndPolluteValue; // 0x100
	private static DelegateBridge __Hotfix0__UpdateAreasPolluteValue; // 0x108
	private static DelegateBridge __Hotfix0__FindAreasRelatedToTile; // 0x110
	private static DelegateBridge __Hotfix0_Awake; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x405b0fc VA: 0x75966730fc
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x405b42c VA: 0x759667342c
	public override Void OnPostInit() { }
	// RVA: 0x405cb54 VA: 0x7596674b54
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x405d260 VA: 0x7596675260
	public Void RebuildCurAreaWithTile(Tile curTile) { }
	// RVA: 0x405df60 VA: 0x7596675f60
	public Boolean CheckTileIsWaterField(Tile tile) { }
	// RVA: 0x405e070 VA: 0x7596676070
	public Void RemoveTilesInSameArea(List`1 tiles) { }
	// RVA: 0x405e268 VA: 0x7596676268
	public Boolean CheckTileIsInPolluteArea(Tile tile) { }
	// RVA: 0x405e3ac VA: 0x75966763ac
	public Int32 GetTilePolluteValue(Tile tile) { }
	// RVA: 0x405e4b8 VA: 0x75966764b8
	public Single GetTilePolluteValueRatio(Tile tile) { }
	// RVA: 0x405e5e0 VA: 0x75966765e0
	public Int32 GetAreaPolluteValueByTile(Tile tile) { }
	// RVA: 0x405e700 VA: 0x7596676700
	public Single GetAreaPolluteVRatioByTile(Tile tile) { }
	// RVA: 0x405e83c VA: 0x759667683c
	public Void AddAreaPolluteValue(Tile tile, Int32 pv) { }
	// RVA: 0x405e99c VA: 0x759667699c
	public Void AddTileExtraTgtPollute(Tile tile, Int32 extraPv) { }
	// RVA: 0x405eab0 VA: 0x7596676ab0
	public Void FlushArea(List`1 tiles, Int32 tgtPv) { }
	// RVA: 0x405ef0c VA: 0x7596676f0c
	public PolluteTileData GetTilePolluteData(Tile tile) { }
	// RVA: 0x405f034 VA: 0x7596677034
	public Int32 GetAreaIndex(PolluteAreaData curArea) { }
	// RVA: 0x405f0fc VA: 0x75966770fc
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x405f2cc VA: 0x75966772cc
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x405f428 VA: 0x7596677428
	private Void _OnGameOverLog(Object arg) { }
	// RVA: 0x405f6a8 VA: 0x75966776a8
	private PolluteAreaData _CreatePolluteAreaData(List`1 tiles) { }
	// RVA: 0x405ba10 VA: 0x7596673a10
	private Void _RebuildAreas() { }
	// RVA: 0x405d9e4 VA: 0x75966759e4
	private Void _RebuildAreasWithRebuildTiles() { }
	// RVA: 0x405cc78 VA: 0x7596674c78
	private Void _UpdateAreaTgtPolluteValue() { }
	// RVA: 0x405d02c VA: 0x759667502c
	private Void _UpdateTilePolluteValueToTgt() { }
	// RVA: 0x405fa30 VA: 0x7596677a30
	private Void _HandleFlushData() { }
	// RVA: 0x4060000 VA: 0x7596678000
	private Int32 _GetUpdatePollute(Int32 curP, Int32 tgtP) { }
	// RVA: 0x405b51c VA: 0x759667351c
	private Void _InitTileAndPolluteValue() { }
	// RVA: 0x405c134 VA: 0x7596674134
	private Void _UpdateAreasPolluteValue(Boolean isInit) { }
	// RVA: 0x405d34c VA: 0x759667534c
	private Void _FindAreasRelatedToTile(Tile curTile) { }
	// RVA: 0x4060228 VA: 0x7596678228
	private Void Awake() { }
	// RVA: 0x40602ec VA: 0x75966782ec
	public Void .ctor() { }
	// RVA: 0x4060970 VA: 0x7596678970
	private static Void .cctor() { }
	// RVA: 0x4060ba8 VA: 0x7596678ba8
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x4060bb0 VA: 0x7596678bb0
	private Void <>xLuaBaseProxy_OnPostInit() { }
	// RVA: 0x4060bb8 VA: 0x7596678bb8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```