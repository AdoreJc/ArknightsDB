# ReturnDailyTaskData

**Namespace:** `Torappu`


## Fields

- `String groupId`

- `String id`

- `Int32 groupSortId`

- `Int32 taskSortId`

- `String template`

- `String desc`

- `Int32 playPoint`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ReturnDailyTaskData
{
	public String groupId; // 0x10
	public String id; // 0x18
	public Int32 groupSortId; // 0x20
	public Int32 taskSortId; // 0x24
	public String template; // 0x28
	public String[] param; // 0x30
	public String desc; // 0x38
	public List`1 rewards; // 0x40
	public Int32 playPoint; // 0x48


	// RVA: 0x34a7718 VA: 0x7595abf718
	public Void .ctor() { }
}
```