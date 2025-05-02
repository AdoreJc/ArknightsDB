# BossRushStageGroupData

**Namespace:** ` `


## Fields

- `String stageGroupId`

- `Int32 sortId`

- `String stageGroupName`

- `Int32 normalStageCount`

- `Boolean isHardStageGroup`

- `String unlockCondtion`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BossRushStageGroupData
{
	public String stageGroupId; // 0x10
	public Int32 sortId; // 0x18
	public String stageGroupName; // 0x20
	public Dictionary`2 stageIdMap; // 0x28
	public List`1 waveBossInfo; // 0x30
	public Int32 normalStageCount; // 0x38
	public Boolean isHardStageGroup; // 0x3c
	public String unlockCondtion; // 0x40


	// RVA: 0x33b9dcc VA: 0x75959d1dcc
	public Void .ctor() { }
}
```