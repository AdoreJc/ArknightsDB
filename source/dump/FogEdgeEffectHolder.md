# FogEdgeEffectHolder

**Namespace:** ` `


## Properties

- `Effect Item`


## Methods

- `Effect get_Item(GridPosition, GridPosition, Direction)`

- `Void set_Item(GridPosition, GridPosition, Direction, Effect)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FogEdgeEffectHolder : ListDict`2, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_Item; // 0x0
	private static DelegateBridge __Hotfix0_set_Item; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Effect Item { get; set; }

	// RVA: 0x406d704 VA: 0x7596685704
	public Effect get_Item(GridPosition fromGridPosition, GridPosition toGridPosition, Direction direction) { }
	// RVA: 0x406d7f0 VA: 0x75966857f0
	public Void set_Item(GridPosition fromGridPosition, GridPosition toGridPosition, Direction direction, Effect value) { }
	// RVA: 0x406d8e8 VA: 0x75966858e8
	public Void .ctor() { }
}
```