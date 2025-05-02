# GroceryOrderSelfShopViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String <goodId>k__BackingField`

- `String <shopId>k__BackingField`

- `Int32 <curSelectingStrategyIndex>k__BackingField`

- `Boolean <isExactOrderCount>k__BackingField`

- `Int32 <exactOrderCount>k__BackingField`

- `Boolean <isSectionOrderCount>k__BackingField`

- `Int32 <sectionDownCount>k__BackingField`

- `Int32 <sectionUpCount>k__BackingField`

- `Boolean <isPermanentGood>k__BackingField`

- `Int32 <stockCount>k__BackingField`

- `GroceryOrderMyShopStatus m_status`


## Properties

- `String goodId`

- `String shopId`

- `Int32 curSelectingStrategyIndex`

- `Boolean isExactOrderCount`

- `Int32 exactOrderCount`

- `Boolean isSectionOrderCount`

- `Int32 sectionDownCount`

- `Int32 sectionUpCount`

- `Boolean isPermanentGood`

- `Int32 stockCount`

- `GroceryOrderMyShopStatus status`


## Methods

- `String get_goodId()`

- `Void set_goodId(String)`

- `String get_shopId()`

- `Void set_shopId(String)`

- `Int32 get_curSelectingStrategyIndex()`

- `Void set_curSelectingStrategyIndex(Int32)`

- `Boolean get_isExactOrderCount()`

- `Void set_isExactOrderCount(Boolean)`

- `Int32 get_exactOrderCount()`

- `Void set_exactOrderCount(Int32)`

- `Boolean get_isSectionOrderCount()`

- `Void set_isSectionOrderCount(Boolean)`

- `Int32 get_sectionDownCount()`

- `Void set_sectionDownCount(Int32)`

- `Int32 get_sectionUpCount()`

- `Void set_sectionUpCount(Int32)`

- `Boolean get_isPermanentGood()`

- `Void set_isPermanentGood(Boolean)`

- `Int32 get_stockCount()`

- `Void set_stockCount(Int32)`

- `GroceryOrderMyShopStatus get_status()`

