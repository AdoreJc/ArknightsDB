# GroceryOrderGoodItemViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String <goodId>k__BackingField`

- `String <goodName>k__BackingField`

- `String <goodIconId>k__BackingField`

- `Int32 <buyerCount>k__BackingField`

- `Boolean m_isValid`

- `String m_actId`

- `Boolean m_hasInquireTimeLeft`

- `GroceryOrderSelfShopViewModel m_selfShopItemViewModel`


## Properties

- `String goodId`

- `String goodName`

- `String goodIconId`

- `Int32 buyerCount`

- `GroceryOrderSelfShopViewModel selfShopItemViewModel`


## Methods

- `String get_goodId()`

- `Void set_goodId(String)`

- `String get_goodName()`

- `Void set_goodName(String)`

- `String get_goodIconId()`

- `Void set_goodIconId(String)`

- `Int32 get_buyerCount()`

- `Void set_buyerCount(Int32)`

- `GroceryOrderSelfShopViewModel get_selfShopItemViewModel()`

- `Void LoadData(String, String, String, Act27SideData, PlayerAct27SideActivity)`

- `Boolean IsOtherShopCanInquire(String)`

- `GroceryOrderOtherShopStatus GetOtherShopInquireStatus(String)`

- `Void InquireOtherShop()`

- `Boolean RefreshMyShopStrategy(Int32)`

- `Void TryRefreshOtherShopIfCanInquire(InquireInfo)`

- `Void _LoadShopData(String, Act27SideGoodData, List`1, Dictionary`2)`

- `Void _RefreshPlayerData()`

- `Void _RefreshStrategyInfosFromPlayerData(PlayerAct27SideActivity)`

