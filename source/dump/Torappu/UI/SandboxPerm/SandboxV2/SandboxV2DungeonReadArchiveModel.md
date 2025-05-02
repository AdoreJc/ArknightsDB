# SandboxV2DungeonReadArchiveModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topicId>k__BackingField`

- `Int32 <curSelectingDay>k__BackingField`

- `Int32 <savesCount>k__BackingField`

- `Int32 <selectIndex>k__BackingField`

- `String <surviveDayTxt>k__BackingField`

- `SandboxV2DungeonReadArchiveType <readArchiveType>k__BackingField`

- `SandboxV2DungeonReadArchiveCurDayInfoItemData m_curDayInfoItemData`


## Properties

- `String topicId`

- `Int32 curSelectingDay`

- `Int32 savesCount`

- `Int32 selectIndex`

- `String surviveDayTxt`

- `SandboxV2DungeonReadArchiveType readArchiveType`

- `SandboxV2DungeonReadArchiveCurDayInfoItemData curDayInfoItemData`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Int32 get_curSelectingDay()`

- `Void set_curSelectingDay(Int32)`

- `Int32 get_savesCount()`

- `Void set_savesCount(Int32)`

- `Int32 get_selectIndex()`

- `Void set_selectIndex(Int32)`

- `String get_surviveDayTxt()`

- `Void set_surviveDayTxt(String)`

- `SandboxV2DungeonReadArchiveType get_readArchiveType()`

- `Void set_readArchiveType(SandboxV2DungeonReadArchiveType)`

- `SandboxV2DungeonReadArchiveCurDayInfoItemData get_curDayInfoItemData()`

- `Void LoadData(String, SandboxV2DungeonReadArchiveType)`

- `Void SelectDay(Int32)`

- `Void UnSelectDay()`

- `Void _RefreshSelectType(Int32)`

- `Void _AddArchiveItemModel(Save, SandboxV2GameConst)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonReadArchiveModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private Int32 <curSelectingDay>k__BackingField; // 0x18
	private Int32 <savesCount>k__BackingField; // 0x1c
	private Int32 <selectIndex>k__BackingField; // 0x20
	private String <surviveDayTxt>k__BackingField; // 0x28
	private SandboxV2DungeonReadArchiveType <readArchiveType>k__BackingField; // 0x30
	private SandboxV2DungeonReadArchiveCurDayInfoItemData m_curDayInfoItemData; // 0x38
	private List`1 m_archiveItems; // 0x50
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_curSelectingDay; // 0x10
	private static DelegateBridge __Hotfix0_set_curSelectingDay; // 0x18
	private static DelegateBridge __Hotfix0_get_savesCount; // 0x20
	private static DelegateBridge __Hotfix0_set_savesCount; // 0x28
	private static DelegateBridge __Hotfix0_get_selectIndex; // 0x30
	private static DelegateBridge __Hotfix0_set_selectIndex; // 0x38
	private static DelegateBridge __Hotfix0_get_surviveDayTxt; // 0x40
	private static DelegateBridge __Hotfix0_set_surviveDayTxt; // 0x48
	private static DelegateBridge __Hotfix0_get_readArchiveType; // 0x50
	private static DelegateBridge __Hotfix0_set_readArchiveType; // 0x58
	private static DelegateBridge __Hotfix0_get_curDayInfoItemData; // 0x60
	private static DelegateBridge __Hotfix0_get_archiveItems; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x70
	private static DelegateBridge __Hotfix0_SelectDay; // 0x78
	private static DelegateBridge __Hotfix0_UnSelectDay; // 0x80
	private static DelegateBridge __Hotfix0__RefreshSelectType; // 0x88
	private static DelegateBridge __Hotfix0__AddArchiveItemModel; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public String topicId { get; set; }
	public Int32 curSelectingDay { get; set; }
	public Int32 savesCount { get; set; }
	public Int32 selectIndex { get; set; }
	public String surviveDayTxt { get; set; }
	public SandboxV2DungeonReadArchiveType readArchiveType { get; set; }
	public SandboxV2DungeonReadArchiveCurDayInfoItemData curDayInfoItemData { get; }
	public List`1 archiveItems { get; }

	// RVA: 0x252bf08 VA: 0x7594b43f08
	public String get_topicId() { }
	// RVA: 0x252ce58 VA: 0x7594b44e58
	private Void set_topicId(String value) { }
	// RVA: 0x252bf70 VA: 0x7594b43f70
	public Int32 get_curSelectingDay() { }
	// RVA: 0x252cedc VA: 0x7594b44edc
	private Void set_curSelectingDay(Int32 value) { }
	// RVA: 0x252cf58 VA: 0x7594b44f58
	public Int32 get_savesCount() { }
	// RVA: 0x252cfc0 VA: 0x7594b44fc0
	private Void set_savesCount(Int32 value) { }
	// RVA: 0x252bacc VA: 0x7594b43acc
	public Int32 get_selectIndex() { }
	// RVA: 0x252d03c VA: 0x7594b4503c
	private Void set_selectIndex(Int32 value) { }
	// RVA: 0x252d0b8 VA: 0x7594b450b8
	public String get_surviveDayTxt() { }
	// RVA: 0x252d120 VA: 0x7594b45120
	private Void set_surviveDayTxt(String value) { }
	// RVA: 0x252bea0 VA: 0x7594b43ea0
	public SandboxV2DungeonReadArchiveType get_readArchiveType() { }
	// RVA: 0x252d1a4 VA: 0x7594b451a4
	private Void set_readArchiveType(SandboxV2DungeonReadArchiveType value) { }
	// RVA: 0x252d220 VA: 0x7594b45220
	public SandboxV2DungeonReadArchiveCurDayInfoItemData get_curDayInfoItemData() { }
	// RVA: 0x252d2b0 VA: 0x7594b452b0
	public List`1 get_archiveItems() { }
	// RVA: 0x252b368 VA: 0x7594b43368
	public Void LoadData(String topic, SandboxV2DungeonReadArchiveType type) { }
	// RVA: 0x252bbac VA: 0x7594b43bac
	public Void SelectDay(Int32 day) { }
	// RVA: 0x252bb34 VA: 0x7594b43b34
	public Void UnSelectDay() { }
	// RVA: 0x252d454 VA: 0x7594b45454
	private Void _RefreshSelectType(Int32 day) { }
	// RVA: 0x252d318 VA: 0x7594b45318
	private Void _AddArchiveItemModel(Save save, SandboxV2GameConst gameConst) { }
	// RVA: 0x252d55c VA: 0x7594b4555c
	public Void .ctor() { }
}
```