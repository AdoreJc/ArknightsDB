# SandboxV2HomeModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topicId>k__BackingField`

- `Boolean <inGame>k__BackingField`

- `Boolean <isGuide>k__BackingField`

- `Boolean <isRift>k__BackingField`

- `SandboxV2DungeonMonthBrief <monthBrief>k__BackingField`

- `SandboxV2Data <sbV2DataBase>k__BackingField`

- `Int32 <currentDay>k__BackingField`

- `Int32 <maxDay>k__BackingField`

- `Int32 <shopCoin>k__BackingField`

- `Int64 <curUpdateTime>k__BackingField`

- `Int64 <nextSyncTime>k__BackingField`

- `TimeSpan <nextSyncTimeDelta>k__BackingField`

- `Boolean <needCurrentUpdateTips>k__BackingField`

- `String <medalGroupId>k__BackingField`

- `Boolean m_hasExploreMode`

- `Int32 <mode>k__BackingField`

- `SandboxV2ChallengeModeViewModel challengeModeViewModel`

- `Int32 initSeq`


## Properties

- `String topicId`

- `Boolean inGame`

- `Boolean isGuide`

- `Boolean isRift`

- `SandboxV2DungeonMonthBrief monthBrief`

- `SandboxV2Data sbV2DataBase`

- `Int32 currentDay`

- `Int32 maxDay`

- `Int32 shopCoin`

- `Int64 curUpdateTime`

- `Int64 nextSyncTime`

- `TimeSpan nextSyncTimeDelta`

- `Boolean needCurrentUpdateTips`

- `String medalGroupId`

