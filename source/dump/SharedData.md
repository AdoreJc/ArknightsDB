# SharedData

**Namespace:** ` `


## Fields

- `Int32 skillTriggerCnt`

- `Int32 spScaleCnt`

- `Int32 buildCnt`

- `Int32 deathCnt`

- `FinishReason lastFinishReason`

- `ProfessionCategory extraProfession`

- `Blackboard blackboard`

- `Object extraDatas`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SharedData
{
	public Int32 skillTriggerCnt; // 0x10
	public Int32 spScaleCnt; // 0x14
	public Nullable`1 originCost; // 0x18
	public Int32 buildCnt; // 0x20
	public Int32 deathCnt; // 0x24
	public List`1 managedProjectiles; // 0x28
	public FinishReason lastFinishReason; // 0x30
	public ProfessionCategory extraProfession; // 0x34
	public Blackboard blackboard; // 0x38
	public Object extraDatas; // 0x40
	public Dictionary`2 externalBlackboardDict; // 0x48


	// RVA: 0x1c42338 VA: 0x759425a338
	public Void .ctor() { }
}
```