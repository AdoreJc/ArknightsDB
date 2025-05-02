# StorylineStorySetData

**Namespace:** `Torappu`


## Fields

- `String storySetId`

- `StorylineStorySetType storySetType`

- `Int32 sortByYear`

- `Int32 sortWithinYear`

- `String kvImageId`

- `String titleImageId`

- `String backgroundId`

- `String gameMusicId`

- `ItemType coreRewardType`

- `String coreRewardId`

- `String relevantActivityId`

- `StorylineMainlineData mainlineData`

- `StorylineSSData ssData`

- `StorylineCollectData collectData`


## Methods

- `Boolean ShouldSerializekvImageId()`

- `Boolean ShouldSerializetitleImageId()`

- `Boolean ShouldSerializebackgroundId()`

- `Boolean ShouldSerializecoreRewardType()`

- `Boolean ShouldSerializecoreRewardId()`

- `Boolean ShouldSerializerelevantActivityId()`

- `Boolean ShouldSerializemainlineData()`

- `Boolean ShouldSerializessData()`

- `Boolean ShouldSerializecollectData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StorylineStorySetData
{
	public String storySetId; // 0x10
	public StorylineStorySetType storySetType; // 0x18
	public Int32 sortByYear; // 0x1c
	public Int32 sortWithinYear; // 0x20
	public String kvImageId; // 0x28
	public String titleImageId; // 0x30
	public String backgroundId; // 0x38
	public String gameMusicId; // 0x40
	public ItemType coreRewardType; // 0x48
	public String coreRewardId; // 0x50
	public String relevantActivityId; // 0x58
	public StorylineMainlineData mainlineData; // 0x60
	public StorylineSSData ssData; // 0x68
	public StorylineCollectData collectData; // 0x70


	// RVA: 0x34f7f94 VA: 0x7595b0ff94
	public Boolean ShouldSerializekvImageId() { }
	// RVA: 0x34f7fb4 VA: 0x7595b0ffb4
	public Boolean ShouldSerializetitleImageId() { }
	// RVA: 0x34f7fd4 VA: 0x7595b0ffd4
	public Boolean ShouldSerializebackgroundId() { }
	// RVA: 0x34f7ff4 VA: 0x7595b0fff4
	public Boolean ShouldSerializecoreRewardType() { }
	// RVA: 0x34f8004 VA: 0x7595b10004
	public Boolean ShouldSerializecoreRewardId() { }
	// RVA: 0x34f8024 VA: 0x7595b10024
	public Boolean ShouldSerializerelevantActivityId() { }
	// RVA: 0x34f8044 VA: 0x7595b10044
	public Boolean ShouldSerializemainlineData() { }
	// RVA: 0x34f8054 VA: 0x7595b10054
	public Boolean ShouldSerializessData() { }
	// RVA: 0x34f8064 VA: 0x7595b10064
	public Boolean ShouldSerializecollectData() { }
	// RVA: 0x34f8074 VA: 0x7595b10074
	public Void .ctor() { }
}
```