# MissionData

**Namespace:** `Torappu`


## Fields

- `String id`

- `Int32 sortId`

- `String description`

- `MissionType type`

- `MissionItemBgType itemBgType`

- `String template`

- `String templateType`

- `String unlockCondition`

- `String missionGroup`

- `String toPage`

- `Int32 periodicalPoint`

- `String backImagePath`

- `String foldId`

- `Boolean haveSubMissionToUnlock`

- `Int64 countEndTs`


## Methods

- `Boolean ShouldSerializecountEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MissionData
{
	public String id; // 0x10
	public Int32 sortId; // 0x18
	public String description; // 0x20
	public MissionType type; // 0x28
	public MissionItemBgType itemBgType; // 0x2c
	public List`1 preMissionIds; // 0x30
	public String template; // 0x38
	public String templateType; // 0x40
	public String[] param; // 0x48
	public String unlockCondition; // 0x50
	public String[] unlockParam; // 0x58
	public String missionGroup; // 0x60
	public String toPage; // 0x68
	public Int32 periodicalPoint; // 0x70
	public List`1 rewards; // 0x78
	public String backImagePath; // 0x80
	public String foldId; // 0x88
	public Boolean haveSubMissionToUnlock; // 0x90
	public Int64 countEndTs; // 0x98


	// RVA: 0x34a5cb0 VA: 0x7595abdcb0
	public Boolean ShouldSerializecountEndTs() { }
	// RVA: 0x349bf38 VA: 0x7595ab3f38
	public Void .ctor() { }
}
```