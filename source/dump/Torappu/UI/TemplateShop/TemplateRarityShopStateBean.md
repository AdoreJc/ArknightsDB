# TemplateRarityShopStateBean

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `TemplateShopData shopDataCache`


## Methods

- `Void RefreshBuySituationOnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateRarityShopStateBean : TemplateCommonShopGoodListStateBean
{
	public TemplateShopData shopDataCache; // 0x10
	public List`1 shopRarityViewModelList; // 0x18
	private Dictionary`2 shopRarityViewModelDict; // 0x20
	private static DelegateBridge __Hotfix0_RefreshBuySituationOnResume; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2356474 VA: 0x759496e474
	public Void RefreshBuySituationOnResume() { }
	// RVA: 0x2361778 VA: 0x7594979778
	public override Void LoadData(TemplateShopData data, Int64 _) { }
	// RVA: 0x2357108 VA: 0x759496f108
	public Void .ctor() { }
}
```