# TemplateGroupShopStateBean

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `TemplateShopData shopDataCache`

- `Int64 nextSyncTime`


## Methods

- `Void RefreshBuySituationOnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateGroupShopStateBean : TemplateCommonShopGoodListStateBean
{
	public TemplateShopData shopDataCache; // 0x10
	public List`1 shopGroupViewModelList; // 0x18
	public Int64 nextSyncTime; // 0x20
	private static DelegateBridge __Hotfix0_RefreshBuySituationOnResume; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2354c0c VA: 0x759496cc0c
	public Void RefreshBuySituationOnResume() { }
	// RVA: 0x2360cf8 VA: 0x7594978cf8
	public override Void LoadData(TemplateShopData data, Int64 nextSyncTs) { }
	// RVA: 0x2355b98 VA: 0x759496db98
	public Void .ctor() { }
}
```