# GroceryOrderViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String <actId>k__BackingField`

- `Int32 <curRemainInquireCount>k__BackingField`

- `Int32 <maxInquireCount>k__BackingField`

- `Boolean <hasInquireTime>k__BackingField`

- `Int32 <drinkBuyerCount>k__BackingField`

- `Int32 <foodBuyerCount>k__BackingField`

- `Int32 <coinBuyerCount>k__BackingField`

- `String <cachedGoodId>k__BackingField`

- `String m_groupId`

- `String m_myShopId`

- `Int32 m_strateyMaxCount`


## Properties

- `String actId`

- `Int32 curRemainInquireCount`

- `Int32 maxInquireCount`

- `Boolean hasInquireTime`

- `Int32 drinkBuyerCount`

- `Int32 foodBuyerCount`

- `Int32 coinBuyerCount`

- `String cachedGoodId`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `Int32 get_curRemainInquireCount()`

- `Void set_curRemainInquireCount(Int32)`

- `Int32 get_maxInquireCount()`

- `Void set_maxInquireCount(Int32)`

- `Boolean get_hasInquireTime()`

- `Void set_hasInquireTime(Boolean)`

- `Int32 get_drinkBuyerCount()`

- `Void set_drinkBuyerCount(Int32)`

- `Int32 get_foodBuyerCount()`

- `Void set_foodBuyerCount(Int32)`

- `Int32 get_coinBuyerCount()`

- `Void set_coinBuyerCount(Int32)`

- `String get_cachedGoodId()`

- `Void set_cachedGoodId(String)`

- `Void LoadData(String)`

- `Boolean IsShopCanInquire(String, String)`

- `Boolean RefreshMyShopCurSelectStrategy(String, Int32)`

- `Boolean InquireOtherShop(String)`

- `Boolean GetGoodsStrategyIdList(out)`

- `Void _LoadGoodItems(Act27SideGoodLaunchData, Act27SideData, PlayerAct27SideActivity)`

