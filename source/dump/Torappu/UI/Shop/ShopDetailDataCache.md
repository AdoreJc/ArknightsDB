# ShopDetailDataCache

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ResourceBarViewProperty _resourceBarProperty`

- `LMTGSResourceBar _lmtgsResBar`

- `StateEngine _stateEngine`

- `DetailCommonViewModel m_detailItem`

- `FurnGroupViewModel m_furnGroup`

- `UIExclusiveCoroutineInPage m_host`

- `Boolean m_isDetailTransiting`


## Methods

- `UIExclusiveCoroutineInPage _EnsureHost()`

- `Void ApplyResourceShopType(ShopType)`

- `Void ApplyQCShopType(QCShopDetailShopEnum)`

- `Void ApplyCreditUnlockState()`

- `Void _StateEngineAddDetailSecured()`

- `IEnumerator _WaitForAddTopCoroutine()`

- `Boolean _DetailLayerAddTop()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailDataCache : PageSingleComponent, IDataBindWrapper, IPlayerDataListener, IHotfixable
{
	private ResourceBarViewProperty _resourceBarProperty; // 0x20
	private LMTGSResourceBar _lmtgsResBar; // 0x28
	private StateEngine _stateEngine; // 0x30
	private DetailCommonViewModel m_detailItem; // 0x38
	private FurnGroupViewModel m_furnGroup; // 0x40
	private UIExclusiveCoroutineInPage m_host; // 0x48
	private Boolean m_isDetailTransiting; // 0x50
	private static DelegateBridge __Hotfix0__EnsureHost; // 0x0
	private static DelegateBridge __Hotfix0_get_detailItem; // 0x8
	private static DelegateBridge __Hotfix0_get_furnGroup; // 0x10
	private static DelegateBridge __Hotfix0_ApplyLMTGSItem; // 0x18
	private static DelegateBridge __Hotfix0_ApplyEPGSItem; // 0x20
	private static DelegateBridge __Hotfix0_ApplyREPItem; // 0x28
	private static DelegateBridge __Hotfix0_ApplyDetailItem; // 0x30
	private static DelegateBridge __Hotfix1_ApplyDetailItem; // 0x38
	private static DelegateBridge __Hotfix0_ApplyQCExtraItem; // 0x40
	private static DelegateBridge __Hotfix0__ApplyGPDetailItem; // 0x48
	private static DelegateBridge __Hotfix0_ApplyDetailItemChoose; // 0x50
	private static DelegateBridge __Hotfix2_ApplyDetailItem; // 0x58
	private static DelegateBridge __Hotfix3_ApplyDetailItem; // 0x60
	private static DelegateBridge __Hotfix4_ApplyDetailItem; // 0x68
	private static DelegateBridge __Hotfix5_ApplyDetailItem; // 0x70
	private static DelegateBridge __Hotfix6_ApplyDetailItem; // 0x78
	private static DelegateBridge __Hotfix7_ApplyDetailItem; // 0x80
	private static DelegateBridge __Hotfix0_ReturnItemByType; // 0x88
	private static DelegateBridge __Hotfix0_ApplyResourceShopType; // 0x90
	private static DelegateBridge __Hotfix0_ApplyQCShopType; // 0x98
	private static DelegateBridge __Hotfix0_GetResourceShowType; // 0xa0
	private static DelegateBridge __Hotfix1_GetResourceShowType; // 0xa8
	private static DelegateBridge __Hotfix0_ApplyCreditUnlockState; // 0xb0
	private static DelegateBridge __Hotfix0_GetShopBuyCount; // 0xb8
	private static DelegateBridge __Hotfix0__StateEngineAddDetailSecured; // 0xc0
	private static DelegateBridge __Hotfix0__WaitForAddTopCoroutine; // 0xc8
	private static DelegateBridge __Hotfix0__DetailLayerAddTop; // 0xd0
	private static DelegateBridge __Hotfix0__SingleCompOnShopPage; // 0xd8
	private static DelegateBridge __Hotfix0_OnCreate; // 0xe0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xe8
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0xf0
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	public static DetailCommonViewModel detailItem { get; }
	public static FurnGroupViewModel furnGroup { get; }

	// RVA: 0x2432590 VA: 0x7594a4a590
	private UIExclusiveCoroutineInPage _EnsureHost() { }
	// RVA: 0x2431894 VA: 0x7594a49894
	public static DetailCommonViewModel get_detailItem() { }
	// RVA: 0x242cbd4 VA: 0x7594a44bd4
	public static FurnGroupViewModel get_furnGroup() { }
	// RVA: 0x24326d8 VA: 0x7594a4a6d8
	public static Void ApplyLMTGSItem(LMTGSViewModel limitViewModel) { }
	// RVA: 0x24328fc VA: 0x7594a4a8fc
	public static Void ApplyEPGSItem(EPGSViewModel epGSViewModel) { }
	// RVA: 0x2432afc VA: 0x7594a4aafc
	public static Void ApplyREPItem(QCShopREPGood repViewModel) { }
	// RVA: 0x2432d0c VA: 0x7594a4ad0c
	public static Void ApplyDetailItem(ShopDetailPriceType priceType, QCCommonObj obj) { }
	// RVA: 0x2433274 VA: 0x7594a4b274
	public static Void ApplyDetailItem(ShopDetailPriceType priceType, QCShopObjProgressViewModel item) { }
	// RVA: 0x24335fc VA: 0x7594a4b5fc
	public static Void ApplyQCExtraItem(ShopDetailPriceType priceType, QCShopExtraObj obj) { }
	// RVA: 0x2433afc VA: 0x7594a4bafc
	private static Void _ApplyGPDetailItem(ShopType shopType, ShopDetailPriceType priceType, NormalGPItem item, PlayerGoodItemData playerInfo, Int64 endTime) { }
	// RVA: 0x2433d34 VA: 0x7594a4bd34
	public static Void ApplyDetailItemChoose(ShopType shopType, ShopDetailPriceType priceType, ChooseGPItem item, ShopGPCommonItemViewModel itemModel, Int64 endTime) { }
	// RVA: 0x2433fe0 VA: 0x7594a4bfe0
	public static Void ApplyDetailItem(ShopGPCondTrigItemViewModel itemModel) { }
	// RVA: 0x2434288 VA: 0x7594a4c288
	public static Void ApplyDetailItem(ShopType shopType, ShopDetailPriceType priceType, NormalGPItem item, PlayerGoodItemData playerInfo, Int64 endTime) { }
	// RVA: 0x24343b8 VA: 0x7594a4c3b8
	public static Void ApplyDetailItem(ShopGPMonthlySubItemViewModel subItem) { }
	// RVA: 0x24345c0 VA: 0x7594a4c5c0
	public static Void ApplyDetailItem(FurnGroupViewModel viewModel) { }
	// RVA: 0x2434714 VA: 0x7594a4c714
	public static Void ApplyDetailItem(Good good) { }
	// RVA: 0x2434a38 VA: 0x7594a4ca38
	public static Void ApplyDetailItem(ShopCreditViewModel viewModel) { }
	// RVA: 0x242b608 VA: 0x7594a43608
	public static UIItemViewModel ReturnItemByType(ShopDetailPriceType priceType) { }
	// RVA: 0x2434e04 VA: 0x7594a4ce04
	public Void ApplyResourceShopType(ShopType shopType) { }
	// RVA: 0x2434ee4 VA: 0x7594a4cee4
	public Void ApplyQCShopType(QCShopDetailShopEnum type) { }
	// RVA: 0x2434fd8 VA: 0x7594a4cfd8
	public static ResourceBarViewModel GetResourceShowType(QCShopDetailShopEnum type) { }
	// RVA: 0x24334b8 VA: 0x7594a4b4b8
	public static ResourceBarViewModel GetResourceShowType(ShopType shopType) { }
	// RVA: 0x24350dc VA: 0x7594a4d0dc
	public Void ApplyCreditUnlockState() { }
	// RVA: 0x243515c VA: 0x7594a4d15c
	public static Int32 GetShopBuyCount(ShopRouteTarget shopType, String goodId) { }
	// RVA: 0x VA: 0x0
	private Void _StateEngineAddDetailSecured() { }
	// RVA: 0x VA: 0x0
	private IEnumerator _WaitForAddTopCoroutine() { }
	// RVA: 0x VA: 0x0
	private Boolean _DetailLayerAddTop() { }
	// RVA: 0x2432648 VA: 0x7594a4a648
	private static ShopDetailDataCache _SingleCompOnShopPage() { }
	// RVA: 0x2435978 VA: 0x7594a4d978
	protected override Void OnCreate() { }
	// RVA: 0x24359f0 VA: 0x7594a4d9f0
	protected override Void OnDestroy() { }
	// RVA: 0x2435a68 VA: 0x7594a4da68
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x2435b08 VA: 0x7594a4db08
	public Void OnPlayerDataChanged() { }
	// RVA: 0x2435bd0 VA: 0x7594a4dbd0
	public Void .ctor() { }
	// RVA: 0x2435c80 VA: 0x7594a4dc80
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2435c88 VA: 0x7594a4dc88
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```