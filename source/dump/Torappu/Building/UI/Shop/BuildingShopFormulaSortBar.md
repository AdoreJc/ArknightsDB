# BuildingShopFormulaSortBar

**Namespace:** `Torappu.Building.UI.Shop`


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
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopFormulaSortBar : DataBinder`1
{
	private BuildingShopFormulaSortItem[] _sortItems; // 0x20
	public Action`1 onSortClicked; // 0x28
	private Boolean m_isInited; // 0x30
	private FormulaSortType m_sortType; // 0x34
	private Boolean m_isInverse; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Init; // 0x8
	private static DelegateBridge __Hotfix0__OnSortClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3dbf574 VA: 0x75963d7574
	public override Void OnValueChanged(SFormulaGroupProperty property) { }
	// RVA: 0x3dbf6bc VA: 0x75963d76bc
	private Void _Init() { }
	// RVA: 0x3dbf7dc VA: 0x75963d77dc
	private Void _OnSortClicked(FormulaSortType sortType) { }
	// RVA: 0x3dbf87c VA: 0x75963d787c
	public Void .ctor() { }
}
```