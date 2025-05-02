# Act1LockZoneMapViewModel

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `String m_selectStageId`

- `String id`

- `String name`

- `Boolean isFinalUnlocked`

- `Boolean anyInterlockUnlocked`


## Properties

- `String selectedStageId`

- `Boolean hasStage`


## Methods

- `String get_selectedStageId()`

- `Void set_selectedStageId(String)`

- `Boolean get_hasStage()`

- `Void RefreshInfo()`

- `Void LoadData()`

- `Act1LockStageViewModel GetStageViewModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockZoneMapViewModel : IHotfixable
{
	private String m_selectStageId; // 0x10
	public String id; // 0x18
	public String name; // 0x20
	public Boolean isFinalUnlocked; // 0x28
	public Boolean anyInterlockUnlocked; // 0x29
	public List`1 stageViewModelList; // 0x30
	public Dictionary`2 stageDict; // 0x38
	private static DelegateBridge __Hotfix0_get_selectedStageId; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedStageId; // 0x8
	private static DelegateBridge __Hotfix0_get_hasStage; // 0x10
	private static DelegateBridge __Hotfix0_RefreshInfo; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_GetStageViewModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String selectedStageId { get; set; }
	public Boolean hasStage { get; }

	// RVA: 0x33cf368 VA: 0x75959e7368
	public String get_selectedStageId() { }
	// RVA: 0x33d99bc VA: 0x75959f19bc
	public Void set_selectedStageId(String value) { }
	// RVA: 0x33d9a40 VA: 0x75959f1a40
	public Boolean get_hasStage() { }
	// RVA: 0x33d9acc VA: 0x75959f1acc
	public Void RefreshInfo() { }
	// RVA: 0x33d9c98 VA: 0x75959f1c98
	public Void LoadData() { }
	// RVA: 0x33cef4c VA: 0x75959e6f4c
	public Act1LockStageViewModel GetStageViewModel(String stageId) { }
	// RVA: 0x33da1b8 VA: 0x75959f21b8
	public Void .ctor() { }
}
```