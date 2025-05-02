# ShopGPSimplePanelAdapter

**Namespace:** `Torappu.UI.Shop`


## Fields

- `IShopGPSimplePanelHolder m_holder`


## Methods

- `Void RebuildAll()`

- `Void _GenerateVirtualViews(IList`1, IList`1, ShopGPMonthlySubItem, ShopGPCommonItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPSimplePanelAdapter : UIRecycleLayoutAdapter
{
	private IShopGPSimplePanelHolder m_holder; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RebuildAll; // 0x8
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x10
	private static DelegateBridge __Hotfix0__GenerateVirtualViews; // 0x18


	// RVA: 0x243f600 VA: 0x7594a57600
	public Void .ctor(IShopGPSimplePanelHolder holder) { }
	// RVA: 0x243f744 VA: 0x7594a57744
	public Void RebuildAll() { }
	// RVA: 0x2441a04 VA: 0x7594a59a04
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x2441d50 VA: 0x7594a59d50
	private Void _GenerateVirtualViews(IList`1 viewModels, IList`1 ret, ShopGPMonthlySubItem monthlyPrefab, ShopGPCommonItemView commonPrefab) { }
}
```