# HiddenAreaTileListener

**Namespace:** `Torappu.Battle.Sandbox`


## Methods

- `Void OnLocatedCharacterUpdate(Character)`

- `Void OnEntityEnter(Entity)`

- `Void OnEntityLeave(Entity)`

- `Void _HideEntity(Entity)`

- `Void _ShowEntity(Entity)`

- `Void OnTileHidden(Tile)`

- `Void OnTileShown(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class HiddenAreaTileListener : IHotfixable, ITileListener
{
	private List`1 m_entitiesOnTile; // 0x10
	private ListDict`2 m_cachedOptions; // 0x18
	private static DelegateBridge __Hotfix0_OnLocatedCharacterUpdate; // 0x0
	private static DelegateBridge __Hotfix0_OnEntityEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnEntityLeave; // 0x10
	private static DelegateBridge __Hotfix0__HideEntity; // 0x18
	private static DelegateBridge __Hotfix0__ShowEntity; // 0x20
	private static DelegateBridge __Hotfix0_OnTileHidden; // 0x28
	private static DelegateBridge __Hotfix0_OnTileShown; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1df4120 VA: 0x759440c120
	public Void OnLocatedCharacterUpdate(Character character) { }
	// RVA: 0x1df4198 VA: 0x759440c198
	public Void OnEntityEnter(Entity entity) { }
	// RVA: 0x1df42f4 VA: 0x759440c2f4
	public Void OnEntityLeave(Entity entity) { }
	// RVA: 0x1df4218 VA: 0x759440c218
	public Void _HideEntity(Entity entity) { }
	// RVA: 0x1df4374 VA: 0x759440c374
	private Void _ShowEntity(Entity entity) { }
	// RVA: 0x1df4530 VA: 0x759440c530
	public Void OnTileHidden(Tile tile) { }
	// RVA: 0x1df4b54 VA: 0x759440cb54
	public Void OnTileShown(Tile tile) { }
	// RVA: 0x1df51b0 VA: 0x759440d1b0
	public Void .ctor() { }
}
```