# MagicCircuitController

**Namespace:** `Torappu.Battle`


## Fields

- `MagicCircuitTiles2D m_Tiles`

- `CoroutineId m_tileCheckCoroutine`

- `CoroutineId m_characterCheckCoroutine`

- `CoroutineId m_enemyCheckCoroutine`


## Properties

- `MagicCircuitTiles2D magicTiles`


## Methods

- `Void OnTileEnterRoute(Tile, Direction)`

- `Void OnTileLeaveRoute(Tile, Direction)`

- `Void OnCharacterEnterRoute(Character)`

- `Void OnCharacterLeaveRoute(Character)`

- `Void OnEnemyEnterRoute(Enemy)`

- `Void OnEnemyLeaveRoute(Enemy)`

- `Void OnReallyTileEnterRoute(MagicCircuitTile)`

- `Void OnReallyTileLeaveRoute(MagicCircuitTile)`

- `Void OnReallyCharacterEnterRoute(ObjectPtr`1)`

- `Void OnReallyCharacterLeaveRoute(ObjectPtr`1)`

- `Void OnReallyEnemyEnterRoute(ObjectPtr`1)`

- `Void OnReallyEnemyLeaveRoute(ObjectPtr`1)`

- `MagicCircuitTiles2D get_magicTiles()`

- `Void InitParams()`

- `Void _StartTileCheckInRoute()`

- `Void _StartCharacterCheckInRoute()`

- `Void _StartEnemyCheckInRoute()`

- `IEnumerator _CkeckTileInRoute()`

- `IEnumerator _CkeckCharacterInRoute()`

- `IEnumerator _CkeckEnemyInRoute()`

- `Boolean IsMagicCiruitAffect(Character)`

- `Boolean IsMagicCiruitSpAffect(Character)`

- `Boolean _CanCharacterChangeRouteDir(Character)`

- `Boolean GetMagicCiruitNextDir(Character, ref)`

- `Void RegisterCharacterOnRoute(Character)`

- `Void UnregisterCharacterOnRoute(Character)`

- `Void _OnUnitFinish(Object)`

- `Void _OnUnitBorn(Object)`

- `Void _OnCharacterChanged(Object)`

- `Void RegisterMagicCircuitRoute(Entity)`

- `Void UnregisterMagicCircuitRoute(Tile, Direction)`

- `Void RegisterSpAffectCharacters(Character, Boolean)`

- `Void UnregisterSpAffectCharacters(Character)`

- `Void RefreshAllRoutes()`

- `Void RecheckAllRoutes()`

- `Void RefreshAllRoutesEffect()`

- `Boolean CheckCharacterInMagicCircuit(Character)`

- `Boolean CheckEnemyInMagicCircuit(Enemy)`

- `Void SetMagicTileObstacle(Entity, Tile, Boolean)`

- `Boolean IsMagicCircuitTile(Tile)`

- `Void <>xLuaBaseProxy_Init(Map)`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MagicCircuitController : MapController
{
	private const Single EFFECT_EDGE_ON_TILE; // 0x0
	private const Single EFFECT_TAILEDGE_ON_TILE_BLOCK; // 0x0
	private const Single EFFECT_TAILEDGE_ON_TILE_NOBLOCK; // 0x0
	private const Single EFFECT_HEIGHT_ON_HIGHLAND; // 0x0
	private const String effectDefaultKey; // 0x0
	private Dictionary`2 m_magicCircuitCharacterStatus; // 0x18
	private Dictionary`2 m_magicCircuitEnemyStatus; // 0x20
	private List`1 m_routes; // 0x28
	private MagicCircuitTiles2D m_Tiles; // 0x30
	private CoroutineId m_tileCheckCoroutine; // 0x38
	private CoroutineId m_characterCheckCoroutine; // 0x48
	private CoroutineId m_enemyCheckCoroutine; // 0x58
	private Dictionary`2 m_magicCircuitSpAffectCharacters; // 0x68
	private static DelegateBridge __Hotfix0_OnTileEnterRoute; // 0x0
	private static DelegateBridge __Hotfix0_OnTileLeaveRoute; // 0x8
	private static DelegateBridge __Hotfix0_OnCharacterEnterRoute; // 0x10
	private static DelegateBridge __Hotfix0_OnCharacterLeaveRoute; // 0x18
	private static DelegateBridge __Hotfix0_OnEnemyEnterRoute; // 0x20
	private static DelegateBridge __Hotfix0_OnEnemyLeaveRoute; // 0x28
	private static DelegateBridge __Hotfix0_OnReallyTileEnterRoute; // 0x30
	private static DelegateBridge __Hotfix0_OnReallyTileLeaveRoute; // 0x38
	private static DelegateBridge __Hotfix0_OnReallyCharacterEnterRoute; // 0x40
	private static DelegateBridge __Hotfix0_OnReallyCharacterLeaveRoute; // 0x48
	private static DelegateBridge __Hotfix0_OnReallyEnemyEnterRoute; // 0x50
	private static DelegateBridge __Hotfix0_OnReallyEnemyLeaveRoute; // 0x58
	private static DelegateBridge __Hotfix0_get_magicTiles; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68
	private static DelegateBridge __Hotfix0_Init; // 0x70
	private static DelegateBridge __Hotfix0_InitParams; // 0x78
	private static DelegateBridge __Hotfix0_Reset; // 0x80
	private static DelegateBridge __Hotfix0__StartTileCheckInRoute; // 0x88
	private static DelegateBridge __Hotfix0__StartCharacterCheckInRoute; // 0x90
	private static DelegateBridge __Hotfix0__StartEnemyCheckInRoute; // 0x98
	private static DelegateBridge __Hotfix0__CkeckTileInRoute; // 0xa0
	private static DelegateBridge __Hotfix0__CkeckCharacterInRoute; // 0xa8
	private static DelegateBridge __Hotfix0__CkeckEnemyInRoute; // 0xb0
	private static DelegateBridge __Hotfix0_IsMagicCiruitAffect; // 0xb8
	private static DelegateBridge __Hotfix0_IsMagicCiruitSpAffect; // 0xc0
	private static DelegateBridge __Hotfix0__CanCharacterChangeRouteDir; // 0xc8
	private static DelegateBridge __Hotfix0_GetMagicCiruitNextDir; // 0xd0
	private static DelegateBridge __Hotfix0_RegisterCharacterOnRoute; // 0xd8
	private static DelegateBridge __Hotfix0_UnregisterCharacterOnRoute; // 0xe0
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0xe8
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0xf0
	private static DelegateBridge __Hotfix0__OnCharacterChanged; // 0xf8
	private static DelegateBridge __Hotfix0_RegisterMagicCircuitRoute; // 0x100
	private static DelegateBridge __Hotfix0_UnregisterMagicCircuitRoute; // 0x108
	private static DelegateBridge __Hotfix0_RegisterSpAffectCharacters; // 0x110
	private static DelegateBridge __Hotfix0_UnregisterSpAffectCharacters; // 0x118
	private static DelegateBridge __Hotfix0_RefreshAllRoutes; // 0x120
	private static DelegateBridge __Hotfix0_RecheckAllRoutes; // 0x128
	private static DelegateBridge __Hotfix0_RefreshAllRoutesEffect; // 0x130
	private static DelegateBridge __Hotfix0_GetCharactersInSameRoute; // 0x138
	private static DelegateBridge __Hotfix0_CheckCharacterInMagicCircuit; // 0x140
	private static DelegateBridge __Hotfix0_CheckEnemyInMagicCircuit; // 0x148
	private static DelegateBridge __Hotfix0_SetMagicTileObstacle; // 0x150
	private static DelegateBridge __Hotfix0_IsMagicCircuitTile; // 0x158

	public MagicCircuitTiles2D magicTiles { get; }

	// RVA: 0x4009b54 VA: 0x7596621b54
	private Void OnTileEnterRoute(Tile tile, Direction dir) { }
	// RVA: 0x400a2f4 VA: 0x75966222f4
	private Void OnTileLeaveRoute(Tile tile, Direction dir) { }
	// RVA: 0x400a894 VA: 0x7596622894
	public Void OnCharacterEnterRoute(Character character) { }
	// RVA: 0x400ab4c VA: 0x7596622b4c
	public Void OnCharacterLeaveRoute(Character character) { }
	// RVA: 0x400a03c VA: 0x759662203c
	private Void OnEnemyEnterRoute(Enemy enemy) { }
	// RVA: 0x400a714 VA: 0x7596622714
	private Void OnEnemyLeaveRoute(Enemy enemy) { }
	// RVA: 0x4009fa4 VA: 0x7596621fa4
	private Void OnReallyTileEnterRoute(MagicCircuitTile tile) { }
	// RVA: 0x400a680 VA: 0x7596622680
	private Void OnReallyTileLeaveRoute(MagicCircuitTile tile) { }
	// RVA: 0x400ae04 VA: 0x7596622e04
	private Void OnReallyCharacterEnterRoute(ObjectPtr`1 character) { }
	// RVA: 0x400aef4 VA: 0x7596622ef4
	private Void OnReallyCharacterLeaveRoute(ObjectPtr`1 character) { }
	// RVA: 0x400afe4 VA: 0x7596622fe4
	private Void OnReallyEnemyEnterRoute(ObjectPtr`1 enemy) { }
	// RVA: 0x400b0d4 VA: 0x75966230d4
	private Void OnReallyEnemyLeaveRoute(ObjectPtr`1 enemy) { }
	// RVA: 0x400b1c4 VA: 0x75966231c4
	public MagicCircuitTiles2D get_magicTiles() { }
	// RVA: 0x400b22c VA: 0x759662322c
	public Void .ctor() { }
	// RVA: 0x400b890 VA: 0x7596623890
	public override Void Init(Map map) { }
	// RVA: 0x400ba0c VA: 0x7596623a0c
	public Void InitParams() { }
	// RVA: 0x400bb14 VA: 0x7596623b14
	public override Void Reset() { }
	// RVA: 0x400a1bc VA: 0x75966221bc
	private Void _StartTileCheckInRoute() { }
	// RVA: 0x400aa14 VA: 0x7596622a14
	private Void _StartCharacterCheckInRoute() { }
	// RVA: 0x400accc VA: 0x7596622ccc
	private Void _StartEnemyCheckInRoute() { }
	// RVA: 0x400be2c VA: 0x7596623e2c
	private IEnumerator _CkeckTileInRoute() { }
	// RVA: 0x400bed8 VA: 0x7596623ed8
	private IEnumerator _CkeckCharacterInRoute() { }
	// RVA: 0x400bf84 VA: 0x7596623f84
	private IEnumerator _CkeckEnemyInRoute() { }
	// RVA: 0x400c0a8 VA: 0x75966240a8
	public Boolean IsMagicCiruitAffect(Character character) { }
	// RVA: 0x400c15c VA: 0x759662415c
	public Boolean IsMagicCiruitSpAffect(Character character) { }
	// RVA: 0x400c1fc VA: 0x75966241fc
	private Boolean _CanCharacterChangeRouteDir(Character character) { }
	// RVA: 0x400c29c VA: 0x759662429c
	public Boolean GetMagicCiruitNextDir(Character character, ref Direction curDir) { }
	// RVA: 0x400c4c8 VA: 0x75966244c8
	public Void RegisterCharacterOnRoute(Character character) { }
	// RVA: 0x400cb14 VA: 0x7596624b14
	public Void UnregisterCharacterOnRoute(Character character) { }
	// RVA: 0x400ce6c VA: 0x7596624e6c
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x400d0a8 VA: 0x75966250a8
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x400d1cc VA: 0x75966251cc
	private Void _OnCharacterChanged(Object arg) { }
	// RVA: 0x400d514 VA: 0x7596625514
	public Void RegisterMagicCircuitRoute(Entity target) { }
	// RVA: 0x400dc9c VA: 0x7596625c9c
	public Void UnregisterMagicCircuitRoute(Tile rootTile, Direction direction) { }
	// RVA: 0x400de80 VA: 0x7596625e80
	public Void RegisterSpAffectCharacters(Character character, Boolean isTwoEntriesOnly) { }
	// RVA: 0x400e114 VA: 0x7596626114
	public Void UnregisterSpAffectCharacters(Character character) { }
	// RVA: 0x400c81c VA: 0x759662481c
	public Void RefreshAllRoutes() { }
	// RVA: 0x400e6c8 VA: 0x75966266c8
	public Void RecheckAllRoutes() { }
	// RVA: 0x400c998 VA: 0x7596624998
	public Void RefreshAllRoutesEffect() { }
	// RVA: 0x400ef08 VA: 0x7596626f08
	public List`1 GetCharactersInSameRoute(Character character) { }
	// RVA: 0x400d354 VA: 0x7596625354
	public Boolean CheckCharacterInMagicCircuit(Character character) { }
	// RVA: 0x400f22c VA: 0x759662722c
	public Boolean CheckEnemyInMagicCircuit(Enemy enemy) { }
	// RVA: 0x400f2c8 VA: 0x75966272c8
	public Void SetMagicTileObstacle(Entity source, Tile tile, Boolean isObstacle) { }
	// RVA: 0x400cfac VA: 0x7596624fac
	public Boolean IsMagicCircuitTile(Tile tile) { }
	// RVA: 0x400f4b8 VA: 0x75966274b8
	private Void <>xLuaBaseProxy_Init(Map P0) { }
	// RVA: 0x400f4bc VA: 0x75966274bc
	private Void <>xLuaBaseProxy_Reset() { }
}
```