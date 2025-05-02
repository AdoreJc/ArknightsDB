# Act1VAutoChessMileStoneGroupViewModelPlugin

**Namespace:** `Torappu.Activity.Act1VAutoChess`


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
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessMileStoneGroupViewModelPlugin : ITemplateActivityMilestonePlugin
{


	// RVA: 0x335e254 VA: 0x7595976254
	public Void InitMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x335e684 VA: 0x7595976684
	public Void UpdateMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x335e8e8 VA: 0x75959768e8
	public Int32 SortMilestoneItem(TemplateActivityMileStoneItemModel m1, TemplateActivityMileStoneItemModel m2) { }
	// RVA: 0x335e91c VA: 0x759597691c
	public Boolean IsItemShow(TemplateActivityMileStoneItemModel itemModel) { }
	// RVA: 0x335e924 VA: 0x7595976924
	public String GetMilestoneId(String actId) { }
	// RVA: 0x335e990 VA: 0x7595976990
	public Int32 UpdateMilestoneCount(String actId) { }
	// RVA: 0x335ea00 VA: 0x7595976a00
	public Boolean NeedFocusToIdx() { }
	// RVA: 0x335ea08 VA: 0x7595976a08
	public IMilestoneServiceConfig GenOneMilConfig(String actId, String milestoneId, Action`1 onProceed) { }
	// RVA: 0x335ea84 VA: 0x7595976a84
	public IMilestoneServiceConfig GenAllMilConfig(String actId, List`1 milestoneList, Action`1 onProceed) { }
	// RVA: 0x335eaf8 VA: 0x7595976af8
	public Boolean IsMilestoneUnlock(String actId) { }
	// RVA: 0x335eb00 VA: 0x7595976b00
	public String GetMilestoneLockedToastDesc(String actId) { }
	// RVA: 0x335eb48 VA: 0x7595976b48
	public Void .ctor() { }
}
```