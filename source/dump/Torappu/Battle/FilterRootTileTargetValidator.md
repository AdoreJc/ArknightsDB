# FilterRootTileTargetValidator

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _filterHeightType`

- `HeightType _tileHeightType`


## Properties

- `Boolean filterHeightType`


## Methods

- `Boolean get_filterHeightType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FilterRootTileTargetValidator : TargetValidator
{
	private Boolean _filterHeightType; // 0x8a
	private HeightType _tileHeightType; // 0x8c

	private Boolean filterHeightType { get; }

	// RVA: 0x1bdad34 VA: 0x75941f2d34
	private Boolean get_filterHeightType() { }
	// RVA: 0x1bdad3c VA: 0x75941f2d3c
	public override Boolean Validate(Entity target) { }
	// RVA: 0x1bdae68 VA: 0x75941f2e68
	public Void .ctor() { }
}
```