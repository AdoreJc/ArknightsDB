# Act38sideFireworkSquadPluginViewModel

**Namespace:** `Torappu.Activity.Act38side`


## Fields

- `Boolean isUnlock`

- `String groupId`

- `String stageId`

- `Boolean canEdit`

- `String currentAnimId`

- `FireworkPlateModel plateModel`

- `StageData stageData`

- `Boolean isShow`


## Methods

- `Void LoadData(PluginInputParams)`

- `String _GetRetroGroupIdByStageId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act38side
public class Act38sideFireworkSquadPluginViewModel : IHotfixable
{
	public Boolean isUnlock; // 0x10
	public String groupId; // 0x18
	public String stageId; // 0x20
	public Boolean canEdit; // 0x28
	public String currentAnimId; // 0x30
	public List`1 itemModelList; // 0x38
	public Dictionary`2 itemModelMap; // 0x40
	public FireworkPlateModel plateModel; // 0x48
	public StageData stageData; // 0x50
	public Boolean isShow; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__GetRetroGroupIdByStageId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x323f338 VA: 0x7595857338
	public Void LoadData(PluginInputParams param) { }
	// RVA: 0x3240bac VA: 0x7595858bac
	private String _GetRetroGroupIdByStageId(String stageId) { }
	// RVA: 0x3240594 VA: 0x7595858594
	public Void .ctor() { }
}
```