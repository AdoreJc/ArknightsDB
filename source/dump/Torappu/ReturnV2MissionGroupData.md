# ReturnV2MissionGroupData

**Namespace:** `Torappu`


## Fields

- `String groupId`

- `Int32 sortId`

- `String tabTitle`

- `String title`

- `String desc`

- `Int32 diffMissionCount`

- `Int64 startTime`

- `Int64 endTime`

- `String imageId`

- `String iconId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ReturnV2MissionGroupData
{
	public String groupId; // 0x10
	public Int32 sortId; // 0x18
	public String tabTitle; // 0x20
	public String title; // 0x28
	public String desc; // 0x30
	public Int32 diffMissionCount; // 0x38
	public Int64 startTime; // 0x40
	public Int64 endTime; // 0x48
	public String imageId; // 0x50
	public String iconId; // 0x58
	public List`1 missionList; // 0x60


	// RVA: 0x34a7a64 VA: 0x7595abfa64
	public Void .ctor() { }
}
```