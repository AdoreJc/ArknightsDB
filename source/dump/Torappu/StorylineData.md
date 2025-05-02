# StorylineData

**Namespace:** `Torappu`


## Fields

- `String storylineId`

- `StorylineType storylineType`

- `Int32 sortId`

- `String storylineName`

- `String storylineIconId`

- `String backgroundId`

- `Int64 startTs`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StorylineData
{
	public String storylineId; // 0x10
	public StorylineType storylineType; // 0x18
	public Int32 sortId; // 0x1c
	public String storylineName; // 0x20
	public String storylineIconId; // 0x28
	public String backgroundId; // 0x30
	public Int64 startTs; // 0x38
	public ListDict`2 locations; // 0x40


	// RVA: 0x34f7f0c VA: 0x7595b0ff0c
	public Void .ctor() { }
}
```