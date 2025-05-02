# ShopRecommendState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopRecommendStateBean _stateBean`

- `ShopRecommendTabButton _tabButton`

- `ShopKeeperPanel _shopKeeper`

- `SimpleLayoutContent _buttonContainer`

- `Transform _layoutContainer`

- `String m_selectedTab`

- `ShopRecommendLayoutView m_layout`

- `TabAdapter m_tabAdapter`

- `Boolean m_isInitialUpdateStatus`


## Methods

- `Void OnClickHandler(String)`

- `Void OnClickDropHandler(ShopRecommendData)`

- `Void _FocusOnSelected(ShopRecommendViewModel)`

- `Void _UpdateShopStatus()`

- `Void <_UpdateShopStatus>b__17_0(GetGoodPurchaseStateResponse, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendState : ShopCommonState
{
	private ShopRecommendStateBean _stateBean; // 0x68
	private ShopRecommendTabButton _tabButton; // 0x70
	private ShopKeeperPanel _shopKeeper; // 0x78
	private SimpleLayoutContent _buttonContainer; // 0x80
	private Transform _layoutContainer; // 0x88
	private String m_selectedTab; // 0x90
	private List`1 m_buttonList; // 0x98
	private ShopRecommendLayoutView m_layout; // 0xa0
	private TabAdapter m_tabAdapter; // 0xa8
	private Boolean m_isInitialUpdateStatus; // 0xb0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnClickHandler; // 0x10
	private static DelegateBridge __Hotfix0_OnClickDropHandler; // 0x18
	private static DelegateBridge __Hotfix0__FocusOnSelected; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0__UpdateShopStatus; // 0x30
	private static DelegateBridge __Hotfix0__RestrictSelectedTab; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2474a8c VA: 0x7594a8ca8c
	protected override Void OnEnter() { }
	// RVA: 0x2474c68 VA: 0x7594a8cc68
	protected override Void OnResume() { }
	// RVA: 0x2474ce0 VA: 0x7594a8cce0
	public Void OnClickHandler(String tabId) { }
	// RVA: 0x2474d88 VA: 0x7594a8cd88
	public Void OnClickDropHandler(ShopRecommendData recommend) { }
	// RVA: 0x2474e98 VA: 0x7594a8ce98
	private Void _FocusOnSelected(ShopRecommendViewModel closureViewModel) { }
	// RVA: 0x24751ec VA: 0x7594a8d1ec
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2474b48 VA: 0x7594a8cb48
	private Void _UpdateShopStatus() { }
	// RVA: 0x2475254 VA: 0x7594a8d254
	private static String _RestrictSelectedTab(ShopRecommendStateBean stateBean, String selectedTag) { }
	// RVA: 0x24753dc VA: 0x7594a8d3dc
	public Void .ctor() { }
	// RVA: 0x2475454 VA: 0x7594a8d454
	private Void <_UpdateShopStatus>b__17_0(GetGoodPurchaseStateResponse response, Boolean isDataUpdated) { }
	// RVA: 0x24755d8 VA: 0x7594a8d5d8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x24755e0 VA: 0x7594a8d5e0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```