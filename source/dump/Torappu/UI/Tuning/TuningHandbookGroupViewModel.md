# TuningHandbookGroupViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String actId`

- `String groupId`

- `String groupName`

- `String groupDesc`

- `String defaultBgmSignal`

- `String groupEngName`

- `String groupSmallName`

- `String groupTypeIcon`

- `String groupTypeBasePic`

- `Int32 groupSortId`

- `Boolean isSpecial`

- `Boolean isLock`

- `String selectId`


## Methods

- `Void LoadData(String, String, Act29SideProductGroupData, String)`

- `Void SetFormulaList(Act29SideProductGroupData, Dictionary`2, Dictionary`2, List`1, Boolean)`

- `Void UpdateSelect(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHandbookGroupViewModel : IHotfixable
{
	public String actId; // 0x10
	public String groupId; // 0x18
	public String groupName; // 0x20
	public String groupDesc; // 0x28
	public String defaultBgmSignal; // 0x30
	public String groupEngName; // 0x38
	public String groupSmallName; // 0x40
	public String groupTypeIcon; // 0x48
	public String groupTypeBasePic; // 0x50
	public Int32 groupSortId; // 0x58
	public Boolean isSpecial; // 0x5c
	public Boolean isLock; // 0x5d
	public String selectId; // 0x60
	public List`1 formulaModelList; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetFormulaList; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSelect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2324f28 VA: 0x759493cf28
	public Void LoadData(String actId, String emotionId, Act29SideProductGroupData groupData, String selectId) { }
	// RVA: 0x2325070 VA: 0x759493d070
	public Void SetFormulaList(Act29SideProductGroupData groupData, Dictionary`2 formulaDataList, Dictionary`2 fragDataList, List`1 formBag, Boolean isSpLock) { }
	// RVA: 0x232553c VA: 0x759493d53c
	public Void UpdateSelect(String id) { }
	// RVA: 0x23255c0 VA: 0x759493d5c0
	public Void .ctor() { }
}
```