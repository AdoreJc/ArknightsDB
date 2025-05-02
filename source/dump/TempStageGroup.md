# TempStageGroup

**Namespace:** ` `


## Fields

- `String runeGroupId`

- `String stageName`

- `Int64 startTs`

- `Int64 endTs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TempStageGroup
{
	public String runeGroupId; // 0x10
	public String stageName; // 0x18
	public Int64 startTs; // 0x20
	public Int64 endTs; // 0x28
	public String[] runeList; // 0x30
	public Dictionary`2 stagePointLevelInfo; // 0x38
	public List`1 stageChallengeInfo; // 0x40


	// RVA: 0x34b2294 VA: 0x7595aca294
	public Void .ctor() { }
}
```