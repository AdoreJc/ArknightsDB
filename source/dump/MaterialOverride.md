# MaterialOverride

**Namespace:** ` `


## Fields

- `Int32 _useCount`

- `Material <original>k__BackingField`

- `Material <replacement>k__BackingField`


## Properties

- `Material original`

- `Material replacement`


## Methods

- `Material get_original()`

- `Void set_original(Material)`

- `Material get_replacement()`

- `Void set_replacement(Material)`

- `Material Get()`

- `Boolean Release()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MaterialOverride
{
	private Int32 _useCount; // 0x10
	private Material <original>k__BackingField; // 0x18
	private Material <replacement>k__BackingField; // 0x20

	public Material original { get; set; }
	public Material replacement { get; set; }

	// RVA: 0x2b4cac4 VA: 0x7595164ac4
	public Void .ctor(Material original, Material replacement) { }
	// RVA: 0x2b4ce5c VA: 0x7595164e5c
	public Material get_original() { }
	// RVA: 0x2b4ce64 VA: 0x7595164e64
	private Void set_original(Material value) { }
	// RVA: 0x2b4ce6c VA: 0x7595164e6c
	public Material get_replacement() { }
	// RVA: 0x2b4ce74 VA: 0x7595164e74
	private Void set_replacement(Material value) { }
	// RVA: 0x2b4caac VA: 0x7595164aac
	public Material Get() { }
	// RVA: 0x2b4cc60 VA: 0x7595164c60
	public Boolean Release() { }
}
```