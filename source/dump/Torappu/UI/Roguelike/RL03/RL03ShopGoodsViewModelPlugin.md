# RL03ShopGoodsViewModelPlugin

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `Boolean m_hasBoss`

- `Boolean m_hasBuffUnlock`


## Methods

- `String <>xLuaBaseProxy_get_refreshConfirmTips()`

- `Boolean <>xLuaBaseProxy_get_canRefresh()`

- `Boolean <>xLuaBaseProxy_get_showRefreshBtn()`

- `Void <>xLuaBaseProxy_LoadData(String, ShopContent, CurrentData)`

- `Void <>xLuaBaseProxy_OnShopRefreshed(RoguelikeShopStateBean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03ShopGoodsViewModelPlugin : RoguelikeGameShopViewModelPlugin
{
	private Boolean m_hasBoss; // 0x11
	private Boolean m_hasBuffUnlock; // 0x12
	private static DelegateBridge __Hotfix0_get_refreshConfirmTips; // 0x0
	private static DelegateBridge __Hotfix0_get_canRefresh; // 0x8
	private static DelegateBridge __Hotfix0_get_showRefreshBtn; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_OnShopRefreshed; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override String refreshConfirmTips { get; }
	public override Boolean canRefresh { get; }
	public override Boolean showRefreshBtn { get; }

	// RVA: 0x2ba491c VA: 0x75951bc91c
	public override String get_refreshConfirmTips() { }
	// RVA: 0x2ba49a8 VA: 0x75951bc9a8
	public override Boolean get_canRefresh() { }
	// RVA: 0x2ba4a30 VA: 0x75951bca30
	public override Boolean get_showRefreshBtn() { }
	// RVA: 0x2ba4ab0 VA: 0x75951bcab0
	public override Void LoadData(String topicId, ShopContent shopPlayerData, CurrentData current) { }
	// RVA: 0x2ba4b74 VA: 0x75951bcb74
	public override Void OnShopRefreshed(RoguelikeShopStateBean stateBean) { }
	// RVA: 0x2ba4c20 VA: 0x75951bcc20
	public Void .ctor() { }
	// RVA: 0x2ba4c90 VA: 0x75951bcc90
	private String <>xLuaBaseProxy_get_refreshConfirmTips() { }
	// RVA: 0x2ba4c98 VA: 0x75951bcc98
	private Boolean <>xLuaBaseProxy_get_canRefresh() { }
	// RVA: 0x2ba4ca0 VA: 0x75951bcca0
	private Boolean <>xLuaBaseProxy_get_showRefreshBtn() { }
	// RVA: 0x2ba4ca8 VA: 0x75951bcca8
	private Void <>xLuaBaseProxy_LoadData(String P0, ShopContent P1, CurrentData P2) { }
	// RVA: 0x2ba4cb0 VA: 0x75951bccb0
	private Void <>xLuaBaseProxy_OnShopRefreshed(RoguelikeShopStateBean P0) { }
}
```