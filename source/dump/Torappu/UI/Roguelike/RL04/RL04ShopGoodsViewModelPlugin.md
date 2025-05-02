# RL04ShopGoodsViewModelPlugin

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Boolean m_hasBoss`

- `Boolean m_hasRefreshBuffUnlock`


## Methods

- `Void _LoadFragments(String, ShopContent, CurrentData)`

- `Void _LoadFragment(String, Goods, RoguelikeTopicDetail, Dictionary`2, Dictionary`2)`

- `Boolean <>xLuaBaseProxy_get_canRefresh()`

- `Boolean <>xLuaBaseProxy_get_showRefreshBtn()`

- `String <>xLuaBaseProxy_get_refreshConfirmTips()`

- `Void <>xLuaBaseProxy_LoadData(String, ShopContent, CurrentData)`

- `Void <>xLuaBaseProxy_OnShopRefreshed(RoguelikeShopStateBean)`

- `Void <>xLuaBaseProxy_PostProcessRecycleGoods(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ShopGoodsViewModelPlugin : RoguelikeGameShopViewModelPlugin
{
	private Boolean m_hasBoss; // 0x11
	private Boolean m_hasRefreshBuffUnlock; // 0x12
	private readonly Dictionary`2 m_fragments; // 0x18
	private static DelegateBridge __Hotfix0_get_canRefresh; // 0x0
	private static DelegateBridge __Hotfix0_get_showRefreshBtn; // 0x8
	private static DelegateBridge __Hotfix0_get_preloadedRecycleGoods; // 0x10
	private static DelegateBridge __Hotfix0_get_refreshConfirmTips; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_OnShopRefreshed; // 0x28
	private static DelegateBridge __Hotfix0_PostProcessRecycleGoods; // 0x30
	private static DelegateBridge __Hotfix0__LoadFragments; // 0x38
	private static DelegateBridge __Hotfix0__LoadFragment; // 0x40
	private static DelegateBridge __Hotfix0__GoodsSort; // 0x48
	private static DelegateBridge __Hotfix0__TypeComparison; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override Boolean canRefresh { get; }
	public override Boolean showRefreshBtn { get; }
	public override Dictionary`2 preloadedRecycleGoods { get; }
	public override String refreshConfirmTips { get; }

	// RVA: 0x2b54290 VA: 0x759516c290
	public override Boolean get_canRefresh() { }
	// RVA: 0x2b54318 VA: 0x759516c318
	public override Boolean get_showRefreshBtn() { }
	// RVA: 0x2b54398 VA: 0x759516c398
	public override Dictionary`2 get_preloadedRecycleGoods() { }
	// RVA: 0x2b54400 VA: 0x759516c400
	public override String get_refreshConfirmTips() { }
	// RVA: 0x2b5448c VA: 0x759516c48c
	public override Void LoadData(String topicId, ShopContent shopPlayerData, CurrentData current) { }
	// RVA: 0x2b5477c VA: 0x759516c77c
	public override Void OnShopRefreshed(RoguelikeShopStateBean stateBean) { }
	// RVA: 0x2b54828 VA: 0x759516c828
	public override Void PostProcessRecycleGoods(List`1 recycleGoodsList) { }
	// RVA: 0x2b54560 VA: 0x759516c560
	private Void _LoadFragments(String topicId, ShopContent shopPlayerData, CurrentData current) { }
	// RVA: 0x2b54920 VA: 0x759516c920
	private Void _LoadFragment(String topicId, Goods goods, RoguelikeTopicDetail detailData, Dictionary`2 fragmentDataDict, Dictionary`2 fragmentsInInventory) { }
	// RVA: 0x2b54be8 VA: 0x759516cbe8
	private static Int32 _GoodsSort(RoguelikeGoodsViewModel x, RoguelikeGoodsViewModel y) { }
	// RVA: 0x2b54da0 VA: 0x759516cda0
	private static Int32 _TypeComparison(RoguelikeFragmentType x, RoguelikeFragmentType y) { }
	// RVA: 0x2b54e68 VA: 0x759516ce68
	public Void .ctor() { }
	// RVA: 0x2b54f2c VA: 0x759516cf2c
	private Boolean <>xLuaBaseProxy_get_canRefresh() { }
	// RVA: 0x2b54f34 VA: 0x759516cf34
	private Boolean <>xLuaBaseProxy_get_showRefreshBtn() { }
	// RVA: 0x2b54f3c VA: 0x759516cf3c
	private Dictionary`2 <>xLuaBaseProxy_get_preloadedRecycleGoods() { }
	// RVA: 0x2b54f44 VA: 0x759516cf44
	private String <>xLuaBaseProxy_get_refreshConfirmTips() { }
	// RVA: 0x2b54f4c VA: 0x759516cf4c
	private Void <>xLuaBaseProxy_LoadData(String P0, ShopContent P1, CurrentData P2) { }
	// RVA: 0x2b54f54 VA: 0x759516cf54
	private Void <>xLuaBaseProxy_OnShopRefreshed(RoguelikeShopStateBean P0) { }
	// RVA: 0x2b54f5c VA: 0x759516cf5c
	private Void <>xLuaBaseProxy_PostProcessRecycleGoods(List`1 P0) { }
}
```