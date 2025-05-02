# HoleTile

**Namespace:** `Torappu.Battle`


## Methods

- `Int32 <>xLuaBaseProxy_get_moveCost()`

- `Boolean <>xLuaBaseProxy_get_isObstacleLike()`

- `Void <>xLuaBaseProxy_OnEnemyEnter(Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class HoleTile : Tile
{
	private static DelegateBridge __Hotfix0_get_moveCost; // 0x0
	private static DelegateBridge __Hotfix0_get_isObstacleLike; // 0x8
	private static DelegateBridge __Hotfix0_OnEnemyEnter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 moveCost { get; }
	public override Boolean isObstacleLike { get; }

	// RVA: 0x40910e0 VA: 0x75966a90e0
	public override Int32 get_moveCost() { }
	// RVA: 0x409114c VA: 0x75966a914c
	public override Boolean get_isObstacleLike() { }
	// RVA: 0x40911b4 VA: 0x75966a91b4
	protected override Void OnEnemyEnter(Enemy enemy) { }
	// RVA: 0x40912a0 VA: 0x75966a92a0
	public Void .ctor() { }
	// RVA: 0x409130c VA: 0x75966a930c
	private Int32 <>xLuaBaseProxy_get_moveCost() { }
	// RVA: 0x4091384 VA: 0x75966a9384
	private Boolean <>xLuaBaseProxy_get_isObstacleLike() { }
	// RVA: 0x4091408 VA: 0x75966a9408
	private Void <>xLuaBaseProxy_OnEnemyEnter(Enemy P0) { }
}
```