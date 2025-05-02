# TuningHandbookViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String actId`

- `String selectGroupId`

- `String playBgmId`

- `Boolean isSpecial`


## Methods

- `Void LoadData(String, String)`

- `Void SetSelectGroupId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHandbookViewModel : IHotfixable
{
	public String actId; // 0x10
	public ListDict`2 groupList; // 0x18
	private List`1 formBag; // 0x20
	public String selectGroupId; // 0x28
	public String playBgmId; // 0x30
	public Boolean isSpecial; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetFormulaList; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectGroupId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x232391c VA: 0x759493b91c
	public Void LoadData(String actId, String groupId) { }
	// RVA: 0x2324a34 VA: 0x759493ca34
	public List`1 GetFormulaList() { }
	// RVA: 0x2323ff0 VA: 0x759493bff0
	public Void SetSelectGroupId(String groupId) { }
	// RVA: 0x2323858 VA: 0x759493b858
	public Void .ctor() { }
}
```