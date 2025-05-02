# ActivityThemeData

**Namespace:** `Torappu`


## Fields

- `String id`

- `ActivityThemeType type`

- `String funcId`

- `Int64 endTs`

- `Int32 sortId`

- `String itemId`

- `Int64 startTs`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActivityThemeData : ITimeValidInfo
{
	public String id; // 0x10
	public ActivityThemeType type; // 0x18
	public String funcId; // 0x20
	public Int64 endTs; // 0x28
	public Int32 sortId; // 0x30
	public String itemId; // 0x38
	public List`1 timeNodes; // 0x40
	public List`1 picGroups; // 0x48
	public Int64 startTs; // 0x50


	// RVA: 0x33bcdb0 VA: 0x75959d4db0
	public Int64 GetStartTs() { }
	// RVA: 0x33bcdb8 VA: 0x75959d4db8
	public Int64 GetEndTs() { }
	// RVA: 0x33bcdc0 VA: 0x75959d4dc0
	public Void .ctor() { }
}
```