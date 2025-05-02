# RL04ShopPlugin

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04ShopDetailExtraInfoPlugin _detailExtraInfo`

- `RoguelikeGoodsObjDiscountView _goodsDiscountPrefab`

- `RL04GoodsObjFragmentIconView _goodsIconViewPrefab`

- `RL04GoodsObjFragmentIconView _detailGoodsIconViewPrefab`

- `RL04ShopLineupRecycleAddonPlugin _lineupRecycleAddonPrefab`

- `RoguelikeGameBankSimpleWithdrawView _bankWithdrawPrefab`

- `RoguelikeGameShopBattleConfirmView _battleConfirmViewPrefab`


## Methods

- `RoguelikeGameShopViewModelPlugin <>xLuaBaseProxy_GetShopViewModelPlugin()`

- `RoguelikeGoodsObjPlugin <>xLuaBaseProxy_GetDetailGoodIconPlugin()`

- `RoguelikeShopDetailExtraInfoPlugin <>xLuaBaseProxy_GetDetailExtraInfoViewModelPlugin()`

- `RoguelikeGameBankWithdrawCommonView <>xLuaBaseProxy_GetBankWithDrawlViewPrefab()`

- `BankWithdrawModelPlugin <>xLuaBaseProxy_GetBankViewModelPlugin()`

- `RoguelikeGameShopBattleConfirmView <>xLuaBaseProxy_GetBattleConfirmViewPrefab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ShopPlugin : RoguelikeCommonShopPlugin
{
	private RL04ShopDetailExtraInfoPlugin _detailExtraInfo; // 0x18
	private RoguelikeGoodsObjDiscountView _goodsDiscountPrefab; // 0x20
	private RL04GoodsObjFragmentIconView _goodsIconViewPrefab; // 0x28
	private RL04GoodsObjFragmentIconView _detailGoodsIconViewPrefab; // 0x30
	private RL04ShopLineupRecycleAddonPlugin _lineupRecycleAddonPrefab; // 0x38
	private RoguelikeGameBankSimpleWithdrawView _bankWithdrawPrefab; // 0x40
	private RoguelikeGameShopBattleConfirmView _battleConfirmViewPrefab; // 0x48
	private static DelegateBridge __Hotfix0_GetShopViewModelPlugin; // 0x0
	private static DelegateBridge __Hotfix0_GetGoodObjPlugins; // 0x8
	private static DelegateBridge __Hotfix0_GetDetailGoodIconPlugin; // 0x10
	private static DelegateBridge __Hotfix0_GetDetailExtraInfoViewModelPlugin; // 0x18
	private static DelegateBridge __Hotfix0_GetLineupAddonPlugins; // 0x20
	private static DelegateBridge __Hotfix0_GetBankWithDrawlViewPrefab; // 0x28
	private static DelegateBridge __Hotfix0_GetBankViewModelPlugin; // 0x30
	private static DelegateBridge __Hotfix0_GetBattleConfirmViewPrefab; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2b55154 VA: 0x759516d154
	public override RoguelikeGameShopViewModelPlugin GetShopViewModelPlugin() { }
	// RVA: 0x2b551e8 VA: 0x759516d1e8
	public override List`1 GetGoodObjPlugins() { }
	// RVA: 0x2b55360 VA: 0x759516d360
	public override RoguelikeGoodsObjPlugin GetDetailGoodIconPlugin() { }
	// RVA: 0x2b553c8 VA: 0x759516d3c8
	public override RoguelikeShopDetailExtraInfoPlugin GetDetailExtraInfoViewModelPlugin() { }
	// RVA: 0x2b55430 VA: 0x759516d430
	public override List`1 GetLineupAddonPlugins() { }
	// RVA: 0x2b5554c VA: 0x759516d54c
	public override RoguelikeGameBankWithdrawCommonView GetBankWithDrawlViewPrefab() { }
	// RVA: 0x2b555b4 VA: 0x759516d5b4
	public override BankWithdrawModelPlugin GetBankViewModelPlugin() { }
	// RVA: 0x2b55648 VA: 0x759516d648
	public override RoguelikeGameShopBattleConfirmView GetBattleConfirmViewPrefab() { }
	// RVA: 0x2b556b0 VA: 0x759516d6b0
	public Void .ctor() { }
	// RVA: 0x2b55720 VA: 0x759516d720
	private RoguelikeGameShopViewModelPlugin <>xLuaBaseProxy_GetShopViewModelPlugin() { }
	// RVA: 0x2b55728 VA: 0x759516d728
	private List`1 <>xLuaBaseProxy_GetGoodObjPlugins() { }
	// RVA: 0x2b55730 VA: 0x759516d730
	private RoguelikeGoodsObjPlugin <>xLuaBaseProxy_GetDetailGoodIconPlugin() { }
	// RVA: 0x2b55738 VA: 0x759516d738
	private RoguelikeShopDetailExtraInfoPlugin <>xLuaBaseProxy_GetDetailExtraInfoViewModelPlugin() { }
	// RVA: 0x2b55740 VA: 0x759516d740
	private List`1 <>xLuaBaseProxy_GetLineupAddonPlugins() { }
	// RVA: 0x2b55748 VA: 0x759516d748
	private RoguelikeGameBankWithdrawCommonView <>xLuaBaseProxy_GetBankWithDrawlViewPrefab() { }
	// RVA: 0x2b55750 VA: 0x759516d750
	private BankWithdrawModelPlugin <>xLuaBaseProxy_GetBankViewModelPlugin() { }
	// RVA: 0x2b55758 VA: 0x759516d758
	private RoguelikeGameShopBattleConfirmView <>xLuaBaseProxy_GetBattleConfirmViewPrefab() { }
}
```