# BuildingManufactFormulaCategoryTab

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `TwoStateToggle _toggle`

- `FormulaItemType _itemType`


## Methods

- `Void EventOnItemTypeClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactFormulaCategoryTab : DataBinder`1
{
	private TwoStateToggle _toggle; // 0x20
	private FormulaItemType _itemType; // 0x28
	public Action`1 onItemTypeClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnItemTypeClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3e0955c VA: 0x759642155c
	public override Void OnValueChanged(MFormulaGroupProperty property) { }
	// RVA: 0x3e0961c VA: 0x759642161c
	public Void EventOnItemTypeClicked() { }
	// RVA: 0x3e096a4 VA: 0x75964216a4
	public Void .ctor() { }
}
```