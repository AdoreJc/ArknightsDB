# ShopSkinState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `SkinShopStateBean _stateBean`

- `SkinShopListView _skinShopView`


## Methods

- `Void OnClick(String)`

- `Void _UpdateShopSkinState()`

- `Void ApplyData(GetSkinGoodListResponse)`

- `IEnumerator _ShowSkinDetailCoroutine(String)`

- `Void _OpenSkinDetailPage(String)`

- `Void <_UpdateShopSkinState>b__6_0(GetSkinGoodListResponse, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopSkinState : ShopCommonState
{
	private SkinShopStateBean _stateBean; // 0x68
	private SkinShopListView _skinShopView; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__UpdateShopSkinState; // 0x20
	private static DelegateBridge __Hotfix0_ApplyData; // 0x28
	private static DelegateBridge __Hotfix0__ShowSkinDetailCoroutine; // 0x30
	private static DelegateBridge __Hotfix0__OpenSkinDetailPage; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2475bd8 VA: 0x7594a8dbd8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2475c40 VA: 0x7594a8dc40
	protected override Void OnEnter() { }
	// RVA: 0x2475dd4 VA: 0x7594a8ddd4
	protected override Void OnResume() { }
	// RVA: 0x2475e4c VA: 0x7594a8de4c
	public Void OnClick(String skinId) { }
	// RVA: 0x2475cb4 VA: 0x7594a8dcb4
	private Void _UpdateShopSkinState() { }
	// RVA: 0x2475f98 VA: 0x7594a8df98
	public Void ApplyData(GetSkinGoodListResponse response) { }
	// RVA: 0x24761f4 VA: 0x7594a8e1f4
	private IEnumerator _ShowSkinDetailCoroutine(String goodId) { }
	// RVA: 0x2475ecc VA: 0x7594a8decc
	private Void _OpenSkinDetailPage(String skinId) { }
	// RVA: 0x24762c4 VA: 0x7594a8e2c4
	public Void .ctor() { }
	// RVA: 0x2476334 VA: 0x7594a8e334
	private Void <_UpdateShopSkinState>b__6_0(GetSkinGoodListResponse response, Boolean isDataUpdated) { }
	// RVA: 0x2476408 VA: 0x7594a8e408
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2476410 VA: 0x7594a8e410
	private Void <>xLuaBaseProxy_OnResume() { }
}
```