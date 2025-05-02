# RL04AlchemyFragmentListViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `String m_topicid`

- `Int32 m_enterSequenceNum`

- `Int32 m_listRefreshSequenceNum`

- `Int32 m_maxCanSelectFragmentCount`


## Properties

- `FragmentStorageStatus status`

- `Int32 enterSequenceNum`

- `Int32 listRefreshSequenceNum`


## Methods

- `FragmentStorageStatus get_status()`

- `Int32 get_enterSequenceNum()`

- `Int32 get_listRefreshSequenceNum()`

- `Void LoadData(String, Int32, Int32)`

- `Void RefreshData()`

- `Boolean TryRefreshFragmentItemSelectState(String, Boolean)`

- `Boolean CheckIfFragmentIsSelected(String)`

- `RL04AlchemyFragmentItemViewModel TryGetFragmentItemViewModel(String)`

- `Void _GeneListViewModel(Dictionary`2, RoguelikeFragmentModuleData, RoguelikeTopicDetail)`

- `Void _TryAddItemViewToWholeItemViewModels(ListDict`2, Dictionary`2, ref)`

- `Boolean _TrySelectFragmentItem(RL04AlchemyFragmentItemViewModel)`

- `Boolean _TryUnselectFragmentItem(RL04AlchemyFragmentItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyFragmentListViewModel : IHotfixable
{
	private String m_topicid; // 0x10
	private Int32 m_enterSequenceNum; // 0x18
	private Int32 m_listRefreshSequenceNum; // 0x1c
	private Int32 m_maxCanSelectFragmentCount; // 0x20
	private List`1 m_selectedFragmentInstIdList; // 0x28
	private List`1 m_wholeItemViewModels; // 0x30
	private ListDict`2 m_normalItemViewModels; // 0x38
	private const Int32 ONE_ROW_ITEM_MAX_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_get_status; // 0x0
	private static DelegateBridge __Hotfix0_get_enterSequenceNum; // 0x8
	private static DelegateBridge __Hotfix0_get_listRefreshSequenceNum; // 0x10
	private static DelegateBridge __Hotfix0_get_selectedFragmentInstIdList; // 0x18
	private static DelegateBridge __Hotfix0_get_wholeItemViewModels; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_RefreshData; // 0x30
	private static DelegateBridge __Hotfix0_TryRefreshFragmentItemSelectState; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfFragmentIsSelected; // 0x40
	private static DelegateBridge __Hotfix0_TryGetFragmentItemViewModel; // 0x48
	private static DelegateBridge __Hotfix0__GeneListViewModel; // 0x50
	private static DelegateBridge __Hotfix0__TryAddItemViewToWholeItemViewModels; // 0x58
	private static DelegateBridge __Hotfix0__TrySelectFragmentItem; // 0x60
	private static DelegateBridge __Hotfix0__TryUnselectFragmentItem; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public FragmentStorageStatus status { get; }
	public Int32 enterSequenceNum { get; }
	public Int32 listRefreshSequenceNum { get; }
	public List`1 selectedFragmentInstIdList { get; }
	public List`1 wholeItemViewModels { get; }

	// RVA: 0x2b010f4 VA: 0x75951190f4
	public FragmentStorageStatus get_status() { }
	// RVA: 0x2b011ec VA: 0x75951191ec
	public Int32 get_enterSequenceNum() { }
	// RVA: 0x2b01254 VA: 0x7595119254
	public Int32 get_listRefreshSequenceNum() { }
	// RVA: 0x2b012bc VA: 0x75951192bc
	public List`1 get_selectedFragmentInstIdList() { }
	// RVA: 0x2b01184 VA: 0x7595119184
	public List`1 get_wholeItemViewModels() { }
	// RVA: 0x2b01324 VA: 0x7595119324
	public Void LoadData(String topicId, Int32 iSequenceNum, Int32 maxCanSelectFragmentCount) { }
	// RVA: 0x2b013d4 VA: 0x75951193d4
	public Void RefreshData() { }
	// RVA: 0x2b01af0 VA: 0x7595119af0
	public Boolean TryRefreshFragmentItemSelectState(String fragmentInstId, Boolean select) { }
	// RVA: 0x2b01edc VA: 0x7595119edc
	public Boolean CheckIfFragmentIsSelected(String fragmentInstId) { }
	// RVA: 0x2b01bac VA: 0x7595119bac
	public RL04AlchemyFragmentItemViewModel TryGetFragmentItemViewModel(String fragmentInstId) { }
	// RVA: 0x2b01550 VA: 0x7595119550
	private Void _GeneListViewModel(Dictionary`2 fragmentMap, RoguelikeFragmentModuleData fragmentData, RoguelikeTopicDetail detailData) { }
	// RVA: 0x2b01fc4 VA: 0x7595119fc4
	private Void _TryAddItemViewToWholeItemViewModels(ListDict`2 itemNormalViewModels, Dictionary`2 fragmentTypeData, ref List`1 iWholeItemViewModels) { }
	// RVA: 0x2b01ca4 VA: 0x7595119ca4
	private Boolean _TrySelectFragmentItem(RL04AlchemyFragmentItemViewModel fragmentItemViewModel) { }
	// RVA: 0x2b01e00 VA: 0x7595119e00
	private Boolean _TryUnselectFragmentItem(RL04AlchemyFragmentItemViewModel fragmentItemViewModel) { }
	// RVA: 0x2b02598 VA: 0x759511a598
	public Void .ctor() { }
}
```