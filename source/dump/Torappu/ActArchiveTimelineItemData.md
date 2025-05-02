# ActArchiveTimelineItemData

**Namespace:** `Torappu`


## Fields

- `String timelineId`

- `Int32 timelineSortId`

- `String timelineTitle`

- `String timelineDes`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActArchiveTimelineItemData
{
	public String timelineId; // 0x10
	public Int32 timelineSortId; // 0x18
	public String timelineTitle; // 0x20
	public String timelineDes; // 0x28
	public List`1 picIdList; // 0x30
	public List`1 audioIdList; // 0x38
	public List`1 avgIdList; // 0x40
	public List`1 storyIdList; // 0x48
	public List`1 newsIdList; // 0x50


	// RVA: 0x33b4708 VA: 0x75959cc708
	public virtual Boolean ShouldSerializepicIdList() { }
	// RVA: 0x33b4718 VA: 0x75959cc718
	public virtual Boolean ShouldSerializeaudioIdList() { }
	// RVA: 0x33b4728 VA: 0x75959cc728
	public virtual Boolean ShouldSerializeavgIdList() { }
	// RVA: 0x33b4738 VA: 0x75959cc738
	public virtual Boolean ShouldSerializestoryIdList() { }
	// RVA: 0x33b4748 VA: 0x75959cc748
	public virtual Boolean ShouldSerializenewsIdList() { }
	// RVA: 0x33b4758 VA: 0x75959cc758
	public Void .ctor() { }
}
```