# RL04AlchemyImplViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `String <topicId>k__BackingField`

- `Int32 <maxAlchemyField>k__BackingField`

- `Int32 <maxAlchemyCount>k__BackingField`

- `Int32 <maxAlchemyPoolRarity>k__BackingField`

- `Boolean <isInDisaster>k__BackingField`

- `LeaveBtnStatus <leaveBtnStatus>k__BackingField`

- `Boolean <isLeaving>k__BackingField`

- `ViewAlchemyStatus <viewStatus>k__BackingField`

- `RL04AlchemyForecastRandomViewModel <emptyRandomViewModel>k__BackingField`

- `RL04AlchemyResultViewModel <resultViewModel>k__BackingField`

- `RL04AlchemySlotListViewModel m_slotListViewModel`

- `RL04AlchemyForecastViewModel m_forecastViewModel`

- `RL04AlchemyFragmentListViewModel m_fragmentStorageViewModel`

- `Int32 m_sequenceNum`


## Properties

- `String topicId`

- `Int32 maxAlchemyField`

- `Int32 maxAlchemyCount`

- `Int32 maxAlchemyPoolRarity`

- `Boolean isInDisaster`

- `LeaveBtnStatus leaveBtnStatus`

- `Boolean isLeaving`

- `ViewAlchemyStatus viewStatus`

- `RL04AlchemyForecastRandomViewModel emptyRandomViewModel`

- `RL04AlchemyResultViewModel resultViewModel`

- `RL04AlchemySlotListViewModel slotListViewModel`

- `RL04AlchemyForecastViewModel forecastViewModel`

- `RL04AlchemyFragmentListViewModel fragmentStorageViewModel`

- `ForecastStatus forecastStatus`

