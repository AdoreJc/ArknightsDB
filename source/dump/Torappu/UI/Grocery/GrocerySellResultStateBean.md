# GrocerySellResultStateBean

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GrocerySellResultProperty property`


## Methods

- `Void LoadData(String, SellGoodState)`

- `Void UpdateSaleSettle(Int32, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultStateBean : IStateBean, IHotfixable
{
	public GrocerySellResultProperty property; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateSaleSettle; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28a39a8 VA: 0x7594ebb9a8
	public Void LoadData(String actId, SellGoodState sellGoodState) { }
	// RVA: 0x28a3a5c VA: 0x7594ebba5c
	public Void UpdateSaleSettle(Int32 fund, List`1 rewards) { }
	// RVA: 0x28a3b14 VA: 0x7594ebbb14
	public Void .ctor() { }
}
```