# ActVecBreakMileStoneGroupPlugin

**Namespace:** `Torappu.Activity.ActVecBreak`


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
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakMileStoneGroupPlugin : ITemplateActivityMilestonePlugin
{
	private Boolean m_hasAddedLockedItem; // 0x10


	// RVA: 0x30d4eb8 VA: 0x75956eceb8
	public Void InitMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x30d521c VA: 0x75956ed21c
	public Void UpdateMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x30d5364 VA: 0x75956ed364
	public Int32 SortMilestoneItem(TemplateActivityMileStoneItemModel m1, TemplateActivityMileStoneItemModel m2) { }
	// RVA: 0x30d5398 VA: 0x75956ed398
	public Boolean IsItemShow(TemplateActivityMileStoneItemModel itemModel) { }
	// RVA: 0x30d53dc VA: 0x75956ed3dc
	public String GetMilestoneId(String actId) { }
	// RVA: 0x30d5408 VA: 0x75956ed408
	public Int32 UpdateMilestoneCount(String actId) { }
	// RVA: 0x30d5434 VA: 0x75956ed434
	public Boolean NeedFocusToIdx() { }
	// RVA: 0x30d543c VA: 0x75956ed43c
	public IMilestoneServiceConfig GenOneMilConfig(String actId, String milestoneId, Action`1 onProceed) { }
	// RVA: 0x30d54b8 VA: 0x75956ed4b8
	public IMilestoneServiceConfig GenAllMilConfig(String actId, List`1 milestoneList, Action`1 onProceed) { }
	// RVA: 0x30d552c VA: 0x75956ed52c
	public Boolean IsMilestoneUnlock(String actId) { }
	// RVA: 0x30d5534 VA: 0x75956ed534
	public String GetMilestoneLockedToastDesc(String actId) { }
	// RVA: 0x30d36b0 VA: 0x75956eb6b0
	public Void .ctor() { }
}
```