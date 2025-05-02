# RecordRewardInfo

**Namespace:** `Torappu`


## Fields

- `String bindStageId`

- `RecordRewardStageDiff stageDiff1`

- `StageDiffGroup stageDiff`

- `String picRes`

- `String textPath`

- `String textDesc`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RecordRewardInfo
{
	public String bindStageId; // 0x10
	public RecordRewardStageDiff stageDiff1; // 0x18
	public StageDiffGroup stageDiff; // 0x1c
	public String picRes; // 0x20
	public String textPath; // 0x28
	public String textDesc; // 0x30
	public ItemBundle[] recordReward; // 0x38


	// RVA: 0x34f92b0 VA: 0x7595b112b0
	public Void .ctor() { }
}
```