# VecBreakOffenseModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `String m_navLockToastStr`

- `String <actId>k__BackingField`

- `Int32 <maxLevel>k__BackingField`

- `String <currStageId>k__BackingField`

- `String <bossDescTitle>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`


## Properties

- `String actId`

- `Int32 maxLevel`

- `String currStageId`

- `String bossDescTitle`

- `Int32 enterSeqNum`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `Int32 get_maxLevel()`

- `Void set_maxLevel(Int32)`

- `String get_currStageId()`

- `Void set_currStageId(String)`

- `String get_bossDescTitle()`

- `Void set_bossDescTitle(String)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Void InitData(String, String, Boolean)`

- `Void UpdateEnterSeqNum()`

- `String _CalcSelectStageId(String, Boolean)`

- `VecBreakOffenseStageModel _FindMaxUnlockStageModel()`

- `Void UpdatePlayerData()`

- `Void _InitBuffList(String, ActVecBreakData)`

- `Void _InitStageList(String, ActVecBreakData)`

- `VecBreakOffenseStageModel FindCurrStageModel()`

- `VecBreakOffenseStageModel FindStageModelById(String)`

- `Int32 FindCurrStageIdx()`

- `Int32 _FindStageIndexById(String)`

- `VecBreakOffenseStageModel _FindStageModelById(String)`

- `Void _GetNextStageAndNavType(String, out, out)`

- `VecBreakOffenseNavType GetNavNextType()`

- `Boolean TryGetNextNotOpenRegion(out, out, out)`

- `Boolean TryNavToNext(out)`

- `VecBreakOffenseStageModel _FindPrevAvailStage()`

- `Boolean IsPrevStageAvail()`

- `Void NavToPrev()`

