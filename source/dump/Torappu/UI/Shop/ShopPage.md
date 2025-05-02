# ShopPage

**Namespace:** `Torappu.UI.Shop`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `ShopStateItemContainer _controller`


## Methods

- `Boolean IsTransitting()`

- `Boolean CanInteractBuilding()`

- `Void _OnBackClicked()`

- `Void _TryUpdateStatusWhenRouted()`

- `Void _UpdateStatusWhenBackToShop(UIPageTransContext)`

- `Void <OnCreate>b__9_0(GameObject)`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Boolean <>xLuaBaseProxy_get_shouldTrigAudioSignal()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStateEngineReady(Boolean)`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopPage : StateEnginePage, IBuildingPage, IHotfixable
{
	private PrefabInstHolder _topMenuHolder; // 0xe8
	private ShopStateItemContainer _controller; // 0xf0
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x0
	private static DelegateBridge __Hotfix0_get_shouldTrigAudioSignal; // 0x8
	private static DelegateBridge __Hotfix0_IsTransitting; // 0x10
	private static DelegateBridge __Hotfix0_CanInteractBuilding; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge __Hotfix0_OnStateEngineReady; // 0x28
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x30
	private static DelegateBridge __Hotfix0__PickInitShopType; // 0x38
	private static DelegateBridge __Hotfix0__OnBackClicked; // 0x40
	private static DelegateBridge __Hotfix0__TryUpdateStatusWhenRouted; // 0x48
	private static DelegateBridge __Hotfix0__UpdateStatusWhenBackToShop; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override AVGPageKey avgPage { get; }
	public override Boolean shouldTrigAudioSignal { get; }

	// RVA: 0x2467838 VA: 0x7594a7f838
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x24678a0 VA: 0x7594a7f8a0
	public override Boolean get_shouldTrigAudioSignal() { }
	// RVA: 0x2467908 VA: 0x7594a7f908
	public Boolean IsTransitting() { }
	// RVA: 0x246799c VA: 0x7594a7f99c
	public Boolean CanInteractBuilding() { }
	// RVA: 0x2467a00 VA: 0x7594a7fa00
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2467ae8 VA: 0x7594a7fae8
	protected override Void OnStateEngineReady(Boolean isFromStack) { }
	// RVA: 0x2467ed0 VA: 0x7594a7fed0
	protected override Void OnPageRouted() { }
	// RVA: 0x2467be0 VA: 0x7594a7fbe0
	private static ShopRouteTarget _PickInitShopType(Params pageParam) { }
	// RVA: 0x2468150 VA: 0x7594a80150
	private Void _OnBackClicked() { }
	// RVA: 0x2467f80 VA: 0x7594a7ff80
	private Void _TryUpdateStatusWhenRouted() { }
	// RVA: 0x2468310 VA: 0x7594a80310
	private Void _UpdateStatusWhenBackToShop(UIPageTransContext transContext) { }
	// RVA: 0x24686a8 VA: 0x7594a806a8
	public Void .ctor() { }
	// RVA: 0x2468718 VA: 0x7594a80718
	private Void <OnCreate>b__9_0(GameObject inst) { }
	// RVA: 0x24687d0 VA: 0x7594a807d0
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x24687d8 VA: 0x7594a807d8
	private Boolean <>xLuaBaseProxy_get_shouldTrigAudioSignal() { }
	// RVA: 0x24687e0 VA: 0x7594a807e0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x24687e8 VA: 0x7594a807e8
	private Void <>xLuaBaseProxy_OnStateEngineReady(Boolean P0) { }
	// RVA: 0x24687f4 VA: 0x7594a807f4
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```