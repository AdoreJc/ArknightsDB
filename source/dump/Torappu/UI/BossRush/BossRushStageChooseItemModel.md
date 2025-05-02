# BossRushStageChooseItemModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String stageGroupId`

- `String stageGroupName`

- `String stageUnlockCond`

- `Boolean isLocked`

- `Int32 sortId`

- `Boolean isHardStage`

- `Int32 normalStageCount`

- `Int32 waveCount`


## Properties

- `Boolean isStageGroupComplete`

- `Boolean isNormalStageComplete`

- `Boolean isSpComplete`

- `Int32 completeStageCount`


## Methods

- `Boolean get_isStageGroupComplete()`

- `Boolean get_isNormalStageComplete()`

- `Boolean get_isSpComplete()`

- `Int32 get_completeStageCount()`

- `Void LoadData(BossRushStageGroupData)`

- `Void _UpdateStageGroupStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageChooseItemModel : IHotfixable
{
	public String stageGroupId; // 0x10
	public String stageGroupName; // 0x18
	public String stageUnlockCond; // 0x20
	public Boolean isLocked; // 0x28
	public Int32 sortId; // 0x2c
	public Boolean isHardStage; // 0x30
	public Int32 normalStageCount; // 0x34
	public Int32 waveCount; // 0x38
	private Dictionary`2 m_stageIdMap; // 0x40
	private HashSet`1 m_completeStageSet; // 0x48
	private static DelegateBridge __Hotfix0_get_isStageGroupComplete; // 0x0
	private static DelegateBridge __Hotfix0_get_isNormalStageComplete; // 0x8
	private static DelegateBridge __Hotfix0_get_isSpComplete; // 0x10
	private static DelegateBridge __Hotfix0_get_completeStageCount; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0__UpdateStageGroupStatus; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isStageGroupComplete { get; }
	public Boolean isNormalStageComplete { get; }
	public Boolean isSpComplete { get; }
	public Int32 completeStageCount { get; }

	// RVA: 0x2e6f4e4 VA: 0x75954874e4
	public Boolean get_isStageGroupComplete() { }
	// RVA: 0x2e710f4 VA: 0x75954890f4
	public Boolean get_isNormalStageComplete() { }
	// RVA: 0x2e6f570 VA: 0x7595487570
	public Boolean get_isSpComplete() { }
	// RVA: 0x2e6f5fc VA: 0x75954875fc
	public Int32 get_completeStageCount() { }
	// RVA: 0x2e70fcc VA: 0x7595488fcc
	public Void LoadData(BossRushStageGroupData data) { }
	// RVA: 0x2e71348 VA: 0x7595489348
	private Void _UpdateStageGroupStatus() { }
	// RVA: 0x2e70f08 VA: 0x7595488f08
	public Void .ctor() { }
}
```