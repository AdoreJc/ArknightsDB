# ActMultiV3PrepareMapInfoViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `MapType <mapType>k__BackingField`

- `ActMultiV3MapModeType <modeType>k__BackingField`

- `ActMultiV3MapDiffType <diffType>k__BackingField`

- `String <stageId>k__BackingField`

- `String <previewPicId>k__BackingField`

- `String <mapCode>k__BackingField`

- `String <mapName>k__BackingField`

- `String <mapPicId>k__BackingField`

- `String <modeName>k__BackingField`

- `String <diffName>k__BackingField`

- `ActMultiV3ConstData m_constData`


## Properties

- `MapType mapType`

- `ActMultiV3MapModeType modeType`

- `ActMultiV3MapDiffType diffType`

- `Boolean isEmpty`

- `String stageId`

- `String previewPicId`

- `String mapCode`

- `String mapName`

- `String mapPicId`

- `String modeName`

- `String diffName`


## Methods

- `MapType get_mapType()`

- `Void set_mapType(MapType)`

- `ActMultiV3MapModeType get_modeType()`

- `Void set_modeType(ActMultiV3MapModeType)`

- `ActMultiV3MapDiffType get_diffType()`

- `Void set_diffType(ActMultiV3MapDiffType)`

- `Boolean get_isEmpty()`

- `String get_stageId()`

- `Void set_stageId(String)`

- `String get_previewPicId()`

- `Void set_previewPicId(String)`

- `String get_mapCode()`

- `Void set_mapCode(String)`

- `String get_mapName()`

- `Void set_mapName(String)`

- `String get_mapPicId()`

- `Void set_mapPicId(String)`

- `String get_modeName()`

- `Void set_modeName(String)`

- `String get_diffName()`

- `Void set_diffName(String)`

- `Void LoadSelectMapData(String, String)`

- `Void LoadRandomData(String, StageRandomType)`

- `Void LoadEmptyData(String)`

- `Void _LoadStableDataIfNull(String)`

- `String FormatCopyRoomIdToast(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PrepareMapInfoViewModel
{
	private MapType <mapType>k__BackingField; // 0x10
	private ActMultiV3MapModeType <modeType>k__BackingField; // 0x14
	private ActMultiV3MapDiffType <diffType>k__BackingField; // 0x18
	private String <stageId>k__BackingField; // 0x20
	private String <previewPicId>k__BackingField; // 0x28
	private String <mapCode>k__BackingField; // 0x30
	private String <mapName>k__BackingField; // 0x38
	private String <mapPicId>k__BackingField; // 0x40
	private String <modeName>k__BackingField; // 0x48
	private String <diffName>k__BackingField; // 0x50
	private ActMultiV3ConstData m_constData; // 0x58

	public MapType mapType { get; set; }
	public ActMultiV3MapModeType modeType { get; set; }
	public ActMultiV3MapDiffType diffType { get; set; }
	public Boolean isEmpty { get; }
	public String stageId { get; set; }
	public String previewPicId { get; set; }
	public String mapCode { get; set; }
	public String mapName { get; set; }
	public String mapPicId { get; set; }
	public String modeName { get; set; }
	public String diffName { get; set; }

	// RVA: 0x3123ae0 VA: 0x759573bae0
	public MapType get_mapType() { }
	// RVA: 0x3123ae8 VA: 0x759573bae8
	private Void set_mapType(MapType value) { }
	// RVA: 0x3123af0 VA: 0x759573baf0
	public ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x3123af8 VA: 0x759573baf8
	private Void set_modeType(ActMultiV3MapModeType value) { }
	// RVA: 0x3123b00 VA: 0x759573bb00
	public ActMultiV3MapDiffType get_diffType() { }
	// RVA: 0x3123b08 VA: 0x759573bb08
	private Void set_diffType(ActMultiV3MapDiffType value) { }
	// RVA: 0x3123b10 VA: 0x759573bb10
	public Boolean get_isEmpty() { }
	// RVA: 0x3123b20 VA: 0x759573bb20
	public String get_stageId() { }
	// RVA: 0x3123b28 VA: 0x759573bb28
	private Void set_stageId(String value) { }
	// RVA: 0x3123b30 VA: 0x759573bb30
	public String get_previewPicId() { }
	// RVA: 0x3123b38 VA: 0x759573bb38
	private Void set_previewPicId(String value) { }
	// RVA: 0x3123b40 VA: 0x759573bb40
	public String get_mapCode() { }
	// RVA: 0x3123b48 VA: 0x759573bb48
	private Void set_mapCode(String value) { }
	// RVA: 0x3123b50 VA: 0x759573bb50
	public String get_mapName() { }
	// RVA: 0x3123b58 VA: 0x759573bb58
	private Void set_mapName(String value) { }
	// RVA: 0x3123b60 VA: 0x759573bb60
	public String get_mapPicId() { }
	// RVA: 0x3123b68 VA: 0x759573bb68
	private Void set_mapPicId(String value) { }
	// RVA: 0x3123b70 VA: 0x759573bb70
	public String get_modeName() { }
	// RVA: 0x3123b78 VA: 0x759573bb78
	private Void set_modeName(String value) { }
	// RVA: 0x3123b80 VA: 0x759573bb80
	public String get_diffName() { }
	// RVA: 0x3123b88 VA: 0x759573bb88
	private Void set_diffName(String value) { }
	// RVA: 0x3123b90 VA: 0x759573bb90
	public Void LoadSelectMapData(String actId, String stageId) { }
	// RVA: 0x3123e88 VA: 0x759573be88
	public Void LoadRandomData(String actId, StageRandomType randType) { }
	// RVA: 0x3124014 VA: 0x759573c014
	public Void LoadEmptyData(String actId) { }
	// RVA: 0x3123e4c VA: 0x759573be4c
	private Void _LoadStableDataIfNull(String actId) { }
	// RVA: 0x3124104 VA: 0x759573c104
	public String FormatCopyRoomIdToast(String roomId) { }
	// RVA: 0x3124478 VA: 0x759573c478
	public Void .ctor() { }
}
```