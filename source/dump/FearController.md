# FearController

**Namespace:** ` `


## Fields

- `Enemy m_owner`

- `DirectionCursor m_fearCursor`

- `Route m_fearRoute`


## Properties

- `DirectionCursor fearCursor`


## Methods

- `DirectionCursor get_fearCursor()`

- `Void Reset(Enemy)`

- `Void OnInit()`

- `Void OnTick(FP)`

- `Void AddFearTargetTiles(Buff, List`1)`

- `Void RemoveFearTargetTiles(Buff)`

- `Void UpdateFearCursor(Boolean)`

- `RouteData _InitializeFearRouteData()`

- `Boolean _TryGetFearRouteReachable(RouteData, Buff)`

- `Void _UpdateFearRoute(RouteData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FearController
{
	private const Single MAX_FEAR_MOVE_DISTANCE; // 0x0
	private Enemy m_owner; // 0x10
	private ListDict`2 m_fearBuffDict; // 0x18
	private DirectionCursor m_fearCursor; // 0x20
	private Route m_fearRoute; // 0x28

	public DirectionCursor fearCursor { get; }
	public ListDict`2 fearBuffDict { get; }

	// RVA: 0x1c17ce4 VA: 0x759422fce4
	public DirectionCursor get_fearCursor() { }
	// RVA: 0x1c17cec VA: 0x759422fcec
	public ListDict`2 get_fearBuffDict() { }
	// RVA: 0x1c17cf4 VA: 0x759422fcf4
	public Void Reset(Enemy owner) { }
	// RVA: 0x1c17cfc VA: 0x759422fcfc
	public Void OnInit() { }
	// RVA: 0x1c17dd8 VA: 0x759422fdd8
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x1c17dec VA: 0x759422fdec
	public Void AddFearTargetTiles(Buff buff, List`1 targetTiles) { }
	// RVA: 0x1c17ee4 VA: 0x759422fee4
	public Void RemoveFearTargetTiles(Buff buff) { }
	// RVA: 0x1c0b61c VA: 0x759422361c
	public Void UpdateFearCursor(Boolean force) { }
	// RVA: 0x1c17fbc VA: 0x759422ffbc
	private RouteData _InitializeFearRouteData() { }
	// RVA: 0x1c1822c VA: 0x759423022c
	private Boolean _TryGetFearRouteReachable(RouteData routeData, Buff currentBuff) { }
	// RVA: 0x1c18470 VA: 0x7594230470
	private Void _UpdateFearRoute(RouteData routeData) { }
	// RVA: 0x1c18504 VA: 0x7594230504
	public Void .ctor() { }
}
```