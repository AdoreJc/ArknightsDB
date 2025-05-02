# UniEquipLevelUpStateBean

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `LevelUpViewProperty levelUpViewProperty`

- `UniEquipData uniEquipData`


## Methods

- `Void LoadData(Param)`

- `Void RefreshRequiresData()`

- `Void ReLoadData()`

- `String CheckLevelUpRequirements()`

- `Boolean TrySelectLevel(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpStateBean : IStateBean, IHotfixable, IDataBindWrapper
{
	public LevelUpViewProperty levelUpViewProperty; // 0x10
	public UniEquipData uniEquipData; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshRequiresData; // 0x8
	private static DelegateBridge __Hotfix0_ReLoadData; // 0x10
	private static DelegateBridge __Hotfix0_CheckLevelUpRequirements; // 0x18
	private static DelegateBridge __Hotfix0_TrySelectLevel; // 0x20
	private static DelegateBridge __Hotfix0__CheckEquipRequirementsSatisfied; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2305de4 VA: 0x759491dde4
	public Void LoadData(Param param) { }
	// RVA: 0x2306364 VA: 0x759491e364
	public Void RefreshRequiresData() { }
	// RVA: 0x2306480 VA: 0x759491e480
	public Void ReLoadData() { }
	// RVA: 0x2306864 VA: 0x759491e864
	public String CheckLevelUpRequirements() { }
	// RVA: 0x2306b38 VA: 0x759491eb38
	public Boolean TrySelectLevel(Int32 selectLevel) { }
	// RVA: 0x2306924 VA: 0x759491e924
	private static Boolean _CheckEquipRequirementsSatisfied(List`1 requireViewModels, out String msg) { }
	// RVA: 0x2306ca4 VA: 0x759491eca4
	public Void .ctor() { }
}
```