# BuildingShopFormulaCategoryTab

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `TwoStateToggle _toggle`

- `FormulaItemType _itemType`


## Methods

- `Void EventOnItemTypeClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopFormulaCategoryTab : DataBinder`1
{
	private TwoStateToggle _toggle; // 0x20
	private FormulaItemType _itemType; // 0x28
	public Action`1 onItemTypeClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnItemTypeClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3dbec70 VA: 0x75963d6c70
	public override Void OnValueChanged(SFormulaGroupProperty property) { }
	// RVA: 0x3dbed30 VA: 0x75963d6d30
	public Void EventOnItemTypeClicked() { }
	// RVA: 0x3dbedb8 VA: 0x75963d6db8
	public Void .ctor() { }
}
```