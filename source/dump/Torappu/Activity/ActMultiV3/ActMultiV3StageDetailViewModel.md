# ActMultiV3StageDetailViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String <actId>k__BackingField`

- `String <stageId>k__BackingField`

- `String <stagePreviewPicId>k__BackingField`

- `ActMultiV3DifficultyIconViewModel <diffIconModel>k__BackingField`

- `String <stageDetailDesc>k__BackingField`

- `Int32 <maxStarNum>k__BackingField`

- `Int32 <recordStarNum>k__BackingField`

- `Int64 <recordScoreNum>k__BackingField`

- `String <recordScoreText>k__BackingField`

- `Boolean <hasRecord>k__BackingField`

- `ActMultiV3PrepareMapInfoViewModel m_mapInfoViewModel`


## Properties

- `String actId`

- `String stageId`

- `String stagePreviewPicId`

- `String stageCode`

- `String modeName`

- `ActMultiV3MapDiffType diffType`

- `ActMultiV3MapModeType modeType`

- `ActMultiV3DifficultyIconViewModel diffIconModel`

- `String stageDetailDesc`

- `Int32 maxStarNum`

- `Int32 recordStarNum`

- `Int64 recordScoreNum`

- `String recordScoreText`

- `Boolean hasRecord`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_stageId()`

- `Void set_stageId(String)`

- `String get_stagePreviewPicId()`

- `Void set_stagePreviewPicId(String)`

- `String get_stageCode()`

- `String get_modeName()`

- `ActMultiV3MapDiffType get_diffType()`

- `ActMultiV3MapModeType get_modeType()`

- `ActMultiV3DifficultyIconViewModel get_diffIconModel()`

- `Void set_diffIconModel(ActMultiV3DifficultyIconViewModel)`

- `String get_stageDetailDesc()`

- `Void set_stageDetailDesc(String)`

- `Void set_goalItemParams(List`1)`

- `Int32 get_maxStarNum()`

- `Void set_maxStarNum(Int32)`

- `Int32 get_recordStarNum()`

- `Void set_recordStarNum(Int32)`

- `Int64 get_recordScoreNum()`

- `Void set_recordScoreNum(Int64)`

- `String get_recordScoreText()`

- `Void set_recordScoreText(String)`

- `Boolean get_hasRecord()`

- `Void set_hasRecord(Boolean)`

- `Void LoadData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageDetailViewModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	private String <stageId>k__BackingField; // 0x18
	private String <stagePreviewPicId>k__BackingField; // 0x20
	private ActMultiV3DifficultyIconViewModel <diffIconModel>k__BackingField; // 0x28
	private String <stageDetailDesc>k__BackingField; // 0x30
	private List`1 <goalItemParams>k__BackingField; // 0x38
	private Int32 <maxStarNum>k__BackingField; // 0x40
	private Int32 <recordStarNum>k__BackingField; // 0x44
	private Int64 <recordScoreNum>k__BackingField; // 0x48
	private String <recordScoreText>k__BackingField; // 0x50
	private Boolean <hasRecord>k__BackingField; // 0x58
	public List`1 enemyItemModelList; // 0x60
	private ActMultiV3PrepareMapInfoViewModel m_mapInfoViewModel; // 0x68
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_stageId; // 0x10
	private static DelegateBridge __Hotfix0_set_stageId; // 0x18
	private static DelegateBridge __Hotfix0_get_stagePreviewPicId; // 0x20
	private static DelegateBridge __Hotfix0_set_stagePreviewPicId; // 0x28
	private static DelegateBridge __Hotfix0_get_stageCode; // 0x30
	private static DelegateBridge __Hotfix0_get_modeName; // 0x38
	private static DelegateBridge __Hotfix0_get_diffType; // 0x40
	private static DelegateBridge __Hotfix0_get_modeType; // 0x48
	private static DelegateBridge __Hotfix0_get_diffIconModel; // 0x50
	private static DelegateBridge __Hotfix0_set_diffIconModel; // 0x58
	private static DelegateBridge __Hotfix0_get_stageDetailDesc; // 0x60
	private static DelegateBridge __Hotfix0_set_stageDetailDesc; // 0x68
	private static DelegateBridge __Hotfix0_get_goalItemParams; // 0x70
	private static DelegateBridge __Hotfix0_set_goalItemParams; // 0x78
	private static DelegateBridge __Hotfix0_get_maxStarNum; // 0x80
	private static DelegateBridge __Hotfix0_set_maxStarNum; // 0x88
	private static DelegateBridge __Hotfix0_get_recordStarNum; // 0x90
	private static DelegateBridge __Hotfix0_set_recordStarNum; // 0x98
	private static DelegateBridge __Hotfix0_get_recordScoreNum; // 0xa0
	private static DelegateBridge __Hotfix0_set_recordScoreNum; // 0xa8
	private static DelegateBridge __Hotfix0_get_recordScoreText; // 0xb0
	private static DelegateBridge __Hotfix0_set_recordScoreText; // 0xb8
	private static DelegateBridge __Hotfix0_get_hasRecord; // 0xc0
	private static DelegateBridge __Hotfix0_set_hasRecord; // 0xc8
	private static DelegateBridge __Hotfix0_LoadData; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public String actId { get; set; }
	public String stageId { get; set; }
	public String stagePreviewPicId { get; set; }
	public String stageCode { get; }
	public String modeName { get; }
	public ActMultiV3MapDiffType diffType { get; }
	public ActMultiV3MapModeType modeType { get; }
	public ActMultiV3DifficultyIconViewModel diffIconModel { get; set; }
	public String stageDetailDesc { get; set; }
	public List`1 goalItemParams { get; set; }
	public Int32 maxStarNum { get; set; }
	public Int32 recordStarNum { get; set; }
	public Int64 recordScoreNum { get; set; }
	public String recordScoreText { get; set; }
	public Boolean hasRecord { get; set; }

	// RVA: 0x3146764 VA: 0x759575e764
	public String get_actId() { }
	// RVA: 0x3147318 VA: 0x759575f318
	private Void set_actId(String value) { }
	// RVA: 0x314739c VA: 0x759575f39c
	public String get_stageId() { }
	// RVA: 0x3147404 VA: 0x759575f404
	private Void set_stageId(String value) { }
	// RVA: 0x31466fc VA: 0x759575e6fc
	public String get_stagePreviewPicId() { }
	// RVA: 0x3147488 VA: 0x759575f488
	private Void set_stagePreviewPicId(String value) { }
	// RVA: 0x31464d0 VA: 0x759575e4d0
	public String get_stageCode() { }
	// RVA: 0x3146544 VA: 0x759575e544
	public String get_modeName() { }
	// RVA: 0x314750c VA: 0x759575f50c
	public ActMultiV3MapDiffType get_diffType() { }
	// RVA: 0x3146688 VA: 0x759575e688
	public ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x31465b8 VA: 0x759575e5b8
	public ActMultiV3DifficultyIconViewModel get_diffIconModel() { }
	// RVA: 0x3147580 VA: 0x759575f580
	private Void set_diffIconModel(ActMultiV3DifficultyIconViewModel value) { }
	// RVA: 0x3146620 VA: 0x759575e620
	public String get_stageDetailDesc() { }
	// RVA: 0x3147604 VA: 0x759575f604
	private Void set_stageDetailDesc(String value) { }
	// RVA: 0x3146904 VA: 0x759575e904
	public List`1 get_goalItemParams() { }
	// RVA: 0x3147688 VA: 0x759575f688
	private Void set_goalItemParams(List`1 value) { }
	// RVA: 0x314707c VA: 0x759575f07c
	public Int32 get_maxStarNum() { }
	// RVA: 0x314770c VA: 0x759575f70c
	private Void set_maxStarNum(Int32 value) { }
	// RVA: 0x31472a0 VA: 0x759575f2a0
	public Int32 get_recordStarNum() { }
	// RVA: 0x3147788 VA: 0x759575f788
	private Void set_recordStarNum(Int32 value) { }
	// RVA: 0x3146834 VA: 0x759575e834
	public Int64 get_recordScoreNum() { }
	// RVA: 0x3147804 VA: 0x759575f804
	private Void set_recordScoreNum(Int64 value) { }
	// RVA: 0x314689c VA: 0x759575e89c
	public String get_recordScoreText() { }
	// RVA: 0x3147880 VA: 0x759575f880
	private Void set_recordScoreText(String value) { }
	// RVA: 0x31467cc VA: 0x759575e7cc
	public Boolean get_hasRecord() { }
	// RVA: 0x3147904 VA: 0x759575f904
	private Void set_hasRecord(Boolean value) { }
	// RVA: 0x3147984 VA: 0x759575f984
	public Void LoadData(String actId, String stageId) { }
	// RVA: 0x3148294 VA: 0x7595760294
	public Void .ctor() { }
}
```