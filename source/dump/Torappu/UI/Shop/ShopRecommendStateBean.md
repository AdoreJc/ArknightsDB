# ShopRecommendStateBean

**Namespace:** `Torappu.UI.Shop`


## Methods

- `Void InitData(Int64)`

- `Void RefreshData()`

- `ShopRecommendViewModel GetViewModelByKey(String)`

- `Boolean _CheckIfForbidden(List`1, ShopRecommendItem)`

- `Boolean _GetViewModel(ShopRecommendViewModel, Dictionary`2, out)`

- `ShopPurchaseState LoadGoodsForPurchaseState()`

- `Boolean CheckShopItemAvailAble(ShopRecommendData)`

- `Int32 <RefreshData>b__8_0(KeyValuePair`2, KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendStateBean : PageSingleComponent, IStateBean, IHotfixable
{
	public List`1 onShowList; // 0x20
	public List`1 shopKeeperClickWords; // 0x28
	public List`1 shopKeeperWelcomeWords; // 0x30
	public List`1 viewModelList; // 0x38
	public Dictionary`2 templateList; // 0x40
	public Dictionary`2 resultList; // 0x48
	private static readonly Dictionary`2 s_templateTypeDict; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge __Hotfix0_GetViewModelByKey; // 0x18
	private static DelegateBridge __Hotfix0_GetImgListByKey; // 0x20
	private static DelegateBridge __Hotfix0__CheckFurnGroupState; // 0x28
	private static DelegateBridge __Hotfix0__CheckSkinFurnLockState; // 0x30
	private static DelegateBridge __Hotfix0__CheckAvail; // 0x38
	private static DelegateBridge __Hotfix0__CheckIfForbidden; // 0x40
	private static DelegateBridge __Hotfix0__CheckIfCondTrigGPAvail; // 0x48
	private static DelegateBridge __Hotfix0__GetViewModel; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfGoodAvailable; // 0x58
	private static DelegateBridge __Hotfix0_CheckIfGoodUnlock; // 0x60
	private static DelegateBridge __Hotfix0_LoadGoodsForPurchaseState; // 0x68
	private static DelegateBridge __Hotfix0_CheckShopItemAvailAble; // 0x70
	private static DelegateBridge __Hotfix0_GetGoodListFromPurchaseState; // 0x78
	private static DelegateBridge __Hotfix0_CheckAvailableImageList; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x245b674 VA: 0x7594a73674
	public Void InitData(Int64 curTs) { }
	// RVA: 0x245bedc VA: 0x7594a73edc
	public Void RefreshData() { }
	// RVA: 0x245cde4 VA: 0x7594a74de4
	public ShopRecommendViewModel GetViewModelByKey(String tagId) { }
	// RVA: 0x245cf08 VA: 0x7594a74f08
	public List`1 GetImgListByKey(String tagId) { }
	// RVA: 0x245d078 VA: 0x7594a75078
	private static Boolean _CheckFurnGroupState(String furnGroup) { }
	// RVA: 0x245d174 VA: 0x7594a75174
	private static Boolean _CheckSkinFurnLockState(String goodId) { }
	// RVA: 0x245d290 VA: 0x7594a75290
	private static Boolean _CheckAvail(ShopRouteTarget shopType, String param1, String skinId, String furnId, Dictionary`2 unlockType) { }
	// RVA: 0x245bb28 VA: 0x7594a73b28
	private Boolean _CheckIfForbidden(List`1 forbiddenIds, ShopRecommendItem recommendItem) { }
	// RVA: 0x245d5c8 VA: 0x7594a755c8
	private static Boolean _CheckIfCondTrigGPAvail(ShopClientGPData gpData) { }
	// RVA: 0x245c4b0 VA: 0x7594a744b0
	private Boolean _GetViewModel(ShopRecommendViewModel viewModel, Dictionary`2 unlockType, out List`1 showResult) { }
	// RVA: 0x245d7d8 VA: 0x7594a757d8
	public static Boolean CheckIfGoodAvailable(ShopRouteTarget shopType, String param1, String skinId, String furnId, Dictionary`2 unlockType) { }
	// RVA: 0x245d8a8 VA: 0x7594a758a8
	public static Boolean CheckIfGoodUnlock(String goodId) { }
	// RVA: 0x245d930 VA: 0x7594a75930
	public ShopPurchaseState LoadGoodsForPurchaseState() { }
	// RVA: 0x245dca8 VA: 0x7594a75ca8
	private Boolean CheckShopItemAvailAble(ShopRecommendData data) { }
	// RVA: 0x245dba8 VA: 0x7594a75ba8
	public static List`1 GetGoodListFromPurchaseState(ShopPurchaseState purchaseState, ShopRouteTarget target) { }
	// RVA: 0x245bc44 VA: 0x7594a73c44
	public Dictionary`2 CheckAvailableImageList(ShopRecommendItem closureItem) { }
	// RVA: 0x245dd34 VA: 0x7594a75d34
	public Void .ctor() { }
	// RVA: 0x245df2c VA: 0x7594a75f2c
	private static Void .cctor() { }
	// RVA: 0x245e0e8 VA: 0x7594a760e8
	private Int32 <RefreshData>b__8_0(KeyValuePair`2 a, KeyValuePair`2 b) { }
}
```