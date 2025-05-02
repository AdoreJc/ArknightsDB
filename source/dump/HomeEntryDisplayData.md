# HomeEntryDisplayData

**Namespace:** ` `


## Fields

- `String displayId`

- `String topicId`

- `Int64 startTs`

- `Int64 endTs`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HomeEntryDisplayData : ITimeValidInfo, IComparable
{
	public String displayId; // 0x10
	public String topicId; // 0x18
	public Int64 startTs; // 0x20
	public Int64 endTs; // 0x28


	// RVA: 0x34f41c0 VA: 0x7595b0c1c0
	public Int64 GetStartTs() { }
	// RVA: 0x34f41c8 VA: 0x7595b0c1c8
	public Int64 GetEndTs() { }
	// RVA: 0x34f41d0 VA: 0x7595b0c1d0
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x34f4294 VA: 0x7595b0c294
	public Void .ctor() { }
}
```