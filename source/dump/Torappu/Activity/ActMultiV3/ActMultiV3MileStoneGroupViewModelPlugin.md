# ActMultiV3MileStoneGroupViewModelPlugin

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Boolean m_hasAddedLockedItem`


## Methods

- `Void InitMilestoneList(String, List`1)`

- `Void UpdateMilestoneList(String, List`1)`

- `Int32 SortMilestoneItem(TemplateActivityMileStoneItemModel, TemplateActivityMileStoneItemModel)`

- `Boolean IsItemShow(TemplateActivityMileStoneItemModel)`

- `String GetMilestoneId(String)`

- `Int32 UpdateMilestoneCount(String)`

- `Boolean NeedFocusToIdx()`

- `IMilestoneServiceConfig GenOneMilConfig(String, String, Action`1)`

- `IMilestoneServiceConfig GenAllMilConfig(String, List`1, Action`1)`

- `Boolean IsMilestoneUnlock(String)`

- `String GetMilestoneLockedToastDesc(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MileStoneGroupViewModelPlugin : ITemplateActivityMilestonePlugin
{
	private Boolean m_hasAddedLockedItem; // 0x10


	// RVA: 0x30f5764 VA: 0x759570d764
	public Void InitMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x30f5a6c VA: 0x759570da6c
	public Void UpdateMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x30f5bb4 VA: 0x759570dbb4
	public Int32 SortMilestoneItem(TemplateActivityMileStoneItemModel m1, TemplateActivityMileStoneItemModel m2) { }
	// RVA: 0x30f5be8 VA: 0x759570dbe8
	public Boolean IsItemShow(TemplateActivityMileStoneItemModel itemModel) { }
	// RVA: 0x30f5c2c VA: 0x759570dc2c
	public String GetMilestoneId(String actId) { }
	// RVA: 0x30f5c5c VA: 0x759570dc5c
	public Int32 UpdateMilestoneCount(String actId) { }
	// RVA: 0x30f5c88 VA: 0x759570dc88
	public Boolean NeedFocusToIdx() { }
	// RVA: 0x30f5c90 VA: 0x759570dc90
	public IMilestoneServiceConfig GenOneMilConfig(String actId, String milestoneId, Action`1 onProceed) { }
	// RVA: 0x30f5d0c VA: 0x759570dd0c
	public IMilestoneServiceConfig GenAllMilConfig(String actId, List`1 milestoneList, Action`1 onProceed) { }
	// RVA: 0x30f5d80 VA: 0x759570dd80
	public Boolean IsMilestoneUnlock(String actId) { }
	// RVA: 0x30f5d88 VA: 0x759570dd88
	public String GetMilestoneLockedToastDesc(String actId) { }
	// RVA: 0x30f5dd0 VA: 0x759570ddd0
	public Void .ctor() { }
}
```