# GroceryOrderOtherShopItemViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String <goodId>k__BackingField`

- `String <shopId>k__BackingField`

- `String <shopIconId>k__BackingField`

- `String <strategy>k__BackingField`

- `Boolean <isExactOrderCount>k__BackingField`

- `Int32 <exactOrderCount>k__BackingField`

- `Boolean <isSectionOrderCount>k__BackingField`

- `Int32 <sectionDownCount>k__BackingField`

- `Int32 <sectionUpCount>k__BackingField`

- `Boolean <isEmptyShop>k__BackingField`

- `Boolean <hasInquireCount>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `GroceryOrderOtherShopStatus m_status`

- `Int32 m_strategyIndex`


## Properties

- `String goodId`

- `String shopId`

- `String shopIconId`

- `String strategy`

- `Boolean isExactOrderCount`

- `Int32 exactOrderCount`

- `Boolean isSectionOrderCount`

- `Int32 sectionDownCount`

- `Int32 sectionUpCount`

- `Boolean isEmptyShop`

- `Boolean hasInquireCount`

- `Int32 sortId`

- `GroceryOrderOtherShopStatus status`


## Methods

- `String get_goodId()`

- `Void set_goodId(String)`

- `String get_shopId()`

- `Void set_shopId(String)`

- `String get_shopIconId()`

- `Void set_shopIconId(String)`

- `String get_strategy()`

- `Void set_strategy(String)`

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

- `Boolean get_isEmptyShop()`

- `Void set_isEmptyShop(Boolean)`

- `Boolean get_hasInquireCount()`

- `Void set_hasInquireCount(Boolean)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `GroceryOrderOtherShopStatus get_status()`