- `Void LoadData(Act27SideGoodData, Act27SideShopData, List`1)`

- `Void RefreshShopExpectedOrder(Int32[])`

- `Void RefreshShopGoodStockCount(Int32)`

- `Void RefreshCurSelectIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderSelfShopViewModel : IHotfixable
{
	private String <goodId>k__BackingField; // 0x10
	private String <shopId>k__BackingField; // 0x18
	private Int32 <curSelectingStrategyIndex>k__BackingField; // 0x20
	private Boolean <isExactOrderCount>k__BackingField; // 0x24
	private Int32 <exactOrderCount>k__BackingField; // 0x28
	private Boolean <isSectionOrderCount>k__BackingField; // 0x2c
	private Int32 <sectionDownCount>k__BackingField; // 0x30
	private Int32 <sectionUpCount>k__BackingField; // 0x34
	private Boolean <isPermanentGood>k__BackingField; // 0x38
	private Int32 <stockCount>k__BackingField; // 0x3c
	private GroceryOrderMyShopStatus m_status; // 0x40
	private List`1 m_strategyItemViewModelList; // 0x48
	private List`1 m_orderCount; // 0x50
	private static DelegateBridge __Hotfix0_get_goodId; // 0x0
	private static DelegateBridge __Hotfix0_set_goodId; // 0x8
	private static DelegateBridge __Hotfix0_get_shopId; // 0x10
	private static DelegateBridge __Hotfix0_set_shopId; // 0x18
	private static DelegateBridge __Hotfix0_get_curSelectingStrategyIndex; // 0x20
	private static DelegateBridge __Hotfix0_set_curSelectingStrategyIndex; // 0x28
	private static DelegateBridge __Hotfix0_get_isExactOrderCount; // 0x30
	private static DelegateBridge __Hotfix0_set_isExactOrderCount; // 0x38
	private static DelegateBridge __Hotfix0_get_exactOrderCount; // 0x40
	private static DelegateBridge __Hotfix0_set_exactOrderCount; // 0x48
	private static DelegateBridge __Hotfix0_get_isSectionOrderCount; // 0x50
	private static DelegateBridge __Hotfix0_set_isSectionOrderCount; // 0x58
	private static DelegateBridge __Hotfix0_get_sectionDownCount; // 0x60
	private static DelegateBridge __Hotfix0_set_sectionDownCount; // 0x68
	private static DelegateBridge __Hotfix0_get_sectionUpCount; // 0x70
	private static DelegateBridge __Hotfix0_set_sectionUpCount; // 0x78
	private static DelegateBridge __Hotfix0_get_isPermanentGood; // 0x80
	private static DelegateBridge __Hotfix0_set_isPermanentGood; // 0x88
	private static DelegateBridge __Hotfix0_get_stockCount; // 0x90
	private static DelegateBridge __Hotfix0_set_stockCount; // 0x98
	private static DelegateBridge __Hotfix0_get_status; // 0xa0
	private static DelegateBridge __Hotfix0_get_strategyItemViewModelList; // 0xa8
	private static DelegateBridge __Hotfix0_LoadData; // 0xb0
	private static DelegateBridge __Hotfix0_RefreshShopExpectedOrder; // 0xb8
	private static DelegateBridge __Hotfix0_RefreshShopGoodStockCount; // 0xc0
	private static DelegateBridge __Hotfix0_RefreshCurSelectIndex; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public String goodId { get; set; }
	public String shopId { get; set; }
	public Int32 curSelectingStrategyIndex { get; set; }
	public Boolean isExactOrderCount { get; set; }
	public Int32 exactOrderCount { get; set; }
	public Boolean isSectionOrderCount { get; set; }
	public Int32 sectionDownCount { get; set; }
	public Int32 sectionUpCount { get; set; }
	public Boolean isPermanentGood { get; set; }
	public Int32 stockCount { get; set; }
	public GroceryOrderMyShopStatus status { get; }
	public List`1 strategyItemViewModelList { get; }

	// RVA: 0x2888470 VA: 0x7594ea0470
	public String get_goodId() { }
	// RVA: 0x288fd5c VA: 0x7594ea7d5c
	private Void set_goodId(String value) { }
	// RVA: 0x288fde0 VA: 0x7594ea7de0
	public String get_shopId() { }
	// RVA: 0x288fe48 VA: 0x7594ea7e48
	private Void set_shopId(String value) { }
	// RVA: 0x288fecc VA: 0x7594ea7ecc
	public Int32 get_curSelectingStrategyIndex() { }
	// RVA: 0x288ff34 VA: 0x7594ea7f34
	private Void set_curSelectingStrategyIndex(Int32 value) { }
	// RVA: 0x288878c VA: 0x7594ea078c
	public Boolean get_isExactOrderCount() { }
	// RVA: 0x288ffb0 VA: 0x7594ea7fb0
	private Void set_isExactOrderCount(Boolean value) { }
	// RVA: 0x288885c VA: 0x7594ea085c
	public Int32 get_exactOrderCount() { }
	// RVA: 0x2890030 VA: 0x7594ea8030
	private Void set_exactOrderCount(Int32 value) { }
	// RVA: 0x28887f4 VA: 0x7594ea07f4
	public Boolean get_isSectionOrderCount() { }
	// RVA: 0x28900ac VA: 0x7594ea80ac
	private Void set_isSectionOrderCount(Boolean value) { }
	// RVA: 0x28888c4 VA: 0x7594ea08c4
	public Int32 get_sectionDownCount() { }
	// RVA: 0x289012c VA: 0x7594ea812c
	private Void set_sectionDownCount(Int32 value) { }
	// RVA: 0x288892c VA: 0x7594ea092c
	public Int32 get_sectionUpCount() { }
	// RVA: 0x28901a8 VA: 0x7594ea81a8
	private Void set_sectionUpCount(Int32 value) { }
	// RVA: 0x2888628 VA: 0x7594ea0628
	public Boolean get_isPermanentGood() { }
	// RVA: 0x2890224 VA: 0x7594ea8224
	private Void set_isPermanentGood(Boolean value) { }
	// RVA: 0x2888690 VA: 0x7594ea0690
	public Int32 get_stockCount() { }
	// RVA: 0x28902a4 VA: 0x7594ea82a4
	private Void set_stockCount(Int32 value) { }
	// RVA: 0x2890320 VA: 0x7594ea8320
	public GroceryOrderMyShopStatus get_status() { }
	// RVA: 0x2888aa4 VA: 0x7594ea0aa4
	public List`1 get_strategyItemViewModelList() { }
	// RVA: 0x2890388 VA: 0x7594ea8388
	public Void LoadData(Act27SideGoodData goodData, Act27SideShopData shopData, List`1 strategyList) { }
	// RVA: 0x28907a4 VA: 0x7594ea87a4
	public Void RefreshShopExpectedOrder(Int32[] order) { }
	// RVA: 0x28909f0 VA: 0x7594ea89f0
	public Void RefreshShopGoodStockCount(Int32 stock) { }
	// RVA: 0x2890690 VA: 0x7594ea8690
	public Void RefreshCurSelectIndex(Int32 index) { }
	// RVA: 0x2890a88 VA: 0x7594ea8a88
	public Void .ctor() { }
}
```