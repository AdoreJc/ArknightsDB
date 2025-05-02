# FurnitureGroupDataAdapter

**Namespace:** ` `


## Fields

- `GroupData m_groupData`


## Properties

- `String id`

- `String displayName`

- `String themeId`


## Methods

- `String get_id()`

- `String get_displayName()`

- `String get_themeId()`

- `Int32 GetCollectComfort(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FurnitureGroupDataAdapter : IFurnitureGroupData
{
	private GroupData m_groupData; // 0x10

	public String id { get; }
	public String displayName { get; }
	public String themeId { get; }
	public IEnumerable`1 furnitures { get; }

	// RVA: 0x37cf5f4 VA: 0x7595de75f4
	public Void .ctor(GroupData groupData) { }
	// RVA: 0x37d008c VA: 0x7595de808c
	public String get_id() { }
	// RVA: 0x37d00a8 VA: 0x7595de80a8
	public String get_displayName() { }
	// RVA: 0x37d00c4 VA: 0x7595de80c4
	public String get_themeId() { }
	// RVA: 0x37d00e0 VA: 0x7595de80e0
	public Int32 GetCollectComfort(Int32 count) { }
	// RVA: 0x37d0110 VA: 0x7595de8110
	public IEnumerable`1 get_furnitures() { }
}
```