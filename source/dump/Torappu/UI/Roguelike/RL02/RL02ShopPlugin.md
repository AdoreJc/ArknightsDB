# RL02ShopPlugin

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `RoguelikeGoodsObjPlugin _goodDiscountViewPrefab`

- `RoguelikeGameBankConsumeWithdrawView _bankWithdrawalViewPrefab`

- `RoguelikeGameShopBattleConfirmView _battleConfirmViewPrefab`


## Methods

- `RoguelikeGameShopViewModelPlugin <>xLuaBaseProxy_GetShopViewModelPlugin()`

- `RoguelikeGameBankWithdrawCommonView <>xLuaBaseProxy_GetBankWithDrawlViewPrefab()`

- `BankWithdrawModelPlugin <>xLuaBaseProxy_GetBankViewModelPlugin()`

- `RoguelikeGameShopBattleConfirmView <>xLuaBaseProxy_GetBattleConfirmViewPrefab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ShopPlugin : RoguelikeCommonShopPlugin
{
	private RoguelikeGoodsObjPlugin _goodDiscountViewPrefab; // 0x18
	private RoguelikeGameBankConsumeWithdrawView _bankWithdrawalViewPrefab; // 0x20
	private RoguelikeGameShopBattleConfirmView _battleConfirmViewPrefab; // 0x28
	private static DelegateBridge __Hotfix0_GetGoodObjPlugins; // 0x0
	private static DelegateBridge __Hotfix0_GetShopViewModelPlugin; // 0x8
	private static DelegateBridge __Hotfix0_GetBankWithDrawlViewPrefab; // 0x10
	private static DelegateBridge __Hotfix0_GetBankViewModelPlugin; // 0x18
	private static DelegateBridge __Hotfix0_GetBattleConfirmViewPrefab; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b72d38 VA: 0x759518ad38
	public override List`1 GetGoodObjPlugins() { }
	// RVA: 0x2b72e54 VA: 0x759518ae54
	public override RoguelikeGameShopViewModelPlugin GetShopViewModelPlugin() { }
	// RVA: 0x2b72ee8 VA: 0x759518aee8
	public override RoguelikeGameBankWithdrawCommonView GetBankWithDrawlViewPrefab() { }
	// RVA: 0x2b72f50 VA: 0x759518af50
	public override BankWithdrawModelPlugin GetBankViewModelPlugin() { }
	// RVA: 0x2b72fe4 VA: 0x759518afe4
	public override RoguelikeGameShopBattleConfirmView GetBattleConfirmViewPrefab() { }
	// RVA: 0x2b7304c VA: 0x759518b04c
	public Void .ctor() { }
	// RVA: 0x2b730bc VA: 0x759518b0bc
	private List`1 <>xLuaBaseProxy_GetGoodObjPlugins() { }
	// RVA: 0x2b730c4 VA: 0x759518b0c4
	private RoguelikeGameShopViewModelPlugin <>xLuaBaseProxy_GetShopViewModelPlugin() { }
	// RVA: 0x2b730cc VA: 0x759518b0cc
	private RoguelikeGameBankWithdrawCommonView <>xLuaBaseProxy_GetBankWithDrawlViewPrefab() { }
	// RVA: 0x2b730d4 VA: 0x759518b0d4
	private BankWithdrawModelPlugin <>xLuaBaseProxy_GetBankViewModelPlugin() { }
	// RVA: 0x2b730dc VA: 0x759518b0dc
	private RoguelikeGameShopBattleConfirmView <>xLuaBaseProxy_GetBattleConfirmViewPrefab() { }
}
```