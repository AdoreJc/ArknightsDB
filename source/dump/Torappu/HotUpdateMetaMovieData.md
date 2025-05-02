# HotUpdateMetaMovieData

**Namespace:** `Torappu`


## Fields

- `String videoId`

- `String videoPath`

- `Int64 endTime`

- `Int32 sortId`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HotUpdateMetaMovieData : ITimeValidInfo
{
	public String videoId; // 0x10
	public String videoPath; // 0x18
	public Int64 endTime; // 0x20
	public Int32 sortId; // 0x28


	// RVA: 0x34a3478 VA: 0x7595abb478
	public Int64 GetStartTs() { }
	// RVA: 0x34a3480 VA: 0x7595abb480
	public Int64 GetEndTs() { }
	// RVA: 0x34a3488 VA: 0x7595abb488
	public Void .ctor() { }
}
```