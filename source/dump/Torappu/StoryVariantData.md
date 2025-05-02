# StoryVariantData

**Namespace:** `Torappu`


## Fields

- `String plotTaskId`

- `String spStoryId`

- `String storyId`

- `Int32 priority`

- `Int64 startTime`

- `Int64 endTime`

- `String template`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StoryVariantData
{
	public String plotTaskId; // 0x10
	public String spStoryId; // 0x18
	public String storyId; // 0x20
	public Int32 priority; // 0x28
	public Int64 startTime; // 0x30
	public Int64 endTime; // 0x38
	public String template; // 0x40
	public String[] param; // 0x48


	// RVA: 0x349e09c VA: 0x7595ab609c
	public static Int32 Compare(StoryVariantData lhs, StoryVariantData rhs) { }
	// RVA: 0x349e0f0 VA: 0x7595ab60f0
	public Void .ctor() { }
}
```