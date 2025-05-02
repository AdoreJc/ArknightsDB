# MagicCircuitRoute

**Namespace:** ` `


## Fields

- `Tile m_rootTile`

- `Direction m_rootDir`

- `MagicCircuitController m_controller`

- `Entity m_rootTarget`

- `MagicCircuitRouteEffect m_routeEffect`


## Properties

- `MagicCircuitRouteEffect routeEffect`


## Methods

- `MagicCircuitRouteEffect get_routeEffect()`

- `Boolean IsSameRoute(Tile, Direction)`

- `Boolean ContainsTarget(Character)`

- `Void DeleteSelf()`

- `Void _GenerateLeafTiles(Tile, Direction)`

- `Void RefreshEffectPositions()`

- `Vector3 _GetTileEffectPosition(Tile, Direction, Boolean)`

- `Void _AddLeafTile(Tile, Direction)`

- `Tile _GetNextTile(Tile, ref)`

- `Tile _GetNextTileNoCheck(Tile, Direction)`

- `Boolean RegisterCharacter(Character)`

- `Boolean UnregisterCharacter(Character)`

- `Void RefreshRoute()`

- `Void RecheckRoute()`

- `Void _RemoveLeafTilesFromSource(Tile)`

- `Void RemoveLeafTilesFromSource(Tile)`

- `Void _OnRemoveLeafTile(KeyValuePair`2)`

- `Void _OnCharacterEnterRoute(Character)`

- `Void _OnCharacterLeaveRoute(Character)`

- `Void _OnTileEnterRoute(Tile, Direction)`

- `Void _OnTileLeaveRoute(Tile, Direction)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MagicCircuitRoute : IHotfixable
{
	private Tile m_rootTile; // 0x10
	private Direction m_rootDir; // 0x18
	private List`1 m_leafTiles; // 0x20
	private List`1 m_locatedCharacters; // 0x28
	private MagicCircuitController m_controller; // 0x30
	private Dictionary`2 m_leafTilesDict; // 0x38
	private Entity m_rootTarget; // 0x40
	private MagicCircuitRouteEffect m_routeEffect; // 0x48
	private List`1 m_effectPositions; // 0x50
	private static DelegateBridge __Hotfix0_get_routeEffect; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_IsSameRoute; // 0x10
	private static DelegateBridge __Hotfix0_ContainsTarget; // 0x18
	private static DelegateBridge __Hotfix0_GetCharactersInSameRoute; // 0x20
	private static DelegateBridge __Hotfix0_DeleteSelf; // 0x28
	private static DelegateBridge __Hotfix0__GenerateLeafTiles; // 0x30
	private static DelegateBridge __Hotfix0_RefreshEffectPositions; // 0x38
	private static DelegateBridge __Hotfix0__GetTileEffectPosition; // 0x40
	private static DelegateBridge __Hotfix0__AddLeafTile; // 0x48
	private static DelegateBridge __Hotfix0__GetNextTile; // 0x50
	private static DelegateBridge __Hotfix0__GetNextTileNoCheck; // 0x58
	private static DelegateBridge __Hotfix0_RegisterCharacter; // 0x60
	private static DelegateBridge __Hotfix0_UnregisterCharacter; // 0x68
	private static DelegateBridge __Hotfix0_RefreshRoute; // 0x70
	private static DelegateBridge __Hotfix0_RecheckRoute; // 0x78
	private static DelegateBridge __Hotfix0__RemoveLeafTilesFromSource; // 0x80
	private static DelegateBridge __Hotfix0_RemoveLeafTilesFromSource; // 0x88
	private static DelegateBridge __Hotfix0__OnRemoveLeafTile; // 0x90
	private static DelegateBridge __Hotfix0__OnCharacterEnterRoute; // 0x98
	private static DelegateBridge __Hotfix0__OnCharacterLeaveRoute; // 0xa0
	private static DelegateBridge __Hotfix0__OnTileEnterRoute; // 0xa8
	private static DelegateBridge __Hotfix0__OnTileLeaveRoute; // 0xb0

	public MagicCircuitRouteEffect routeEffect { get; }

	// RVA: 0x400fc54 VA: 0x7596627c54
	public MagicCircuitRouteEffect get_routeEffect() { }
	// RVA: 0x400d98c VA: 0x759662598c
	public Void .ctor(MagicCircuitController controller, Entity target) { }
	// RVA: 0x400d86c VA: 0x759662586c
	public Boolean IsSameRoute(Tile tile, Direction dir) { }
	// RVA: 0x400e088 VA: 0x7596626088
	public Boolean ContainsTarget(Character character) { }
	// RVA: 0x400f148 VA: 0x7596627148
	public List`1 GetCharactersInSameRoute(Character character) { }
	// RVA: 0x400ddec VA: 0x7596625dec
	public Void DeleteSelf() { }
	// RVA: 0x4010150 VA: 0x7596628150
	private Void _GenerateLeafTiles(Tile tile, Direction dir) { }
	// RVA: 0x400e974 VA: 0x7596626974
	public Void RefreshEffectPositions() { }
	// RVA: 0x4010574 VA: 0x7596628574
	private Vector3 _GetTileEffectPosition(Tile tile, Direction dir, Boolean isTailPosition) { }
	// RVA: 0x400fd38 VA: 0x7596627d38
	private Void _AddLeafTile(Tile tile, Direction dir) { }
	// RVA: 0x4010438 VA: 0x7596628438
	private Tile _GetNextTile(Tile curTile, ref Direction curDir) { }
	// RVA: 0x4010740 VA: 0x7596628740
	private Tile _GetNextTileNoCheck(Tile curTile, Direction curDir) { }
	// RVA: 0x400c674 VA: 0x7596624674
	public Boolean RegisterCharacter(Character character) { }
	// RVA: 0x400ccc0 VA: 0x7596624cc0
	public Boolean UnregisterCharacter(Character character) { }
	// RVA: 0x400e310 VA: 0x7596626310
	public Void RefreshRoute() { }
	// RVA: 0x400e844 VA: 0x7596626844
	public Void RecheckRoute() { }
	// RVA: 0x400ffc0 VA: 0x7596627fc0
	private Void _RemoveLeafTilesFromSource(Tile sourceTile) { }
	// RVA: 0x400d90c VA: 0x759662590c
	public Void RemoveLeafTilesFromSource(Tile sourceTile) { }
	// RVA: 0x4010b20 VA: 0x7596628b20
	private Void _OnRemoveLeafTile(KeyValuePair`2 tileWithDir) { }
	// RVA: 0x40109a8 VA: 0x75966289a8
	public Void _OnCharacterEnterRoute(Character character) { }
	// RVA: 0x4010a98 VA: 0x7596628a98
	public Void _OnCharacterLeaveRoute(Character character) { }
	// RVA: 0x4010914 VA: 0x7596628914
	public Void _OnTileEnterRoute(Tile tile, Direction dir) { }
	// RVA: 0x4010cd0 VA: 0x7596628cd0
	public Void _OnTileLeaveRoute(Tile tile, Direction dir) { }
}
```