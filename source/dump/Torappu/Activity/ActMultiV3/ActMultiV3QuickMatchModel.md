# ActMultiV3QuickMatchModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3InverseUnlockCond m_inverseUnlockCond`

- `Boolean m_isInverseUnlock`

- `Boolean m_isInverseActive`

- `Int64 m_banFinishTs`

- `Single m_matchingSecs`

- `Boolean <isMatchUnlock>k__BackingField`

- `Int32 <matchStatusSeqNum>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`

- `ActMultiV3MatchStatus <matchStatus>k__BackingField`

- `ActMultiV3MatchResult <matchResult>k__BackingField`

- `ActMultiV3MatchPosType <partnerPosType>k__BackingField`

- `Boolean <isPosListShow>k__BackingField`

- `ActMultiV3MatchPosType <currPosType>k__BackingField`

- `Int32 <tipSwitchTime>k__BackingField`

- `String <trainingStageConfirmDesc>k__BackingField`

- `String <trainingLockToastStr>k__BackingField`

- `String <nothingSelectToastStr>k__BackingField`

- `String <continuousClickToastStr>k__BackingField`

- `String <bannedToastStr>k__BackingField`

- `String <serverOverloadToastStr>k__BackingField`

- `String <inverseDescStr>k__BackingField`

- `String <inverseUnlockHintToastStr>k__BackingField`

- `String <matchConnectFailedToastStr>k__BackingField`

- `String <actId>k__BackingField`


## Properties

- `Boolean isMatchUnlock`

- `Int32 matchStatusSeqNum`

- `Int32 enterSeqNum`

- `ActMultiV3MatchStatus matchStatus`

- `ActMultiV3MatchResult matchResult`

- `ActMultiV3MatchPosType partnerPosType`

- `Boolean isPosListShow`

- `ActMultiV3MatchPosType currPosType`

- `Int32 tipSwitchTime`

- `String trainingStageConfirmDesc`

- `String trainingLockToastStr`

- `String nothingSelectToastStr`

- `String continuousClickToastStr`

- `String bannedToastStr`

- `String serverOverloadToastStr`

- `String inverseDescStr`

- `String inverseUnlockHintToastStr`

- `String matchConnectFailedToastStr`

- `String actId`

- `Boolean isInverseActive`

- `Boolean isInverseUnlock`

- `Boolean isMatching`

- `Boolean isMatchBanned`

- `Int32 waitSeconds`


## Methods

- `Boolean get_isMatchUnlock()`

- `Void set_isMatchUnlock(Boolean)`

- `Int32 get_matchStatusSeqNum()`

