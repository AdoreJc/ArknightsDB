# RuntimeAsset

**Namespace:** ` `


## Fields

- `Boolean <fromResource>k__BackingField`

- `TextAsset <asset>k__BackingField`


## Properties

- `Boolean fromResource`

- `TextAsset asset`


## Methods

- `Boolean get_fromResource()`

- `Void set_fromResource(Boolean)`

- `TextAsset get_asset()`

- `Void set_asset(TextAsset)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RuntimeAsset : IDisposable
{
	private Boolean <fromResource>k__BackingField; // 0x10
	private TextAsset <asset>k__BackingField; // 0x18

	public Boolean fromResource { get; set; }
	public TextAsset asset { get; set; }

	// RVA: 0x371ea94 VA: 0x7595d36a94
	public Boolean get_fromResource() { }
	// RVA: 0x371ea9c VA: 0x7595d36a9c
	private Void set_fromResource(Boolean value) { }
	// RVA: 0x371eaa8 VA: 0x7595d36aa8
	public TextAsset get_asset() { }
	// RVA: 0x371eab0 VA: 0x7595d36ab0
	private Void set_asset(TextAsset value) { }
	// RVA: 0x371e678 VA: 0x7595d36678
	public Void .ctor(TextAsset pAsset, Boolean pFromResource) { }
	// RVA: 0x371c390 VA: 0x7595d34390
	public Void Dispose() { }
}
```