# BuildingManufactFormulaSortBar

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `Boolean m_isInited`

- `FormulaSortType m_sortType`

- `Boolean m_isInverse`


## Methods

- `Void _Init()`

- `Void _OnSortClicked(FormulaSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactFormulaSortBar : DataBinder`1
{
	private BuildingManufactFormulaSortItem[] _sortItems; // 0x20
	public Action`1 onSortClicked; // 0x28
	private Boolean m_isInited; // 0x30
	private FormulaSortType m_sortType; // 0x34
	private Boolean m_isInverse; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Init; // 0x8
	private static DelegateBridge __Hotfix0__OnSortClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3e0a78c VA: 0x759642278c
	public override Void OnValueChanged(MFormulaGroupProperty property) { }
	// RVA: 0x3e0a8d4 VA: 0x75964228d4
	private Void _Init() { }
	// RVA: 0x3e0a9f4 VA: 0x75964229f4
	private Void _OnSortClicked(FormulaSortType sortType) { }
	// RVA: 0x3e0aa94 VA: 0x7596422a94
	public Void .ctor() { }
}
```