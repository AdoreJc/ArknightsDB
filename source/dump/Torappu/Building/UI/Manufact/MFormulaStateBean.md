# MFormulaStateBean

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `Input input`

- `Output output`

- `MFormulaGroupProperty formulaGroupProperty`


## Methods

- `Void LoadData()`

- `Void SetItemType(FormulaItemType)`

- `Void ToggleSortType(FormulaSortType)`

- `Void UpdateData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class MFormulaStateBean : IStateBean, IHotfixable
{
	public Input input; // 0x10
	public Output output; // 0x18
	public MFormulaGroupProperty formulaGroupProperty; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetItemType; // 0x8
	private static DelegateBridge __Hotfix0_ToggleSortType; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3e00f7c VA: 0x7596418f7c
	public Void LoadData() { }
	// RVA: 0x3e0140c VA: 0x759641940c
	public Void SetItemType(FormulaItemType formulaType) { }
	// RVA: 0x3e015a4 VA: 0x75964195a4
	public Void ToggleSortType(FormulaSortType sortType) { }
	// RVA: 0x3e01690 VA: 0x7596419690
	public Void UpdateData() { }
	// RVA: 0x3e01748 VA: 0x7596419748
	public Void .ctor() { }
}
```