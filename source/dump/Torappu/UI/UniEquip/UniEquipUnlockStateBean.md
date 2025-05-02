# UniEquipUnlockStateBean

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `UnlockViewProperty unlockViewProperty`

- `UniEquipData uniEquipData`


## Methods

- `Void LoadData(Param)`

- `Void RefreshData()`

- `String CheckUnlockRequirements()`

- `Void _GeneEquipData(CharQuery, String)`

- `Void _CheckEquipMissionRequirementsSatisfied(UniEquipUnlockViewModel, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipUnlockStateBean : IStateBean, IHotfixable, IDataBindWrapper
{
	public UnlockViewProperty unlockViewProperty; // 0x10
	public UniEquipData uniEquipData; // 0x18
	public List`1 uniEquipMissionList; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0_CheckUnlockRequirements; // 0x10
	private static DelegateBridge __Hotfix0__GeneEquipData; // 0x18
	private static DelegateBridge __Hotfix0__CheckEquipMissionRequirementsSatisfied; // 0x20
	private static DelegateBridge __Hotfix0__CheckEquipRequirementsSatisfied; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x230c804 VA: 0x7594924804
	public Void LoadData(Param param) { }
	// RVA: 0x230d06c VA: 0x759492506c
	public Void RefreshData() { }
	// RVA: 0x230d188 VA: 0x7594925188
	public String CheckUnlockRequirements() { }
	// RVA: 0x230cbe4 VA: 0x7594924be4
	private Void _GeneEquipData(CharQuery charQuery, String equipId) { }
	// RVA: 0x230d29c VA: 0x759492529c
	private Void _CheckEquipMissionRequirementsSatisfied(UniEquipUnlockViewModel viewModel, out String msg) { }
	// RVA: 0x230d508 VA: 0x7594925508
	private static Boolean _CheckEquipRequirementsSatisfied(List`1 requireViewModels, out String msg) { }
	// RVA: 0x230d748 VA: 0x7594925748
	public Void .ctor() { }
}
```