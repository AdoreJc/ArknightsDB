# SpineEffectPreset

**Namespace:** ` `


## Fields

- `Transform bone`

- `DirectionType _directionType`

- `Boolean createAtWorldPos`


## Properties

- `String effect`

- `Boolean isSingle`


## Methods

- `String get_effect()`

- `Void set_effect(String)`

- `Void set_effects(String[])`

- `Boolean get_isSingle()`

- `Direction _GetDirection(Entity)`

- `String GetEffect(Entity)`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpineEffectPreset
{
	public Transform bone; // 0x10
	private DirectionType _directionType; // 0x18
	public Boolean createAtWorldPos; // 0x1c
	private String[] _effects; // 0x20

	public String effect { get; set; }
	public String[] effects { get; set; }
	public Boolean isSingle { get; }

	// RVA: 0x3fba538 VA: 0x75965d2538
	public String get_effect() { }
	// RVA: 0x3fba560 VA: 0x75965d2560
	public Void set_effect(String value) { }
	// RVA: 0x3fba5c0 VA: 0x75965d25c0
	public String[] get_effects() { }
	// RVA: 0x3fba5c8 VA: 0x75965d25c8
	public Void set_effects(String[] value) { }
	// RVA: 0x3fba5d0 VA: 0x75965d25d0
	public Boolean get_isSingle() { }
	// RVA: 0x3fba5e0 VA: 0x75965d25e0
	private Direction _GetDirection(Entity entity) { }
	// RVA: 0x3fba040 VA: 0x75965d2040
	public String GetEffect(Entity owner) { }
	// RVA: 0x3fba314 VA: 0x75965d2314
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x3fba6b4 VA: 0x75965d26b4
	public Void .ctor() { }
}
```