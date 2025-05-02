# SStockViewModel

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `Boolean m_isEditing`

- `ShopStockInfoViewModel info`

- `SRoomEditStruct initEditInfo`

- `SRoomEditStruct editInfo`


## Properties

- `Boolean isEditing`


## Methods

- `Boolean get_isEditing()`

- `Void set_isEditing(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class SStockViewModel
{
	private Boolean m_isEditing; // 0x10
	public ShopStockInfoViewModel info; // 0x18
	public SRoomEditStruct initEditInfo; // 0x20
	public SRoomEditStruct editInfo; // 0x38

	public Boolean isEditing { get; set; }

	// RVA: 0x3dbaa04 VA: 0x75963d2a04
	public Boolean get_isEditing() { }
	// RVA: 0x3dba038 VA: 0x75963d2038
	public Void set_isEditing(Boolean value) { }
	// RVA: 0x3dbaa0c VA: 0x75963d2a0c
	public Void .ctor() { }
}
```