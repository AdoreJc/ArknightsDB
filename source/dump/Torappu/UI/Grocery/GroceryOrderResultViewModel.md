# GroceryOrderResultViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Int32 <purchaseTotalCost>k__BackingField`

- `String m_actId`

- `String m_groupId`

- `String m_myShopId`


## Properties

- `Int32 purchaseTotalCost`


## Methods

- `Int32 get_purchaseTotalCost()`

- `Void set_purchaseTotalCost(Int32)`

- `Void LoadData(String)`

- `Void _LoadGoodItems(Act27SideGoodLaunchData, Act27SideData, Dictionary`2)`

- `Void _LoadGoodItemData(String, Act27SideData, Dictionary`2)`

- `Void _RefreshMyShopTotalCost()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderResultViewModel : IHotfixable
{
	private Int32 <purchaseTotalCost>k__BackingField; // 0x10
	private String m_actId; // 0x18
	private String m_groupId; // 0x20
	private String m_myShopId; // 0x28
	private List`1 m_goodItemViewModelList; // 0x30
	private static DelegateBridge __Hotfix0_get_purchaseTotalCost; // 0x0
	private static DelegateBridge __Hotfix0_set_purchaseTotalCost; // 0x8
	private static DelegateBridge __Hotfix0_get_goodItemViewModelList; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0__LoadGoodItems; // 0x20
	private static DelegateBridge __Hotfix0__LoadGoodItemData; // 0x28
	private static DelegateBridge __Hotfix0__RefreshMyShopTotalCost; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 purchaseTotalCost { get; set; }
	public List`1 goodItemViewModelList { get; }

	// RVA: 0x289607c VA: 0x7594eae07c
	public Int32 get_purchaseTotalCost() { }
	// RVA: 0x2897dd0 VA: 0x7594eafdd0
	private Void set_purchaseTotalCost(Int32 value) { }
	// RVA: 0x2895cec VA: 0x7594eadcec
	public List`1 get_goodItemViewModelList() { }
	// RVA: 0x288c4c8 VA: 0x7594ea44c8
	public Void LoadData(String activityId) { }
	// RVA: 0x2897e4c VA: 0x7594eafe4c
	private Void _LoadGoodItems(Act27SideGoodLaunchData launchData, Act27SideData actData, Dictionary`2 allPurchaseInfo) { }
	// RVA: 0x2898134 VA: 0x7594eb0134
	private Void _LoadGoodItemData(String goodId, Act27SideData actData, Dictionary`2 purchaseInfos) { }
	// RVA: 0x2898000 VA: 0x7594eb0000
	private Void _RefreshMyShopTotalCost() { }
	// RVA: 0x28982d8 VA: 0x7594eb02d8
	public Void .ctor() { }
}
```