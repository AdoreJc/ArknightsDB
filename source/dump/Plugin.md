# Plugin

**Namespace:** ` `


## Methods

- `Void InitMilestoneList(String, List`1)`

- `Void UpdateMilestoneList(String, List`1)`

- `Int32 SortMilestoneItem(TemplateActivityMileStoneItemModel, TemplateActivityMileStoneItemModel)`

- `Boolean IsItemShow(TemplateActivityMileStoneItemModel)`

- `String GetMilestoneId(String)`

- `Int32 UpdateMilestoneCount(String)`

- `Boolean NeedFocusToIdx()`

- `Boolean IsMilestoneUnlock(String)`

- `IMilestoneServiceConfig GenOneMilConfig(String, String, Action`1)`

- `IMilestoneServiceConfig GenAllMilConfig(String, List`1, Action`1)`

- `String GetMilestoneLockedToastDesc(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Plugin : ITemplateActivityMilestonePlugin
{


	// RVA: 0x3403070 VA: 0x7595a1b070
	public Void InitMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x340337c VA: 0x7595a1b37c
	public Void UpdateMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x34034c4 VA: 0x7595a1b4c4
	public Int32 SortMilestoneItem(TemplateActivityMileStoneItemModel m1, TemplateActivityMileStoneItemModel m2) { }
	// RVA: 0x34034f8 VA: 0x7595a1b4f8
	public Boolean IsItemShow(TemplateActivityMileStoneItemModel itemModel) { }
	// RVA: 0x3403500 VA: 0x7595a1b500
	public String GetMilestoneId(String actId) { }
	// RVA: 0x340352c VA: 0x7595a1b52c
	public Int32 UpdateMilestoneCount(String actId) { }
	// RVA: 0x340355c VA: 0x7595a1b55c
	public Boolean NeedFocusToIdx() { }
	// RVA: 0x3403564 VA: 0x7595a1b564
	public Boolean IsMilestoneUnlock(String actId) { }
	// RVA: 0x340356c VA: 0x7595a1b56c
	public IMilestoneServiceConfig GenOneMilConfig(String actId, String milestoneId, Action`1 onProceed) { }
	// RVA: 0x34035e8 VA: 0x7595a1b5e8
	public IMilestoneServiceConfig GenAllMilConfig(String actId, List`1 milestoneList, Action`1 onProceed) { }
	// RVA: 0x340365c VA: 0x7595a1b65c
	public String GetMilestoneLockedToastDesc(String actId) { }
	// RVA: 0x33fe690 VA: 0x7595a16690
	public Void .ctor() { }
}
```