# ActMultiV3PrepareMainViewModel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `String <activityId>k__BackingField`

- `Boolean <isMatch>k__BackingField`

- `Boolean <isInvertMode>k__BackingField`

- `ActMultiV3PrepareStepType <currStep>k__BackingField`

- `ActMultiV3SelectStepData <currStepData>k__BackingField`

- `TeamState <teamState>k__BackingField`

- `ActMultiV3PrepareMainViewConfig <mainViewConfig>k__BackingField`

- `StepCDInfo <stepCD>k__BackingField`

- `StageInfo <curStageInfo>k__BackingField`

- `ActMultiV3DifficultyIconViewModel <diffIconModel>k__BackingField`

- `ActMultiV3PrepareMainPlayerInfoViewModel <playerInfoViewModel>k__BackingField`

- `String <cachedPartnerUID>k__BackingField`

- `FriendDataWithNameCard <cachedPartnerNameCardData>k__BackingField`

- `Boolean <inEmergency>k__BackingField`

- `LeftChatPosType <chatPosType>k__BackingField`

- `Int32 <chatCdSeqNum>k__BackingField`

- `Int32 <chatCdDuration>k__BackingField`


## Properties

- `String activityId`

- `Boolean isMatch`

- `Boolean isInvertMode`

- `ActMultiV3PrepareStepType currStep`

- `ActMultiV3SelectStepData currStepData`

- `TeamState teamState`

- `ActMultiV3PrepareMainViewConfig mainViewConfig`

- `StepCDInfo stepCD`

- `StageInfo curStageInfo`

- `ActMultiV3DifficultyIconViewModel diffIconModel`

- `ActMultiV3PrepareMainPlayerInfoViewModel playerInfoViewModel`

- `String cachedPartnerUID`

- `FriendDataWithNameCard cachedPartnerNameCardData`

- `Boolean inEmergency`

- `LeftChatPosType chatPosType`

- `Int32 chatCdSeqNum`

- `Int32 chatCdDuration`


## Methods

- `String get_activityId()`

- `Void set_activityId(String)`

- `Boolean get_isMatch()`

- `Void set_isMatch(Boolean)`

- `Boolean get_isInvertMode()`

- `Void set_isInvertMode(Boolean)`

- `ActMultiV3PrepareStepType get_currStep()`

- `Void set_currStep(ActMultiV3PrepareStepType)`

- `ActMultiV3SelectStepData get_currStepData()`

- `Void set_currStepData(ActMultiV3SelectStepData)`

- `TeamState get_teamState()`

- `Void set_teamState(TeamState)`

- `ActMultiV3PrepareMainViewConfig get_mainViewConfig()`

- `Void set_mainViewConfig(ActMultiV3PrepareMainViewConfig)`

