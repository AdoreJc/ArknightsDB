# BasicData

**Namespace:** ` `


## Fields

- `String id`

- `ActivityType type`

- `ActivityDisplayType displayType`

- `String name`

- `Int64 startTime`

- `Int64 endTime`

- `Int64 rewardEndTime`

- `Boolean displayOnHome`

- `Boolean hasStage`

- `String templateShopId`

- `String medalGroupId`

- `Boolean isReplicate`

- `Boolean needFixedSync`

- `String trapDomainId`

- `ActivityCompleteType recType`

- `Boolean isPageEntry`

- `Boolean isMagnify`

- `Boolean usePicGroup`


## Methods

- `Boolean ShouldSerializedisplayType()`

- `Boolean ShouldSerializeungroupedMedalIds()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BasicData
{
	public String id; // 0x10
	public ActivityType type; // 0x18
	public ActivityDisplayType displayType; // 0x1c
	public String name; // 0x20
	public Int64 startTime; // 0x28
	public Int64 endTime; // 0x30
	public Int64 rewardEndTime; // 0x38
	public Boolean displayOnHome; // 0x40
	public Boolean hasStage; // 0x41
	public String templateShopId; // 0x48
	public String medalGroupId; // 0x50
	public List`1 ungroupedMedalIds; // 0x58
	public Boolean isReplicate; // 0x60
	public Boolean needFixedSync; // 0x61
	public String trapDomainId; // 0x68
	public ActivityCompleteType recType; // 0x70
	public Boolean isPageEntry; // 0x74
	public Boolean isMagnify; // 0x75
	public List`1 picGroup; // 0x78
	public Boolean usePicGroup; // 0x80


	// RVA: 0x33be52c VA: 0x75959d652c
	public Boolean ShouldSerializedisplayType() { }
	// RVA: 0x33be53c VA: 0x75959d653c
	public Boolean ShouldSerializeungroupedMedalIds() { }
	// RVA: 0x33be590 VA: 0x75959d6590
	public Void .ctor() { }
}
```