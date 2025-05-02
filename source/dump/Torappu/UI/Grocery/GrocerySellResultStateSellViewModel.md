# GrocerySellResultStateSellViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String goodId`

- `String goodIconId`

- `String goodName`

- `Int32 totalIncome`

- `PlayerPurchaseInfo playerPurchaseInfo`


## Methods

- `SellInfo GetPlayerSellInfo()`

- `Void LoadStateSellData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultStateSellViewModel : IHotfixable
{
	public String goodId; // 0x10
	public String goodIconId; // 0x18
	public String goodName; // 0x20
	public Int32 totalIncome; // 0x28
	public PlayerPurchaseInfo playerPurchaseInfo; // 0x30
	public List`1 sellInfos; // 0x38
	private static DelegateBridge __Hotfix0_GetPlayerSellInfo; // 0x0
	private static DelegateBridge __Hotfix0_LoadStateSellData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28a2ce0 VA: 0x7594ebace0
	public SellInfo GetPlayerSellInfo() { }
	// RVA: 0x28a2504 VA: 0x7594eba504
	public Void LoadStateSellData(String actId, String goodId) { }
	// RVA: 0x28a2408 VA: 0x7594eba408
	public Void .ctor() { }
}
```