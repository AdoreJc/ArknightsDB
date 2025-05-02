# QCShopExtraObj

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ExtraQCObject objData`

- `PlayerGoodItemData playerShop`

- `Boolean isNew`


## Properties

- `ExtraShopGroupType groupType`

- `Boolean SoldOutFlag`

- `Int32 RemainCount`


## Methods

- `ExtraShopGroupType get_groupType()`

- `SortingOrderGroup GetSortingOrderGroup()`

- `Boolean get_SoldOutFlag()`

- `Int32 get_RemainCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopExtraObj
{
	public ExtraQCObject objData; // 0x10
	public PlayerGoodItemData playerShop; // 0x18
	public Boolean isNew; // 0x20

	public ExtraShopGroupType groupType { get; }
	public Boolean SoldOutFlag { get; }
	public Int32 RemainCount { get; }

	// RVA: 0x2453170 VA: 0x7594a6b170
	public ExtraShopGroupType get_groupType() { }
	// RVA: 0x24542a4 VA: 0x7594a6c2a4
	public SortingOrderGroup GetSortingOrderGroup() { }
	// RVA: 0x2454338 VA: 0x7594a6c338
	public Boolean get_SoldOutFlag() { }
	// RVA: 0x2454374 VA: 0x7594a6c374
	public Int32 get_RemainCount() { }
	// RVA: 0x24543ac VA: 0x7594a6c3ac
	public Void .ctor() { }
}
```