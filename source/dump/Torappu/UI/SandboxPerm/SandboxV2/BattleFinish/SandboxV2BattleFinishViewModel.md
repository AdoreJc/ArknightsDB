# SandboxV2BattleFinishViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2.BattleFinish`


## Fields

- `Boolean m_isTargetDefeated`

- `Single m_targetRatio`

- `Boolean m_isBattleSuccess`

- `SandboxV2BattleFinishMode m_mode`

- `Boolean <needSkip>k__BackingField`

- `Boolean <isValid>k__BackingField`

- `String <topicId>k__BackingField`

- `String <nodeId>k__BackingField`

- `SandboxV2NodeType <nodeType>k__BackingField`

- `String <stageId>k__BackingField`

- `String <stageName>k__BackingField`

- `String <typeName>k__BackingField`

- `CharUISkinStruct <finishIllust>k__BackingField`

- `Boolean <isEnemyRush>k__BackingField`

- `Int32 <prevEnemyCnt>k__BackingField`

- `Int32 <currEnemyCnt>k__BackingField`

- `String <monthlyRushId>k__BackingField`

- `Boolean <needMonthToast>k__BackingField`

- `CharWordData <charWord>k__BackingField`


## Properties

- `Boolean needSkip`

- `Boolean isValid`

- `String topicId`

- `String nodeId`

- `SandboxV2NodeType nodeType`

- `String stageId`

- `String stageName`

- `String typeName`

- `CharUISkinStruct finishIllust`

- `Boolean isEnemyRush`

- `Int32 prevEnemyCnt`

- `Int32 currEnemyCnt`

- `String monthlyRushId`

- `Boolean needMonthToast`

- `CharWordData charWord`

- `Boolean isTargetDefeated`

- `Single hpRatio`

- `Boolean showReward`

- `Boolean showBasementHp`

- `Boolean showTargetHp`

- `Boolean isMonthMode`


## Methods

- `Boolean get_needSkip()`

- `Void set_needSkip(Boolean)`

- `Boolean get_isValid()`

- `Void set_isValid(Boolean)`

- `String get_topicId()`

- `Void set_topicId(String)`

- `String get_nodeId()`

- `Void set_nodeId(String)`

- `SandboxV2NodeType get_nodeType()`

- `Void set_nodeType(SandboxV2NodeType)`

- `String get_stageId()`

- `Void set_stageId(String)`

- `String get_stageName()`

- `Void set_stageName(String)`

- `String get_typeName()`

- `Void set_typeName(String)`

- `CharUISkinStruct get_finishIllust()`

- `Void set_finishIllust(CharUISkinStruct)`

- `Boolean get_isEnemyRush()`

- `Void set_isEnemyRush(Boolean)`

- `Int32 get_prevEnemyCnt()`

- `Void set_prevEnemyCnt(Int32)`

- `Int32 get_currEnemyCnt()`

- `Void set_currEnemyCnt(Int32)`

