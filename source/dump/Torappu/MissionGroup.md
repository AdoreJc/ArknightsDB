# MissionGroup

**Namespace:** `Torappu`


## Fields

- `String id`

- `String title`

- `MissionType type`

- `String preMissionGroup`

- `Int64 startTs`

- `Int64 endTs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MissionGroup
{
	public String id; // 0x10
	public String title; // 0x18
	public MissionType type; // 0x20
	public String preMissionGroup; // 0x28
	public Int32[] period; // 0x30
	public List`1 rewards; // 0x38
	public String[] missionIds; // 0x40
	public Int64 startTs; // 0x48
	public Int64 endTs; // 0x50


	// RVA: 0x34a5cd8 VA: 0x7595abdcd8
	public Void .ctor() { }
}
```