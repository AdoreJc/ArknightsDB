# GroceryOrderSelfShopStrategyItemViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String <goodId>k__BackingField`

- `Int32 <index>k__BackingField`

- `String <shopIconId>k__BackingField`

- `Int32 <priceCount>k__BackingField`

- `String <strategyName>k__BackingField`

- `Boolean <isSelecting>k__BackingField`


## Properties

- `String goodId`

- `Int32 index`

- `String shopIconId`

- `Int32 priceCount`

- `String strategyName`

- `Boolean isSelecting`


## Methods

- `String get_goodId()`

- `Void set_goodId(String)`

- `Int32 get_index()`

- `Void set_index(Int32)`

- `String get_shopIconId()`

- `Void set_shopIconId(String)`

- `Int32 get_priceCount()`

- `Void set_priceCount(Int32)`

- `String get_strategyName()`

- `Void set_strategyName(String)`

- `Boolean get_isSelecting()`

- `Void set_isSelecting(Boolean)`

- `Void LoadData(String, Int32, String, Int32, String)`

- `Void RefreshSelect(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderSelfShopStrategyItemViewModel : IHotfixable
{
	private String <goodId>k__BackingField; // 0x10
	private Int32 <index>k__BackingField; // 0x18
	private String <shopIconId>k__BackingField; // 0x20
	private Int32 <priceCount>k__BackingField; // 0x28
	private String <strategyName>k__BackingField; // 0x30
	private Boolean <isSelecting>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_goodId; // 0x0
	private static DelegateBridge __Hotfix0_set_goodId; // 0x8
	private static DelegateBridge __Hotfix0_get_index; // 0x10
	private static DelegateBridge __Hotfix0_set_index; // 0x18
	private static DelegateBridge __Hotfix0_get_shopIconId; // 0x20
	private static DelegateBridge __Hotfix0_set_shopIconId; // 0x28
	private static DelegateBridge __Hotfix0_get_priceCount; // 0x30
	private static DelegateBridge __Hotfix0_set_priceCount; // 0x38
	private static DelegateBridge __Hotfix0_get_strategyName; // 0x40
	private static DelegateBridge __Hotfix0_set_strategyName; // 0x48
	private static DelegateBridge __Hotfix0_get_isSelecting; // 0x50
	private static DelegateBridge __Hotfix0_set_isSelecting; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_RefreshSelect; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String goodId { get; set; }
	public Int32 index { get; set; }
	public String shopIconId { get; set; }
	public Int32 priceCount { get; set; }
	public String strategyName { get; set; }
	public Boolean isSelecting { get; set; }

	// RVA: 0x288d3d4 VA: 0x7594ea53d4
	public String get_goodId() { }
	// RVA: 0x288f880 VA: 0x7594ea7880
	private Void set_goodId(String value) { }
	// RVA: 0x288d43c VA: 0x7594ea543c
	public Int32 get_index() { }
	// RVA: 0x288f904 VA: 0x7594ea7904
	private Void set_index(Int32 value) { }
	// RVA: 0x288d574 VA: 0x7594ea5574
	public String get_shopIconId() { }
	// RVA: 0x288f980 VA: 0x7594ea7980
	private Void set_shopIconId(String value) { }
	// RVA: 0x288d4a4 VA: 0x7594ea54a4
	public Int32 get_priceCount() { }
	// RVA: 0x288fa04 VA: 0x7594ea7a04
	private Void set_priceCount(Int32 value) { }
	// RVA: 0x288d50c VA: 0x7594ea550c
	public String get_strategyName() { }
	// RVA: 0x288fa80 VA: 0x7594ea7a80
	private Void set_strategyName(String value) { }
	// RVA: 0x288d5dc VA: 0x7594ea55dc
	public Boolean get_isSelecting() { }
	// RVA: 0x288fb04 VA: 0x7594ea7b04
	private Void set_isSelecting(Boolean value) { }
	// RVA: 0x288fb84 VA: 0x7594ea7b84
	public Void LoadData(String goodId, Int32 strategyIndex, String iconId, Int32 price, String strategy) { }
	// RVA: 0x288fc6c VA: 0x7594ea7c6c
	public Void RefreshSelect(Boolean isSelect) { }
	// RVA: 0x288fcec VA: 0x7594ea7cec
	public Void .ctor() { }
}
```