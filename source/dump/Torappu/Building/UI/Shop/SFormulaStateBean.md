# SFormulaStateBean

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `Input input`

- `Output output`

- `SFormulaGroupProperty formulaGroupProperty`


## Methods

- `Void LoadData()`

- `Void SetItemType(FormulaItemType)`

- `Void ToggleSortType(FormulaSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class SFormulaStateBean : IStateBean, IHotfixable
{
	public Input input; // 0x10
	public Output output; // 0x18
	public SFormulaGroupProperty formulaGroupProperty; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetItemType; // 0x8
	private static DelegateBridge __Hotfix0_ToggleSortType; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3db79cc VA: 0x75963cf9cc
	public Void LoadData() { }
	// RVA: 0x3db8170 VA: 0x75963d0170
	public Void SetItemType(FormulaItemType formulaType) { }
	// RVA: 0x3db8308 VA: 0x75963d0308
	public Void ToggleSortType(FormulaSortType sortType) { }
	// RVA: 0x3db83f4 VA: 0x75963d03f4
	public Void .ctor() { }
}
```