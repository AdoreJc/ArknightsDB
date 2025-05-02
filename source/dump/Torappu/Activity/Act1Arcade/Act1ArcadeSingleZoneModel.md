# Act1ArcadeSingleZoneModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `String <actId>k__BackingField`

- `String <zoneId>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `String <zoneEntryPicId>k__BackingField`

- `String <stageInfoPrefabId>k__BackingField`

- `SubModeType <subModeType>k__BackingField`

- `ZoneStatus <zoneStatus>k__BackingField`

- `Int64 <zoneStartTs>k__BackingField`

- `Int64 <zoneEndTs>k__BackingField`


## Properties

- `String actId`

- `String zoneId`

- `Int32 sortId`

- `String zoneEntryPicId`

- `String stageInfoPrefabId`

- `SubModeType subModeType`

- `ZoneStatus zoneStatus`

- `Int64 zoneStartTs`

- `Int64 zoneEndTs`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_zoneId()`

- `Void set_zoneId(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `String get_zoneEntryPicId()`

- `Void set_zoneEntryPicId(String)`

- `String get_stageInfoPrefabId()`

- `Void set_stageInfoPrefabId(String)`

- `Void set_stages(List`1)`

- `SubModeType get_subModeType()`

- `Void set_subModeType(SubModeType)`

- `ZoneStatus get_zoneStatus()`

- `Void set_zoneStatus(ZoneStatus)`

- `Int64 get_zoneStartTs()`

- `Void set_zoneStartTs(Int64)`

- `Int64 get_zoneEndTs()`

- `Void set_zoneEndTs(Int64)`

- `Void LoadData(String, ArcadeZoneAdditionalData)`

- `Void _UpdateZoneStatus(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSingleZoneModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	private String <zoneId>k__BackingField; // 0x18
	private Int32 <sortId>k__BackingField; // 0x20
	private String <zoneEntryPicId>k__BackingField; // 0x28
	private String <stageInfoPrefabId>k__BackingField; // 0x30
	private List`1 <stages>k__BackingField; // 0x38
	private SubModeType <subModeType>k__BackingField; // 0x40
	private ZoneStatus <zoneStatus>k__BackingField; // 0x44
	private Int64 <zoneStartTs>k__BackingField; // 0x48
	private Int64 <zoneEndTs>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x10
	private static DelegateBridge __Hotfix0_set_zoneId; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_set_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_zoneEntryPicId; // 0x30
	private static DelegateBridge __Hotfix0_set_zoneEntryPicId; // 0x38
	private static DelegateBridge __Hotfix0_get_stageInfoPrefabId; // 0x40
	private static DelegateBridge __Hotfix0_set_stageInfoPrefabId; // 0x48
	private static DelegateBridge __Hotfix0_get_stages; // 0x50
	private static DelegateBridge __Hotfix0_set_stages; // 0x58
	private static DelegateBridge __Hotfix0_get_subModeType; // 0x60
	private static DelegateBridge __Hotfix0_set_subModeType; // 0x68
	private static DelegateBridge __Hotfix0_get_zoneStatus; // 0x70
	private static DelegateBridge __Hotfix0_set_zoneStatus; // 0x78
	private static DelegateBridge __Hotfix0_get_zoneStartTs; // 0x80
	private static DelegateBridge __Hotfix0_set_zoneStartTs; // 0x88
	private static DelegateBridge __Hotfix0_get_zoneEndTs; // 0x90
	private static DelegateBridge __Hotfix0_set_zoneEndTs; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateZoneStatus; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public String actId { get; set; }
	public String zoneId { get; set; }
	public Int32 sortId { get; set; }
	public String zoneEntryPicId { get; set; }
	public String stageInfoPrefabId { get; set; }
	public List`1 stages { get; set; }
	public SubModeType subModeType { get; set; }
	public ZoneStatus zoneStatus { get; set; }
	public Int64 zoneStartTs { get; set; }
	public Int64 zoneEndTs { get; set; }

	// RVA: 0x340cc98 VA: 0x7595a24c98
	public String get_actId() { }
	// RVA: 0x340cd00 VA: 0x7595a24d00
	private Void set_actId(String value) { }
	// RVA: 0x340cd84 VA: 0x7595a24d84
	public String get_zoneId() { }
	// RVA: 0x340cdec VA: 0x7595a24dec
	private Void set_zoneId(String value) { }
	// RVA: 0x340ce70 VA: 0x7595a24e70
	public Int32 get_sortId() { }
	// RVA: 0x340ced8 VA: 0x7595a24ed8
	private Void set_sortId(Int32 value) { }
	// RVA: 0x340cf54 VA: 0x7595a24f54
	public String get_zoneEntryPicId() { }
	// RVA: 0x340cfbc VA: 0x7595a24fbc
	private Void set_zoneEntryPicId(String value) { }
	// RVA: 0x340d040 VA: 0x7595a25040
	public String get_stageInfoPrefabId() { }
	// RVA: 0x340d0a8 VA: 0x7595a250a8
	private Void set_stageInfoPrefabId(String value) { }
	// RVA: 0x340d12c VA: 0x7595a2512c
	public List`1 get_stages() { }
	// RVA: 0x340d194 VA: 0x7595a25194
	private Void set_stages(List`1 value) { }
	// RVA: 0x340d218 VA: 0x7595a25218
	public SubModeType get_subModeType() { }
	// RVA: 0x340d280 VA: 0x7595a25280
	private Void set_subModeType(SubModeType value) { }
	// RVA: 0x340d2fc VA: 0x7595a252fc
	public ZoneStatus get_zoneStatus() { }
	// RVA: 0x340d364 VA: 0x7595a25364
	private Void set_zoneStatus(ZoneStatus value) { }
	// RVA: 0x340d3e0 VA: 0x7595a253e0
	public Int64 get_zoneStartTs() { }
	// RVA: 0x340d448 VA: 0x7595a25448
	private Void set_zoneStartTs(Int64 value) { }
	// RVA: 0x340d4c4 VA: 0x7595a254c4
	public Int64 get_zoneEndTs() { }
	// RVA: 0x340d52c VA: 0x7595a2552c
	private Void set_zoneEndTs(Int64 value) { }
	// RVA: 0x340d5a8 VA: 0x7595a255a8
	public Void LoadData(String actId, ArcadeZoneAdditionalData zoneAdditionalData) { }
	// RVA: 0x340d698 VA: 0x7595a25698
	private Void _UpdateZoneStatus(String actId, String zoneId) { }
	// RVA: 0x340d828 VA: 0x7595a25828
	public Void .ctor() { }
}
```