- `Void set_pingConds(List`1)`

- `StepCDInfo get_stepCD()`

- `Void set_stepCD(StepCDInfo)`

- `StageInfo get_curStageInfo()`

- `Void set_curStageInfo(StageInfo)`

- `ActMultiV3DifficultyIconViewModel get_diffIconModel()`

- `Void set_diffIconModel(ActMultiV3DifficultyIconViewModel)`

- `ActMultiV3PrepareMainPlayerInfoViewModel get_playerInfoViewModel()`

- `Void set_playerInfoViewModel(ActMultiV3PrepareMainPlayerInfoViewModel)`

- `String get_cachedPartnerUID()`

- `Void set_cachedPartnerUID(String)`

- `FriendDataWithNameCard get_cachedPartnerNameCardData()`

- `Void set_cachedPartnerNameCardData(FriendDataWithNameCard)`

- `Boolean get_inEmergency()`

- `Void set_inEmergency(Boolean)`

- `LeftChatPosType get_chatPosType()`

- `Void set_chatPosType(LeftChatPosType)`

- `Int32 get_chatCdSeqNum()`

- `Void set_chatCdSeqNum(Int32)`

- `Int32 get_chatCdDuration()`

- `Void set_chatCdDuration(Int32)`

- `Void LoadStableData(String)`

- `Void Update()`

- `Void RefreshPlayerInfoTrackpoint()`

- `Void _LoadCurStageData(TeamInfo)`

- `ActMultiV3PrepareStepType _GetStep(TeamState)`

- `Void SetPartnerNameCardData(String, FriendDataWithNameCard)`

- `Void SetMainViewConfig(ActMultiV3PrepareMainViewConfig, out)`

- `Void SetInEmergency(Boolean)`

- `Void NotifyChatCD()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainViewModel : IHotfixable
{
	private String <activityId>k__BackingField; // 0x10
	private Boolean <isMatch>k__BackingField; // 0x18
	private Boolean <isInvertMode>k__BackingField; // 0x19
	private ActMultiV3PrepareStepType <currStep>k__BackingField; // 0x1c
	private ActMultiV3SelectStepData <currStepData>k__BackingField; // 0x20
	private TeamState <teamState>k__BackingField; // 0x28
	private ActMultiV3PrepareMainViewConfig <mainViewConfig>k__BackingField; // 0x2c
	private List`1 <pingConds>k__BackingField; // 0x38
	private StepCDInfo <stepCD>k__BackingField; // 0x40
	private StageInfo <curStageInfo>k__BackingField; // 0x50
	private ActMultiV3DifficultyIconViewModel <diffIconModel>k__BackingField; // 0x78
	private ActMultiV3PrepareMainPlayerInfoViewModel <playerInfoViewModel>k__BackingField; // 0x80
	private String <cachedPartnerUID>k__BackingField; // 0x88
	private FriendDataWithNameCard <cachedPartnerNameCardData>k__BackingField; // 0x90
	private Boolean <inEmergency>k__BackingField; // 0x98
	private LeftChatPosType <chatPosType>k__BackingField; // 0x9c
	private Int32 <chatCdSeqNum>k__BackingField; // 0xa0
	private Int32 <chatCdDuration>k__BackingField; // 0xa4
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_set_activityId; // 0x8
	private static DelegateBridge __Hotfix0_get_isMatch; // 0x10
	private static DelegateBridge __Hotfix0_set_isMatch; // 0x18
	private static DelegateBridge __Hotfix0_get_isInvertMode; // 0x20
	private static DelegateBridge __Hotfix0_set_isInvertMode; // 0x28
	private static DelegateBridge __Hotfix0_get_currStep; // 0x30
	private static DelegateBridge __Hotfix0_set_currStep; // 0x38
	private static DelegateBridge __Hotfix0_get_currStepData; // 0x40
	private static DelegateBridge __Hotfix0_set_currStepData; // 0x48
	private static DelegateBridge __Hotfix0_get_teamState; // 0x50
	private static DelegateBridge __Hotfix0_set_teamState; // 0x58
	private static DelegateBridge __Hotfix0_get_mainViewConfig; // 0x60
	private static DelegateBridge __Hotfix0_set_mainViewConfig; // 0x68
	private static DelegateBridge __Hotfix0_get_pingConds; // 0x70
	private static DelegateBridge __Hotfix0_set_pingConds; // 0x78
	private static DelegateBridge __Hotfix0_get_stepCD; // 0x80
	private static DelegateBridge __Hotfix0_set_stepCD; // 0x88
	private static DelegateBridge __Hotfix0_get_curStageInfo; // 0x90
	private static DelegateBridge __Hotfix0_set_curStageInfo; // 0x98
	private static DelegateBridge __Hotfix0_get_diffIconModel; // 0xa0
	private static DelegateBridge __Hotfix0_set_diffIconModel; // 0xa8
	private static DelegateBridge __Hotfix0_get_playerInfoViewModel; // 0xb0
	private static DelegateBridge __Hotfix0_set_playerInfoViewModel; // 0xb8
	private static DelegateBridge __Hotfix0_get_cachedPartnerUID; // 0xc0
	private static DelegateBridge __Hotfix0_set_cachedPartnerUID; // 0xc8
	private static DelegateBridge __Hotfix0_get_cachedPartnerNameCardData; // 0xd0
	private static DelegateBridge __Hotfix0_set_cachedPartnerNameCardData; // 0xd8
	private static DelegateBridge __Hotfix0_get_inEmergency; // 0xe0
	private static DelegateBridge __Hotfix0_set_inEmergency; // 0xe8
	private static DelegateBridge __Hotfix0_get_chatPosType; // 0xf0
	private static DelegateBridge __Hotfix0_set_chatPosType; // 0xf8
	private static DelegateBridge __Hotfix0_get_chatCdSeqNum; // 0x100
	private static DelegateBridge __Hotfix0_set_chatCdSeqNum; // 0x108
	private static DelegateBridge __Hotfix0_get_chatCdDuration; // 0x110
	private static DelegateBridge __Hotfix0_set_chatCdDuration; // 0x118
	private static DelegateBridge __Hotfix0_LoadStableData; // 0x120
	private static DelegateBridge __Hotfix0_Update; // 0x128
	private static DelegateBridge __Hotfix0_RefreshPlayerInfoTrackpoint; // 0x130
	private static DelegateBridge __Hotfix0__LoadCurStageData; // 0x138
	private static DelegateBridge __Hotfix0__GetStep; // 0x140
	private static DelegateBridge __Hotfix0_SetPartnerNameCardData; // 0x148
	private static DelegateBridge __Hotfix0_SetMainViewConfig; // 0x150
	private static DelegateBridge __Hotfix0_SetInEmergency; // 0x158
	private static DelegateBridge __Hotfix0_NotifyChatCD; // 0x160
	private static DelegateBridge _c__Hotfix0_ctor; // 0x168

	public String activityId { get; set; }
	public Boolean isMatch { get; set; }
	public Boolean isInvertMode { get; set; }
	public ActMultiV3PrepareStepType currStep { get; set; }
	public ActMultiV3SelectStepData currStepData { get; set; }
	public TeamState teamState { get; set; }
	public ActMultiV3PrepareMainViewConfig mainViewConfig { get; set; }
	public List`1 pingConds { get; set; }
	public StepCDInfo stepCD { get; set; }
	public StageInfo curStageInfo { get; set; }
	public ActMultiV3DifficultyIconViewModel diffIconModel { get; set; }
	public ActMultiV3PrepareMainPlayerInfoViewModel playerInfoViewModel { get; set; }
	public String cachedPartnerUID { get; set; }
	public FriendDataWithNameCard cachedPartnerNameCardData { get; set; }
	public Boolean inEmergency { get; set; }
	public LeftChatPosType chatPosType { get; set; }
	public Int32 chatCdSeqNum { get; set; }
	public Int32 chatCdDuration { get; set; }

	// RVA: 0x3159754 VA: 0x7595771754
	public String get_activityId() { }
	// RVA: 0x315bab4 VA: 0x7595773ab4
	private Void set_activityId(String value) { }
	// RVA: 0x315b140 VA: 0x7595773140
	public Boolean get_isMatch() { }
	// RVA: 0x315bb38 VA: 0x7595773b38
	private Void set_isMatch(Boolean value) { }
	// RVA: 0x315bbb8 VA: 0x7595773bb8
	public Boolean get_isInvertMode() { }
	// RVA: 0x315bc20 VA: 0x7595773c20
	private Void set_isInvertMode(Boolean value) { }
	// RVA: 0x315abcc VA: 0x7595772bcc
	public ActMultiV3PrepareStepType get_currStep() { }
	// RVA: 0x315bca0 VA: 0x7595773ca0
	private Void set_currStep(ActMultiV3PrepareStepType value) { }
	// RVA: 0x315bd1c VA: 0x7595773d1c
	public ActMultiV3SelectStepData get_currStepData() { }
	// RVA: 0x315bd84 VA: 0x7595773d84
	private Void set_currStepData(ActMultiV3SelectStepData value) { }
	// RVA: 0x315b5bc VA: 0x75957735bc
	public TeamState get_teamState() { }
	// RVA: 0x315be08 VA: 0x7595773e08
	private Void set_teamState(TeamState value) { }
	// RVA: 0x315be84 VA: 0x7595773e84
	public ActMultiV3PrepareMainViewConfig get_mainViewConfig() { }
	// RVA: 0x315bef4 VA: 0x7595773ef4
	private Void set_mainViewConfig(ActMultiV3PrepareMainViewConfig value) { }
	// RVA: 0x315bf78 VA: 0x7595773f78
	public List`1 get_pingConds() { }
	// RVA: 0x315bfe0 VA: 0x7595773fe0
	private Void set_pingConds(List`1 value) { }
	// RVA: 0x315c064 VA: 0x7595774064
	public StepCDInfo get_stepCD() { }
	// RVA: 0x315c0c8 VA: 0x75957740c8
	private Void set_stepCD(StepCDInfo value) { }
	// RVA: 0x31597bc VA: 0x75957717bc
	public StageInfo get_curStageInfo() { }
	// RVA: 0x315c14c VA: 0x759577414c
	private Void set_curStageInfo(StageInfo value) { }
	// RVA: 0x315c1fc VA: 0x75957741fc
	public ActMultiV3DifficultyIconViewModel get_diffIconModel() { }
	// RVA: 0x315c264 VA: 0x7595774264
	private Void set_diffIconModel(ActMultiV3DifficultyIconViewModel value) { }
	// RVA: 0x315b0d8 VA: 0x75957730d8
	public ActMultiV3PrepareMainPlayerInfoViewModel get_playerInfoViewModel() { }
	// RVA: 0x315c2e8 VA: 0x75957742e8
	private Void set_playerInfoViewModel(ActMultiV3PrepareMainPlayerInfoViewModel value) { }
	// RVA: 0x315ae88 VA: 0x7595772e88
	public String get_cachedPartnerUID() { }
	// RVA: 0x315c36c VA: 0x759577436c
	private Void set_cachedPartnerUID(String value) { }
	// RVA: 0x315b1a8 VA: 0x75957731a8
	public FriendDataWithNameCard get_cachedPartnerNameCardData() { }
	// RVA: 0x315c3f0 VA: 0x75957743f0
	private Void set_cachedPartnerNameCardData(FriendDataWithNameCard value) { }
	// RVA: 0x315c474 VA: 0x7595774474
	public Boolean get_inEmergency() { }
	// RVA: 0x315c4dc VA: 0x75957744dc
	private Void set_inEmergency(Boolean value) { }
	// RVA: 0x315ada8 VA: 0x7595772da8
	public LeftChatPosType get_chatPosType() { }
	// RVA: 0x315c55c VA: 0x759577455c
	private Void set_chatPosType(LeftChatPosType value) { }
	// RVA: 0x315c5d8 VA: 0x75957745d8
	public Int32 get_chatCdSeqNum() { }
	// RVA: 0x315c640 VA: 0x7595774640
	private Void set_chatCdSeqNum(Int32 value) { }
	// RVA: 0x315c6bc VA: 0x75957746bc
	public Int32 get_chatCdDuration() { }
	// RVA: 0x315c724 VA: 0x7595774724
	private Void set_chatCdDuration(Int32 value) { }
	// RVA: 0x3158964 VA: 0x7595770964
	public Void LoadStableData(String actId) { }
	// RVA: 0x3158c40 VA: 0x7595770c40
	public Void Update() { }
	// RVA: 0x315ae10 VA: 0x7595772e10
	public Void RefreshPlayerInfoTrackpoint() { }
	// RVA: 0x315c838 VA: 0x7595774838
	private Void _LoadCurStageData(TeamInfo teamInfo) { }
	// RVA: 0x315c7a0 VA: 0x75957747a0
	private ActMultiV3PrepareStepType _GetStep(TeamState teamState) { }
	// RVA: 0x315b990 VA: 0x7595773990
	public Void SetPartnerNameCardData(String uid, FriendDataWithNameCard data) { }
	// RVA: 0x3159448 VA: 0x7595771448
	public Void SetMainViewConfig(ActMultiV3PrepareMainViewConfig mvConfig, out Boolean isChatPosTypeChanged) { }
	// RVA: 0x315ad28 VA: 0x7595772d28
	public Void SetInEmergency(Boolean state) { }
	// RVA: 0x315b30c VA: 0x759577330c
	public Void NotifyChatCD() { }
	// RVA: 0x315caa0 VA: 0x7595774aa0
	public Void .ctor() { }
}
```