- `Void set_normalRewardList(List`1)`

- `Void set_randomRewardList(List`1)`

- `String get_monthlyRushId()`

- `Void set_monthlyRushId(String)`

- `Boolean get_needMonthToast()`

- `Void set_needMonthToast(Boolean)`

- `CharWordData get_charWord()`

- `Void set_charWord(CharWordData)`

- `Boolean get_isTargetDefeated()`

- `Single get_hpRatio()`

- `Boolean get_showReward()`

- `Boolean get_showBasementHp()`

- `Boolean get_showTargetHp()`

- `Boolean get_isMonthMode()`

- `Void LoadData()`

- `Boolean _LoadDataFromMonthModeResponse(CommonFinishBattleResponse)`

- `Boolean _LoadDataFromNormalModeResponse(CommonFinishBattleResponse)`

- `Void _FindProperCharVoice()`

- `Boolean _TryGetProperWordType(out)`

- `Void _AddEntityToList(List`1, List`1)`

- `Boolean _CheckNeedSkip(PlayerSandboxV2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2.BattleFinish
public class SandboxV2BattleFinishViewModel : IHotfixable
{
	private Boolean m_isTargetDefeated; // 0x10
	private Single m_targetRatio; // 0x14
	private Boolean m_isBattleSuccess; // 0x18
	private SandboxV2BattleFinishMode m_mode; // 0x1c
	private Boolean <needSkip>k__BackingField; // 0x20
	private Boolean <isValid>k__BackingField; // 0x21
	private String <topicId>k__BackingField; // 0x28
	private String <nodeId>k__BackingField; // 0x30
	private SandboxV2NodeType <nodeType>k__BackingField; // 0x38
	private String <stageId>k__BackingField; // 0x40
	private String <stageName>k__BackingField; // 0x48
	private String <typeName>k__BackingField; // 0x50
	private CharUISkinStruct <finishIllust>k__BackingField; // 0x58
	private Boolean <isEnemyRush>k__BackingField; // 0x68
	private Int32 <prevEnemyCnt>k__BackingField; // 0x6c
	private Int32 <currEnemyCnt>k__BackingField; // 0x70
	private List`1 <normalRewardList>k__BackingField; // 0x78
	private List`1 <randomRewardList>k__BackingField; // 0x80
	private String <monthlyRushId>k__BackingField; // 0x88
	private Boolean <needMonthToast>k__BackingField; // 0x90
	private CharWordData <charWord>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_needSkip; // 0x0
	private static DelegateBridge __Hotfix0_set_needSkip; // 0x8
	private static DelegateBridge __Hotfix0_get_isValid; // 0x10
	private static DelegateBridge __Hotfix0_set_isValid; // 0x18
	private static DelegateBridge __Hotfix0_get_topicId; // 0x20
	private static DelegateBridge __Hotfix0_set_topicId; // 0x28
	private static DelegateBridge __Hotfix0_get_nodeId; // 0x30
	private static DelegateBridge __Hotfix0_set_nodeId; // 0x38
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x40
	private static DelegateBridge __Hotfix0_set_nodeType; // 0x48
	private static DelegateBridge __Hotfix0_get_stageId; // 0x50
	private static DelegateBridge __Hotfix0_set_stageId; // 0x58
	private static DelegateBridge __Hotfix0_get_stageName; // 0x60
	private static DelegateBridge __Hotfix0_set_stageName; // 0x68
	private static DelegateBridge __Hotfix0_get_typeName; // 0x70
	private static DelegateBridge __Hotfix0_set_typeName; // 0x78
	private static DelegateBridge __Hotfix0_get_finishIllust; // 0x80
	private static DelegateBridge __Hotfix0_set_finishIllust; // 0x88
	private static DelegateBridge __Hotfix0_get_isEnemyRush; // 0x90
	private static DelegateBridge __Hotfix0_set_isEnemyRush; // 0x98
	private static DelegateBridge __Hotfix0_get_prevEnemyCnt; // 0xa0
	private static DelegateBridge __Hotfix0_set_prevEnemyCnt; // 0xa8
	private static DelegateBridge __Hotfix0_get_currEnemyCnt; // 0xb0
	private static DelegateBridge __Hotfix0_set_currEnemyCnt; // 0xb8
	private static DelegateBridge __Hotfix0_get_normalRewardList; // 0xc0
	private static DelegateBridge __Hotfix0_set_normalRewardList; // 0xc8
	private static DelegateBridge __Hotfix0_get_randomRewardList; // 0xd0
	private static DelegateBridge __Hotfix0_set_randomRewardList; // 0xd8
	private static DelegateBridge __Hotfix0_get_monthlyRushId; // 0xe0
	private static DelegateBridge __Hotfix0_set_monthlyRushId; // 0xe8
	private static DelegateBridge __Hotfix0_get_needMonthToast; // 0xf0
	private static DelegateBridge __Hotfix0_set_needMonthToast; // 0xf8
	private static DelegateBridge __Hotfix0_get_charWord; // 0x100
	private static DelegateBridge __Hotfix0_set_charWord; // 0x108
	private static DelegateBridge __Hotfix0_get_isTargetDefeated; // 0x110
	private static DelegateBridge __Hotfix0_get_hpRatio; // 0x118
	private static DelegateBridge __Hotfix0_get_showReward; // 0x120
	private static DelegateBridge __Hotfix0_get_showBasementHp; // 0x128
	private static DelegateBridge __Hotfix0_get_showTargetHp; // 0x130
	private static DelegateBridge __Hotfix0_get_isMonthMode; // 0x138
	private static DelegateBridge __Hotfix0_LoadData; // 0x140
	private static DelegateBridge __Hotfix0__LoadDataFromMonthModeResponse; // 0x148
	private static DelegateBridge __Hotfix0__LoadDataFromNormalModeResponse; // 0x150
	private static DelegateBridge __Hotfix0__FindProperCharVoice; // 0x158
	private static DelegateBridge __Hotfix0__TryGetProperWordType; // 0x160
	private static DelegateBridge __Hotfix0__GetNodeStageEntityList; // 0x168
	private static DelegateBridge __Hotfix0__AddEntityToList; // 0x170
	private static DelegateBridge __Hotfix0__CheckNeedSkip; // 0x178
	private static DelegateBridge _c__Hotfix0_ctor; // 0x180

	public Boolean needSkip { get; set; }
	public Boolean isValid { get; set; }
	public String topicId { get; set; }
	public String nodeId { get; set; }
	public SandboxV2NodeType nodeType { get; set; }
	public String stageId { get; set; }
	public String stageName { get; set; }
	public String typeName { get; set; }
	public CharUISkinStruct finishIllust { get; set; }
	public Boolean isEnemyRush { get; set; }
	public Int32 prevEnemyCnt { get; set; }
	public Int32 currEnemyCnt { get; set; }
	public List`1 normalRewardList { get; set; }
	public List`1 randomRewardList { get; set; }
	public String monthlyRushId { get; set; }
	public Boolean needMonthToast { get; set; }
	public CharWordData charWord { get; set; }
	public Boolean isTargetDefeated { get; }
	public Single hpRatio { get; }
	public Boolean showReward { get; }
	public Boolean showBasementHp { get; }
	public Boolean showTargetHp { get; }
	public Boolean isMonthMode { get; }

	// RVA: 0x2627140 VA: 0x7594c3f140
	public Boolean get_needSkip() { }
	// RVA: 0x2628d04 VA: 0x7594c40d04
	private Void set_needSkip(Boolean value) { }
	// RVA: 0x2626fe8 VA: 0x7594c3efe8
	public Boolean get_isValid() { }
	// RVA: 0x2628d84 VA: 0x7594c40d84
	private Void set_isValid(Boolean value) { }
	// RVA: 0x2628e04 VA: 0x7594c40e04
	public String get_topicId() { }
	// RVA: 0x2628e6c VA: 0x7594c40e6c
	private Void set_topicId(String value) { }
	// RVA: 0x2628ef0 VA: 0x7594c40ef0
	public String get_nodeId() { }
	// RVA: 0x2628f58 VA: 0x7594c40f58
	private Void set_nodeId(String value) { }
	// RVA: 0x26270d8 VA: 0x7594c3f0d8
	public SandboxV2NodeType get_nodeType() { }
	// RVA: 0x2628fdc VA: 0x7594c40fdc
	private Void set_nodeType(SandboxV2NodeType value) { }
	// RVA: 0x2629058 VA: 0x7594c41058
	public String get_stageId() { }
	// RVA: 0x26290c0 VA: 0x7594c410c0
	private Void set_stageId(String value) { }
	// RVA: 0x2627518 VA: 0x7594c3f518
	public String get_stageName() { }
	// RVA: 0x2629144 VA: 0x7594c41144
	private Void set_stageName(String value) { }
	// RVA: 0x26274b0 VA: 0x7594c3f4b0
	public String get_typeName() { }
	// RVA: 0x26291c8 VA: 0x7594c411c8
	private Void set_typeName(String value) { }
	// RVA: 0x262744c VA: 0x7594c3f44c
	public CharUISkinStruct get_finishIllust() { }
	// RVA: 0x262924c VA: 0x7594c4124c
	private Void set_finishIllust(CharUISkinStruct value) { }
	// RVA: 0x2628284 VA: 0x7594c40284
	public Boolean get_isEnemyRush() { }
	// RVA: 0x26292dc VA: 0x7594c412dc
	private Void set_isEnemyRush(Boolean value) { }
	// RVA: 0x26285c0 VA: 0x7594c405c0
	public Int32 get_prevEnemyCnt() { }
	// RVA: 0x262935c VA: 0x7594c4135c
	private Void set_prevEnemyCnt(Int32 value) { }
	// RVA: 0x2628558 VA: 0x7594c40558
	public Int32 get_currEnemyCnt() { }
	// RVA: 0x26293d8 VA: 0x7594c413d8
	private Void set_currEnemyCnt(Int32 value) { }
	// RVA: 0x2628404 VA: 0x7594c40404
	public List`1 get_normalRewardList() { }
	// RVA: 0x2629454 VA: 0x7594c41454
	private Void set_normalRewardList(List`1 value) { }
	// RVA: 0x26284f0 VA: 0x7594c404f0
	public List`1 get_randomRewardList() { }
	// RVA: 0x26294d8 VA: 0x7594c414d8
	private Void set_randomRewardList(List`1 value) { }
	// RVA: 0x262955c VA: 0x7594c4155c
	public String get_monthlyRushId() { }
	// RVA: 0x26295c4 VA: 0x7594c415c4
	private Void set_monthlyRushId(String value) { }
	// RVA: 0x26280c8 VA: 0x7594c400c8
	public Boolean get_needMonthToast() { }
	// RVA: 0x2629648 VA: 0x7594c41648
	private Void set_needMonthToast(Boolean value) { }
	// RVA: 0x2628060 VA: 0x7594c40060
	public CharWordData get_charWord() { }
	// RVA: 0x26296c8 VA: 0x7594c416c8
	private Void set_charWord(CharWordData value) { }
	// RVA: 0x26287c0 VA: 0x7594c407c0
	public Boolean get_isTargetDefeated() { }
	// RVA: 0x2628628 VA: 0x7594c40628
	public Single get_hpRatio() { }
	// RVA: 0x26282ec VA: 0x7594c402ec
	public Boolean get_showReward() { }
	// RVA: 0x2628130 VA: 0x7594c40130
	public Boolean get_showBasementHp() { }
	// RVA: 0x26281c8 VA: 0x7594c401c8
	public Boolean get_showTargetHp() { }
	// RVA: 0x262974c VA: 0x7594c4174c
	public Boolean get_isMonthMode() { }
	// RVA: 0x2626920 VA: 0x7594c3e920
	public Void LoadData() { }
	// RVA: 0x26297bc VA: 0x7594c417bc
	private Boolean _LoadDataFromMonthModeResponse(CommonFinishBattleResponse finishResponse) { }
	// RVA: 0x2629920 VA: 0x7594c41920
	private Boolean _LoadDataFromNormalModeResponse(CommonFinishBattleResponse finishResponse) { }
	// RVA: 0x262a0b0 VA: 0x7594c420b0
	private Void _FindProperCharVoice() { }
	// RVA: 0x262a270 VA: 0x7594c42270
	private Boolean _TryGetProperWordType(out CharWordShowType wordType) { }
	// RVA: 0x2629e54 VA: 0x7594c41e54
	private List`1 _GetNodeStageEntityList(PlayerSandboxV2 playerSandboxV2) { }
	// RVA: 0x VA: 0x0
	private Void _AddEntityToList(List`1 dstList, List`1 srcList) { }
	// RVA: 0x2629d18 VA: 0x7594c41d18
	private Boolean _CheckNeedSkip(PlayerSandboxV2 playerSandboxV2) { }
	// RVA: 0x2628a60 VA: 0x7594c40a60
	public Void .ctor() { }
}
```