# ShopGPCommonSortPanelModel

**Namespace:** `Torappu.UI.Shop`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPCommonSortPanelModel : AbstractShopGPPanelModel
{
	public List`1 shopItemList; // 0x10
	public List`1 soldOutItemList; // 0x18
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ShopGPPanelType panelType { get; }

	// RVA: 0x2449708 VA: 0x7594a61708
	public override ShopGPPanelType get_panelType() { }
	// RVA: 0x244976c VA: 0x7594a6176c
	public override Void RefreshData(ShopGPTabDisplayData data, ShopGpTabGroupModel groupModel) { }
	// RVA: 0x244981c VA: 0x7594a6181c
	public Void .ctor() { }
}
```