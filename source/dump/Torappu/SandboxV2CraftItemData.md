# SandboxV2CraftItemData

**Namespace:** `Torappu`


## Fields

- `String itemId`

- `SandboxV2CraftItemType type`

- `String buildingUnlockDesc`

- `Int32 outputRatio`

- `Int32 withdrawRatio`

- `Int32 repairCost`

- `Boolean isHidden`

- `String craftGroupId`

- `Int32 recipeLevel`


## Methods

- `Boolean ShouldSerializeisHidden()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2CraftItemData
{
	public String itemId; // 0x10
	public SandboxV2CraftItemType type; // 0x18
	public String buildingUnlockDesc; // 0x20
	public Dictionary`2 materialItems; // 0x28
	public Dictionary`2 upgradeItems; // 0x30
	public Int32 outputRatio; // 0x38
	public Int32 withdrawRatio; // 0x3c
	public Int32 repairCost; // 0x40
	public Boolean isHidden; // 0x44
	public String craftGroupId; // 0x48
	public Int32 recipeLevel; // 0x50


	// RVA: 0x34b2668 VA: 0x7595aca668
	public Boolean ShouldSerializeisHidden() { }
	// RVA: 0x34b2670 VA: 0x7595aca670
	public Void .ctor() { }
}
```