# GroceryOrderResultShopItemViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String <shopId>k__BackingField`

- `String <shopIcon>k__BackingField`

- `Boolean <isSelfShop>k__BackingField`

- `String <strategy>k__BackingField`

- `Int32 <purchaseCost>k__BackingField`

- `Int32 <purchaseCount>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `Boolean <isEmptyShop>k__BackingField`

- `Int32 <index>k__BackingField`

- `Single <sliderPercent>k__BackingField`


## Properties

- `String shopId`

- `String shopIcon`

- `Boolean isSelfShop`

- `String strategy`

- `Int32 purchaseCost`

- `Int32 purchaseCount`

- `Int32 sortId`

- `Boolean isEmptyShop`

- `Int32 index`

- `Single sliderPercent`


## Methods

- `String get_shopId()`

- `Void set_shopId(String)`

- `String get_shopIcon()`

- `Void set_shopIcon(String)`

- `Boolean get_isSelfShop()`

- `Void set_isSelfShop(Boolean)`

- `String get_strategy()`

- `Void set_strategy(String)`

- `Int32 get_purchaseCost()`

- `Void set_purchaseCost(Int32)`

- `Int32 get_purchaseCount()`

- `Void set_purchaseCount(Int32)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Boolean get_isEmptyShop()`

- `Void set_isEmptyShop(Boolean)`

- `Int32 get_index()`

- `Void set_index(Int32)`

- `Single get_sliderPercent()`

- `Void set_sliderPercent(Single)`

- `Void LoadData(Act27SideShopData, String, Int32, Int32, Boolean)`

- `Void RefreshData(Int32, Single)`

- `Int32 GetPurchaseTotalCost()`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderResultShopItemViewModel : IHotfixable, IComparable
{
	private String <shopId>k__BackingField; // 0x10
	private String <shopIcon>k__BackingField; // 0x18
	private Boolean <isSelfShop>k__BackingField; // 0x20
	private String <strategy>k__BackingField; // 0x28
	private Int32 <purchaseCost>k__BackingField; // 0x30
	private Int32 <purchaseCount>k__BackingField; // 0x34
	private Int32 <sortId>k__BackingField; // 0x38
	private Boolean <isEmptyShop>k__BackingField; // 0x3c
	private Int32 <index>k__BackingField; // 0x40
	private Single <sliderPercent>k__BackingField; // 0x44
	public static GroceryOrderResultShopItemViewModel EMPTY; // 0x0
	private static DelegateBridge __Hotfix0_get_shopId; // 0x8
	private static DelegateBridge __Hotfix0_set_shopId; // 0x10
	private static DelegateBridge __Hotfix0_get_shopIcon; // 0x18
	private static DelegateBridge __Hotfix0_set_shopIcon; // 0x20
	private static DelegateBridge __Hotfix0_get_isSelfShop; // 0x28
	private static DelegateBridge __Hotfix0_set_isSelfShop; // 0x30
	private static DelegateBridge __Hotfix0_get_strategy; // 0x38
	private static DelegateBridge __Hotfix0_set_strategy; // 0x40
	private static DelegateBridge __Hotfix0_get_purchaseCost; // 0x48
	private static DelegateBridge __Hotfix0_set_purchaseCost; // 0x50
	private static DelegateBridge __Hotfix0_get_purchaseCount; // 0x58
	private static DelegateBridge __Hotfix0_set_purchaseCount; // 0x60
	private static DelegateBridge __Hotfix0_get_sortId; // 0x68
	private static DelegateBridge __Hotfix0_set_sortId; // 0x70
	private static DelegateBridge __Hotfix0_get_isEmptyShop; // 0x78
	private static DelegateBridge __Hotfix0_set_isEmptyShop; // 0x80
	private static DelegateBridge __Hotfix0_get_index; // 0x88
	private static DelegateBridge __Hotfix0_set_index; // 0x90
	private static DelegateBridge __Hotfix0_get_sliderPercent; // 0x98
	private static DelegateBridge __Hotfix0_set_sliderPercent; // 0xa0
	private static DelegateBridge __Hotfix0_LoadData; // 0xa8
	private static DelegateBridge __Hotfix0_RefreshData; // 0xb0
	private static DelegateBridge __Hotfix0_GetPurchaseTotalCost; // 0xb8
	private static DelegateBridge __Hotfix0_CompareTo; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public String shopId { get; set; }
	public String shopIcon { get; set; }
	public Boolean isSelfShop { get; set; }
	public String strategy { get; set; }
	public Int32 purchaseCost { get; set; }
	public Int32 purchaseCount { get; set; }
	public Int32 sortId { get; set; }
	public Boolean isEmptyShop { get; set; }
	public Int32 index { get; set; }
	public Single sliderPercent { get; set; }

	// RVA: 0x2896134 VA: 0x7594eae134
	public String get_shopId() { }
	// RVA: 0x28961ac VA: 0x7594eae1ac
	private Void set_shopId(String value) { }
	// RVA: 0x2894f74 VA: 0x7594eacf74
	public String get_shopIcon() { }
	// RVA: 0x2896240 VA: 0x7594eae240
	private Void set_shopIcon(String value) { }
	// RVA: 0x2894efc VA: 0x7594eacefc
	public Boolean get_isSelfShop() { }
	// RVA: 0x28962d4 VA: 0x7594eae2d4
	private Void set_isSelfShop(Boolean value) { }
	// RVA: 0x2894e0c VA: 0x7594eace0c
	public String get_strategy() { }
	// RVA: 0x2896364 VA: 0x7594eae364
	private Void set_strategy(String value) { }
	// RVA: 0x2894e84 VA: 0x7594eace84
	public Int32 get_purchaseCost() { }
	// RVA: 0x28963f8 VA: 0x7594eae3f8
	private Void set_purchaseCost(Int32 value) { }
	// RVA: 0x289513c VA: 0x7594ead13c
	public Int32 get_purchaseCount() { }
	// RVA: 0x2896484 VA: 0x7594eae484
	private Void set_purchaseCount(Int32 value) { }
	// RVA: 0x2896510 VA: 0x7594eae510
	public Int32 get_sortId() { }
	// RVA: 0x2896588 VA: 0x7594eae588
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2894d94 VA: 0x7594eacd94
	public Boolean get_isEmptyShop() { }
	// RVA: 0x2896614 VA: 0x7594eae614
	private Void set_isEmptyShop(Boolean value) { }
	// RVA: 0x28966a4 VA: 0x7594eae6a4
	public Int32 get_index() { }
	// RVA: 0x289671c VA: 0x7594eae71c
	private Void set_index(Int32 value) { }
	// RVA: 0x28951b4 VA: 0x7594ead1b4
	public Single get_sliderPercent() { }
	// RVA: 0x28967a8 VA: 0x7594eae7a8
	private Void set_sliderPercent(Single value) { }
	// RVA: 0x2896834 VA: 0x7594eae834
	public Void LoadData(Act27SideShopData shopData, String strategy, Int32 perCost, Int32 count, Boolean isSelfShop) { }
	// RVA: 0x2896978 VA: 0x7594eae978
	public Void RefreshData(Int32 index, Single sliderPercent) { }
	// RVA: 0x2896a48 VA: 0x7594eaea48
	public Int32 GetPurchaseTotalCost() { }
	// RVA: 0x2896ad4 VA: 0x7594eaead4
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2896c14 VA: 0x7594eaec14
	public Void .ctor() { }
	// RVA: 0x2896c94 VA: 0x7594eaec94
	private static Void .cctor() { }
}
```