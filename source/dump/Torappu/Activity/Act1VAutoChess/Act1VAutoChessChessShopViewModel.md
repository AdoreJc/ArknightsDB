# Act1VAutoChessChessShopViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <activityId>k__BackingField`

- `Int32 <curAssistCnt>k__BackingField`

- `Int32 <maxCanAssistCnt>k__BackingField`

- `Int32 <notTopicCharCnt>k__BackingField`

- `Act1VAutoChessShopQuickEditType <curQuickEditType>k__BackingField`

- `FocusParams <focusCharListParams>k__BackingField`

- `FocusParams <focusTrapListParams>k__BackingField`

- `Int32 <curSelectingShopLevel>k__BackingField`

- `Act1VAutoChessShopStatus <shopStatus>k__BackingField`

- `Act1VAutoChessChessShopLevelCharGroupListViewModel m_charListViewModel`

- `Act1VAutoChessChessShopLevelTrapGroupListViewModel m_trapListViewModel`

- `Act1VAutoChessCharSelectDetailViewModel m_detailViewModel`

- `ActivityAutoChessVerify1Data m_cachedData`

- `Int32 m_sequenceNum`

- `String m_cachedSingleEditCharChessId`


## Properties

- `String activityId`

- `Int32 curAssistCnt`

- `Int32 maxCanAssistCnt`

- `Int32 notTopicCharCnt`

- `Act1VAutoChessShopQuickEditType curQuickEditType`

- `FocusParams focusCharListParams`

- `FocusParams focusTrapListParams`

- `Int32 curSelectingShopLevel`

- `Act1VAutoChessShopStatus shopStatus`

- `Boolean hasNotTopicChar`

- `Act1VAutoChessChessShopLevelCharGroupListViewModel charListViewModel`

- `Act1VAutoChessChessShopLevelTrapGroupListViewModel trapListViewModel`

- `Act1VAutoChessCharSelectDetailViewModel detailViewModel`

- `String cachedSingleEditCharChessId`


## Methods

- `String get_activityId()`

- `Void set_activityId(String)`

- `Int32 get_curAssistCnt()`

- `Void set_curAssistCnt(Int32)`

- `Int32 get_maxCanAssistCnt()`

- `Void set_maxCanAssistCnt(Int32)`

- `Int32 get_notTopicCharCnt()`

- `Void set_notTopicCharCnt(Int32)`

- `Act1VAutoChessShopQuickEditType get_curQuickEditType()`

- `Void set_curQuickEditType(Act1VAutoChessShopQuickEditType)`

- `FocusParams get_focusCharListParams()`

- `Void set_focusCharListParams(FocusParams)`

- `FocusParams get_focusTrapListParams()`

- `Void set_focusTrapListParams(FocusParams)`

- `Int32 get_curSelectingShopLevel()`

- `Void set_curSelectingShopLevel(Int32)`

- `Act1VAutoChessShopStatus get_shopStatus()`

- `Void set_shopStatus(Act1VAutoChessShopStatus)`

- `Boolean get_hasNotTopicChar()`

- `Act1VAutoChessChessShopLevelCharGroupListViewModel get_charListViewModel()`

- `Act1VAutoChessChessShopLevelTrapGroupListViewModel get_trapListViewModel()`

- `Act1VAutoChessCharSelectDetailViewModel get_detailViewModel()`

- `String get_cachedSingleEditCharChessId()`

- `Void LoadData(String)`

- `Void RefreshByPlayerData(Boolean, FocusParams)`

- `Void RefreshSelectShopLevel(Int32)`

- `Boolean RefreshShopStatus(Act1VAutoChessShopStatus)`

- `Void RefreshQuickEditType(Act1VAutoChessShopQuickEditType)`

- `Boolean RefreshMultiEditChessSelectSkillId(String, Int32, String, String)`

- `Boolean RefreshMultiEditChessSelectModuleId(String, Int32, String, String)`

- `Boolean RefreshCharChessSelectId(String, FocusParams)`

- `Void RefreshChessEditSkillAndModeCachedDict(String)`