- `Void FillBuffRuneList(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffenseModel : IHotfixable
{
	private String m_navLockToastStr; // 0x10
	private List`1 m_buffList; // 0x18
	private List`1 m_stageList; // 0x20
	private String <actId>k__BackingField; // 0x28
	private Int32 <maxLevel>k__BackingField; // 0x30
	private String <currStageId>k__BackingField; // 0x38
	private String <bossDescTitle>k__BackingField; // 0x40
	private Int32 <enterSeqNum>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_maxLevel; // 0x10
	private static DelegateBridge __Hotfix0_set_maxLevel; // 0x18
	private static DelegateBridge __Hotfix0_get_currStageId; // 0x20
	private static DelegateBridge __Hotfix0_set_currStageId; // 0x28
	private static DelegateBridge __Hotfix0_get_bossDescTitle; // 0x30
	private static DelegateBridge __Hotfix0_set_bossDescTitle; // 0x38
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x40
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x48
	private static DelegateBridge __Hotfix0_get_stageList; // 0x50
	private static DelegateBridge __Hotfix0_get_defenseBuffList; // 0x58
	private static DelegateBridge __Hotfix0_InitData; // 0x60
	private static DelegateBridge __Hotfix0_UpdateEnterSeqNum; // 0x68
	private static DelegateBridge __Hotfix0__CalcSelectStageId; // 0x70
	private static DelegateBridge __Hotfix0__FindMaxUnlockStageModel; // 0x78
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x80
	private static DelegateBridge __Hotfix0__InitBuffList; // 0x88
	private static DelegateBridge __Hotfix0__InitStageList; // 0x90
	private static DelegateBridge __Hotfix0_FindCurrStageModel; // 0x98
	private static DelegateBridge __Hotfix0_FindStageModelById; // 0xa0
	private static DelegateBridge __Hotfix0_FindCurrStageIdx; // 0xa8
	private static DelegateBridge __Hotfix0__FindStageIndexById; // 0xb0
	private static DelegateBridge __Hotfix0__FindStageModelById; // 0xb8
	private static DelegateBridge __Hotfix0__GetNextStageAndNavType; // 0xc0
	private static DelegateBridge __Hotfix0_GetNavNextType; // 0xc8
	private static DelegateBridge __Hotfix0_TryGetNextNotOpenRegion; // 0xd0
	private static DelegateBridge __Hotfix0_TryNavToNext; // 0xd8
	private static DelegateBridge __Hotfix0__FindPrevAvailStage; // 0xe0
	private static DelegateBridge __Hotfix0_IsPrevStageAvail; // 0xe8
	private static DelegateBridge __Hotfix0_NavToPrev; // 0xf0
	private static DelegateBridge __Hotfix0_FillBuffRuneList; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	public String actId { get; set; }
	public Int32 maxLevel { get; set; }
	public String currStageId { get; set; }
	public String bossDescTitle { get; set; }
	public Int32 enterSeqNum { get; set; }
	public List`1 stageList { get; }
	public List`1 defenseBuffList { get; }

	// RVA: 0x22d10e0 VA: 0x75948e90e0
	public String get_actId() { }
	// RVA: 0x22d1148 VA: 0x75948e9148
	private Void set_actId(String value) { }
	// RVA: 0x22d11cc VA: 0x75948e91cc
	public Int32 get_maxLevel() { }
	// RVA: 0x22d1234 VA: 0x75948e9234
	private Void set_maxLevel(Int32 value) { }
	// RVA: 0x22d12b0 VA: 0x75948e92b0
	public String get_currStageId() { }
	// RVA: 0x22d1318 VA: 0x75948e9318
	private Void set_currStageId(String value) { }
	// RVA: 0x22d139c VA: 0x75948e939c
	public String get_bossDescTitle() { }
	// RVA: 0x22d1404 VA: 0x75948e9404
	private Void set_bossDescTitle(String value) { }
	// RVA: 0x22d1488 VA: 0x75948e9488
	public Int32 get_enterSeqNum() { }
	// RVA: 0x22d14f0 VA: 0x75948e94f0
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x22d156c VA: 0x75948e956c
	public List`1 get_stageList() { }
	// RVA: 0x22d15d4 VA: 0x75948e95d4
	public List`1 get_defenseBuffList() { }
	// RVA: 0x22cea4c VA: 0x75948e6a4c
	public Void InitData(String actId, String prevBattleStageId, Boolean isStageCompleteBeforeBattle) { }
	// RVA: 0x22ceb84 VA: 0x75948e6b84
	public Void UpdateEnterSeqNum() { }
	// RVA: 0x22d1c74 VA: 0x75948e9c74
	private String _CalcSelectStageId(String prevBattleStageId, Boolean isStageCompleteBeforeBattle) { }
	// RVA: 0x22d1ef0 VA: 0x75948e9ef0
	private VecBreakOffenseStageModel _FindMaxUnlockStageModel() { }
	// RVA: 0x22d2148 VA: 0x75948ea148
	public Void UpdatePlayerData() { }
	// RVA: 0x22d1994 VA: 0x75948e9994
	private Void _InitBuffList(String actId, ActVecBreakData actData) { }
	// RVA: 0x22d163c VA: 0x75948e963c
	private Void _InitStageList(String actId, ActVecBreakData actData) { }
	// RVA: 0x22d2230 VA: 0x75948ea230
	public VecBreakOffenseStageModel FindCurrStageModel() { }
	// RVA: 0x22d22a4 VA: 0x75948ea2a4
	public VecBreakOffenseStageModel FindStageModelById(String stageId) { }
	// RVA: 0x22d2324 VA: 0x75948ea324
	public Int32 FindCurrStageIdx() { }
	// RVA: 0x22d2398 VA: 0x75948ea398
	private Int32 _FindStageIndexById(String stageId) { }
	// RVA: 0x22d1dc4 VA: 0x75948e9dc4
	private VecBreakOffenseStageModel _FindStageModelById(String stageId) { }
	// RVA: 0x22d1fd4 VA: 0x75948e9fd4
	private Void _GetNextStageAndNavType(String currStageId, out VecBreakOffenseNavType navType, out VecBreakOffenseStageModel nextStageModel) { }
	// RVA: 0x22d24b0 VA: 0x75948ea4b0
	public VecBreakOffenseNavType GetNavNextType() { }
	// RVA: 0x22d2540 VA: 0x75948ea540
	public Boolean TryGetNextNotOpenRegion(out Int32 startIdx, out Int32 endIdx, out Int64 openTs) { }
	// RVA: 0x22d26c8 VA: 0x75948ea6c8
	public Boolean TryNavToNext(out String failMsg) { }
	// RVA: 0x22d27e0 VA: 0x75948ea7e0
	private VecBreakOffenseStageModel _FindPrevAvailStage() { }
	// RVA: 0x22d28b4 VA: 0x75948ea8b4
	public Boolean IsPrevStageAvail() { }
	// RVA: 0x22d2928 VA: 0x75948ea928
	public Void NavToPrev() { }
	// RVA: 0x22d29b0 VA: 0x75948ea9b0
	public Void FillBuffRuneList(List`1 runeList) { }
	// RVA: 0x22d2b64 VA: 0x75948eab64
	public Void .ctor() { }
}
```