- `Void LoadData(String, Act27SideShopData, List`1)`

- `Void RefreshHasInquireCount(Boolean)`

- `Void RefreshShopStrategy(Int32)`

- `Void RefreshShopOrder(Int32[])`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderOtherShopItemViewModel : IHotfixable, IComparable
{
	private String <goodId>k__BackingField; // 0x10
	private String <shopId>k__BackingField; // 0x18
	private String <shopIconId>k__BackingField; // 0x20
	private String <strategy>k__BackingField; // 0x28
	private Boolean <isExactOrderCount>k__BackingField; // 0x30
	private Int32 <exactOrderCount>k__BackingField; // 0x34
	private Boolean <isSectionOrderCount>k__BackingField; // 0x38
	private Int32 <sectionDownCount>k__BackingField; // 0x3c
	private Int32 <sectionUpCount>k__BackingField; // 0x40
	private Boolean <isEmptyShop>k__BackingField; // 0x44
	private Boolean <hasInquireCount>k__BackingField; // 0x45
	private Int32 <sortId>k__BackingField; // 0x48
	private GroceryOrderOtherShopStatus m_status; // 0x4c
	private Int32 m_strategyIndex; // 0x50
	private List`1 m_orderCount; // 0x58
	private List`1 m_strategyNameList; // 0x60
	public static GroceryOrderOtherShopItemViewModel EMPTY; // 0x0
	private static DelegateBridge __Hotfix0_get_goodId; // 0x8
	private static DelegateBridge __Hotfix0_set_goodId; // 0x10
	private static DelegateBridge __Hotfix0_get_shopId; // 0x18
	private static DelegateBridge __Hotfix0_set_shopId; // 0x20
	private static DelegateBridge __Hotfix0_get_shopIconId; // 0x28
	private static DelegateBridge __Hotfix0_set_shopIconId; // 0x30
	private static DelegateBridge __Hotfix0_get_strategy; // 0x38
	private static DelegateBridge __Hotfix0_set_strategy; // 0x40
	private static DelegateBridge __Hotfix0_get_isExactOrderCount; // 0x48
	private static DelegateBridge __Hotfix0_set_isExactOrderCount; // 0x50
	private static DelegateBridge __Hotfix0_get_exactOrderCount; // 0x58
	private static DelegateBridge __Hotfix0_set_exactOrderCount; // 0x60
	private static DelegateBridge __Hotfix0_get_isSectionOrderCount; // 0x68
	private static DelegateBridge __Hotfix0_set_isSectionOrderCount; // 0x70
	private static DelegateBridge __Hotfix0_get_sectionDownCount; // 0x78
	private static DelegateBridge __Hotfix0_set_sectionDownCount; // 0x80
	private static DelegateBridge __Hotfix0_get_sectionUpCount; // 0x88
	private static DelegateBridge __Hotfix0_set_sectionUpCount; // 0x90
	private static DelegateBridge __Hotfix0_get_isEmptyShop; // 0x98
	private static DelegateBridge __Hotfix0_set_isEmptyShop; // 0xa0
	private static DelegateBridge __Hotfix0_get_hasInquireCount; // 0xa8
	private static DelegateBridge __Hotfix0_set_hasInquireCount; // 0xb0
	private static DelegateBridge __Hotfix0_get_sortId; // 0xb8
	private static DelegateBridge __Hotfix0_set_sortId; // 0xc0
	private static DelegateBridge __Hotfix0_get_status; // 0xc8
	private static DelegateBridge __Hotfix0_LoadData; // 0xd0
	private static DelegateBridge __Hotfix0_RefreshHasInquireCount; // 0xd8
	private static DelegateBridge __Hotfix0_RefreshShopStrategy; // 0xe0
	private static DelegateBridge __Hotfix0_RefreshShopOrder; // 0xe8
	private static DelegateBridge __Hotfix0_CompareTo; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8

	public String goodId { get; set; }
	public String shopId { get; set; }
	public String shopIconId { get; set; }
	public String strategy { get; set; }
	public Boolean isExactOrderCount { get; set; }
	public Int32 exactOrderCount { get; set; }
	public Boolean isSectionOrderCount { get; set; }
	public Int32 sectionDownCount { get; set; }
	public Int32 sectionUpCount { get; set; }
	public Boolean isEmptyShop { get; set; }
	public Boolean hasInquireCount { get; set; }
	public Int32 sortId { get; set; }
	public GroceryOrderOtherShopStatus status { get; }

	// RVA: 0x2889464 VA: 0x7594ea1464
	public String get_goodId() { }
	// RVA: 0x288e908 VA: 0x7594ea6908
	private Void set_goodId(String value) { }
	// RVA: 0x28893ec VA: 0x7594ea13ec
	public String get_shopId() { }
	// RVA: 0x288e99c VA: 0x7594ea699c
	private Void set_shopId(String value) { }
	// RVA: 0x28894dc VA: 0x7594ea14dc
	public String get_shopIconId() { }
	// RVA: 0x288ea30 VA: 0x7594ea6a30
	private Void set_shopIconId(String value) { }
	// RVA: 0x288970c VA: 0x7594ea170c
	public String get_strategy() { }
	// RVA: 0x288eac4 VA: 0x7594ea6ac4
	private Void set_strategy(String value) { }
	// RVA: 0x28897fc VA: 0x7594ea17fc
	public Boolean get_isExactOrderCount() { }
	// RVA: 0x288eb58 VA: 0x7594ea6b58
	private Void set_isExactOrderCount(Boolean value) { }
	// RVA: 0x2889874 VA: 0x7594ea1874
	public Int32 get_exactOrderCount() { }
	// RVA: 0x288ebe8 VA: 0x7594ea6be8
	private Void set_exactOrderCount(Int32 value) { }
	// RVA: 0x28898ec VA: 0x7594ea18ec
	public Boolean get_isSectionOrderCount() { }
	// RVA: 0x288ec74 VA: 0x7594ea6c74
	private Void set_isSectionOrderCount(Boolean value) { }
	// RVA: 0x2889964 VA: 0x7594ea1964
	public Int32 get_sectionDownCount() { }
	// RVA: 0x288ed04 VA: 0x7594ea6d04
	private Void set_sectionDownCount(Int32 value) { }
	// RVA: 0x28899dc VA: 0x7594ea19dc
	public Int32 get_sectionUpCount() { }
	// RVA: 0x288ed90 VA: 0x7594ea6d90
	private Void set_sectionUpCount(Int32 value) { }
	// RVA: 0x2889374 VA: 0x7594ea1374
	public Boolean get_isEmptyShop() { }
	// RVA: 0x288ee1c VA: 0x7594ea6e1c
	private Void set_isEmptyShop(Boolean value) { }
	// RVA: 0x2889784 VA: 0x7594ea1784
	public Boolean get_hasInquireCount() { }
	// RVA: 0x288eeac VA: 0x7594ea6eac
	private Void set_hasInquireCount(Boolean value) { }
	// RVA: 0x288ef3c VA: 0x7594ea6f3c
	public Int32 get_sortId() { }
	// RVA: 0x288efb4 VA: 0x7594ea6fb4
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2889554 VA: 0x7594ea1554
	public GroceryOrderOtherShopStatus get_status() { }
	// RVA: 0x288f040 VA: 0x7594ea7040
	public Void LoadData(String goodId, Act27SideShopData shopData, List`1 strategyList) { }
	// RVA: 0x288f144 VA: 0x7594ea7144
	public Void RefreshHasInquireCount(Boolean inquireCountLeft) { }
	// RVA: 0x288f1d4 VA: 0x7594ea71d4
	public Void RefreshShopStrategy(Int32 strategyIndex) { }
	// RVA: 0x288f314 VA: 0x7594ea7314
	public Void RefreshShopOrder(Int32[] order) { }
	// RVA: 0x288f59c VA: 0x7594ea759c
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x288f6dc VA: 0x7594ea76dc
	public Void .ctor() { }
	// RVA: 0x288f808 VA: 0x7594ea7808
	private static Void .cctor() { }
}
```