- `Void set_matchStatusSeqNum(Int32)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `ActMultiV3MatchStatus get_matchStatus()`

- `Void set_matchStatus(ActMultiV3MatchStatus)`

- `ActMultiV3MatchResult get_matchResult()`

- `Void set_matchResult(ActMultiV3MatchResult)`

- `ActMultiV3MatchPosType get_partnerPosType()`

- `Void set_partnerPosType(ActMultiV3MatchPosType)`

- `Boolean get_isPosListShow()`

- `Void set_isPosListShow(Boolean)`

- `ActMultiV3MatchPosType get_currPosType()`

- `Void set_currPosType(ActMultiV3MatchPosType)`

- `Int32 get_tipSwitchTime()`

- `Void set_tipSwitchTime(Int32)`

- `String get_trainingStageConfirmDesc()`

- `Void set_trainingStageConfirmDesc(String)`

- `String get_trainingLockToastStr()`

- `Void set_trainingLockToastStr(String)`

- `String get_nothingSelectToastStr()`

- `Void set_nothingSelectToastStr(String)`

- `String get_continuousClickToastStr()`

- `Void set_continuousClickToastStr(String)`

- `String get_bannedToastStr()`

- `Void set_bannedToastStr(String)`

- `String get_serverOverloadToastStr()`

- `Void set_serverOverloadToastStr(String)`

- `String get_inverseDescStr()`

- `Void set_inverseDescStr(String)`

- `String get_inverseUnlockHintToastStr()`

- `Void set_inverseUnlockHintToastStr(String)`

- `String get_matchConnectFailedToastStr()`

- `Void set_matchConnectFailedToastStr(String)`

- `String get_actId()`

- `Void set_actId(String)`

- `Boolean get_isInverseActive()`

- `Boolean get_isInverseUnlock()`

- `Boolean get_isMatching()`

- `Boolean get_isMatchBanned()`

- `Int32 get_waitSeconds()`

- `Option CreateStartMatchOption()`

- `Boolean CheckModeGroupSelect(ActMultiV3MapModeType)`

- `Boolean CheckModeSelect(String)`

- `Void ToggleModeSelect(String)`

- `Void ToggleInverse()`

- `Int32 GetSelectCount()`

- `ActMultiV3MatchPosModel FindCurrMatchPosModel()`

- `ActMultiV3MatchPosModel FindMatchPosModel(ActMultiV3MatchPosType)`

- `ActMultiV3MatchPosModel _FindMatchPosModel(ActMultiV3MatchPosType)`

- `Void LoadData(String)`

- `Void _InitTipList(String, ActMultiV3Data)`

- `String FetchRandomTip()`

- `Void _InitMatchPosList(String, ActMultiV3Data)`

- `Void _InitModeGroupList(String, ActMultiV3Data)`

- `Void UpdateBanTime()`

- `Void MarkStartMatch()`

- `Void MarkMatchTick(Single)`

- `Void MarkEndMatch(ActMultiV3MatchResult)`

- `Void SetPartnerPos(ActMultiV3MatchPosType)`

- `Void MarkEnter()`

- `Void _UpdateBanTime()`

- `ActMultiV3MatchModeDiffModel FindModeDiffModel(String)`

- `ActMultiV3MatchModeGroupModel FindModeGroupModel(ActMultiV3MapModeType)`

- `ActMultiV3MatchModeDiffModel FindModeDiffModel(ActMultiV3MapModeType, ActMultiV3MapDiffType)`

- `Void ConsumeSelectModeTrack()`

- `Void ConsumeModeTrack(String)`

- `Void _ConsumeModeTrack(String)`

- `ActMultiV3MatchModeGroupModel _FindModeGroupModel(ActMultiV3MapModeType)`

- `Void _UpdateModeDiffUnlockStatus()`

- `Void _UpdateInverseUnlockStatus()`

- `Void _UpdatePosUnlockStatus()`

- `Void _UpdateMapScore()`

- `Void _InitMatchConfig(ActMultiV3Data)`

- `Void _InitMatchConfigUsingPlayerData(MatchInfo)`

- `Void _InitMatchConfigUsingGameData(ActMultiV3Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3QuickMatchModel : IHotfixable
{
	private List`1 m_posList; // 0x10
	private List`1 m_modeGroupList; // 0x18
	private ActMultiV3InverseUnlockCond m_inverseUnlockCond; // 0x20
	private Boolean m_isInverseUnlock; // 0x28
	private Boolean m_isInverseActive; // 0x29
	private Int64 m_banFinishTs; // 0x30
	private Single m_matchingSecs; // 0x38
	private List`1 m_selectList; // 0x40
	private List`1 m_allTipList; // 0x48
	private List`1 m_drawTipList; // 0x50
	private Boolean <isMatchUnlock>k__BackingField; // 0x58
	private Int32 <matchStatusSeqNum>k__BackingField; // 0x5c
	private Int32 <enterSeqNum>k__BackingField; // 0x60
	private ActMultiV3MatchStatus <matchStatus>k__BackingField; // 0x64
	private ActMultiV3MatchResult <matchResult>k__BackingField; // 0x68
	private ActMultiV3MatchPosType <partnerPosType>k__BackingField; // 0x6c
	private Boolean <isPosListShow>k__BackingField; // 0x70
	private ActMultiV3MatchPosType <currPosType>k__BackingField; // 0x74
	private Int32 <tipSwitchTime>k__BackingField; // 0x78
	private String <trainingStageConfirmDesc>k__BackingField; // 0x80
	private String <trainingLockToastStr>k__BackingField; // 0x88
	private String <nothingSelectToastStr>k__BackingField; // 0x90
	private String <continuousClickToastStr>k__BackingField; // 0x98
	private String <bannedToastStr>k__BackingField; // 0xa0
	private String <serverOverloadToastStr>k__BackingField; // 0xa8
	private String <inverseDescStr>k__BackingField; // 0xb0
	private String <inverseUnlockHintToastStr>k__BackingField; // 0xb8
	private String <matchConnectFailedToastStr>k__BackingField; // 0xc0
	private String <actId>k__BackingField; // 0xc8
	private static DelegateBridge __Hotfix0_get_isMatchUnlock; // 0x0
	private static DelegateBridge __Hotfix0_set_isMatchUnlock; // 0x8
	private static DelegateBridge __Hotfix0_get_matchStatusSeqNum; // 0x10
	private static DelegateBridge __Hotfix0_set_matchStatusSeqNum; // 0x18
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x28
	private static DelegateBridge __Hotfix0_get_matchStatus; // 0x30
	private static DelegateBridge __Hotfix0_set_matchStatus; // 0x38
	private static DelegateBridge __Hotfix0_get_matchResult; // 0x40
	private static DelegateBridge __Hotfix0_set_matchResult; // 0x48
	private static DelegateBridge __Hotfix0_get_partnerPosType; // 0x50
	private static DelegateBridge __Hotfix0_set_partnerPosType; // 0x58
	private static DelegateBridge __Hotfix0_get_isPosListShow; // 0x60
	private static DelegateBridge __Hotfix0_set_isPosListShow; // 0x68
	private static DelegateBridge __Hotfix0_get_currPosType; // 0x70
	private static DelegateBridge __Hotfix0_set_currPosType; // 0x78
	private static DelegateBridge __Hotfix0_get_tipSwitchTime; // 0x80
	private static DelegateBridge __Hotfix0_set_tipSwitchTime; // 0x88
	private static DelegateBridge __Hotfix0_get_trainingStageConfirmDesc; // 0x90
	private static DelegateBridge __Hotfix0_set_trainingStageConfirmDesc; // 0x98
	private static DelegateBridge __Hotfix0_get_trainingLockToastStr; // 0xa0
	private static DelegateBridge __Hotfix0_set_trainingLockToastStr; // 0xa8
	private static DelegateBridge __Hotfix0_get_nothingSelectToastStr; // 0xb0
	private static DelegateBridge __Hotfix0_set_nothingSelectToastStr; // 0xb8
	private static DelegateBridge __Hotfix0_get_continuousClickToastStr; // 0xc0
	private static DelegateBridge __Hotfix0_set_continuousClickToastStr; // 0xc8
	private static DelegateBridge __Hotfix0_get_bannedToastStr; // 0xd0
	private static DelegateBridge __Hotfix0_set_bannedToastStr; // 0xd8
	private static DelegateBridge __Hotfix0_get_serverOverloadToastStr; // 0xe0
	private static DelegateBridge __Hotfix0_set_serverOverloadToastStr; // 0xe8
	private static DelegateBridge __Hotfix0_get_inverseDescStr; // 0xf0
	private static DelegateBridge __Hotfix0_set_inverseDescStr; // 0xf8
	private static DelegateBridge __Hotfix0_get_inverseUnlockHintToastStr; // 0x100
	private static DelegateBridge __Hotfix0_set_inverseUnlockHintToastStr; // 0x108
	private static DelegateBridge __Hotfix0_get_matchConnectFailedToastStr; // 0x110
	private static DelegateBridge __Hotfix0_set_matchConnectFailedToastStr; // 0x118
	private static DelegateBridge __Hotfix0_get_actId; // 0x120
	private static DelegateBridge __Hotfix0_set_actId; // 0x128
	private static DelegateBridge __Hotfix0_get_isInverseActive; // 0x130
	private static DelegateBridge __Hotfix0_get_isInverseUnlock; // 0x138
	private static DelegateBridge __Hotfix0_get_isMatching; // 0x140
	private static DelegateBridge __Hotfix0_get_modeGroupList; // 0x148
	private static DelegateBridge __Hotfix0_get_posList; // 0x150
	private static DelegateBridge __Hotfix0_get_isMatchBanned; // 0x158
	private static DelegateBridge __Hotfix0_get_waitSeconds; // 0x160
	private static DelegateBridge __Hotfix0_CreateStartMatchOption; // 0x168
	private static DelegateBridge __Hotfix0_CheckModeGroupSelect; // 0x170
	private static DelegateBridge __Hotfix0_CheckModeSelect; // 0x178
	private static DelegateBridge __Hotfix0_ToggleModeSelect; // 0x180
	private static DelegateBridge __Hotfix0_ToggleInverse; // 0x188
	private static DelegateBridge __Hotfix0_GetSelectCount; // 0x190
	private static DelegateBridge __Hotfix0_FindCurrMatchPosModel; // 0x198
	private static DelegateBridge __Hotfix0_FindMatchPosModel; // 0x1a0
	private static DelegateBridge __Hotfix0__FindMatchPosModel; // 0x1a8
	private static DelegateBridge __Hotfix0_LoadData; // 0x1b0
	private static DelegateBridge __Hotfix0__InitTipList; // 0x1b8
	private static DelegateBridge __Hotfix0_FetchRandomTip; // 0x1c0
	private static DelegateBridge __Hotfix0__InitMatchPosList; // 0x1c8
	private static DelegateBridge __Hotfix0__InitModeGroupList; // 0x1d0
	private static DelegateBridge __Hotfix0_UpdateBanTime; // 0x1d8
	private static DelegateBridge __Hotfix0_MarkStartMatch; // 0x1e0
	private static DelegateBridge __Hotfix0_MarkMatchTick; // 0x1e8
	private static DelegateBridge __Hotfix0_MarkEndMatch; // 0x1f0
	private static DelegateBridge __Hotfix0_SetPartnerPos; // 0x1f8
	private static DelegateBridge __Hotfix0_MarkEnter; // 0x200
	private static DelegateBridge __Hotfix0__UpdateBanTime; // 0x208
	private static DelegateBridge __Hotfix0_FindModeDiffModel; // 0x210
	private static DelegateBridge __Hotfix0_FindModeGroupModel; // 0x218
	private static DelegateBridge __Hotfix1_FindModeDiffModel; // 0x220
	private static DelegateBridge __Hotfix0_ConsumeSelectModeTrack; // 0x228
	private static DelegateBridge __Hotfix0_ConsumeModeTrack; // 0x230
	private static DelegateBridge __Hotfix0__ConsumeModeTrack; // 0x238
	private static DelegateBridge __Hotfix0__FindModeGroupModel; // 0x240
	private static DelegateBridge __Hotfix0__UpdateModeDiffUnlockStatus; // 0x248
	private static DelegateBridge __Hotfix0__UpdateInverseUnlockStatus; // 0x250
	private static DelegateBridge __Hotfix0__UpdatePosUnlockStatus; // 0x258
	private static DelegateBridge __Hotfix0__UpdateMapScore; // 0x260
	private static DelegateBridge __Hotfix0__InitMatchConfig; // 0x268
	private static DelegateBridge __Hotfix0__InitMatchConfigUsingPlayerData; // 0x270
	private static DelegateBridge __Hotfix0__InitMatchConfigUsingGameData; // 0x278
	private static DelegateBridge _c__Hotfix0_ctor; // 0x280

	public Boolean isMatchUnlock { get; set; }
	public Int32 matchStatusSeqNum { get; set; }
	public Int32 enterSeqNum { get; set; }
	public ActMultiV3MatchStatus matchStatus { get; set; }
	public ActMultiV3MatchResult matchResult { get; set; }
	public ActMultiV3MatchPosType partnerPosType { get; set; }
	public Boolean isPosListShow { get; set; }
	public ActMultiV3MatchPosType currPosType { get; set; }
	public Int32 tipSwitchTime { get; set; }
	public String trainingStageConfirmDesc { get; set; }
	public String trainingLockToastStr { get; set; }
	public String nothingSelectToastStr { get; set; }
	public String continuousClickToastStr { get; set; }
	public String bannedToastStr { get; set; }
	public String serverOverloadToastStr { get; set; }
	public String inverseDescStr { get; set; }
	public String inverseUnlockHintToastStr { get; set; }
	public String matchConnectFailedToastStr { get; set; }
	public String actId { get; set; }
	public Boolean isInverseActive { get; }
	public Boolean isInverseUnlock { get; }
	public Boolean isMatching { get; }
	public List`1 modeGroupList { get; }
	public List`1 posList { get; }
	public Boolean isMatchBanned { get; }
	public Int32 waitSeconds { get; }

	// RVA: 0x312d910 VA: 0x7595745910
	public Boolean get_isMatchUnlock() { }
	// RVA: 0x312d978 VA: 0x7595745978
	private Void set_isMatchUnlock(Boolean value) { }
	// RVA: 0x312d9f8 VA: 0x75957459f8
	public Int32 get_matchStatusSeqNum() { }
	// RVA: 0x312da60 VA: 0x7595745a60
	private Void set_matchStatusSeqNum(Int32 value) { }
	// RVA: 0x312dadc VA: 0x7595745adc
	public Int32 get_enterSeqNum() { }
	// RVA: 0x312db44 VA: 0x7595745b44
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x312dbc0 VA: 0x7595745bc0
	public ActMultiV3MatchStatus get_matchStatus() { }
	// RVA: 0x312dc28 VA: 0x7595745c28
	private Void set_matchStatus(ActMultiV3MatchStatus value) { }
	// RVA: 0x312dca4 VA: 0x7595745ca4
	public ActMultiV3MatchResult get_matchResult() { }
	// RVA: 0x312dd0c VA: 0x7595745d0c
	private Void set_matchResult(ActMultiV3MatchResult value) { }
	// RVA: 0x312dd88 VA: 0x7595745d88
	public ActMultiV3MatchPosType get_partnerPosType() { }
	// RVA: 0x312ddf0 VA: 0x7595745df0
	private Void set_partnerPosType(ActMultiV3MatchPosType value) { }
	// RVA: 0x312de6c VA: 0x7595745e6c
	public Boolean get_isPosListShow() { }
	// RVA: 0x312ded4 VA: 0x7595745ed4
	public Void set_isPosListShow(Boolean value) { }
	// RVA: 0x312df54 VA: 0x7595745f54
	public ActMultiV3MatchPosType get_currPosType() { }
	// RVA: 0x312dfbc VA: 0x7595745fbc
	public Void set_currPosType(ActMultiV3MatchPosType value) { }
	// RVA: 0x312e038 VA: 0x7595746038
	public Int32 get_tipSwitchTime() { }
	// RVA: 0x312e0a0 VA: 0x75957460a0
	private Void set_tipSwitchTime(Int32 value) { }
	// RVA: 0x312e11c VA: 0x759574611c
	public String get_trainingStageConfirmDesc() { }
	// RVA: 0x312e184 VA: 0x7595746184
	private Void set_trainingStageConfirmDesc(String value) { }
	// RVA: 0x312e208 VA: 0x7595746208
	public String get_trainingLockToastStr() { }
	// RVA: 0x312e270 VA: 0x7595746270
	private Void set_trainingLockToastStr(String value) { }
	// RVA: 0x312e2f4 VA: 0x75957462f4
	public String get_nothingSelectToastStr() { }
	// RVA: 0x312e35c VA: 0x759574635c
	private Void set_nothingSelectToastStr(String value) { }
	// RVA: 0x312e3e0 VA: 0x75957463e0
	public String get_continuousClickToastStr() { }
	// RVA: 0x312e448 VA: 0x7595746448
	private Void set_continuousClickToastStr(String value) { }
	// RVA: 0x312e4cc VA: 0x75957464cc
	public String get_bannedToastStr() { }
	// RVA: 0x312e534 VA: 0x7595746534
	private Void set_bannedToastStr(String value) { }
	// RVA: 0x312e5b8 VA: 0x75957465b8
	public String get_serverOverloadToastStr() { }
	// RVA: 0x312e620 VA: 0x7595746620
	private Void set_serverOverloadToastStr(String value) { }
	// RVA: 0x312e6a4 VA: 0x75957466a4
	public String get_inverseDescStr() { }
	// RVA: 0x312e70c VA: 0x759574670c
	private Void set_inverseDescStr(String value) { }
	// RVA: 0x312e790 VA: 0x7595746790
	public String get_inverseUnlockHintToastStr() { }
	// RVA: 0x312e7f8 VA: 0x75957467f8
	private Void set_inverseUnlockHintToastStr(String value) { }
	// RVA: 0x312d5d4 VA: 0x75957455d4
	public String get_matchConnectFailedToastStr() { }
	// RVA: 0x312e87c VA: 0x759574687c
	private Void set_matchConnectFailedToastStr(String value) { }
	// RVA: 0x312d63c VA: 0x759574563c
	public String get_actId() { }
	// RVA: 0x312e900 VA: 0x7595746900
	private Void set_actId(String value) { }
	// RVA: 0x312e984 VA: 0x7595746984
	public Boolean get_isInverseActive() { }
	// RVA: 0x312e9ec VA: 0x75957469ec
	public Boolean get_isInverseUnlock() { }
	// RVA: 0x312ea54 VA: 0x7595746a54
	public Boolean get_isMatching() { }
	// RVA: 0x312eac8 VA: 0x7595746ac8
	public List`1 get_modeGroupList() { }
	// RVA: 0x312eb30 VA: 0x7595746b30
	public List`1 get_posList() { }
	// RVA: 0x312eb98 VA: 0x7595746b98
	public Boolean get_isMatchBanned() { }
	// RVA: 0x312ec34 VA: 0x7595746c34
	public Int32 get_waitSeconds() { }
	// RVA: 0x312ed0c VA: 0x7595746d0c
	public Option CreateStartMatchOption() { }
	// RVA: 0x312f008 VA: 0x7595747008
	public Boolean CheckModeGroupSelect(ActMultiV3MapModeType modeType) { }
	// RVA: 0x312f2cc VA: 0x75957472cc
	public Boolean CheckModeSelect(String modeId) { }
	// RVA: 0x312f36c VA: 0x759574736c
	public Void ToggleModeSelect(String modeId) { }
	// RVA: 0x312f74c VA: 0x759574774c
	public Void ToggleInverse() { }
	// RVA: 0x312f7bc VA: 0x75957477bc
	public Int32 GetSelectCount() { }
	// RVA: 0x312ef2c VA: 0x7595746f2c
	public ActMultiV3MatchPosModel FindCurrMatchPosModel() { }
	// RVA: 0x312f94c VA: 0x759574794c
	public ActMultiV3MatchPosModel FindMatchPosModel(ActMultiV3MatchPosType posType) { }
	// RVA: 0x312f83c VA: 0x759574783c
	private ActMultiV3MatchPosModel _FindMatchPosModel(ActMultiV3MatchPosType posType) { }
	// RVA: 0x312f9cc VA: 0x75957479cc
	public Void LoadData(String actId) { }
	// RVA: 0x31301a8 VA: 0x75957481a8
	private Void _InitTipList(String actId, ActMultiV3Data actData) { }
	// RVA: 0x3130b0c VA: 0x7595748b0c
	public String FetchRandomTip() { }
	// RVA: 0x312fed4 VA: 0x7595747ed4
	private Void _InitMatchPosList(String actId, ActMultiV3Data actData) { }
	// RVA: 0x312fbe8 VA: 0x7595747be8
	private Void _InitModeGroupList(String actId, ActMultiV3Data actData) { }
	// RVA: 0x31310b8 VA: 0x75957490b8
	public Void UpdateBanTime() { }
	// RVA: 0x3131120 VA: 0x7595749120
	public Void MarkStartMatch() { }
	// RVA: 0x31311b0 VA: 0x75957491b0
	public Void MarkMatchTick(Single waitSec) { }
	// RVA: 0x313122c VA: 0x759574922c
	public Void MarkEndMatch(ActMultiV3MatchResult result) { }
	// RVA: 0x31312cc VA: 0x75957492cc
	public Void SetPartnerPos(ActMultiV3MatchPosType posType) { }
	// RVA: 0x313134c VA: 0x759574934c
	public Void MarkEnter() { }
	// RVA: 0x3130838 VA: 0x7595748838
	private Void _UpdateBanTime() { }
	// RVA: 0x312f524 VA: 0x7595747524
	public ActMultiV3MatchModeDiffModel FindModeDiffModel(String modeId) { }
	// RVA: 0x313146c VA: 0x759574946c
	public ActMultiV3MatchModeGroupModel FindModeGroupModel(ActMultiV3MapModeType modeType) { }
	// RVA: 0x31315fc VA: 0x75957495fc
	public ActMultiV3MatchModeDiffModel FindModeDiffModel(ActMultiV3MapModeType modeType, ActMultiV3MapDiffType diffType) { }
	// RVA: 0x31317ec VA: 0x75957497ec
	public Void ConsumeSelectModeTrack() { }
	// RVA: 0x3131974 VA: 0x7595749974
	public Void ConsumeModeTrack(String modeId) { }
	// RVA: 0x31318d8 VA: 0x75957498d8
	private Void _ConsumeModeTrack(String modeId) { }
	// RVA: 0x31314ec VA: 0x75957494ec
	private ActMultiV3MatchModeGroupModel _FindModeGroupModel(ActMultiV3MapModeType modeType) { }
	// RVA: 0x3130520 VA: 0x7595748520
	private Void _UpdateModeDiffUnlockStatus() { }
	// RVA: 0x313060c VA: 0x759574860c
	private Void _UpdateInverseUnlockStatus() { }
	// RVA: 0x313074c VA: 0x759574874c
	private Void _UpdatePosUnlockStatus() { }
	// RVA: 0x3130438 VA: 0x7595748438
	private Void _UpdateMapScore() { }
	// RVA: 0x31308c4 VA: 0x75957488c4
	private Void _InitMatchConfig(ActMultiV3Data actData) { }
	// RVA: 0x3131fec VA: 0x7595749fec
	private Void _InitMatchConfigUsingPlayerData(MatchInfo playerMatchInfo) { }
	// RVA: 0x3131e58 VA: 0x7595749e58
	private Void _InitMatchConfigUsingGameData(ActMultiV3Data actData) { }
	// RVA: 0x31324f4 VA: 0x759574a4f4
	public Void .ctor() { }
}
```