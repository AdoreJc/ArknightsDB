# ZoneHomeEntryActivityModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneHomeEntryLockInfo m_lockInfo`

- `ZoneHomeEntryMedalStatus m_medalStatus`

- `ActivityBasicInfo <basicInfo>k__BackingField`

- `Boolean <isStageOpen>k__BackingField`

- `Int32 <actItemCount>k__BackingField`


## Properties

- `ActivityBasicInfo basicInfo`

- `Boolean isStageOpen`

- `Boolean isEntryUnlocked`

- `Int32 actItemCount`


## Methods

- `ActivityBasicInfo get_basicInfo()`

- `Void set_basicInfo(ActivityBasicInfo)`

- `Boolean get_isStageOpen()`

- `Void set_isStageOpen(Boolean)`

- `Boolean get_isEntryUnlocked()`

- `Int32 get_actItemCount()`

- `Void set_actItemCount(Int32)`

- `Void _LoadData(DateTime, ActivityBasicInfo)`

- `ZoneHomeEntryMedalStatus <>xLuaBaseProxy_GetMedalStatus()`

- `ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneHomeEntryActivityModel : ZoneHomeEntryItemModel
{
	private ZoneHomeEntryLockInfo m_lockInfo; // 0x40
	private ZoneHomeEntryMedalStatus m_medalStatus; // 0x58
	private ActivityBasicInfo <basicInfo>k__BackingField; // 0x80
	private Boolean <isStageOpen>k__BackingField; // 0xf8
	private Int32 <actItemCount>k__BackingField; // 0xfc
	private static DelegateBridge __Hotfix0_get_basicInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_basicInfo; // 0x8
	private static DelegateBridge __Hotfix0_get_isStageOpen; // 0x10
	private static DelegateBridge __Hotfix0_set_isStageOpen; // 0x18
	private static DelegateBridge __Hotfix0_get_isEntryUnlocked; // 0x20
	private static DelegateBridge __Hotfix0_get_actItemCount; // 0x28
	private static DelegateBridge __Hotfix0_set_actItemCount; // 0x30
	private static DelegateBridge __Hotfix0_GetMedalStatus; // 0x38
	private static DelegateBridge __Hotfix0_GetLockInfo; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0__LoadData; // 0x50
	private static DelegateBridge __Hotfix0__GetSortIndex; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public ActivityBasicInfo basicInfo { get; set; }
	public Boolean isStageOpen { get; set; }
	public Boolean isEntryUnlocked { get; }
	public Int32 actItemCount { get; set; }

	// RVA: 0x2ef9810 VA: 0x7595511810
	public ActivityBasicInfo get_basicInfo() { }
	// RVA: 0x2efa0e0 VA: 0x75955120e0
	private Void set_basicInfo(ActivityBasicInfo value) { }
	// RVA: 0x2ef9efc VA: 0x7595511efc
	public Boolean get_isStageOpen() { }
	// RVA: 0x2efa198 VA: 0x7595512198
	private Void set_isStageOpen(Boolean value) { }
	// RVA: 0x2ef9f64 VA: 0x7595511f64
	public Boolean get_isEntryUnlocked() { }
	// RVA: 0x2ef9e94 VA: 0x7595511e94
	public Int32 get_actItemCount() { }
	// RVA: 0x2efa218 VA: 0x7595512218
	private Void set_actItemCount(Int32 value) { }
	// RVA: 0x2efa294 VA: 0x7595512294
	public override ZoneHomeEntryMedalStatus GetMedalStatus() { }
	// RVA: 0x2efa334 VA: 0x7595512334
	public override ZoneHomeEntryLockInfo GetLockInfo() { }
	// RVA: 0x2efa3c4 VA: 0x75955123c4
	public static IList`1 LoadData() { }
	// RVA: 0x2efa77c VA: 0x759551277c
	private Void _LoadData(DateTime curTime, ActivityBasicInfo actInfo) { }
	// RVA: 0x2efab70 VA: 0x7595512b70
	private static HomeEntrySortIndex _GetSortIndex(Boolean isStageOpen, ActivityBasicInfo actInfo, ZoneHomeEntryLockInfo lockInfo, ZoneHomeEntryMedalStatus medalStatus) { }
	// RVA: 0x2efa6c4 VA: 0x75955126c4
	public Void .ctor() { }
	// RVA: 0x2efacc4 VA: 0x7595512cc4
	private ZoneHomeEntryMedalStatus <>xLuaBaseProxy_GetMedalStatus() { }
	// RVA: 0x2efacfc VA: 0x7595512cfc
	private ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo() { }
}
```