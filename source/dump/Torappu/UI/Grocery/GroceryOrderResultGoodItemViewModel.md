# GroceryOrderResultGoodItemViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String <goodId>k__BackingField`

- `String <goodName>k__BackingField`

- `String <goodIconId>k__BackingField`


## Properties

- `String goodId`

- `String goodName`

- `String goodIconId`


## Methods

- `String get_goodId()`

- `Void set_goodId(String)`

- `String get_goodName()`

- `Void set_goodName(String)`

- `String get_goodIconId()`

- `Void set_goodIconId(String)`

- `Void LoadData(String, String, Act27SideData, Dictionary`2)`

- `GroceryOrderResultShopItemViewModel GetShopItemViewModel(String)`

- `Void _LoadShopsData(String, Act27SideGoodData, Act27SideConstData, Dictionary`2, Dictionary`2)`

- `ShopSliderType _GetShopSliderPercentType(List`1)`

- `Single _GetSliderPercent(Int32, List`1, Act27SideConstData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderResultGoodItemViewModel : IHotfixable
{
	private String <goodId>k__BackingField; // 0x10
	private String <goodName>k__BackingField; // 0x18
	private String <goodIconId>k__BackingField; // 0x20
	private List`1 m_shopItemViewModelList; // 0x28
	private static DelegateBridge __Hotfix0_get_goodId; // 0x0
	private static DelegateBridge __Hotfix0_set_goodId; // 0x8
	private static DelegateBridge __Hotfix0_get_goodName; // 0x10
	private static DelegateBridge __Hotfix0_set_goodName; // 0x18
	private static DelegateBridge __Hotfix0_get_goodIconId; // 0x20
	private static DelegateBridge __Hotfix0_set_goodIconId; // 0x28
	private static DelegateBridge __Hotfix0_get_shopItemViewModelList; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_GetShopItemViewModel; // 0x40
	private static DelegateBridge __Hotfix0__LoadShopsData; // 0x48
	private static DelegateBridge __Hotfix0__GetShopSliderPercentType; // 0x50
	private static DelegateBridge __Hotfix0__GetSliderPercent; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String goodId { get; set; }
	public String goodName { get; set; }
	public String goodIconId { get; set; }
	public List`1 shopItemViewModelList { get; }

	// RVA: 0x2896d0c VA: 0x7594eaed0c
	public String get_goodId() { }
	// RVA: 0x2896d74 VA: 0x7594eaed74
	private Void set_goodId(String value) { }
	// RVA: 0x2893d98 VA: 0x7594eabd98
	public String get_goodName() { }
	// RVA: 0x2896df8 VA: 0x7594eaedf8
	private Void set_goodName(String value) { }
	// RVA: 0x2893e00 VA: 0x7594eabe00
	public String get_goodIconId() { }
	// RVA: 0x2896e7c VA: 0x7594eaee7c
	private Void set_goodIconId(String value) { }
	// RVA: 0x28940e0 VA: 0x7594eac0e0
	public List`1 get_shopItemViewModelList() { }
	// RVA: 0x2896f00 VA: 0x7594eaef00
	public Void LoadData(String playerShopId, String goodId, Act27SideData actData, Dictionary`2 purchaseDic) { }
	// RVA: 0x2897654 VA: 0x7594eaf654
	public GroceryOrderResultShopItemViewModel GetShopItemViewModel(String shopId) { }
	// RVA: 0x2897078 VA: 0x7594eaf078
	private Void _LoadShopsData(String playerShopId, Act27SideGoodData goodData, Act27SideConstData constData, Dictionary`2 shopDataMap, Dictionary`2 purchaseDic) { }
	// RVA: 0x2897994 VA: 0x7594eaf994
	private ShopSliderType _GetShopSliderPercentType(List`1 shopPurchaseCountList) { }
	// RVA: 0x289777c VA: 0x7594eaf77c
	private Single _GetSliderPercent(Int32 purchaseCount, List`1 shopPurchaseCountList, Act27SideConstData constData) { }
	// RVA: 0x2897c78 VA: 0x7594eafc78
	public Void .ctor() { }
}
```