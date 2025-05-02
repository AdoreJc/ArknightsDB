# SixStarMilestoneItemData

**Namespace:** `Torappu`


## Fields

- `String id`

- `Int32 sortId`

- `Int32 nodePoint`

- `SixStarMilestoneRewardType rewardType`

- `String unlockStageFog`

- `String unlockStageId`

- `String unlockStageName`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SixStarMilestoneItemData : IComparable
{
	public String id; // 0x10
	public Int32 sortId; // 0x18
	public Int32 nodePoint; // 0x1c
	public SixStarMilestoneRewardType rewardType; // 0x20
	public String unlockStageFog; // 0x28
	public String unlockStageId; // 0x30
	public String unlockStageName; // 0x38
	public List`1 rewardList; // 0x40


	// RVA: 0x34f6f00 VA: 0x7595b0ef00
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x34f6fd8 VA: 0x7595b0efd8
	public Void .ctor() { }
}
```