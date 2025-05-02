# MagicCircuitTile

**Namespace:** ` `


## Fields

- `Boolean isEnabled`

- `MagicCircuitController m_controller`

- `Tile tile`


## Properties

- `Boolean isObstacle`


## Methods

- `Boolean get_isObstacle()`

- `Void SetIsObstacle(Entity, Boolean)`

- `Void OnLocatedCharacterUpdate(Character)`

- `Void OnEntityEnter(Entity)`

- `Void OnEntityLeave(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MagicCircuitTile : ITileListener, IHotfixable
{
	public Boolean isEnabled; // 0x10
	private MagicCircuitController m_controller; // 0x18
	public Tile tile; // 0x20
	private ListSet`1 m_obstacleTarget; // 0x28
	private static DelegateBridge __Hotfix0_get_isObstacle; // 0x0
	private static DelegateBridge __Hotfix0_SetIsObstacle; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_OnLocatedCharacterUpdate; // 0x18
	private static DelegateBridge __Hotfix0_OnEntityEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnEntityLeave; // 0x28

	public Boolean isObstacle { get; }

	// RVA: 0x400f4c0 VA: 0x75966274c0
	public Boolean get_isObstacle() { }
	// RVA: 0x400f3b0 VA: 0x75966273b0
	public Void SetIsObstacle(Entity entity, Boolean isObstacle) { }
	// RVA: 0x400f554 VA: 0x7596627554
	public Void .ctor(MagicCircuitController _controller, Tile _tile) { }
	// RVA: 0x400f654 VA: 0x7596627654
	public Void OnLocatedCharacterUpdate(Character character) { }
	// RVA: 0x400f6cc VA: 0x75966276cc
	public Void OnEntityEnter(Entity entity) { }
	// RVA: 0x400f7a8 VA: 0x75966277a8
	public Void OnEntityLeave(Entity entity) { }
}
```