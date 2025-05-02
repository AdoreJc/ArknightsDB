# ViewPool

**Namespace:** ` `


## Fields

- `GameObject m_prefab`

- `Transform m_container`

- `Int32 <viewType>k__BackingField`


## Properties

- `Int32 viewType`


## Methods

- `Int32 get_viewType()`

- `Void set_viewType(Int32)`

- `GameObject Alloc(out)`

- `Boolean Recycle(GameObject)`

- `Void RecycleAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ViewPool
{
	private GameObject m_prefab; // 0x10
	private Transform m_container; // 0x18
	private List`1 m_activeObjs; // 0x20
	private List`1 m_pooledObjs; // 0x28
	private Int32 <viewType>k__BackingField; // 0x30

	public Int32 viewType { get; set; }

	// RVA: 0x2212034 VA: 0x759482a034
	public Int32 get_viewType() { }
	// RVA: 0x221203c VA: 0x759482a03c
	private Void set_viewType(Int32 value) { }
	// RVA: 0x2212044 VA: 0x759482a044
	public Void .ctor(Int32 viewType, GameObject prefab, Transform container) { }
	// RVA: 0x2212138 VA: 0x759482a138
	public GameObject Alloc(out Boolean isNewlyCreated) { }
	// RVA: 0x22122f4 VA: 0x759482a2f4
	public Boolean Recycle(GameObject obj) { }
	// RVA: 0x22124f0 VA: 0x759482a4f0
	public Void RecycleAll() { }
}
```