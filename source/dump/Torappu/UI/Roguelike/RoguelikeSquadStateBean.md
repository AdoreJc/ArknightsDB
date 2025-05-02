# RoguelikeSquadStateBean

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Int32 troopCount`


## Methods

- `Void AttachPluginContexts(List`1)`

- `Void LoadData(String)`

- `Int32 GetCurCapacity()`

- `Void ConfirmSquad()`

- `Void _UniformSquad()`

- `Void SaveLocalCache()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSquadStateBean : IStateBean, IHotfixable
{
	public List`1 viewModelList; // 0x10
	public Int32 troopCount; // 0x18
	private HashSet`1 m_sharedSet; // 0x20
	private Dictionary`2 m_sharedSkillPref; // 0x28
	private Dictionary`2 m_sharedBranchPref; // 0x30
	private Dictionary`2 m_sharedSkillCounts; // 0x38
	private List`1 m_pluginContexts; // 0x40
	private static DelegateBridge __Hotfix0_AttachPluginContexts; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_GetCurCapacity; // 0x10
	private static DelegateBridge __Hotfix0_LoadSquadSkillPref; // 0x18
	private static DelegateBridge __Hotfix0_LoadSquadSkillCount; // 0x20
	private static DelegateBridge __Hotfix0_LoadSquadBranchPref; // 0x28
	private static DelegateBridge __Hotfix0_ConfirmSquad; // 0x30
	private static DelegateBridge __Hotfix0__UniformSquad; // 0x38
	private static DelegateBridge __Hotfix0_SaveLocalCache; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2af2de8 VA: 0x759510ade8
	public Void AttachPluginContexts(List`1 pluginContexts) { }
	// RVA: 0x2af2f68 VA: 0x759510af68
	public Void LoadData(String topicId) { }
	// RVA: 0x2af3218 VA: 0x759510b218
	public Int32 GetCurCapacity() { }
	// RVA: 0x2af3930 VA: 0x759510b930
	public Dictionary`2 LoadSquadSkillPref() { }
	// RVA: 0x2af3a6c VA: 0x759510ba6c
	public Dictionary`2 LoadSquadSkillCount() { }
	// RVA: 0x2af3ba8 VA: 0x759510bba8
	public Dictionary`2 LoadSquadBranchPref() { }
	// RVA: 0x2af41f8 VA: 0x759510c1f8
	public Void ConfirmSquad() { }
	// RVA: 0x2af7ff4 VA: 0x759510fff4
	private Void _UniformSquad() { }
	// RVA: 0x2af4260 VA: 0x759510c260
	public Void SaveLocalCache() { }
	// RVA: 0x2af6f78 VA: 0x759510ef78
	public Void .ctor() { }
}
```