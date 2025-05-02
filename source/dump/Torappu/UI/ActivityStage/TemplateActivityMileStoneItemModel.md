# TemplateActivityMileStoneItemModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `Status m_status`

- `String m_milestoneId`

- `String m_costItemId`

- `String m_milestoneGroupName`

- `Int32 m_costItemCount`

- `Int32 m_sortId`

- `Int64 m_unlockTs`


## Properties

- `Status status`

- `Int32 sortId`

- `String milestoneGroupName`

- `String milestoneId`

- `String costItemId`

- `Int32 costItemCount`

- `Int64 unlockTs`


## Methods

- `Status get_status()`

- `Int32 get_sortId()`

- `String get_milestoneGroupName()`

- `String get_milestoneId()`

- `String get_costItemId()`

- `Int32 get_costItemCount()`

- `Int64 get_unlockTs()`

- `Void UpdateStatus(Int32, Boolean)`

- `ItemBundle GetSkinRewardOrNull()`

- `ItemBundle GetNameCardSkinRewardOrNull()`

- `ItemBundle GetAvatarRewardOrNull()`

- `ItemBundle GetHomeThemeRewardOrNull()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMileStoneItemModel
{
	private Status m_status; // 0x10
	private String m_milestoneId; // 0x18
	private String m_costItemId; // 0x20
	private String m_milestoneGroupName; // 0x28
	private Int32 m_costItemCount; // 0x30
	private Int32 m_sortId; // 0x34
	private Int64 m_unlockTs; // 0x38
	private List`1 m_rewardList; // 0x40

	public Status status { get; }
	public Int32 sortId { get; }
	public String milestoneGroupName { get; }
	public String milestoneId { get; }
	public String costItemId { get; }
	public Int32 costItemCount { get; }
	public List`1 rewardList { get; }
	public Int64 unlockTs { get; }

	// RVA: 0x30ac11c VA: 0x75956c411c
	public Status get_status() { }
	// RVA: 0x30ac124 VA: 0x75956c4124
	public Int32 get_sortId() { }
	// RVA: 0x30ac12c VA: 0x75956c412c
	public String get_milestoneGroupName() { }
	// RVA: 0x30ac134 VA: 0x75956c4134
	public String get_milestoneId() { }
	// RVA: 0x30ac13c VA: 0x75956c413c
	public String get_costItemId() { }
	// RVA: 0x30ac144 VA: 0x75956c4144
	public Int32 get_costItemCount() { }
	// RVA: 0x30ac14c VA: 0x75956c414c
	public List`1 get_rewardList() { }
	// RVA: 0x30ac154 VA: 0x75956c4154
	public Int64 get_unlockTs() { }
	// RVA: 0x30ac15c VA: 0x75956c415c
	private Void .ctor() { }
	// RVA: 0x30ac164 VA: 0x75956c4164
	public static TemplateActivityMileStoneItemModel Create(Param param) { }
	// RVA: 0x30ac3d8 VA: 0x75956c43d8
	public Void UpdateStatus(Int32 currentCnt, Boolean hasGot) { }
	// RVA: 0x30ac47c VA: 0x75956c447c
	public ItemBundle GetSkinRewardOrNull() { }
	// RVA: 0x30ac53c VA: 0x75956c453c
	public ItemBundle GetNameCardSkinRewardOrNull() { }
	// RVA: 0x30ac5fc VA: 0x75956c45fc
	public ItemBundle GetAvatarRewardOrNull() { }
	// RVA: 0x30ac6bc VA: 0x75956c46bc
	public ItemBundle GetHomeThemeRewardOrNull() { }
}
```