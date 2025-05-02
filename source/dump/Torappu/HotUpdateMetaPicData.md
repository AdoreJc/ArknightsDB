# HotUpdateMetaPicData

**Namespace:** `Torappu`


## Fields

- `String picId`

- `Int32 groupId`

- `Int32 sortId`

- `Int64 startTime`

- `Int64 endTime`

- `PicType picType`

- `String logoId`

- `String color`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HotUpdateMetaPicData : ITimeValidInfo
{
	public String picId; // 0x10
	public Int32 groupId; // 0x18
	public Int32 sortId; // 0x1c
	public Int64 startTime; // 0x20
	public Int64 endTime; // 0x28
	public List`1 textList; // 0x30
	public PicType picType; // 0x38
	public String logoId; // 0x40
	public String color; // 0x48


	// RVA: 0x34a3490 VA: 0x7595abb490
	public Int64 GetStartTs() { }
	// RVA: 0x34a3498 VA: 0x7595abb498
	public Int64 GetEndTs() { }
	// RVA: 0x34a34a0 VA: 0x7595abb4a0
	public Void .ctor() { }
}
```