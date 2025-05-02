# ZoneHomeEntryCrisisV2Model

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneHomeEntryLockInfo m_lockInfo`

- `ZoneHomeEntryMedalStatus m_medalStatus`

- `Int32 <mainRank>k__BackingField`

- `String <seasonId>k__BackingField`

- `String <stageId>k__BackingField`


## Properties

- `Int32 mainRank`

- `String seasonId`

- `String stageId`


## Methods

- `Int32 get_mainRank()`

- `Void set_mainRank(Int32)`

- `String get_seasonId()`

- `Void set_seasonId(String)`

- `String get_stageId()`

- `Void set_stageId(String)`

- `Void _LoadPlayerData(String)`

- `ZoneHomeEntryMedalStatus <>xLuaBaseProxy_GetMedalStatus()`

- `ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneHomeEntryCrisisV2Model : ZoneHomeEntryItemModel
{
	private ZoneHomeEntryLockInfo m_lockInfo; // 0x40
	private ZoneHomeEntryMedalStatus m_medalStatus; // 0x58
	private Int32 <mainRank>k__BackingField; // 0x80
	private String <seasonId>k__BackingField; // 0x88
	private String <stageId>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_mainRank; // 0x0
	private static DelegateBridge __Hotfix0_set_mainRank; // 0x8
	private static DelegateBridge __Hotfix0_get_seasonId; // 0x10
	private static DelegateBridge __Hotfix0_set_seasonId; // 0x18
	private static DelegateBridge __Hotfix0_get_stageId; // 0x20
	private static DelegateBridge __Hotfix0_set_stageId; // 0x28
	private static DelegateBridge __Hotfix0_GetMedalStatus; // 0x30
	private static DelegateBridge __Hotfix0_GetLockInfo; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0__LoadPlayerData; // 0x48
	private static DelegateBridge __Hotfix0__GetSortIndex; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Int32 mainRank { get; set; }
	public String seasonId { get; set; }
	public String stageId { get; set; }

	// RVA: 0x2f0d57c VA: 0x759552557c
	public Int32 get_mainRank() { }
	// RVA: 0x2f11048 VA: 0x7595529048
	private Void set_mainRank(Int32 value) { }
	// RVA: 0x2f110c4 VA: 0x75955290c4
	public String get_seasonId() { }
	// RVA: 0x2f1112c VA: 0x759552912c
	private Void set_seasonId(String value) { }
	// RVA: 0x2f111b0 VA: 0x75955291b0
	public String get_stageId() { }
	// RVA: 0x2f11218 VA: 0x7595529218
	private Void set_stageId(String value) { }
	// RVA: 0x2f1129c VA: 0x759552929c
	public override ZoneHomeEntryMedalStatus GetMedalStatus() { }
	// RVA: 0x2f1133c VA: 0x759552933c
	public override ZoneHomeEntryLockInfo GetLockInfo() { }
	// RVA: 0x2f08c48 VA: 0x7595520c48
	public static ZoneHomeEntryCrisisV2Model LoadData() { }
	// RVA: 0x2f114cc VA: 0x75955294cc
	private Void _LoadPlayerData(String seasonId) { }
	// RVA: 0x2f115f4 VA: 0x75955295f4
	private static HomeEntrySortIndex _GetSortIndex(ZoneHomeEntryLockInfo lockInfo, ZoneHomeEntryMedalStatus medalStatus) { }
	// RVA: 0x2f113cc VA: 0x75955293cc
	public Void .ctor() { }
	// RVA: 0x2f116c8 VA: 0x75955296c8
	private ZoneHomeEntryMedalStatus <>xLuaBaseProxy_GetMedalStatus() { }
	// RVA: 0x2f116fc VA: 0x75955296fc
	private ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo() { }
}
```