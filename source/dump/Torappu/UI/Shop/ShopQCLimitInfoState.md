# ShopQCLimitInfoState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Transform _detailViewContainer`

- `QCShopLMTGSDetailView _detailView`


## Methods

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopQCLimitInfoState : PopupFloatState, IHotfixable
{
	private Transform _detailViewContainer; // 0x70
	private QCShopLMTGSDetailView _detailView; // 0x78
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2473d68 VA: 0x7594a8bd68
	protected override Void OnEnter() { }
	// RVA: 0x2473efc VA: 0x7594a8befc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2473f60 VA: 0x7594a8bf60
	public Void .ctor() { }
	// RVA: 0x2473fd0 VA: 0x7594a8bfd0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```