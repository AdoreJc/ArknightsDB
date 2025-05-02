# DailyMissionData

**Namespace:** ` `


## Fields

- `String id`

- `Int32 sortId`

- `String description`

- `String missionName`

- `String template`

- `String templateType`

- `String jumpStageId`

- `Int32 agendaCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DailyMissionData
{
	public String id; // 0x10
	public Int32 sortId; // 0x18
	public String description; // 0x20
	public String missionName; // 0x28
	public String template; // 0x30
	public String templateType; // 0x38
	public String[] param; // 0x40
	public List`1 rewards; // 0x48
	public List`1 orgPool; // 0x50
	public List`1 rewardPool; // 0x58
	public String jumpStageId; // 0x60
	public Int32 agendaCount; // 0x68


	// RVA: 0x33b4de8 VA: 0x75959ccde8
	public Void .ctor() { }
}
```