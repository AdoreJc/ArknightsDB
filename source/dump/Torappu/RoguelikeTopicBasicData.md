# RoguelikeTopicBasicData

**Namespace:** `Torappu`


## Fields

- `String id`

- `String name`

- `Int64 startTime`

- `Int64 disappearTimeOnMainScreen`

- `Int32 sort`

- `String showMedalId`

- `String medalGroupId`

- `Int64 fullStoredTime`

- `String lineText`

- `RoguelikeTopicConfig config`


## Methods

- `Int64 GetEndTs()`

- `Int64 GetStartTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeTopicBasicData : ITimeValidInfo
{
	public String id; // 0x10
	public String name; // 0x18
	public Int64 startTime; // 0x20
	public Int64 disappearTimeOnMainScreen; // 0x28
	public Int32 sort; // 0x30
	public String showMedalId; // 0x38
	public String medalGroupId; // 0x40
	public Int64 fullStoredTime; // 0x48
	public String lineText; // 0x50
	public List`1 homeEntryDisplayData; // 0x58
	public List`1 moduleTypes; // 0x60
	public RoguelikeTopicConfig config; // 0x68


	// RVA: 0x34a95c4 VA: 0x7595ac15c4
	public Int64 GetEndTs() { }
	// RVA: 0x34a95cc VA: 0x7595ac15cc
	public Int64 GetStartTs() { }
	// RVA: 0x34a95d4 VA: 0x7595ac15d4
	public Void .ctor() { }
}
```