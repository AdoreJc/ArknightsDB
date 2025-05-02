# StorylineSSData

**Namespace:** `Torappu`


## Fields

- `String name`

- `String desc`

- `String backgroundId`

- `String reopenActivityId`

- `String retroActivityId`

- `Boolean isRecommended`

- `String recommendHideStageId`


## Methods

- `Boolean ShouldSerializereopenActivityId()`

- `Boolean ShouldSerializeretroActivityId()`

- `Boolean ShouldSerializeisRecommended()`

- `Boolean ShouldSerializerecommendHideStageId()`

- `Boolean ShouldSerializeoverrideStageList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StorylineSSData
{
	public String name; // 0x10
	public String desc; // 0x18
	public String backgroundId; // 0x20
	public List`1 tags; // 0x28
	public String reopenActivityId; // 0x30
	public String retroActivityId; // 0x38
	public Boolean isRecommended; // 0x40
	public String recommendHideStageId; // 0x48
	public List`1 overrideStageList; // 0x50


	// RVA: 0x34f80c4 VA: 0x7595b100c4
	public Boolean ShouldSerializereopenActivityId() { }
	// RVA: 0x34f80e4 VA: 0x7595b100e4
	public Boolean ShouldSerializeretroActivityId() { }
	// RVA: 0x34f8104 VA: 0x7595b10104
	public Boolean ShouldSerializeisRecommended() { }
	// RVA: 0x34f810c VA: 0x7595b1010c
	public Boolean ShouldSerializerecommendHideStageId() { }
	// RVA: 0x34f812c VA: 0x7595b1012c
	public Boolean ShouldSerializeoverrideStageList() { }
	// RVA: 0x34f8180 VA: 0x7595b10180
	public Void .ctor() { }
}
```