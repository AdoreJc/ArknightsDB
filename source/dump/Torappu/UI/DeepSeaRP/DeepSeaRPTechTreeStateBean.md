# DeepSeaRPTechTreeStateBean

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `DeepSeaRPTechTreeViewProperty viewProperty`


## Properties

- `String groupId`


## Methods

- `String get_groupId()`

- `Void LoadData(Boolean, String)`

- `Boolean HaveTechUnlock()`

- `Void UpdateChange(String, TechData)`

- `String GetDefaultBranchId(String)`

- `Void SwitchBranch(String)`

- `Boolean IsSettingChanged()`

- `Void UpdateSettingStateAsChanged()`

- `Void UpdateSettingStateAsSaved()`

- `Void UpdateSettingStateAsNone()`

- `DeepSeaRPTechTreeNodeModel _GetTreeNodeModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPTechTreeStateBean : IStateBean, IHotfixable
{
	public DeepSeaRPTechTreeViewProperty viewProperty; // 0x10
	private static DelegateBridge __Hotfix0_get_groupId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_HaveTechUnlock; // 0x10
	private static DelegateBridge __Hotfix0_UpdateChange; // 0x18
	private static DelegateBridge __Hotfix0_GetDefaultBranchId; // 0x20
	private static DelegateBridge __Hotfix0_SwitchBranch; // 0x28
	private static DelegateBridge __Hotfix0_IsSettingChanged; // 0x30
	private static DelegateBridge __Hotfix0_GetChangedBranchList; // 0x38
	private static DelegateBridge __Hotfix0_UpdateSettingStateAsChanged; // 0x40
	private static DelegateBridge __Hotfix0_UpdateSettingStateAsSaved; // 0x48
	private static DelegateBridge __Hotfix0_UpdateSettingStateAsNone; // 0x50
	private static DelegateBridge __Hotfix0__GetTreeNodeModel; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String groupId { get; }

	// RVA: 0x29e4310 VA: 0x7594ffc310
	public String get_groupId() { }
	// RVA: 0x29e20d0 VA: 0x7594ffa0d0
	public Void LoadData(Boolean isRetro, String groupId) { }
	// RVA: 0x29e2384 VA: 0x7594ffa384
	public Boolean HaveTechUnlock() { }
	// RVA: 0x29e3988 VA: 0x7594ffb988
	public Void UpdateChange(String treeId, TechData data) { }
	// RVA: 0x29e3ba4 VA: 0x7594ffbba4
	public String GetDefaultBranchId(String treeId) { }
	// RVA: 0x29e3e8c VA: 0x7594ffbe8c
	public Void SwitchBranch(String treeId) { }
	// RVA: 0x29e273c VA: 0x7594ffa73c
	public Boolean IsSettingChanged() { }
	// RVA: 0x29e4020 VA: 0x7594ffc020
	public List`1 GetChangedBranchList() { }
	// RVA: 0x29e3c60 VA: 0x7594ffbc60
	public Void UpdateSettingStateAsChanged() { }
	// RVA: 0x29e2fc8 VA: 0x7594ffafc8
	public Void UpdateSettingStateAsSaved() { }
	// RVA: 0x29e33e0 VA: 0x7594ffb3e0
	public Void UpdateSettingStateAsNone() { }
	// RVA: 0x29e496c VA: 0x7594ffc96c
	private DeepSeaRPTechTreeNodeModel _GetTreeNodeModel(String treeId) { }
	// RVA: 0x29e444c VA: 0x7594ffc44c
	public Void .ctor() { }
}
```