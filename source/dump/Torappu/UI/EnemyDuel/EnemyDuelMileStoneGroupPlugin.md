# EnemyDuelMileStoneGroupPlugin

**Namespace:** `Torappu.UI.EnemyDuel`


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
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelMileStoneGroupPlugin : ITemplateActivityMilestonePlugin, IHotfixable
{
	private Boolean m_hasAddedLockedItem; // 0x10
	private static DelegateBridge __Hotfix0_InitMilestoneList; // 0x0
	private static DelegateBridge __Hotfix0_UpdateMilestoneList; // 0x8
	private static DelegateBridge __Hotfix0_SortMilestoneItem; // 0x10
	private static DelegateBridge __Hotfix0_IsItemShow; // 0x18
	private static DelegateBridge __Hotfix0_GetMilestoneId; // 0x20
	private static DelegateBridge __Hotfix0_UpdateMilestoneCount; // 0x28
	private static DelegateBridge __Hotfix0_NeedFocusToIdx; // 0x30
	private static DelegateBridge __Hotfix0_GenOneMilConfig; // 0x38
	private static DelegateBridge __Hotfix0_GenAllMilConfig; // 0x40
	private static DelegateBridge __Hotfix0_IsMilestoneUnlock; // 0x48
	private static DelegateBridge __Hotfix0_GetMilestoneLockedToastDesc; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x29503f0 VA: 0x7594f683f0
	public Void InitMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x2950794 VA: 0x7594f68794
	public Void UpdateMilestoneList(String actId, List`1 milestoneList) { }
	// RVA: 0x2950948 VA: 0x7594f68948
	public Int32 SortMilestoneItem(TemplateActivityMileStoneItemModel m1, TemplateActivityMileStoneItemModel m2) { }
	// RVA: 0x29509f0 VA: 0x7594f689f0
	public Boolean IsItemShow(TemplateActivityMileStoneItemModel itemModel) { }
	// RVA: 0x2950a9c VA: 0x7594f68a9c
	public String GetMilestoneId(String actId) { }
	// RVA: 0x2950b54 VA: 0x7594f68b54
	public Int32 UpdateMilestoneCount(String actId) { }
	// RVA: 0x2950c0c VA: 0x7594f68c0c
	public Boolean NeedFocusToIdx() { }
	// RVA: 0x2950c74 VA: 0x7594f68c74
	public IMilestoneServiceConfig GenOneMilConfig(String actId, String milestoneId, Action`1 onProceed) { }
	// RVA: 0x2950d48 VA: 0x7594f68d48
	public IMilestoneServiceConfig GenAllMilConfig(String actId, List`1 milestoneList, Action`1 onProceed) { }
	// RVA: 0x2950e18 VA: 0x7594f68e18
	public Boolean IsMilestoneUnlock(String actId) { }
	// RVA: 0x2950e94 VA: 0x7594f68e94
	public String GetMilestoneLockedToastDesc(String actId) { }
	// RVA: 0x2946ab8 VA: 0x7594f5eab8
	public Void .ctor() { }
}
```