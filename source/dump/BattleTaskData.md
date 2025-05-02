# BattleTaskData

**Namespace:** ` `


## Fields

- `String taskId`

- `String stageId`

- `String battleTaskDesc`

- `String targetType`

- `String targetTemplate`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BattleTaskData
{
	public String taskId; // 0x10
	public String stageId; // 0x18
	public String battleTaskDesc; // 0x20
	public String targetType; // 0x28
	public String targetTemplate; // 0x30
	public List`1 targetParamList; // 0x38


	// RVA: 0x33b5dd4 VA: 0x75959cddd4
	public virtual Boolean ShouldSerializetargetType() { }
	// RVA: 0x33b5df4 VA: 0x75959cddf4
	public virtual Boolean ShouldSerializetargetTemplate() { }
	// RVA: 0x33b5e14 VA: 0x75959cde14
	public virtual Boolean ShouldSerializetargetParamList() { }
	// RVA: 0x33b5e24 VA: 0x75959cde24
	public Void .ctor() { }
}
```