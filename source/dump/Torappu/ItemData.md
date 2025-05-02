# ItemData

**Namespace:** `Torappu`


## Fields

- `String itemId`

- `String name`

- `String description`

- `ItemRarity rarity`

- `String iconId`

- `String overrideBkg`

- `String stackIconId`

- `Int32 sortId`

- `String usage`

- `String obtainApproach`

- `Boolean hideInItemGet`

- `ItemClassifyType classifyType`

- `ItemType itemType`


## Methods

- `Boolean ShouldSerializehideInItemGet()`

- `Boolean ShouldSerializevoucherRelateList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ItemData
{
	public String itemId; // 0x10
	public String name; // 0x18
	public String description; // 0x20
	public ItemRarity rarity; // 0x28
	public String iconId; // 0x30
	public String overrideBkg; // 0x38
	public String stackIconId; // 0x40
	public Int32 sortId; // 0x48
	public String usage; // 0x50
	public String obtainApproach; // 0x58
	public Boolean hideInItemGet; // 0x60
	public ItemClassifyType classifyType; // 0x64
	public ItemType itemType; // 0x68
	public List`1 stageDropList; // 0x70
	public List`1 buildingProductList; // 0x78
	public List`1 voucherRelateList; // 0x80


	// RVA: 0x34a36f0 VA: 0x7595abb6f0
	public Void .ctor() { }
	// RVA: 0x34a36f8 VA: 0x7595abb6f8
	public Void .ctor(String itemId_, String name_, String description_, ItemType type_, ItemRarity rarity_, String iconId_, String overrideBkg_, String stackIconId_, Int32 sortId_, String usage_, String obtainApproach_, ItemClassifyType classifyType_, Boolean hideInItemGet_) { }
	// RVA: 0x34a3820 VA: 0x7595abb820
	public Boolean ShouldSerializehideInItemGet() { }
	// RVA: 0x34a3828 VA: 0x7595abb828
	public Boolean ShouldSerializevoucherRelateList() { }
}
```