# TuningHandbookStateBean

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String actId`

- `String emotionId`

- `TuningHandbookProperty viewProperty`


## Methods

- `Void LoadData()`

- `Void SelectGroup(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHandbookStateBean : IStateBean, IHotfixable
{
	public String actId; // 0x10
	public String emotionId; // 0x18
	public TuningHandbookProperty viewProperty; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SelectGroup; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2322b78 VA: 0x759493ab78
	public Void LoadData() { }
	// RVA: 0x2322fc8 VA: 0x759493afc8
	public Void SelectGroup(String sId) { }
	// RVA: 0x232379c VA: 0x759493b79c
	public Void .ctor() { }
}
```