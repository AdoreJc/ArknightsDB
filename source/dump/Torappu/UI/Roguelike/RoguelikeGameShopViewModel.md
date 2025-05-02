# RoguelikeGameShopViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Boolean m_hasBoss`

- `Boolean m_canBattle`

- `Boolean m_canRecycle`

- `Int32 m_recycleCount`

- `RoguelikeGameShopViewModelPlugin m_modelPlugin`


## Properties

- `Boolean canRefresh`

- `Boolean showRefreshBtn`

- `String refreshConfirmTips`

- `Int32 goodsCnt`

- `Boolean canBattle`

- `Boolean canRecycle`

- `Int32 recycleCount`


## Methods

- `Boolean get_canRefresh()`

- `Boolean get_showRefreshBtn()`

- `String get_refreshConfirmTips()`

- `Int32 get_goodsCnt()`

- `Boolean get_canBattle()`

- `Boolean get_canRecycle()`

- `Int32 get_recycleCount()`

- `Void LoadData(String, ShopContent, CurrentData)`

- `Void InjectPlugin(RoguelikeGameShopViewModelPlugin)`

- `Void OnLockSlotClicked(RoguelikeGoodsViewModel)`

- `Void OnShopRefreshed(RoguelikeShopStateBean)`

- `Boolean GetRefreshCantToast(out)`

- `Void _InitBaseInfos(ShopContent)`

- `Void _InitSellGoodsList(String, ShopContent, CurrentData)`

- `Void _InitSellGoodItem(String, ShopContent, CurrentData, Boolean)`

- `Boolean _InitBankItem(String, ShopContent)`

- `Void _InitLockSlotItem(String, Boolean)`

- `Void _SortGoodsList(List`1)`

- `Void _InitRecycleGoodsList(String, ShopContent)`

- `Void _InitRecycleGoodItem(String, ShopContent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameShopViewModel : IHotfixable
{
	private static readonly Dictionary`2 TYPE_ITEM_SORT_PRIORITY; // 0x0
	private static readonly Dictionary`2 TYPE_GOODS_PRIORITY; // 0x8
	public List`1 sellGoods; // 0x10
	private Boolean m_hasBoss; // 0x18
	private Boolean m_canBattle; // 0x19
	public List`1 recycleGoods; // 0x20
	private Boolean m_canRecycle; // 0x28
	private Int32 m_recycleCount; // 0x2c
	private RoguelikeGameShopViewModelPlugin m_modelPlugin; // 0x30
	private static DelegateBridge __Hotfix0_get_canRefresh; // 0x10
	private static DelegateBridge __Hotfix0_get_showRefreshBtn; // 0x18
	private static DelegateBridge __Hotfix0_get_refreshConfirmTips; // 0x20
	private static DelegateBridge __Hotfix0_get_goodsCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_canBattle; // 0x30
	private static DelegateBridge __Hotfix0_get_canRecycle; // 0x38
	private static DelegateBridge __Hotfix0_get_recycleCount; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x50
	private static DelegateBridge __Hotfix0_OnLockSlotClicked; // 0x58
	private static DelegateBridge __Hotfix0_OnShopRefreshed; // 0x60
	private static DelegateBridge __Hotfix0_GetRefreshCantToast; // 0x68
	private static DelegateBridge __Hotfix0__InitBaseInfos; // 0x70
	private static DelegateBridge __Hotfix0__InitSellGoodsList; // 0x78
	private static DelegateBridge __Hotfix0__InitSellGoodItem; // 0x80
	private static DelegateBridge __Hotfix0__InitBankItem; // 0x88
	private static DelegateBridge __Hotfix0__InitLockSlotItem; // 0x90
	private static DelegateBridge __Hotfix0__SortGoodsList; // 0x98
	private static DelegateBridge __Hotfix0__InitRecycleGoodsList; // 0xa0
	private static DelegateBridge __Hotfix0__InitRecycleGoodItem; // 0xa8
	private static DelegateBridge __Hotfix0_CompareGoods; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public Boolean canRefresh { get; }
	public Boolean showRefreshBtn { get; }
	public String refreshConfirmTips { get; }
	public Int32 goodsCnt { get; }
	public Boolean canBattle { get; }
	public Boolean canRecycle { get; }
	public Int32 recycleCount { get; }

	// RVA: 0x2ad75cc VA: 0x75950ef5cc
	public Boolean get_canRefresh() { }
	// RVA: 0x2ae2234 VA: 0x75950fa234
	public Boolean get_showRefreshBtn() { }
	// RVA: 0x2ad828c VA: 0x75950f028c
	public String get_refreshConfirmTips() { }
	// RVA: 0x2ae22c4 VA: 0x75950fa2c4
	public Int32 get_goodsCnt() { }
	// RVA: 0x2ad78a8 VA: 0x75950ef8a8
	public Boolean get_canBattle() { }
	// RVA: 0x2ad8c94 VA: 0x75950f0c94
	public Boolean get_canRecycle() { }
	// RVA: 0x2ae2354 VA: 0x75950fa354
	public Int32 get_recycleCount() { }
	// RVA: 0x2ae23cc VA: 0x75950fa3cc
	public Void LoadData(String topicId, ShopContent shopPlayerData, CurrentData current) { }
	// RVA: 0x2ae28bc VA: 0x75950fa8bc
	public Void InjectPlugin(RoguelikeGameShopViewModelPlugin modelPlugin) { }
	// RVA: 0x2ad730c VA: 0x75950ef30c
	public Void OnLockSlotClicked(RoguelikeGoodsViewModel goodsViewModel) { }
	// RVA: 0x2ad7730 VA: 0x75950ef730
	public Void OnShopRefreshed(RoguelikeShopStateBean stateBean) { }
	// RVA: 0x2ad81cc VA: 0x75950f01cc
	public Boolean GetRefreshCantToast(out String cantToast) { }
	// RVA: 0x2ae24bc VA: 0x75950fa4bc
	private Void _InitBaseInfos(ShopContent shopPlayerData) { }
	// RVA: 0x2ae2570 VA: 0x75950fa570
	private Void _InitSellGoodsList(String topicId, ShopContent shopPlayerData, CurrentData current) { }
	// RVA: 0x2ae2ad4 VA: 0x75950faad4
	private Void _InitSellGoodItem(String topicId, ShopContent shopPlayerData, CurrentData current, Boolean isBankOpen) { }
	// RVA: 0x2ae2950 VA: 0x75950fa950
	private Boolean _InitBankItem(String topicId, ShopContent shopPlayerData) { }
	// RVA: 0x2ae2e54 VA: 0x75950fae54
	private Void _InitLockSlotItem(String topicId, Boolean isBankOpen) { }
	// RVA: 0x2ae2fec VA: 0x75950fafec
	private Void _SortGoodsList(List`1 list) { }
	// RVA: 0x2ae26bc VA: 0x75950fa6bc
	private Void _InitRecycleGoodsList(String topicId, ShopContent shopPlayerData) { }
	// RVA: 0x2ae3210 VA: 0x75950fb210
	private Void _InitRecycleGoodItem(String topicId, ShopContent shopPlayerData) { }
	// RVA: 0x2ae35c0 VA: 0x75950fb5c0
	public static Int32 CompareGoods(RoguelikeGoodsViewModel lhs, RoguelikeGoodsViewModel rhs) { }
	// RVA: 0x2ae3690 VA: 0x75950fb690
	public Void .ctor() { }
	// RVA: 0x2ae3798 VA: 0x75950fb798
	private static Void .cctor() { }
}
```