- `ForecastType forecastType`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Int32 get_maxAlchemyField()`

- `Void set_maxAlchemyField(Int32)`

- `Int32 get_maxAlchemyCount()`

- `Void set_maxAlchemyCount(Int32)`

- `Int32 get_maxAlchemyPoolRarity()`

- `Void set_maxAlchemyPoolRarity(Int32)`

- `Boolean get_isInDisaster()`

- `Void set_isInDisaster(Boolean)`

- `LeaveBtnStatus get_leaveBtnStatus()`

- `Void set_leaveBtnStatus(LeaveBtnStatus)`

- `Boolean get_isLeaving()`

- `Void set_isLeaving(Boolean)`

- `ViewAlchemyStatus get_viewStatus()`

- `Void set_viewStatus(ViewAlchemyStatus)`

- `RL04AlchemyForecastRandomViewModel get_emptyRandomViewModel()`

- `Void set_emptyRandomViewModel(RL04AlchemyForecastRandomViewModel)`

- `RL04AlchemyResultViewModel get_resultViewModel()`

- `Void set_resultViewModel(RL04AlchemyResultViewModel)`

- `RL04AlchemySlotListViewModel get_slotListViewModel()`

- `RL04AlchemyForecastViewModel get_forecastViewModel()`

- `RL04AlchemyFragmentListViewModel get_fragmentStorageViewModel()`

- `ForecastStatus get_forecastStatus()`

- `ForecastType get_forecastType()`

- `Void LoadData(String)`

- `Boolean RefreshFragmentItemSelectStatus(String)`

- `Boolean TryUnloadSlotFragmentItem(Int32)`

- `Void RefreshLeaveBtnStatus(Boolean)`

- `Void RefreshIsLeavingStatus(Boolean)`

- `Void RefreshViewStatus(ViewAlchemyStatus)`

- `Void RefreshDataAfterClaimAlchemyReward()`

- `Void RefreshPlayerContent()`

- `Boolean CheckIfCanStartAlchemy()`

- `Void _LoadInAlchemyPending(String)`

- `Void _LoadInAlchemyRewardPending(String)`

- `Void _LoadInternal(String)`

- `Boolean _CheckIfCanOperate()`

- `Int32 _GetMaxPoolRarity()`

- `Void _RefreshPlayerAlchemyContent()`

- `Void _RefreshPlayerAlchemyRewardContent()`

- `Boolean _SelectFragmentItem(String)`

- `Boolean _UnSelectFragmentItem(String)`

- `Void _InitSlotListData()`

- `Void _ResetSlotListData()`

- `Void _RefreshSlotItemData(Int32, String)`

- `RL04AlchemySlotItemViewModel _TryGetSlotItemByFragmentInstId(String)`

- `String _ResetSlotItem(Int32)`

- `RL04AlchemyFragmentItemViewModel _TryGetFragmentItemViewModelByInstId(String)`

- `RL04AlchemySlotItemViewModel _GetFirstSlotItemCanBePut()`

- `Boolean _CheckIfSlotListFull()`

- `Void _RefreshSlotListStatus()`

- `Void _InitFragmentStorageData()`

- `Void _RefreshFragmentItemSelectState(String, Boolean)`

- `Boolean _CheckIfFragmentIsSelected(String)`

- `Void _RefreshFragmentStorageData()`

- `Void _RefreshForecastData()`

- `Void _RefreshForecastStatus()`

- `Void _RefreshForecastType()`

- `RoguelikeAlchemyFormulationData _TryGetAlchemyFormulationData(List`1)`

- `RoguelikeAlchemyData _TryGetAlchemyRecipeData(List`1)`

- `Boolean _TryGetOverrideAlchemyData(RoguelikeAlchemyData, out)`

- `AlchemyContent _GetGameAlchemyContent()`

- `AlchemyRewardContent _GetGameAlchemyRewardContent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyImplViewModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private Int32 <maxAlchemyField>k__BackingField; // 0x18
	private Int32 <maxAlchemyCount>k__BackingField; // 0x1c
	private Int32 <maxAlchemyPoolRarity>k__BackingField; // 0x20
	private Boolean <isInDisaster>k__BackingField; // 0x24
	private LeaveBtnStatus <leaveBtnStatus>k__BackingField; // 0x28
	private Boolean <isLeaving>k__BackingField; // 0x2c
	private ViewAlchemyStatus <viewStatus>k__BackingField; // 0x30
	private RL04AlchemyForecastRandomViewModel <emptyRandomViewModel>k__BackingField; // 0x38
	private RL04AlchemyResultViewModel <resultViewModel>k__BackingField; // 0x40
	private RL04AlchemySlotListViewModel m_slotListViewModel; // 0x48
	private RL04AlchemyForecastViewModel m_forecastViewModel; // 0x50
	private RL04AlchemyFragmentListViewModel m_fragmentStorageViewModel; // 0x58
	private Dictionary`2 m_alchemyFormulaDataDict; // 0x60
	private ListDict`2 m_alchemyDataDict; // 0x68
	private Int32 m_sequenceNum; // 0x70
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_maxAlchemyField; // 0x10
	private static DelegateBridge __Hotfix0_set_maxAlchemyField; // 0x18
	private static DelegateBridge __Hotfix0_get_maxAlchemyCount; // 0x20
	private static DelegateBridge __Hotfix0_set_maxAlchemyCount; // 0x28
	private static DelegateBridge __Hotfix0_get_maxAlchemyPoolRarity; // 0x30
	private static DelegateBridge __Hotfix0_set_maxAlchemyPoolRarity; // 0x38
	private static DelegateBridge __Hotfix0_get_isInDisaster; // 0x40
	private static DelegateBridge __Hotfix0_set_isInDisaster; // 0x48
	private static DelegateBridge __Hotfix0_get_leaveBtnStatus; // 0x50
	private static DelegateBridge __Hotfix0_set_leaveBtnStatus; // 0x58
	private static DelegateBridge __Hotfix0_get_isLeaving; // 0x60
	private static DelegateBridge __Hotfix0_set_isLeaving; // 0x68
	private static DelegateBridge __Hotfix0_get_viewStatus; // 0x70
	private static DelegateBridge __Hotfix0_set_viewStatus; // 0x78
	private static DelegateBridge __Hotfix0_get_emptyRandomViewModel; // 0x80
	private static DelegateBridge __Hotfix0_set_emptyRandomViewModel; // 0x88
	private static DelegateBridge __Hotfix0_get_resultViewModel; // 0x90
	private static DelegateBridge __Hotfix0_set_resultViewModel; // 0x98
	private static DelegateBridge __Hotfix0_get_slotListViewModel; // 0xa0
	private static DelegateBridge __Hotfix0_get_forecastViewModel; // 0xa8
	private static DelegateBridge __Hotfix0_get_fragmentStorageViewModel; // 0xb0
	private static DelegateBridge __Hotfix0_get_forecastStatus; // 0xb8
	private static DelegateBridge __Hotfix0_get_forecastType; // 0xc0
	private static DelegateBridge __Hotfix0_LoadData; // 0xc8
	private static DelegateBridge __Hotfix0_RefreshFragmentItemSelectStatus; // 0xd0
	private static DelegateBridge __Hotfix0_TryUnloadSlotFragmentItem; // 0xd8
	private static DelegateBridge __Hotfix0_RefreshLeaveBtnStatus; // 0xe0
	private static DelegateBridge __Hotfix0_RefreshIsLeavingStatus; // 0xe8
	private static DelegateBridge __Hotfix0_RefreshViewStatus; // 0xf0
	private static DelegateBridge __Hotfix0_RefreshDataAfterClaimAlchemyReward; // 0xf8
	private static DelegateBridge __Hotfix0_RefreshPlayerContent; // 0x100
	private static DelegateBridge __Hotfix0_CheckIfCanStartAlchemy; // 0x108
	private static DelegateBridge __Hotfix0_GetSelectedFragmentInstIdList; // 0x110
	private static DelegateBridge __Hotfix0__LoadInAlchemyPending; // 0x118
	private static DelegateBridge __Hotfix0__LoadInAlchemyRewardPending; // 0x120
	private static DelegateBridge __Hotfix0__LoadInternal; // 0x128
	private static DelegateBridge __Hotfix0__CheckIfCanOperate; // 0x130
	private static DelegateBridge __Hotfix0__GetMaxPoolRarity; // 0x138
	private static DelegateBridge __Hotfix0__RefreshPlayerAlchemyContent; // 0x140
	private static DelegateBridge __Hotfix0__RefreshPlayerAlchemyRewardContent; // 0x148
	private static DelegateBridge __Hotfix0__SelectFragmentItem; // 0x150
	private static DelegateBridge __Hotfix0__UnSelectFragmentItem; // 0x158
	private static DelegateBridge __Hotfix0__InitSlotListData; // 0x160
	private static DelegateBridge __Hotfix0__ResetSlotListData; // 0x168
	private static DelegateBridge __Hotfix0__RefreshSlotItemData; // 0x170
	private static DelegateBridge __Hotfix0__TryGetSlotItemByFragmentInstId; // 0x178
	private static DelegateBridge __Hotfix0__ResetSlotItem; // 0x180
	private static DelegateBridge __Hotfix0__TryGetFragmentItemViewModelByInstId; // 0x188
	private static DelegateBridge __Hotfix0__GetFirstSlotItemCanBePut; // 0x190
	private static DelegateBridge __Hotfix0__CheckIfSlotListFull; // 0x198
	private static DelegateBridge __Hotfix0__RefreshSlotListStatus; // 0x1a0
	private static DelegateBridge __Hotfix0__GetSlotFragmentIdList; // 0x1a8
	private static DelegateBridge __Hotfix0__InitFragmentStorageData; // 0x1b0
	private static DelegateBridge __Hotfix0__RefreshFragmentItemSelectState; // 0x1b8
	private static DelegateBridge __Hotfix0__CheckIfFragmentIsSelected; // 0x1c0
	private static DelegateBridge __Hotfix0__RefreshFragmentStorageData; // 0x1c8
	private static DelegateBridge __Hotfix0__RefreshForecastData; // 0x1d0
	private static DelegateBridge __Hotfix0__RefreshForecastStatus; // 0x1d8
	private static DelegateBridge __Hotfix0__RefreshForecastType; // 0x1e0
	private static DelegateBridge __Hotfix0__TryGetAlchemyFormulationData; // 0x1e8
	private static DelegateBridge __Hotfix0__TryGetAlchemyRecipeData; // 0x1f0
	private static DelegateBridge __Hotfix0__TryGetOverrideAlchemyData; // 0x1f8
	private static DelegateBridge __Hotfix0__GetGameAlchemyContent; // 0x200
	private static DelegateBridge __Hotfix0__GetGameAlchemyRewardContent; // 0x208
	private static DelegateBridge _c__Hotfix0_ctor; // 0x210

	public String topicId { get; set; }
	public Int32 maxAlchemyField { get; set; }
	public Int32 maxAlchemyCount { get; set; }
	public Int32 maxAlchemyPoolRarity { get; set; }
	public Boolean isInDisaster { get; set; }
	public LeaveBtnStatus leaveBtnStatus { get; set; }
	public Boolean isLeaving { get; set; }
	public ViewAlchemyStatus viewStatus { get; set; }
	public RL04AlchemyForecastRandomViewModel emptyRandomViewModel { get; set; }
	public RL04AlchemyResultViewModel resultViewModel { get; set; }
	public RL04AlchemySlotListViewModel slotListViewModel { get; }
	public RL04AlchemyForecastViewModel forecastViewModel { get; }
	public RL04AlchemyFragmentListViewModel fragmentStorageViewModel { get; }
	public ForecastStatus forecastStatus { get; }
	public ForecastType forecastType { get; }

	// RVA: 0x2afcbb8 VA: 0x7595114bb8
	public String get_topicId() { }
	// RVA: 0x2b03354 VA: 0x759511b354
	private Void set_topicId(String value) { }
	// RVA: 0x2b033d8 VA: 0x759511b3d8
	public Int32 get_maxAlchemyField() { }
	// RVA: 0x2b03440 VA: 0x759511b440
	private Void set_maxAlchemyField(Int32 value) { }
	// RVA: 0x2b034bc VA: 0x759511b4bc
	public Int32 get_maxAlchemyCount() { }
	// RVA: 0x2b03524 VA: 0x759511b524
	private Void set_maxAlchemyCount(Int32 value) { }
	// RVA: 0x2b035a0 VA: 0x759511b5a0
	public Int32 get_maxAlchemyPoolRarity() { }
	// RVA: 0x2b03608 VA: 0x759511b608
	private Void set_maxAlchemyPoolRarity(Int32 value) { }
	// RVA: 0x2afcc20 VA: 0x7595114c20
	public Boolean get_isInDisaster() { }
	// RVA: 0x2b03684 VA: 0x759511b684
	private Void set_isInDisaster(Boolean value) { }
	// RVA: 0x2afd7d0 VA: 0x75951157d0
	public LeaveBtnStatus get_leaveBtnStatus() { }
	// RVA: 0x2b03704 VA: 0x759511b704
	private Void set_leaveBtnStatus(LeaveBtnStatus value) { }
	// RVA: 0x2afcf88 VA: 0x7595114f88
	public Boolean get_isLeaving() { }
	// RVA: 0x2b03780 VA: 0x759511b780
	private Void set_isLeaving(Boolean value) { }
	// RVA: 0x2afd620 VA: 0x7595115620
	public ViewAlchemyStatus get_viewStatus() { }
	// RVA: 0x2b03800 VA: 0x759511b800
	private Void set_viewStatus(ViewAlchemyStatus value) { }
	// RVA: 0x2b0387c VA: 0x759511b87c
	public RL04AlchemyForecastRandomViewModel get_emptyRandomViewModel() { }
	// RVA: 0x2b038e4 VA: 0x759511b8e4
	private Void set_emptyRandomViewModel(RL04AlchemyForecastRandomViewModel value) { }
	// RVA: 0x2b03968 VA: 0x759511b968
	public RL04AlchemyResultViewModel get_resultViewModel() { }
	// RVA: 0x2b039d0 VA: 0x759511b9d0
	private Void set_resultViewModel(RL04AlchemyResultViewModel value) { }
	// RVA: 0x2b03a54 VA: 0x759511ba54
	public RL04AlchemySlotListViewModel get_slotListViewModel() { }
	// RVA: 0x2b03abc VA: 0x759511babc
	public RL04AlchemyForecastViewModel get_forecastViewModel() { }
	// RVA: 0x2b03b24 VA: 0x759511bb24
	public RL04AlchemyFragmentListViewModel get_fragmentStorageViewModel() { }
	// RVA: 0x2b03b8c VA: 0x759511bb8c
	public ForecastStatus get_forecastStatus() { }
	// RVA: 0x2b03c04 VA: 0x759511bc04
	public ForecastType get_forecastType() { }
	// RVA: 0x2b03c7c VA: 0x759511bc7c
	public Void LoadData(String iTopicId) { }
	// RVA: 0x2afd8dc VA: 0x75951158dc
	public Boolean RefreshFragmentItemSelectStatus(String fragmentInstId) { }
	// RVA: 0x2afd9a4 VA: 0x75951159a4
	public Boolean TryUnloadSlotFragmentItem(Int32 slotIndex) { }
	// RVA: 0x2afd838 VA: 0x7595115838
	public Void RefreshLeaveBtnStatus(Boolean isSelect) { }
	// RVA: 0x2afcff0 VA: 0x7595114ff0
	public Void RefreshIsLeavingStatus(Boolean iIsLeaving) { }
	// RVA: 0x2afc664 VA: 0x7595114664
	public Void RefreshViewStatus(ViewAlchemyStatus viewAlchemyStatus) { }
	// RVA: 0x2afd74c VA: 0x759511574c
	public Void RefreshDataAfterClaimAlchemyReward() { }
	// RVA: 0x2afcb48 VA: 0x7595114b48
	public Void RefreshPlayerContent() { }
	// RVA: 0x2afc5c0 VA: 0x75951145c0
	public Boolean CheckIfCanStartAlchemy() { }
	// RVA: 0x2afc6e4 VA: 0x75951146e4
	public List`1 GetSelectedFragmentInstIdList() { }
	// RVA: 0x2b03d4c VA: 0x759511bd4c
	private Void _LoadInAlchemyPending(String iTopicId) { }
	// RVA: 0x2b03de0 VA: 0x759511bde0
	private Void _LoadInAlchemyRewardPending(String iTopicId) { }
	// RVA: 0x2b048ac VA: 0x759511c8ac
	private Void _LoadInternal(String iTopicId) { }
	// RVA: 0x2b03e7c VA: 0x759511be7c
	private Boolean _CheckIfCanOperate() { }
	// RVA: 0x2b04a44 VA: 0x759511ca44
	private Int32 _GetMaxPoolRarity() { }
	// RVA: 0x2b046f0 VA: 0x759511c6f0
	private Void _RefreshPlayerAlchemyContent() { }
	// RVA: 0x2b04788 VA: 0x759511c788
	private Void _RefreshPlayerAlchemyRewardContent() { }
	// RVA: 0x2b04030 VA: 0x759511c030
	private Boolean _SelectFragmentItem(String fragmentInstId) { }
	// RVA: 0x2b03f8c VA: 0x759511bf8c
	private Boolean _UnSelectFragmentItem(String fragmentInstId) { }
	// RVA: 0x2b04bb4 VA: 0x759511cbb4
	private Void _InitSlotListData() { }
	// RVA: 0x2b04494 VA: 0x759511c494
	private Void _ResetSlotListData() { }
	// RVA: 0x2b050ac VA: 0x759511d0ac
	private Void _RefreshSlotItemData(Int32 slotIndex, String fragmentInstId) { }
	// RVA: 0x2b051cc VA: 0x759511d1cc
	private RL04AlchemySlotItemViewModel _TryGetSlotItemByFragmentInstId(String fragmentInstId) { }
	// RVA: 0x2b040f8 VA: 0x759511c0f8
	private String _ResetSlotItem(Int32 slotIndex) { }
	// RVA: 0x2b052d8 VA: 0x759511d2d8
	private RL04AlchemyFragmentItemViewModel _TryGetFragmentItemViewModelByInstId(String instId) { }
	// RVA: 0x2b04f98 VA: 0x759511cf98
	private RL04AlchemySlotItemViewModel _GetFirstSlotItemCanBePut() { }
	// RVA: 0x2b05394 VA: 0x759511d394
	private Boolean _CheckIfSlotListFull() { }
	// RVA: 0x2b04220 VA: 0x759511c220
	private Void _RefreshSlotListStatus() { }
	// RVA: 0x2b05410 VA: 0x759511d410
	private List`1 _GetSlotFragmentIdList() { }
	// RVA: 0x2b04c3c VA: 0x759511cc3c
	private Void _InitFragmentStorageData() { }
	// RVA: 0x2b04390 VA: 0x759511c390
	private Void _RefreshFragmentItemSelectState(String instId, Boolean select) { }
	// RVA: 0x2b03f04 VA: 0x759511bf04
	private Boolean _CheckIfFragmentIsSelected(String fragmentInstId) { }
	// RVA: 0x2b04680 VA: 0x759511c680
	private Void _RefreshFragmentStorageData() { }
	// RVA: 0x2b04424 VA: 0x759511c424
	private Void _RefreshForecastData() { }
	// RVA: 0x2b055d8 VA: 0x759511d5d8
	private Void _RefreshForecastStatus() { }
	// RVA: 0x2b05658 VA: 0x759511d658
	private Void _RefreshForecastType() { }
	// RVA: 0x2b05858 VA: 0x759511d858
	private RoguelikeAlchemyFormulationData _TryGetAlchemyFormulationData(List`1 fragmentIds) { }
	// RVA: 0x2b05d80 VA: 0x759511dd80
	private RoguelikeAlchemyData _TryGetAlchemyRecipeData(List`1 fragments) { }
	// RVA: 0x2b063b0 VA: 0x759511e3b0
	private Boolean _TryGetOverrideAlchemyData(RoguelikeAlchemyData alchemyData, out RoguelikeAlchemyData overrideData) { }
	// RVA: 0x2b04ce0 VA: 0x759511cce0
	private AlchemyContent _GetGameAlchemyContent() { }
	// RVA: 0x2b04e3c VA: 0x759511ce3c
	private AlchemyRewardContent _GetGameAlchemyRewardContent() { }
	// RVA: 0x2b066dc VA: 0x759511e6dc
	public Void .ctor() { }
}
```