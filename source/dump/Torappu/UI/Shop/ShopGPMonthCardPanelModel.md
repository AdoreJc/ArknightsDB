# ShopGPMonthCardPanelModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `String priceText`

- `String remainTimeText`

- `ShopGPMonthlySubItemViewModel itemModel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPMonthCardPanelModel : AbstractShopGPPanelModel
{
	public String priceText; // 0x10
	public String remainTimeText; // 0x18
	public ShopGPMonthlySubItemViewModel itemModel; // 0x20
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ShopGPPanelType panelType { get; }

	// RVA: 0x2449a0c VA: 0x7594a61a0c
	public override ShopGPPanelType get_panelType() { }
	// RVA: 0x2449a74 VA: 0x7594a61a74
	public override Void RefreshData(ShopGPTabDisplayData data, ShopGpTabGroupModel groupModel) { }
	// RVA: 0x2449dd4 VA: 0x7594a61dd4
	public Void .ctor() { }
}
```