# ShopDetailCommonState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopDetailCommonView _detailView`


## Methods

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailCommonState : PopupFloatState, IHotfixable, IShopDetailLayer
{
	private ShopDetailCommonView _detailView; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x243178c VA: 0x7594a4978c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x24317f0 VA: 0x7594a497f0
	protected override Void OnEnter() { }
	// RVA: 0x242ef90 VA: 0x7594a46f90
	public Void .ctor() { }
	// RVA: 0x2431948 VA: 0x7594a49948
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```