- `Int32 mode`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Boolean get_inGame()`

- `Void set_inGame(Boolean)`

- `Boolean get_isGuide()`

- `Void set_isGuide(Boolean)`

- `Boolean get_isRift()`

- `Void set_isRift(Boolean)`

- `SandboxV2DungeonMonthBrief get_monthBrief()`

- `Void set_monthBrief(SandboxV2DungeonMonthBrief)`

- `SandboxV2Data get_sbV2DataBase()`

- `Void set_sbV2DataBase(SandboxV2Data)`

- `Int32 get_currentDay()`

- `Void set_currentDay(Int32)`

- `Int32 get_maxDay()`

- `Void set_maxDay(Int32)`

- `Int32 get_shopCoin()`

- `Void set_shopCoin(Int32)`

- `Int64 get_curUpdateTime()`

- `Void set_curUpdateTime(Int64)`

- `Int64 get_nextSyncTime()`

- `Void set_nextSyncTime(Int64)`

- `TimeSpan get_nextSyncTimeDelta()`

- `Void set_nextSyncTimeDelta(TimeSpan)`

- `Boolean get_needCurrentUpdateTips()`

- `Void set_needCurrentUpdateTips(Boolean)`

- `String get_medalGroupId()`

- `Void set_medalGroupId(String)`

- `Int32 get_mode()`

- `Void set_mode(Int32)`

- `Void set_exploreModeBuffDescs(String[])`

- `Void Load(String, Boolean)`

- `Void _LoadShopRelatedData(String, SandboxPermBasicData, SandboxV2Data)`

- `Boolean IsExploreModeSystemActive()`

- `String GetModeName(Int32)`

- `String GenerateDesc4ExploreModeConfirmDialog()`

- `Boolean SetChallengeViewSelected(Boolean)`

- `Boolean CanTriggerChallengeTutorial()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2HomeModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private Boolean <inGame>k__BackingField; // 0x18
	private Boolean <isGuide>k__BackingField; // 0x19
	private Boolean <isRift>k__BackingField; // 0x1a
	private SandboxV2DungeonMonthBrief <monthBrief>k__BackingField; // 0x20
	private SandboxV2Data <sbV2DataBase>k__BackingField; // 0x40
	private Int32 <currentDay>k__BackingField; // 0x48
	private Int32 <maxDay>k__BackingField; // 0x4c
	private Int32 <shopCoin>k__BackingField; // 0x50
	private Int64 <curUpdateTime>k__BackingField; // 0x58
	private Int64 <nextSyncTime>k__BackingField; // 0x60
	private TimeSpan <nextSyncTimeDelta>k__BackingField; // 0x68
	private Boolean <needCurrentUpdateTips>k__BackingField; // 0x70
	private String <medalGroupId>k__BackingField; // 0x78
	private Boolean m_hasExploreMode; // 0x80
	private Int32 <mode>k__BackingField; // 0x84
	private String[] <exploreModeBuffDescs>k__BackingField; // 0x88
	public SandboxV2ChallengeModeViewModel challengeModeViewModel; // 0x90
	public Int32 initSeq; // 0x98
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_inGame; // 0x10
	private static DelegateBridge __Hotfix0_set_inGame; // 0x18
	private static DelegateBridge __Hotfix0_get_isGuide; // 0x20
	private static DelegateBridge __Hotfix0_set_isGuide; // 0x28
	private static DelegateBridge __Hotfix0_get_isRift; // 0x30
	private static DelegateBridge __Hotfix0_set_isRift; // 0x38
	private static DelegateBridge __Hotfix0_get_monthBrief; // 0x40
	private static DelegateBridge __Hotfix0_set_monthBrief; // 0x48
	private static DelegateBridge __Hotfix0_get_sbV2DataBase; // 0x50
	private static DelegateBridge __Hotfix0_set_sbV2DataBase; // 0x58
	private static DelegateBridge __Hotfix0_get_currentDay; // 0x60
	private static DelegateBridge __Hotfix0_set_currentDay; // 0x68
	private static DelegateBridge __Hotfix0_get_maxDay; // 0x70
	private static DelegateBridge __Hotfix0_set_maxDay; // 0x78
	private static DelegateBridge __Hotfix0_get_shopCoin; // 0x80
	private static DelegateBridge __Hotfix0_set_shopCoin; // 0x88
	private static DelegateBridge __Hotfix0_get_curUpdateTime; // 0x90
	private static DelegateBridge __Hotfix0_set_curUpdateTime; // 0x98
	private static DelegateBridge __Hotfix0_get_nextSyncTime; // 0xa0
	private static DelegateBridge __Hotfix0_set_nextSyncTime; // 0xa8
	private static DelegateBridge __Hotfix0_get_nextSyncTimeDelta; // 0xb0
	private static DelegateBridge __Hotfix0_set_nextSyncTimeDelta; // 0xb8
	private static DelegateBridge __Hotfix0_get_needCurrentUpdateTips; // 0xc0
	private static DelegateBridge __Hotfix0_set_needCurrentUpdateTips; // 0xc8
	private static DelegateBridge __Hotfix0_get_medalGroupId; // 0xd0
	private static DelegateBridge __Hotfix0_set_medalGroupId; // 0xd8
	private static DelegateBridge __Hotfix0_get_mode; // 0xe0
	private static DelegateBridge __Hotfix0_set_mode; // 0xe8
	private static DelegateBridge __Hotfix0_get_exploreModeBuffDescs; // 0xf0
	private static DelegateBridge __Hotfix0_set_exploreModeBuffDescs; // 0xf8
	private static DelegateBridge __Hotfix0_Load; // 0x100
	private static DelegateBridge __Hotfix0__LoadShopRelatedData; // 0x108
	private static DelegateBridge __Hotfix0_IsExploreModeSystemActive; // 0x110
	private static DelegateBridge __Hotfix0_GetModeName; // 0x118
	private static DelegateBridge __Hotfix0_GenerateDesc4ExploreModeConfirmDialog; // 0x120
	private static DelegateBridge __Hotfix0_SetChallengeViewSelected; // 0x128
	private static DelegateBridge __Hotfix0_CanTriggerChallengeTutorial; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138

	public String topicId { get; set; }
	public Boolean inGame { get; set; }
	public Boolean isGuide { get; set; }
	public Boolean isRift { get; set; }
	public SandboxV2DungeonMonthBrief monthBrief { get; set; }
	public SandboxV2Data sbV2DataBase { get; set; }
	public Int32 currentDay { get; set; }
	public Int32 maxDay { get; set; }
	public Int32 shopCoin { get; set; }
	public Int64 curUpdateTime { get; set; }
	public Int64 nextSyncTime { get; set; }
	public TimeSpan nextSyncTimeDelta { get; set; }
	public Boolean needCurrentUpdateTips { get; set; }
	public String medalGroupId { get; set; }
	public Int32 mode { get; set; }
	public String[] exploreModeBuffDescs { get; set; }

	// RVA: 0x25d0608 VA: 0x7594be8608
	public String get_topicId() { }
	// RVA: 0x25d2af8 VA: 0x7594beaaf8
	private Void set_topicId(String value) { }
	// RVA: 0x25d2b7c VA: 0x7594beab7c
	public Boolean get_inGame() { }
	// RVA: 0x25d2be4 VA: 0x7594beabe4
	private Void set_inGame(Boolean value) { }
	// RVA: 0x25d0304 VA: 0x7594be8304
	public Boolean get_isGuide() { }
	// RVA: 0x25d2c64 VA: 0x7594beac64
	private Void set_isGuide(Boolean value) { }
	// RVA: 0x25d2ce4 VA: 0x7594beace4
	public Boolean get_isRift() { }
	// RVA: 0x25d2d4c VA: 0x7594bead4c
	private Void set_isRift(Boolean value) { }
	// RVA: 0x25d2dcc VA: 0x7594beadcc
	public SandboxV2DungeonMonthBrief get_monthBrief() { }
	// RVA: 0x25d2e54 VA: 0x7594beae54
	private Void set_monthBrief(SandboxV2DungeonMonthBrief value) { }
	// RVA: 0x25d2edc VA: 0x7594beaedc
	public SandboxV2Data get_sbV2DataBase() { }
	// RVA: 0x25d2f44 VA: 0x7594beaf44
	private Void set_sbV2DataBase(SandboxV2Data value) { }
	// RVA: 0x25d2fc8 VA: 0x7594beafc8
	public Int32 get_currentDay() { }
	// RVA: 0x25d3030 VA: 0x7594beb030
	private Void set_currentDay(Int32 value) { }
	// RVA: 0x25d30ac VA: 0x7594beb0ac
	public Int32 get_maxDay() { }
	// RVA: 0x25d3114 VA: 0x7594beb114
	private Void set_maxDay(Int32 value) { }
	// RVA: 0x25d3190 VA: 0x7594beb190
	public Int32 get_shopCoin() { }
	// RVA: 0x25d31f8 VA: 0x7594beb1f8
	private Void set_shopCoin(Int32 value) { }
	// RVA: 0x25d3274 VA: 0x7594beb274
	public Int64 get_curUpdateTime() { }
	// RVA: 0x25d32dc VA: 0x7594beb2dc
	private Void set_curUpdateTime(Int64 value) { }
	// RVA: 0x25d3358 VA: 0x7594beb358
	public Int64 get_nextSyncTime() { }
	// RVA: 0x25d33c0 VA: 0x7594beb3c0
	private Void set_nextSyncTime(Int64 value) { }
	// RVA: 0x25d343c VA: 0x7594beb43c
	public TimeSpan get_nextSyncTimeDelta() { }
	// RVA: 0x25d34a4 VA: 0x7594beb4a4
	private Void set_nextSyncTimeDelta(TimeSpan value) { }
	// RVA: 0x25d3520 VA: 0x7594beb520
	public Boolean get_needCurrentUpdateTips() { }
	// RVA: 0x25d3588 VA: 0x7594beb588
	private Void set_needCurrentUpdateTips(Boolean value) { }
	// RVA: 0x25cd684 VA: 0x7594be5684
	public String get_medalGroupId() { }
	// RVA: 0x25d3608 VA: 0x7594beb608
	private Void set_medalGroupId(String value) { }
	// RVA: 0x25d05a0 VA: 0x7594be85a0
	public Int32 get_mode() { }
	// RVA: 0x25d368c VA: 0x7594beb68c
	private Void set_mode(Int32 value) { }
	// RVA: 0x25d3708 VA: 0x7594beb708
	public String[] get_exploreModeBuffDescs() { }
	// RVA: 0x25d3770 VA: 0x7594beb770
	private Void set_exploreModeBuffDescs(String[] value) { }
	// RVA: 0x25ce7d4 VA: 0x7594be67d4
	public Void Load(String topicId, Boolean isInit) { }
	// RVA: 0x25d37f4 VA: 0x7594beb7f4
	private Void _LoadShopRelatedData(String topicId, SandboxPermBasicData basicInfo, SandboxV2Data dataBase) { }
	// RVA: 0x25d3c04 VA: 0x7594bebc04
	public Boolean IsExploreModeSystemActive() { }
	// RVA: 0x25d0848 VA: 0x7594be8848
	public String GetModeName(Int32 switchToExploreMode) { }
	// RVA: 0x25d3c80 VA: 0x7594bebc80
	public String GenerateDesc4ExploreModeConfirmDialog() { }
	// RVA: 0x25cddfc VA: 0x7594be5dfc
	public Boolean SetChallengeViewSelected(Boolean selected) { }
	// RVA: 0x25d1174 VA: 0x7594be9174
	public Boolean CanTriggerChallengeTutorial() { }
	// RVA: 0x25d3e7c VA: 0x7594bebe7c
	public Void .ctor() { }
}
```