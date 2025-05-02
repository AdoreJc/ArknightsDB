# TemplateMissionListNormalItemViewModel

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `MissionHoldingState <state>k__BackingField`

- `Int32 <target>k__BackingField`

- `Int32 <value>k__BackingField`

- `MissionData <data>k__BackingField`

- `DataBundle <meta>k__BackingField`

- `TemplateMissionStyleData <styleData>k__BackingField`

- `TemplateMissionGroupSource <param>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `Boolean <showCountRemainTip>k__BackingField`

- `Boolean <showEndRemainTip>k__BackingField`

- `String <textRemainTip>k__BackingField`

- `MissionGroup m_groupData`


## Properties

- `MissionHoldingState state`

- `Int32 target`

- `Int32 value`

- `MissionData data`

- `DataBundle meta`

- `TemplateMissionStyleData styleData`

- `TemplateMissionGroupSource param`

- `String description`

- `Int32 sortId`

- `Boolean showCountRemainTip`

- `Boolean showEndRemainTip`

- `String textRemainTip`


## Methods

- `MissionHoldingState get_state()`

- `Void set_state(MissionHoldingState)`

- `Int32 get_target()`

- `Void set_target(Int32)`

- `Int32 get_value()`

- `Void set_value(Int32)`

- `MissionData get_data()`

- `Void set_data(MissionData)`

- `Void set_rewardList(List`1)`

- `DataBundle get_meta()`

- `Void set_meta(DataBundle)`

- `TemplateMissionStyleData get_styleData()`

- `Void set_styleData(TemplateMissionStyleData)`

- `TemplateMissionGroupSource get_param()`

- `Void set_param(TemplateMissionGroupSource)`

- `String get_description()`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Boolean get_showCountRemainTip()`

- `Void set_showCountRemainTip(Boolean)`

- `Boolean get_showEndRemainTip()`

- `Void set_showEndRemainTip(Boolean)`

- `String get_textRemainTip()`

- `Void set_textRemainTip(String)`

- `TemplateMissionListItemViewType GetItemViewType()`

- `Boolean IsMissionValid(Int64)`

- `Void UpdateRemainTimeTip(Int64)`

- `Boolean CheckIfAbleToClaim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionListNormalItemViewModel : ITemplateMissionListItemViewModel, IHotfixable
{
	private MissionHoldingState <state>k__BackingField; // 0x10
	private Int32 <target>k__BackingField; // 0x14
	private Int32 <value>k__BackingField; // 0x18
	private MissionData <data>k__BackingField; // 0x20
	private List`1 <rewardList>k__BackingField; // 0x28
	private DataBundle <meta>k__BackingField; // 0x30
	private TemplateMissionStyleData <styleData>k__BackingField; // 0x38
	private TemplateMissionGroupSource <param>k__BackingField; // 0x40
	private Int32 <sortId>k__BackingField; // 0x48
	private Boolean <showCountRemainTip>k__BackingField; // 0x4c
	private Boolean <showEndRemainTip>k__BackingField; // 0x4d
	private String <textRemainTip>k__BackingField; // 0x50
	private MissionGroup m_groupData; // 0x58
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_get_target; // 0x10
	private static DelegateBridge __Hotfix0_set_target; // 0x18
	private static DelegateBridge __Hotfix0_get_value; // 0x20
	private static DelegateBridge __Hotfix0_set_value; // 0x28
	private static DelegateBridge __Hotfix0_get_data; // 0x30
	private static DelegateBridge __Hotfix0_set_data; // 0x38
	private static DelegateBridge __Hotfix0_get_rewardList; // 0x40
	private static DelegateBridge __Hotfix0_set_rewardList; // 0x48
	private static DelegateBridge __Hotfix0_get_meta; // 0x50
	private static DelegateBridge __Hotfix0_set_meta; // 0x58
	private static DelegateBridge __Hotfix0_get_styleData; // 0x60
	private static DelegateBridge __Hotfix0_set_styleData; // 0x68
	private static DelegateBridge __Hotfix0_get_param; // 0x70
	private static DelegateBridge __Hotfix0_set_param; // 0x78
	private static DelegateBridge __Hotfix0_get_description; // 0x80
	private static DelegateBridge __Hotfix0_get_sortId; // 0x88
	private static DelegateBridge __Hotfix0_set_sortId; // 0x90
	private static DelegateBridge __Hotfix0_get_showCountRemainTip; // 0x98
	private static DelegateBridge __Hotfix0_set_showCountRemainTip; // 0xa0
	private static DelegateBridge __Hotfix0_get_showEndRemainTip; // 0xa8
	private static DelegateBridge __Hotfix0_set_showEndRemainTip; // 0xb0
	private static DelegateBridge __Hotfix0_get_textRemainTip; // 0xb8
	private static DelegateBridge __Hotfix0_set_textRemainTip; // 0xc0
	private static DelegateBridge __Hotfix0_GetItemViewType; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0
	private static DelegateBridge __Hotfix0_IsMissionValid; // 0xd8
	private static DelegateBridge __Hotfix0_GetRewardPreviewItems; // 0xe0
	private static DelegateBridge __Hotfix0_UpdateRemainTimeTip; // 0xe8
	private static DelegateBridge __Hotfix0_CheckIfAbleToClaim; // 0xf0

	public MissionHoldingState state { get; set; }
	public Int32 target { get; set; }
	public Int32 value { get; set; }
	public MissionData data { get; set; }
	public List`1 rewardList { get; set; }
	public DataBundle meta { get; set; }
	public TemplateMissionStyleData styleData { get; set; }
	public TemplateMissionGroupSource param { get; set; }
	public String description { get; }
	public Int32 sortId { get; set; }
	public Boolean showCountRemainTip { get; set; }
	public Boolean showEndRemainTip { get; set; }
	public String textRemainTip { get; set; }

	// RVA: 0x236d24c VA: 0x759498524c
	public MissionHoldingState get_state() { }
	// RVA: 0x236d2b4 VA: 0x75949852b4
	public Void set_state(MissionHoldingState value) { }
	// RVA: 0x236d330 VA: 0x7594985330
	public Int32 get_target() { }
	// RVA: 0x236d398 VA: 0x7594985398
	public Void set_target(Int32 value) { }
	// RVA: 0x236d414 VA: 0x7594985414
	public Int32 get_value() { }
	// RVA: 0x236d47c VA: 0x759498547c
	public Void set_value(Int32 value) { }
	// RVA: 0x236d4f8 VA: 0x75949854f8
	public MissionData get_data() { }
	// RVA: 0x236d560 VA: 0x7594985560
	private Void set_data(MissionData value) { }
	// RVA: 0x236d5e4 VA: 0x75949855e4
	public List`1 get_rewardList() { }
	// RVA: 0x236d64c VA: 0x759498564c
	private Void set_rewardList(List`1 value) { }
	// RVA: 0x236d6d0 VA: 0x75949856d0
	public DataBundle get_meta() { }
	// RVA: 0x236d738 VA: 0x7594985738
	private Void set_meta(DataBundle value) { }
	// RVA: 0x236d7bc VA: 0x75949857bc
	public TemplateMissionStyleData get_styleData() { }
	// RVA: 0x236d824 VA: 0x7594985824
	private Void set_styleData(TemplateMissionStyleData value) { }
	// RVA: 0x236d8a8 VA: 0x75949858a8
	public TemplateMissionGroupSource get_param() { }
	// RVA: 0x236d910 VA: 0x7594985910
	private Void set_param(TemplateMissionGroupSource value) { }
	// RVA: 0x236d994 VA: 0x7594985994
	public String get_description() { }
	// RVA: 0x236da4c VA: 0x7594985a4c
	public Int32 get_sortId() { }
	// RVA: 0x236dab4 VA: 0x7594985ab4
	private Void set_sortId(Int32 value) { }
	// RVA: 0x236db30 VA: 0x7594985b30
	public Boolean get_showCountRemainTip() { }
	// RVA: 0x236db98 VA: 0x7594985b98
	private Void set_showCountRemainTip(Boolean value) { }
	// RVA: 0x236dc18 VA: 0x7594985c18
	public Boolean get_showEndRemainTip() { }
	// RVA: 0x236dc80 VA: 0x7594985c80
	private Void set_showEndRemainTip(Boolean value) { }
	// RVA: 0x236dd00 VA: 0x7594985d00
	public String get_textRemainTip() { }
	// RVA: 0x236dd68 VA: 0x7594985d68
	private Void set_textRemainTip(String value) { }
	// RVA: 0x236ddec VA: 0x7594985dec
	public TemplateMissionListItemViewType GetItemViewType() { }
	// RVA: 0x236de50 VA: 0x7594985e50
	public Void .ctor(Int32 groupIndex, TemplateMissionGroupSource groupInfo, TemplateMissionStyleData styleData_, MissionHoldingState state_, Int32 target_, Int32 value_, List`1 rewards, MissionData data_, MissionGroup groupData, DataBundle meta_) { }
	// RVA: 0x236dfd8 VA: 0x7594985fd8
	public Boolean IsMissionValid(Int64 currTs) { }
	// RVA: 0x236e0e8 VA: 0x75949860e8
	public List`1 GetRewardPreviewItems() { }
	// RVA: 0x236e438 VA: 0x7594986438
	public Void UpdateRemainTimeTip(Int64 currTs) { }
	// RVA: 0x236e658 VA: 0x7594986658
	public Boolean CheckIfAbleToClaim() { }
}
```