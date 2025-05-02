# ShopCashState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `CashStateBean _stateBean`

- `CashShopListView _listView`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateShopCashState()`

- `Void ApplyData(GetCashGoodListResponse)`

- `Void <_UpdateShopCashState>b__6_0(GetCashGoodListResponse, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopCashState : ShopCommonState
{
	private CashStateBean _stateBean; // 0x68
	private CashShopListView _listView; // 0x70
	private Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__UpdateShopCashState; // 0x18
	private static DelegateBridge __Hotfix0_ApplyData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2471688 VA: 0x7594a89688
	private Void _InitIfNot() { }
	// RVA: 0x24717c4 VA: 0x7594a897c4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x247182c VA: 0x7594a8982c
	protected override Void OnEnter() { }
	// RVA: 0x24718a8 VA: 0x7594a898a8
	private Void _UpdateShopCashState() { }
	// RVA: 0x24719c8 VA: 0x7594a899c8
	public Void ApplyData(GetCashGoodListResponse response) { }
	// RVA: 0x2471b64 VA: 0x7594a89b64
	public Void .ctor() { }
	// RVA: 0x2471bd4 VA: 0x7594a89bd4
	private Void <_UpdateShopCashState>b__6_0(GetCashGoodListResponse response, Boolean isDataUpdated) { }
	// RVA: 0x2471be0 VA: 0x7594a89be0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```