# ActMultiV3GuideBattleFinishRequest

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String activityId`

- `Boolean giveUp`

- `NormalGuideStatus normal`

- `FootballGuideStatus football`

- `DefenceGuideStatus defence`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3GuideBattleFinishRequest : CommonFinishBattleRequest
{
	public String activityId; // 0x20
	public Boolean giveUp; // 0x28
	public NormalGuideStatus normal; // 0x30
	public FootballGuideStatus football; // 0x38
	public DefenceGuideStatus defence; // 0x40


	// RVA: 0x30dc74c VA: 0x75956f474c
	public Void .ctor() { }
}
```