- `Void _RefreshPrePurchaseInfoList(Dictionary`2)`

- `Void _TryRefreshMyShopStock(Dictionary`2)`

- `Void _TryRefreshOtherShopStrategy(Dictionary`2)`

- `Void _TryRefreshOtherShopExpectedOrder()`

- `Void _TryRefreshMyShopExpectedOrder()`

- `GroceryOrderOtherShopItemViewModel _TryGetOtherShopItem(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderGoodItemViewModel : IHotfixable
{
	private String <goodId>k__BackingField; // 0x10
	private String <goodName>k__BackingField; // 0x18
	private String <goodIconId>k__BackingField; // 0x20
	private Int32 <buyerCount>k__BackingField; // 0x28
	private Boolean m_isValid; // 0x2c
	private String m_actId; // 0x30
	private Boolean m_hasInquireTimeLeft; // 0x38
	private List`1 m_otherShopItemViewModelList; // 0x40
	private GroceryOrderSelfShopViewModel m_selfShopItemViewModel; // 0x48
	private List`1 m_prePurchaseInfoList; // 0x50
	private static DelegateBridge __Hotfix0_get_goodId; // 0x0
	private static DelegateBridge __Hotfix0_set_goodId; // 0x8
	private static DelegateBridge __Hotfix0_get_goodName; // 0x10
	private static DelegateBridge __Hotfix0_set_goodName; // 0x18
	private static DelegateBridge __Hotfix0_get_goodIconId; // 0x20
	private static DelegateBridge __Hotfix0_set_goodIconId; // 0x28
	private static DelegateBridge __Hotfix0_get_buyerCount; // 0x30
	private static DelegateBridge __Hotfix0_set_buyerCount; // 0x38
	private static DelegateBridge __Hotfix0_get_otherShopItemViewModels; // 0x40
	private static DelegateBridge __Hotfix0_get_selfShopItemViewModel; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_IsOtherShopCanInquire; // 0x58
	private static DelegateBridge __Hotfix0_GetOtherShopInquireStatus; // 0x60
	private static DelegateBridge __Hotfix0_InquireOtherShop; // 0x68
	private static DelegateBridge __Hotfix0_RefreshMyShopStrategy; // 0x70
	private static DelegateBridge __Hotfix0_TryRefreshOtherShopIfCanInquire; // 0x78
	private static DelegateBridge __Hotfix0__LoadShopData; // 0x80
	private static DelegateBridge __Hotfix0__RefreshPlayerData; // 0x88
	private static DelegateBridge __Hotfix0__RefreshStrategyInfosFromPlayerData; // 0x90
	private static DelegateBridge __Hotfix0__RefreshPrePurchaseInfoList; // 0x98
	private static DelegateBridge __Hotfix0__TryRefreshMyShopStock; // 0xa0
	private static DelegateBridge __Hotfix0__TryRefreshOtherShopStrategy; // 0xa8
	private static DelegateBridge __Hotfix0__TryRefreshOtherShopExpectedOrder; // 0xb0
	private static DelegateBridge __Hotfix0__TryRefreshMyShopExpectedOrder; // 0xb8
	private static DelegateBridge __Hotfix0__TryGetExpectedOrderCountByMyStrategy; // 0xc0
	private static DelegateBridge __Hotfix0__TryGetOtherShopItem; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public String goodId { get; set; }
	public String goodName { get; set; }
	public String goodIconId { get; set; }
	public Int32 buyerCount { get; set; }
	public List`1 otherShopItemViewModels { get; }
	public GroceryOrderSelfShopViewModel selfShopItemViewModel { get; }

	// RVA: 0x288772c VA: 0x7594e9f72c
	public String get_goodId() { }
	// RVA: 0x2890b9c VA: 0x7594ea8b9c
	private Void set_goodId(String value) { }
	// RVA: 0x2887794 VA: 0x7594e9f794
	public String get_goodName() { }
	// RVA: 0x2890c20 VA: 0x7594ea8c20
	private Void set_goodName(String value) { }
	// RVA: 0x2887864 VA: 0x7594e9f864
	public String get_goodIconId() { }
	// RVA: 0x2890ca4 VA: 0x7594ea8ca4
	private Void set_goodIconId(String value) { }
	// RVA: 0x28877fc VA: 0x7594e9f7fc
	public Int32 get_buyerCount() { }
	// RVA: 0x2890d28 VA: 0x7594ea8d28
	private Void set_buyerCount(Int32 value) { }
	// RVA: 0x2887da8 VA: 0x7594e9fda8
	public List`1 get_otherShopItemViewModels() { }
	// RVA: 0x28878cc VA: 0x7594e9f8cc
	public GroceryOrderSelfShopViewModel get_selfShopItemViewModel() { }
	// RVA: 0x2890da4 VA: 0x7594ea8da4
	public Void LoadData(String actId, String playerShopId, String id, Act27SideData actData, PlayerAct27SideActivity playerAct27SideActivity) { }
	// RVA: 0x28914fc VA: 0x7594ea94fc
	public Boolean IsOtherShopCanInquire(String shopId) { }
	// RVA: 0x28915b0 VA: 0x7594ea95b0
	public GroceryOrderOtherShopStatus GetOtherShopInquireStatus(String shopId) { }
	// RVA: 0x289177c VA: 0x7594ea977c
	public Void InquireOtherShop() { }
	// RVA: 0x289181c VA: 0x7594ea981c
	public Boolean RefreshMyShopStrategy(Int32 strategyIndex) { }
	// RVA: 0x2891a34 VA: 0x7594ea9a34
	public Void TryRefreshOtherShopIfCanInquire(InquireInfo inquireInfo) { }
	// RVA: 0x2890f9c VA: 0x7594ea8f9c
	private Void _LoadShopData(String playerShopId, Act27SideGoodData goodData, List`1 strategyNameList, Dictionary`2 shopDataMap) { }
	// RVA: 0x2891380 VA: 0x7594ea9380
	private Void _RefreshPlayerData() { }
	// RVA: 0x289195c VA: 0x7594ea995c
	private Void _RefreshStrategyInfosFromPlayerData(PlayerAct27SideActivity playerActivity) { }
	// RVA: 0x2891b48 VA: 0x7594ea9b48
	private Void _RefreshPrePurchaseInfoList(Dictionary`2 prePurchaseDic) { }
	// RVA: 0x2891ca8 VA: 0x7594ea9ca8
	private Void _TryRefreshMyShopStock(Dictionary`2 stockDic) { }
	// RVA: 0x2891da8 VA: 0x7594ea9da8
	private Void _TryRefreshOtherShopStrategy(Dictionary`2 purchaseInfoDic) { }
	// RVA: 0x2891f24 VA: 0x7594ea9f24
	private Void _TryRefreshOtherShopExpectedOrder() { }
	// RVA: 0x2892054 VA: 0x7594eaa054
	private Void _TryRefreshMyShopExpectedOrder() { }
	// RVA: 0x2892108 VA: 0x7594eaa108
	private Int32[] _TryGetExpectedOrderCountByMyStrategy(Int32 strategyIndex, String shopId) { }
	// RVA: 0x2891648 VA: 0x7594ea9648
	private GroceryOrderOtherShopItemViewModel _TryGetOtherShopItem(String shopId) { }
	// RVA: 0x2892284 VA: 0x7594eaa284
	public Void .ctor() { }
}
```