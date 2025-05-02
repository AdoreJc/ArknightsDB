# TemplateShopData

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `String shopId`

- `String shopName`

- `TShopType type`

- `ItemBundle price`

- `String iconColorCodes`

- `String buttonColorCodes`

- `Int64 startTime`

- `Int64 endTime`

- `GroupShopExtraData groupExtraData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopData
{
	public String shopId; // 0x10
	public String shopName; // 0x18
	public TShopType type; // 0x20
	public ItemBundle price; // 0x28
	public Dictionary`2 shopGroup; // 0x30
	public String iconColorCodes; // 0x38
	public String buttonColorCodes; // 0x40
	public Int64 startTime; // 0x48
	public Int64 endTime; // 0x50
	public GroupShopExtraData groupExtraData; // 0x58


	// RVA: 0x236254c VA: 0x759497a54c
	public Void .ctor() { }
}
```