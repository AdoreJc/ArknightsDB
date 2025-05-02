# SandboxV2RiftSettleViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String riftTopicId`

- `Boolean hasSubTarget`

- `Boolean isSubTargetComplete`

- `Boolean isMainTargetComplete`

- `Boolean isMainTargetFail`

- `Boolean useDifficulty`

- `String mainTargetTitle`

- `Int32 randomRiftDifficultyLevel`

- `Int32 portHpPercent`

- `String riftTeamName`

- `String riftTeamIconId`

- `Int32 riftStayDayCount`

- `String mainTargetDesc`

- `Int32 mainTargetProgress`

- `Int32 mainTargetTotal`

- `String subTargetDesc`

- `Int32 subTargetProgress`

- `Int32 subTargetTotal`


## Methods

- `Void LoadData(String)`

- `Void _GenerateRewardItemViewModel(List`1, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftSettleViewModel
{
	public String riftTopicId; // 0x10
	public Boolean hasSubTarget; // 0x18
	public Boolean isSubTargetComplete; // 0x19
	public Boolean isMainTargetComplete; // 0x1a
	public Boolean isMainTargetFail; // 0x1b
	public Boolean useDifficulty; // 0x1c
	public String mainTargetTitle; // 0x20
	public Int32 randomRiftDifficultyLevel; // 0x28
	public Int32 portHpPercent; // 0x2c
	public String riftTeamName; // 0x30
	public String riftTeamIconId; // 0x38
	public Int32 riftStayDayCount; // 0x40
	public String mainTargetDesc; // 0x48
	public Int32 mainTargetProgress; // 0x50
	public Int32 mainTargetTotal; // 0x54
	public String subTargetDesc; // 0x58
	public Int32 subTargetProgress; // 0x60
	public Int32 subTargetTotal; // 0x64
	public List`1 mainReward; // 0x68
	public List`1 subReward; // 0x70


	// RVA: 0x251b040 VA: 0x7594b33040
	public Void LoadData(String topicId) { }
	// RVA: 0x251d924 VA: 0x7594b35924
	private Void _GenerateRewardItemViewModel(List`1 rewards, ref List`1 outList) { }
	// RVA: 0x251dbb8 VA: 0x7594b35bb8
	public Void .ctor() { }
}
```