- `Void _RefreshBuyerCounts(Act27SideGoodLaunchData, Dictionary`2)`

- `Int32 _TryGetBuyerCount(String, Dictionary`2)`

- `Void _LoadGoodItemData(String, Act27SideData, PlayerAct27SideActivity)`

- `Void _LoadMyStrategyBriefs(Act27SideGoodLaunchData, Dictionary`2, List`1)`

- `String _TryGetGoodDescById(String, Dictionary`2)`

- `GroceryOrderGoodItemViewModel _TryGetGoodItem(String)`

- `Void _RefreshInquireLeftCount()`

- `Boolean _RefreshGoodCurSelectStrategy(String, Int32)`

- `Void _RefreshMyStrategyBriefInfo(String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderViewModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	private Int32 <curRemainInquireCount>k__BackingField; // 0x18
	private Int32 <maxInquireCount>k__BackingField; // 0x1c
	private Boolean <hasInquireTime>k__BackingField; // 0x20
	private Int32 <drinkBuyerCount>k__BackingField; // 0x24
	private Int32 <foodBuyerCount>k__BackingField; // 0x28
	private Int32 <coinBuyerCount>k__BackingField; // 0x2c
	private String <cachedGoodId>k__BackingField; // 0x30
	private String m_groupId; // 0x38
	private String m_myShopId; // 0x40
	private Int32 m_strateyMaxCount; // 0x48
	private List`1 m_goodItemViewModels; // 0x50
	private List`1 m_myStrategyBriefViewModels; // 0x58
	public const Int32 STRATEGY_TYPE_COUNT; // 0x0
	public const Int32 DEFAULT_STRATEGY_INDEX; // 0x0
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_curRemainInquireCount; // 0x10
	private static DelegateBridge __Hotfix0_set_curRemainInquireCount; // 0x18
	private static DelegateBridge __Hotfix0_get_maxInquireCount; // 0x20
	private static DelegateBridge __Hotfix0_set_maxInquireCount; // 0x28
	private static DelegateBridge __Hotfix0_get_hasInquireTime; // 0x30
	private static DelegateBridge __Hotfix0_set_hasInquireTime; // 0x38
	private static DelegateBridge __Hotfix0_get_drinkBuyerCount; // 0x40
	private static DelegateBridge __Hotfix0_set_drinkBuyerCount; // 0x48
	private static DelegateBridge __Hotfix0_get_foodBuyerCount; // 0x50
	private static DelegateBridge __Hotfix0_set_foodBuyerCount; // 0x58
	private static DelegateBridge __Hotfix0_get_coinBuyerCount; // 0x60
	private static DelegateBridge __Hotfix0_set_coinBuyerCount; // 0x68
	private static DelegateBridge __Hotfix0_get_cachedGoodId; // 0x70
	private static DelegateBridge __Hotfix0_set_cachedGoodId; // 0x78
	private static DelegateBridge __Hotfix0_get_goodItemViewModels; // 0x80
	private static DelegateBridge __Hotfix0_get_myStrategyBriefViewModels; // 0x88
	private static DelegateBridge __Hotfix0_LoadData; // 0x90
	private static DelegateBridge __Hotfix0_IsShopCanInquire; // 0x98
	private static DelegateBridge __Hotfix0_RefreshMyShopCurSelectStrategy; // 0xa0
	private static DelegateBridge __Hotfix0_InquireOtherShop; // 0xa8
	private static DelegateBridge __Hotfix0_GetGoodsStrategyIdList; // 0xb0
	private static DelegateBridge __Hotfix0__LoadGoodItems; // 0xb8
	private static DelegateBridge __Hotfix0__RefreshBuyerCounts; // 0xc0
	private static DelegateBridge __Hotfix0__TryGetBuyerCount; // 0xc8
	private static DelegateBridge __Hotfix0__LoadGoodItemData; // 0xd0
	private static DelegateBridge __Hotfix0__LoadMyStrategyBriefs; // 0xd8
	private static DelegateBridge __Hotfix0__TryGetGoodDescById; // 0xe0
	private static DelegateBridge __Hotfix0__TryGetGoodItem; // 0xe8
	private static DelegateBridge __Hotfix0__RefreshInquireLeftCount; // 0xf0
	private static DelegateBridge __Hotfix0__RefreshGoodCurSelectStrategy; // 0xf8
	private static DelegateBridge __Hotfix0__RefreshMyStrategyBriefInfo; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public String actId { get; set; }
	public Int32 curRemainInquireCount { get; set; }
	public Int32 maxInquireCount { get; set; }
	public Boolean hasInquireTime { get; set; }
	public Int32 drinkBuyerCount { get; set; }
	public Int32 foodBuyerCount { get; set; }
	public Int32 coinBuyerCount { get; set; }
	public String cachedGoodId { get; set; }
	public List`1 goodItemViewModels { get; }
	public List`1 myStrategyBriefViewModels { get; }

	// RVA: 0x288b6c8 VA: 0x7594ea36c8
	public String get_actId() { }
	// RVA: 0x28928a8 VA: 0x7594eaa8a8
	private Void set_actId(String value) { }
	// RVA: 0x288dce0 VA: 0x7594ea5ce0
	public Int32 get_curRemainInquireCount() { }
	// RVA: 0x289292c VA: 0x7594eaa92c
	private Void set_curRemainInquireCount(Int32 value) { }
	// RVA: 0x288dd48 VA: 0x7594ea5d48
	public Int32 get_maxInquireCount() { }
	// RVA: 0x28929a8 VA: 0x7594eaa9a8
	private Void set_maxInquireCount(Int32 value) { }
	// RVA: 0x288b730 VA: 0x7594ea3730
	public Boolean get_hasInquireTime() { }
	// RVA: 0x2892a24 VA: 0x7594eaaa24
	private Void set_hasInquireTime(Boolean value) { }
	// RVA: 0x288ddb0 VA: 0x7594ea5db0
	public Int32 get_drinkBuyerCount() { }
	// RVA: 0x2892aa4 VA: 0x7594eaaaa4
	private Void set_drinkBuyerCount(Int32 value) { }
	// RVA: 0x288de18 VA: 0x7594ea5e18
	public Int32 get_foodBuyerCount() { }
	// RVA: 0x2892b20 VA: 0x7594eaab20
	private Void set_foodBuyerCount(Int32 value) { }
	// RVA: 0x288de80 VA: 0x7594ea5e80
	public Int32 get_coinBuyerCount() { }
	// RVA: 0x2892b9c VA: 0x7594eaab9c
	private Void set_coinBuyerCount(Int32 value) { }
	// RVA: 0x288e5dc VA: 0x7594ea65dc
	public String get_cachedGoodId() { }
	// RVA: 0x2892c18 VA: 0x7594eaac18
	private Void set_cachedGoodId(String value) { }
	// RVA: 0x288e39c VA: 0x7594ea639c
	public List`1 get_goodItemViewModels() { }
	// RVA: 0x288e6e4 VA: 0x7594ea66e4
	public List`1 get_myStrategyBriefViewModels() { }
	// RVA: 0x288a7d4 VA: 0x7594ea27d4
	public Void LoadData(String activityId) { }
	// RVA: 0x288b9fc VA: 0x7594ea39fc
	public Boolean IsShopCanInquire(String goodId, String shopId) { }
	// RVA: 0x288be38 VA: 0x7594ea3e38
	public Boolean RefreshMyShopCurSelectStrategy(String goodId, Int32 strategyIndex) { }
	// RVA: 0x288ceec VA: 0x7594ea4eec
	public Boolean InquireOtherShop(String goodId) { }
	// RVA: 0x288bf14 VA: 0x7594ea3f14
	public Boolean GetGoodsStrategyIdList(out List`1 result) { }
	// RVA: 0x2892c9c VA: 0x7594eaac9c
	private Void _LoadGoodItems(Act27SideGoodLaunchData launchData, Act27SideData actData, PlayerAct27SideActivity playerActivity) { }
	// RVA: 0x2893098 VA: 0x7594eab098
	private Void _RefreshBuyerCounts(Act27SideGoodLaunchData launchData, Dictionary`2 buyers) { }
	// RVA: 0x2893848 VA: 0x7594eab848
	private Int32 _TryGetBuyerCount(String goodId, Dictionary`2 buyers) { }
	// RVA: 0x28936bc VA: 0x7594eab6bc
	private Void _LoadGoodItemData(String goodId, Act27SideData actData, PlayerAct27SideActivity playerAct27SideActivity) { }
	// RVA: 0x2892d80 VA: 0x7594eaad80
	private Void _LoadMyStrategyBriefs(Act27SideGoodLaunchData launchData, Dictionary`2 goodDataMap, List`1 purchasePriceName) { }
	// RVA: 0x289393c VA: 0x7594eab93c
	private String _TryGetGoodDescById(String goodId, Dictionary`2 goodDataMap) { }
	// RVA: 0x28931a0 VA: 0x7594eab1a0
	private GroceryOrderGoodItemViewModel _TryGetGoodItem(String goodId) { }
	// RVA: 0x28934d4 VA: 0x7594eab4d4
	private Void _RefreshInquireLeftCount() { }
	// RVA: 0x28932c8 VA: 0x7594eab2c8
	private Boolean _RefreshGoodCurSelectStrategy(String goodId, Int32 strategyIndex) { }
	// RVA: 0x289336c VA: 0x7594eab36c
	private Void _RefreshMyStrategyBriefInfo(String goodId, Int32 strategyIndex) { }
	// RVA: 0x2893a54 VA: 0x7594eaba54
	public Void .ctor() { }
}
```