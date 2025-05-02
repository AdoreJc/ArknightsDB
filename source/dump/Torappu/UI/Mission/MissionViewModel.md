# MissionViewModel

**Namespace:** `Torappu.UI.Mission`


## Fields

- `String missionText`

- `String stringPath`

- `MissionHoldingState state`

- `Int32 target`

- `Int32 value`

- `MissionData data`

- `String foldId`


## Properties

- `String description`


## Methods

- `String get_description()`

- `Boolean CheckIfAbleToFinish()`

- `Single GetMissionProgress()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionViewModel : IHotfixable
{
	public String missionText; // 0x10
	public String stringPath; // 0x18
	public MissionHoldingState state; // 0x20
	public Int32 target; // 0x24
	public Int32 value; // 0x28
	public MissionData data; // 0x30
	public List`1 rewardList; // 0x38
	public String foldId; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_description; // 0x8
	private static DelegateBridge __Hotfix0_ChangeRewardDataType; // 0x10
	private static DelegateBridge __Hotfix0_GetRewardPreviewItem; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfAbleToFinish; // 0x20
	private static DelegateBridge __Hotfix0_GetMissionProgress; // 0x28

	public String description { get; }

	// RVA: 0x2736e7c VA: 0x7594d4ee7c
	public Void .ctor(Int32 state_, Int32 target_, Int32 value_, List`1 rewards, MissionData data_, String backPath_, String foldId_) { }
	// RVA: 0x27383f4 VA: 0x7594d503f4
	public String get_description() { }
	// RVA: 0x273848c VA: 0x7594d5048c
	public static UIItemViewModel ChangeRewardDataType(MissionDisplayRewards data) { }
	// RVA: 0x273853c VA: 0x7594d5053c
	public UIItemViewModel[] GetRewardPreviewItem() { }
	// RVA: 0x2738780 VA: 0x7594d50780
	public Boolean CheckIfAbleToFinish() { }
	// RVA: 0x2738804 VA: 0x7594d50804
	public Single GetMissionProgress() { }
}
```