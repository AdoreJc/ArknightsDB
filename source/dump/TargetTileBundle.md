# TargetTileBundle

**Namespace:** ` `


## Fields

- `Tile tile`

- `FP createdTime`


## Properties

- `Boolean hasEffect`


## Methods

- `Boolean get_hasEffect()`

- `Void ClearEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TargetTileBundle
{
	public Tile tile; // 0x10
	public List`1 enemies; // 0x18
	public FP createdTime; // 0x20
	public ObjectPtr`1 effect; // 0x28

	public Boolean hasEffect { get; }

	// RVA: 0x1e473a8 VA: 0x759445f3a8
	public Boolean get_hasEffect() { }
	// RVA: 0x1e47198 VA: 0x759445f198
	public Void ClearEffect() { }
	// RVA: 0x1e47ca0 VA: 0x759445fca0
	public Void .ctor() { }
}
```