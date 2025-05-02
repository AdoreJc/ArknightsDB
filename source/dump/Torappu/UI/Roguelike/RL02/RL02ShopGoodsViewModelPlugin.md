# RL02ShopGoodsViewModelPlugin

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Boolean m_diceCountLack`

- `Boolean m_hasBoss`


## Methods

- `Boolean <>xLuaBaseProxy_get_canRefresh()`

- `Boolean <>xLuaBaseProxy_get_showRefreshBtn()`

- `String <>xLuaBaseProxy_get_refreshConfirmTips()`

- `Void <>xLuaBaseProxy_LoadData(String, ShopContent, CurrentData)`

- `Boolean <>xLuaBaseProxy_GetCannotRefreshToast(out)`

- `Void <>xLuaBaseProxy_OnShopRefreshed(RoguelikeShopStateBean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ShopGoodsViewModelPlugin : RoguelikeGameShopViewModelPlugin
{
	private Boolean m_diceCountLack; // 0x11
	private Boolean m_hasBoss; // 0x12
	private static DelegateBridge __Hotfix0_get_canRefresh; // 0x0
	private static DelegateBridge __Hotfix0_get_showRefreshBtn; // 0x8
	private static DelegateBridge __Hotfix0_get_refreshConfirmTips; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_GetCannotRefreshToast; // 0x20
	private static DelegateBridge __Hotfix0_OnShopRefreshed; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override Boolean canRefresh { get; }
	public override Boolean showRefreshBtn { get; }
	public override String refreshConfirmTips { get; }

	// RVA: 0x2b72890 VA: 0x759518a890
	public override Boolean get_canRefresh() { }
	// RVA: 0x2b72918 VA: 0x759518a918
	public override Boolean get_showRefreshBtn() { }
	// RVA: 0x2b72980 VA: 0x759518a980
	public override String get_refreshConfirmTips() { }
	// RVA: 0x2b72a0c VA: 0x759518aa0c
	public override Void LoadData(String topicId, ShopContent shopPlayerData, CurrentData current) { }
	// RVA: 0x2b72afc VA: 0x759518aafc
	public override Boolean GetCannotRefreshToast(out String cantToast) { }
	// RVA: 0x2b72bd8 VA: 0x759518abd8
	public override Void OnShopRefreshed(RoguelikeShopStateBean stateBean) { }
	// RVA: 0x2b72c98 VA: 0x759518ac98
	public Void .ctor() { }
	// RVA: 0x2b72d08 VA: 0x759518ad08
	private Boolean <>xLuaBaseProxy_get_canRefresh() { }
	// RVA: 0x2b72d10 VA: 0x759518ad10
	private Boolean <>xLuaBaseProxy_get_showRefreshBtn() { }
	// RVA: 0x2b72d18 VA: 0x759518ad18
	private String <>xLuaBaseProxy_get_refreshConfirmTips() { }
	// RVA: 0x2b72d20 VA: 0x759518ad20
	private Void <>xLuaBaseProxy_LoadData(String P0, ShopContent P1, CurrentData P2) { }
	// RVA: 0x2b72d28 VA: 0x759518ad28
	private Boolean <>xLuaBaseProxy_GetCannotRefreshToast(out String P0) { }
	// RVA: 0x2b72d30 VA: 0x759518ad30
	private Void <>xLuaBaseProxy_OnShopRefreshed(RoguelikeShopStateBean P0) { }
}
```