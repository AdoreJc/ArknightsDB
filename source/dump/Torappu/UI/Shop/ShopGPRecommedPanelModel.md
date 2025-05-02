# ShopGPRecommedPanelModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Int32 limitNum`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPRecommedPanelModel : AbstractShopGPPanelModel
{
	public Int32 limitNum; // 0x10
	public List`1 shopItemList; // 0x18
	public List`1 soldOutItemList; // 0x20
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ShopGPPanelType panelType { get; }

	// RVA: 0x2449888 VA: 0x7594a61888
	public override ShopGPPanelType get_panelType() { }
	// RVA: 0x24498f0 VA: 0x7594a618f0
	public override Void RefreshData(ShopGPTabDisplayData data, ShopGpTabGroupModel groupModel) { }
	// RVA: 0x24499a0 VA: 0x7594a619a0
	public Void .ctor() { }
}
```