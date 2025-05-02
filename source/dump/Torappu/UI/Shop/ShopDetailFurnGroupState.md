# ShopDetailFurnGroupState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopDetailFurnGroupView _detailView`


## Methods

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailFurnGroupState : PopupFloatState, IHotfixable, IShopDetailLayer
{
	private ShopDetailFurnGroupView _detailView; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x242cad4 VA: 0x7594a44ad4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x242cb38 VA: 0x7594a44b38
	protected override Void OnEnter() { }
	// RVA: 0x242d52c VA: 0x7594a4552c
	public Void .ctor() { }
	// RVA: 0x242d59c VA: 0x7594a4559c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```