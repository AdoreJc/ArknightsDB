# BuildingWorkshopFormulaAdapter

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `GameObject _formulaProto`

- `Transform _poolTransform`

- `Boolean m_AVGIsFirstItemRegistered`

- `Int32 m_dataSourceCountCache`


## Methods

- `Void add_onFormulaClicked(Action`1)`

- `Void remove_onFormulaClicked(Action`1)`

- `Void _OnFormulaClicked(IWorkshopFormula)`

- `Void _TryRegisterAVGFirstItem(WorkshopFormulaView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopFormulaAdapter : LoopScrollAdapter`2
{
	private GameObject _formulaProto; // 0x58
	private Transform _poolTransform; // 0x60
	private Action`1 onFormulaClicked; // 0x68
	private Boolean m_AVGIsFirstItemRegistered; // 0x70
	private Int32 m_dataSourceCountCache; // 0x74
	private static DelegateBridge __Hotfix0_add_onFormulaClicked; // 0x0
	private static DelegateBridge __Hotfix0_remove_onFormulaClicked; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x20
	private static DelegateBridge __Hotfix0__OnFormulaClicked; // 0x28
	private static DelegateBridge __Hotfix0__TryRegisterAVGFirstItem; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3d6c874 VA: 0x7596384874
	public Void add_onFormulaClicked(Action`1 value) { }
	// RVA: 0x3d6c968 VA: 0x7596384968
	public Void remove_onFormulaClicked(Action`1 value) { }
	// RVA: 0x3d6ca5c VA: 0x7596384a5c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3d6cb2c VA: 0x7596384b2c
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, IWorkshopFormula data) { }
	// RVA: 0x3d6d558 VA: 0x7596385558
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x3d6d634 VA: 0x7596385634
	private Void _OnFormulaClicked(IWorkshopFormula formula) { }
	// RVA: 0x3d6d414 VA: 0x7596385414
	private Void _TryRegisterAVGFirstItem(WorkshopFormulaView view) { }
	// RVA: 0x3d6d6d4 VA: 0x75963856d4
	public Void .ctor() { }
}
```