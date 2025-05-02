# GroceryHomeGoodItemModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String goodId`

- `String name`

- `String iconId`

- `Boolean isPermanent`

- `Int32 count`


## Methods

- `Void RefreshPlayerData(PlayerAct27SideActivity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryHomeGoodItemModel : IHotfixable
{
	public String goodId; // 0x10
	public String name; // 0x18
	public String iconId; // 0x20
	public Boolean isPermanent; // 0x28
	public Int32 count; // 0x2c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8


	// RVA: 0x2865484 VA: 0x7594e7d484
	public Void .ctor(String goodId, Dictionary`2 goodMap) { }
	// RVA: 0x28655a4 VA: 0x7594e7d5a4
	public Void RefreshPlayerData(PlayerAct27SideActivity playerData) { }
}
```