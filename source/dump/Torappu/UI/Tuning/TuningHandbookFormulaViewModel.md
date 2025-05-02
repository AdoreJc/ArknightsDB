# TuningHandbookFormulaViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String formId`

- `String formDesc`

- `Int32 formSortId`

- `Boolean isLock`


## Methods

- `Void LoadData(String, Act29SideFormData, Dictionary`2, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHandbookFormulaViewModel : IHotfixable
{
	public String formId; // 0x10
	public String formDesc; // 0x18
	public Dictionary`2 fragDataList; // 0x20
	public List`1 fragIdList; // 0x28
	public Int32 formSortId; // 0x30
	public Boolean isLock; // 0x34
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2325448 VA: 0x759493d448
	public Void LoadData(String formId, Act29SideFormData formulaData, Dictionary`2 fragDataList, Boolean isLock) { }
	// RVA: 0x23253d8 VA: 0x759493d3d8
	public Void .ctor() { }
}
```