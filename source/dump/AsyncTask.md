# AsyncTask

**Namespace:** ` `


## Fields

- `Boolean <isLoaded>k__BackingField`

- `Boolean <isReleased>k__BackingField`

- `GameObject <prefab>k__BackingField`

- `String path`

- `Int32 priority`

- `IDynamicAssetWrapper assetWrapper`


## Properties

- `Boolean isLoaded`

- `Boolean isReleased`

- `GameObject prefab`


## Methods

- `Boolean get_isLoaded()`

- `Void set_isLoaded(Boolean)`

- `Boolean get_isReleased()`

- `Void set_isReleased(Boolean)`

- `GameObject get_prefab()`

- `Void set_prefab(GameObject)`

- `Int32 CompareTo(AsyncTask)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AsyncTask : IComparable`1, IDynamicAssetHandler
{
	private Boolean <isLoaded>k__BackingField; // 0x10
	private Boolean <isReleased>k__BackingField; // 0x11
	private GameObject <prefab>k__BackingField; // 0x18
	public String path; // 0x20
	public Int32 priority; // 0x28
	public IDynamicAssetWrapper assetWrapper; // 0x30
	public Action`2 callback; // 0x38

	public Boolean isLoaded { get; set; }
	public Boolean isReleased { get; set; }
	public GameObject prefab { get; set; }

	// RVA: 0x37b1f94 VA: 0x7595dc9f94
	public Boolean get_isLoaded() { }
	// RVA: 0x37b1f9c VA: 0x7595dc9f9c
	public Void set_isLoaded(Boolean value) { }
	// RVA: 0x37b1fa8 VA: 0x7595dc9fa8
	public Boolean get_isReleased() { }
	// RVA: 0x37b1fb0 VA: 0x7595dc9fb0
	public Void set_isReleased(Boolean value) { }
	// RVA: 0x37b1fbc VA: 0x7595dc9fbc
	public GameObject get_prefab() { }
	// RVA: 0x37b1fc4 VA: 0x7595dc9fc4
	public Void set_prefab(GameObject value) { }
	// RVA: 0x37b1fcc VA: 0x7595dc9fcc
	public Int32 CompareTo(AsyncTask other) { }
	// RVA: 0x37b1500 VA: 0x7595dc9500
	public Void .ctor() { }
}
```