- `Act1VAutoChessCharShopChessData GetChessCharShopData(String)`

- `Act1VAutoChessShopCharChessCardViewModel GetCharChessCardViewModel(String)`

- `Void RefreshFocusTrapListParams(FocusParams)`

- `Void RefreshFocusCharListParams(FocusParams)`

- `Void _InitMenuData(Act1VAutoChessShopStatus)`

- `Void _TryResetEditCharSkillAndModeCachedDict()`

- `Void _RefreshDetailViewModel(String, Boolean)`

- `Void _RefreshChessEditSkillAndModeCachedDict(String, String, Int32)`

- `Void _RefreshMenuLevelItemSelectState(Int32)`

- `Void _RefreshMenuLevelItemShopType(Act1VAutoChessShopStatus)`

- `Void _RefreshMenuLevelItemCurDiyCharCnt(Dictionary`2)`

- `Void _RefreshCachedAssistInfos(Dictionary`2)`

- `Void _RefreshCachedDiyChessInfos(Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopViewModel : IHotfixable
{
	private String <activityId>k__BackingField; // 0x10
	private Int32 <curAssistCnt>k__BackingField; // 0x18
	private Int32 <maxCanAssistCnt>k__BackingField; // 0x1c
	private Int32 <notTopicCharCnt>k__BackingField; // 0x20
	private Act1VAutoChessShopQuickEditType <curQuickEditType>k__BackingField; // 0x24
	private FocusParams <focusCharListParams>k__BackingField; // 0x28
	private FocusParams <focusTrapListParams>k__BackingField; // 0x48
	private Int32 <curSelectingShopLevel>k__BackingField; // 0x50
	private Act1VAutoChessShopStatus <shopStatus>k__BackingField; // 0x54
	private List`1 m_menuLevelItemViewModelList; // 0x58
	private Act1VAutoChessChessShopLevelCharGroupListViewModel m_charListViewModel; // 0x60
	private Act1VAutoChessChessShopLevelTrapGroupListViewModel m_trapListViewModel; // 0x68
	private Act1VAutoChessCharSelectDetailViewModel m_detailViewModel; // 0x70
	private ActivityAutoChessVerify1Data m_cachedData; // 0x78
	private Dictionary`2 m_cachedPlayerShopLv2DiyCharCntDict; // 0x80
	private List`1 m_cachedPlayerDiyCharChessIdList; // 0x88
	private Int32 m_sequenceNum; // 0x90
	private String m_cachedSingleEditCharChessId; // 0x98
	private Dictionary`2 m_cachedMultiEditCharChessInfoDict; // 0xa0
	private const Int32 DEFAULT_SELECT_SHOP_CHAR_LEVEL; // 0x0
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_set_activityId; // 0x8
	private static DelegateBridge __Hotfix0_get_curAssistCnt; // 0x10
	private static DelegateBridge __Hotfix0_set_curAssistCnt; // 0x18
	private static DelegateBridge __Hotfix0_get_maxCanAssistCnt; // 0x20
	private static DelegateBridge __Hotfix0_set_maxCanAssistCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_notTopicCharCnt; // 0x30
	private static DelegateBridge __Hotfix0_set_notTopicCharCnt; // 0x38
	private static DelegateBridge __Hotfix0_get_curQuickEditType; // 0x40
	private static DelegateBridge __Hotfix0_set_curQuickEditType; // 0x48
	private static DelegateBridge __Hotfix0_get_focusCharListParams; // 0x50
	private static DelegateBridge __Hotfix0_set_focusCharListParams; // 0x58
	private static DelegateBridge __Hotfix0_get_focusTrapListParams; // 0x60
	private static DelegateBridge __Hotfix0_set_focusTrapListParams; // 0x68
	private static DelegateBridge __Hotfix0_get_curSelectingShopLevel; // 0x70
	private static DelegateBridge __Hotfix0_set_curSelectingShopLevel; // 0x78
	private static DelegateBridge __Hotfix0_get_shopStatus; // 0x80
	private static DelegateBridge __Hotfix0_set_shopStatus; // 0x88
	private static DelegateBridge __Hotfix0_get_hasNotTopicChar; // 0x90
	private static DelegateBridge __Hotfix0_get_menuLevelItemViewModelList; // 0x98
	private static DelegateBridge __Hotfix0_get_charListViewModel; // 0xa0
	private static DelegateBridge __Hotfix0_get_trapListViewModel; // 0xa8
	private static DelegateBridge __Hotfix0_get_detailViewModel; // 0xb0
	private static DelegateBridge __Hotfix0_get_cachedSingleEditCharChessId; // 0xb8
	private static DelegateBridge __Hotfix0_get_cachedMultiEditCharChessInfoDict; // 0xc0
	private static DelegateBridge __Hotfix0_get_cachedPlayerDiyCharChessIdList; // 0xc8
	private static DelegateBridge __Hotfix0_LoadData; // 0xd0
	private static DelegateBridge __Hotfix0_RefreshByPlayerData; // 0xd8
	private static DelegateBridge __Hotfix0_RefreshSelectShopLevel; // 0xe0
	private static DelegateBridge __Hotfix0_RefreshShopStatus; // 0xe8
	private static DelegateBridge __Hotfix0_RefreshQuickEditType; // 0xf0
	private static DelegateBridge __Hotfix0_RefreshMultiEditChessSelectSkillId; // 0xf8
	private static DelegateBridge __Hotfix0_RefreshMultiEditChessSelectModuleId; // 0x100
	private static DelegateBridge __Hotfix0_RefreshCharChessSelectId; // 0x108
	private static DelegateBridge __Hotfix0_RefreshChessEditSkillAndModeCachedDict; // 0x110
	private static DelegateBridge __Hotfix0_GetChessCharShopData; // 0x118
	private static DelegateBridge __Hotfix0_GetCharChessCardViewModel; // 0x120
	private static DelegateBridge __Hotfix0_RefreshFocusTrapListParams; // 0x128
	private static DelegateBridge __Hotfix0_RefreshFocusCharListParams; // 0x130
	private static DelegateBridge __Hotfix0_GetShopLvDiyChessSlotIdList; // 0x138
	private static DelegateBridge __Hotfix0_GetCurShopLvAlreadySelectedDiyCharList; // 0x140
	private static DelegateBridge __Hotfix0_GetCurPlayerDiyChessCharInfos; // 0x148
	private static DelegateBridge __Hotfix0__InitMenuData; // 0x150
	private static DelegateBridge __Hotfix0__TryResetEditCharSkillAndModeCachedDict; // 0x158
	private static DelegateBridge __Hotfix0__RefreshDetailViewModel; // 0x160
	private static DelegateBridge __Hotfix0__RefreshChessEditSkillAndModeCachedDict; // 0x168
	private static DelegateBridge __Hotfix0__RefreshMenuLevelItemSelectState; // 0x170
	private static DelegateBridge __Hotfix0__RefreshMenuLevelItemShopType; // 0x178
	private static DelegateBridge __Hotfix0__RefreshMenuLevelItemCurDiyCharCnt; // 0x180
	private static DelegateBridge __Hotfix0__RefreshCachedAssistInfos; // 0x188
	private static DelegateBridge __Hotfix0__RefreshCachedDiyChessInfos; // 0x190
	private static DelegateBridge __Hotfix0__GetAllShopLevelCharDiySlotIds; // 0x198
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1a0

	public String activityId { get; set; }
	public Int32 curAssistCnt { get; set; }
	public Int32 maxCanAssistCnt { get; set; }
	public Int32 notTopicCharCnt { get; set; }
	public Act1VAutoChessShopQuickEditType curQuickEditType { get; set; }
	public FocusParams focusCharListParams { get; set; }
	public FocusParams focusTrapListParams { get; set; }
	public Int32 curSelectingShopLevel { get; set; }
	public Act1VAutoChessShopStatus shopStatus { get; set; }
	public Boolean hasNotTopicChar { get; }
	public List`1 menuLevelItemViewModelList { get; }
	public Act1VAutoChessChessShopLevelCharGroupListViewModel charListViewModel { get; }
	public Act1VAutoChessChessShopLevelTrapGroupListViewModel trapListViewModel { get; }
	public Act1VAutoChessCharSelectDetailViewModel detailViewModel { get; }
	public String cachedSingleEditCharChessId { get; }
	public Dictionary`2 cachedMultiEditCharChessInfoDict { get; }
	public List`1 cachedPlayerDiyCharChessIdList { get; }

	// RVA: 0x332e2ac VA: 0x75959462ac
	public String get_activityId() { }
	// RVA: 0x332e314 VA: 0x7595946314
	private Void set_activityId(String value) { }
	// RVA: 0x332e398 VA: 0x7595946398
	public Int32 get_curAssistCnt() { }
	// RVA: 0x332e400 VA: 0x7595946400
	private Void set_curAssistCnt(Int32 value) { }
	// RVA: 0x332e47c VA: 0x759594647c
	public Int32 get_maxCanAssistCnt() { }
	// RVA: 0x332e4e4 VA: 0x75959464e4
	private Void set_maxCanAssistCnt(Int32 value) { }
	// RVA: 0x332e560 VA: 0x7595946560
	public Int32 get_notTopicCharCnt() { }
	// RVA: 0x332e5c8 VA: 0x75959465c8
	private Void set_notTopicCharCnt(Int32 value) { }
	// RVA: 0x332e644 VA: 0x7595946644
	public Act1VAutoChessShopQuickEditType get_curQuickEditType() { }
	// RVA: 0x332e6ac VA: 0x75959466ac
	private Void set_curQuickEditType(Act1VAutoChessShopQuickEditType value) { }
	// RVA: 0x332e728 VA: 0x7595946728
	public FocusParams get_focusCharListParams() { }
	// RVA: 0x332e7b4 VA: 0x75959467b4
	private Void set_focusCharListParams(FocusParams value) { }
	// RVA: 0x332e858 VA: 0x7595946858
	public FocusParams get_focusTrapListParams() { }
	// RVA: 0x332e8c0 VA: 0x75959468c0
	private Void set_focusTrapListParams(FocusParams value) { }
	// RVA: 0x332e93c VA: 0x759594693c
	public Int32 get_curSelectingShopLevel() { }
	// RVA: 0x332e9a4 VA: 0x75959469a4
	private Void set_curSelectingShopLevel(Int32 value) { }
	// RVA: 0x332ea20 VA: 0x7595946a20
	public Act1VAutoChessShopStatus get_shopStatus() { }
	// RVA: 0x332ea88 VA: 0x7595946a88
	private Void set_shopStatus(Act1VAutoChessShopStatus value) { }
	// RVA: 0x332eb04 VA: 0x7595946b04
	public Boolean get_hasNotTopicChar() { }
	// RVA: 0x332eb78 VA: 0x7595946b78
	public List`1 get_menuLevelItemViewModelList() { }
	// RVA: 0x332ebe0 VA: 0x7595946be0
	public Act1VAutoChessChessShopLevelCharGroupListViewModel get_charListViewModel() { }
	// RVA: 0x332ec48 VA: 0x7595946c48
	public Act1VAutoChessChessShopLevelTrapGroupListViewModel get_trapListViewModel() { }
	// RVA: 0x332ecb0 VA: 0x7595946cb0
	public Act1VAutoChessCharSelectDetailViewModel get_detailViewModel() { }
	// RVA: 0x332ed18 VA: 0x7595946d18
	public String get_cachedSingleEditCharChessId() { }
	// RVA: 0x332ed80 VA: 0x7595946d80
	public Dictionary`2 get_cachedMultiEditCharChessInfoDict() { }
	// RVA: 0x332ede8 VA: 0x7595946de8
	public List`1 get_cachedPlayerDiyCharChessIdList() { }
	// RVA: 0x332ee50 VA: 0x7595946e50
	public Void LoadData(String actId) { }
	// RVA: 0x332f6b0 VA: 0x75959476b0
	public Void RefreshByPlayerData(Boolean needResetCharChessList, FocusParams focusCharParams) { }
	// RVA: 0x332f130 VA: 0x7595947130
	public Void RefreshSelectShopLevel(Int32 selectShopLevel) { }
	// RVA: 0x332f1bc VA: 0x75959471bc
	public Boolean RefreshShopStatus(Act1VAutoChessShopStatus status) { }
	// RVA: 0x332f61c VA: 0x759594761c
	public Void RefreshQuickEditType(Act1VAutoChessShopQuickEditType newQuickEditType) { }
	// RVA: 0x33303f4 VA: 0x75959483f4
	public Boolean RefreshMultiEditChessSelectSkillId(String actId, Int32 chessLevel, String chessId, String skillId) { }
	// RVA: 0x33304ac VA: 0x75959484ac
	public Boolean RefreshMultiEditChessSelectModuleId(String actId, Int32 chessLevel, String chessId, String moduleId) { }
	// RVA: 0x3330564 VA: 0x7595948564
	public Boolean RefreshCharChessSelectId(String chessId, FocusParams focusParams) { }
	// RVA: 0x3330674 VA: 0x7595948674
	public Void RefreshChessEditSkillAndModeCachedDict(String chessId) { }
	// RVA: 0x33309ac VA: 0x75959489ac
	public Act1VAutoChessCharShopChessData GetChessCharShopData(String chessId) { }
	// RVA: 0x3330738 VA: 0x7595948738
	public Act1VAutoChessShopCharChessCardViewModel GetCharChessCardViewModel(String chessId) { }
	// RVA: 0x332f0b0 VA: 0x75959470b0
	public Void RefreshFocusTrapListParams(FocusParams focusParams) { }
	// RVA: 0x332f844 VA: 0x7595947844
	public Void RefreshFocusCharListParams(FocusParams focusParams) { }
	// RVA: 0x3330a80 VA: 0x7595948a80
	public List`1 GetShopLvDiyChessSlotIdList(Int32 shopLv) { }
	// RVA: 0x3330b44 VA: 0x7595948b44
	public List`1 GetCurShopLvAlreadySelectedDiyCharList(Int32 shopLv) { }
	// RVA: 0x3330e94 VA: 0x7595948e94
	public Dictionary`2 GetCurPlayerDiyChessCharInfos() { }
	// RVA: 0x332f290 VA: 0x7595947290
	private Void _InitMenuData(Act1VAutoChessShopStatus status) { }
	// RVA: 0x3330254 VA: 0x7595948254
	private Void _TryResetEditCharSkillAndModeCachedDict() { }
	// RVA: 0x332fee8 VA: 0x7595947ee8
	private Void _RefreshDetailViewModel(String chessId, Boolean forceUpdate) { }
	// RVA: 0x3330828 VA: 0x7595948828
	private Void _RefreshChessEditSkillAndModeCachedDict(String chessId, String equipId, Int32 skillIndex) { }
	// RVA: 0x333014c VA: 0x759594814c
	private Void _RefreshMenuLevelItemSelectState(Int32 selectingShopLevel) { }
	// RVA: 0x3330308 VA: 0x7595948308
	private Void _RefreshMenuLevelItemShopType(Act1VAutoChessShopStatus status) { }
	// RVA: 0x3330018 VA: 0x7595948018
	private Void _RefreshMenuLevelItemCurDiyCharCnt(Dictionary`2 shopLv2DiyCharCntDict) { }
	// RVA: 0x332f8d8 VA: 0x75959478d8
	private Void _RefreshCachedAssistInfos(Dictionary`2 playerChessPool) { }
	// RVA: 0x332fae4 VA: 0x7595947ae4
	private Void _RefreshCachedDiyChessInfos(Dictionary`2 playerChessPool) { }
	// RVA: 0x333114c VA: 0x759594914c
	private List`1 _GetAllShopLevelCharDiySlotIds() { }
	// RVA: 0x3331324 VA: 0x7595949324
	public Void .ctor() { }
}
```