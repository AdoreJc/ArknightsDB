# CommonAvailCheck

**Namespace:** `Torappu`


## Fields

- `Int64 startTs`

- `Int64 endTs`

- `CommonUnlockType type`

- `Single rate`

- `StageUnlockParam stageUnlockParam`

- `CharUnlockParam charUnlockParam`


## Methods

- `Boolean ShouldSerializestageUnlockParam()`

- `Boolean ShouldSerializecharUnlockParam()`

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CommonAvailCheck : ITimeValidInfo
{
	public Int64 startTs; // 0x10
	public Int64 endTs; // 0x18
	public CommonUnlockType type; // 0x20
	public Single rate; // 0x24
	public StageUnlockParam stageUnlockParam; // 0x28
	public CharUnlockParam charUnlockParam; // 0x30


	// RVA: 0x34a535c VA: 0x7595abd35c
	public Boolean ShouldSerializestageUnlockParam() { }
	// RVA: 0x34a536c VA: 0x7595abd36c
	public Boolean ShouldSerializecharUnlockParam() { }
	// RVA: 0x34a537c VA: 0x7595abd37c
	public Int64 GetStartTs() { }
	// RVA: 0x34a5384 VA: 0x7595abd384
	public Int64 GetEndTs() { }
	// RVA: 0x34a538c VA: 0x7595abd38c
	public Void .ctor() { }
}
```