# TemplateMissionViewModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `String actId`

- `String missionText`

- `MissionHoldingState state`

- `Int32 target`

- `Int32 value`

- `MissionData data`

- `DataBundle meta`


## Properties

- `String description`


## Methods

- `String get_description()`

- `Boolean CheckIfAbleToFinish()`

- `Single GetMissionProgress()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateMissionViewModel : IHotfixable
{
	public String actId; // 0x10
	public String missionText; // 0x18
	public MissionHoldingState state; // 0x20
	public Int32 target; // 0x24
	public Int32 value; // 0x28
	public MissionData data; // 0x30
	public List`1 rewardList; // 0x38
	public DataBundle meta; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge _c__Hotfix1_ctor; // 0x8
	private static DelegateBridge __Hotfix0_get_description; // 0x10
	private static DelegateBridge __Hotfix0_ChangeRewardDataType; // 0x18
	private static DelegateBridge __Hotfix0_GetRewardPreviewItem; // 0x20
	private static DelegateBridge __Hotfix0_CheckIfAbleToFinish; // 0x28
	private static DelegateBridge __Hotfix0_GetMissionProgress; // 0x30

	public String description { get; }

	// RVA: 0x30aea10 VA: 0x75956c6a10
	public Void .ctor() { }
	// RVA: 0x30aea80 VA: 0x75956c6a80
	public Void .ctor(String actId_, Int32 state_, Int32 target_, Int32 value_, List`1 rewards, MissionData data_, DataBundle meta_) { }
	// RVA: 0x30aeb8c VA: 0x75956c6b8c
	public String get_description() { }
	// RVA: 0x30aec24 VA: 0x75956c6c24
	public static BasicActivityItemViewModel ChangeRewardDataType(String actId, MissionDisplayRewards data) { }
	// RVA: 0x30aed00 VA: 0x75956c6d00
	public List`1 GetRewardPreviewItem() { }
	// RVA: 0x30aef04 VA: 0x75956c6f04
	public Boolean CheckIfAbleToFinish() { }
	// RVA: 0x30aef88 VA: 0x75956c6f88
	public Single GetMissionProgress() { }
}
```