# ShopFurnState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopFurnitureStateBean _stateBean`

- `LoopHorizontalScrollRect _layoutContent`

- `ShopFurnAdapter _adapter`


## Methods

- `Void _RefreshData()`

- `Void _OnListServiceResponse(BuildingGetFurnitureGoodListResponse, Boolean)`

- `Void _RefreshPlayerData()`

- `Void _RefreshView()`

- `Void _TryOpenItemDetail()`

- `IEnumerator _TryApplyDetailCoroutine(String)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopFurnState : ShopCommonState
{
	private ShopFurnitureStateBean _stateBean; // 0x68
	private LoopHorizontalScrollRect _layoutContent; // 0x70
	private ShopFurnAdapter _adapter; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__RefreshData; // 0x8
	private static DelegateBridge __Hotfix0__OnListServiceResponse; // 0x10
	private static DelegateBridge __Hotfix0__RefreshPlayerData; // 0x18
	private static DelegateBridge __Hotfix0__RefreshView; // 0x20
	private static DelegateBridge __Hotfix0__TryOpenItemDetail; // 0x28
	private static DelegateBridge __Hotfix0__TryApplyDetailCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnResume; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x247209c VA: 0x7594a8a09c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2472104 VA: 0x7594a8a104
	private Void _RefreshData() { }
	// RVA: 0x2472224 VA: 0x7594a8a224
	private Void _OnListServiceResponse(BuildingGetFurnitureGoodListResponse response, Boolean isDataUpdated) { }
	// RVA: 0x2472730 VA: 0x7594a8a730
	private Void _RefreshPlayerData() { }
	// RVA: 0x24725dc VA: 0x7594a8a5dc
	private Void _RefreshView() { }
	// RVA: 0x2472670 VA: 0x7594a8a670
	private Void _TryOpenItemDetail() { }
	// RVA: 0x24728a0 VA: 0x7594a8a8a0
	private IEnumerator _TryApplyDetailCoroutine(String openItemGoodId) { }
	// RVA: 0x2472998 VA: 0x7594a8a998
	protected override Void OnEnter() { }
	// RVA: 0x2472a0c VA: 0x7594a8aa0c
	protected override Void OnResume() { }
	// RVA: 0x2472a8c VA: 0x7594a8aa8c
	public Void .ctor() { }
	// RVA: 0x2472afc VA: 0x7594a8aafc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2472b04 VA: 0x7594a8ab04
	private Void <>xLuaBaseProxy_OnResume() { }
}
```