# CrossAppShareMission

**Namespace:** `Torappu`


## Fields

- `String shareMissionId`

- `CrossAppShareMissionType missionType`

- `String relateActivityId`

- `Int64 startTime`

- `Int64 endTime`

- `Int32 limitCount`

- `String condTemplate`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CrossAppShareMission
{
	public String shareMissionId; // 0x10
	public CrossAppShareMissionType missionType; // 0x18
	public String relateActivityId; // 0x20
	public Int64 startTime; // 0x28
	public Int64 endTime; // 0x30
	public Int32 limitCount; // 0x38
	public String condTemplate; // 0x40
	public List`1 condParam; // 0x48
	public List`1 rewardsList; // 0x50


	// RVA: 0x34a5d60 VA: 0x7595abdd60
	public Void .ctor() { }
}
```