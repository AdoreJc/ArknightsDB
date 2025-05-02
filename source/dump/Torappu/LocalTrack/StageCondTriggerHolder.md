# StageCondTriggerHolder

**Namespace:** `Torappu.LocalTrack`


## Methods

- `Boolean _CheckIfStageRankSatisfied(String, PlayerStageState, PlayerDataModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.LocalTrack
public class StageCondTriggerHolder : PlayerTrackTriggerHolder`1
{
	private static DelegateBridge __Hotfix0_CreatePlayerDataPathList; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfToTrigger; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfStageRankSatisfied; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f199c8 VA: 0x75965319c8
	protected override IList`1 CreatePlayerDataPathList() { }
	// RVA: 0x3f19b68 VA: 0x7596531b68
	protected override Boolean CheckIfToTrigger(StageCondTrigger trigger, PlayerDataModel prevData, PlayerDataModel curData) { }
	// RVA: 0x3f19c58 VA: 0x7596531c58
	private Boolean _CheckIfStageRankSatisfied(String stageId, PlayerStageState target, PlayerDataModel data) { }
	// RVA: 0x3f19d78 VA: 0x7596531d78
	public Void .ctor() { }
}
```