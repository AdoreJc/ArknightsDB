# VecBreakDefenseStageViewModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `String stageActId`

- `Boolean isOpen`

- `Int64 openTime`

- `Boolean isBuffActive`

- `String daysToOpen`

- `String stageId`

- `Int32 sortId`

- `String stageName`

- `String stageDesc`

- `Boolean passed`

- `Int32 defenseCharLimit`

- `String rewardItemId`

- `Int32 rewardCnt`

- `String bossIconId`

- `String buffId`

- `String buffName`

- `String buffDesc`

- `String buffIconId`


## Methods

- `Void LoadData(String, ActVecBreakBattleBuffData, StageData, ActVecBreakDefenseStageData)`

- `Void RefreshPlayerData(PlayerVecBreakActivity, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseStageViewModel : IHotfixable
{
	public String stageActId; // 0x10
	public Boolean isOpen; // 0x18
	public Int64 openTime; // 0x20
	public Boolean isBuffActive; // 0x28
	public String daysToOpen; // 0x30
	public String stageId; // 0x38
	public Int32 sortId; // 0x40
	public String stageName; // 0x48
	public String stageDesc; // 0x50
	public Boolean passed; // 0x58
	public Int32 defenseCharLimit; // 0x5c
	public String rewardItemId; // 0x60
	public Int32 rewardCnt; // 0x68
	public String bossIconId; // 0x70
	public String buffId; // 0x78
	public String buffName; // 0x80
	public String buffDesc; // 0x88
	public String buffIconId; // 0x90
	public List`1 defendChars; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22c9730 VA: 0x75948e1730
	public Void LoadData(String actId, ActVecBreakBattleBuffData buffData, StageData stageData, ActVecBreakDefenseStageData defStageData) { }
	// RVA: 0x22c9938 VA: 0x75948e1938
	public Void RefreshPlayerData(PlayerVecBreakActivity playerVecData, Dictionary`2 playerStages) { }
	// RVA: 0x22ca2fc VA: 0x75948e22fc
	public Void .ctor() { }
}
```