# RL04FragmentViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `FragmentBagStatus status`

- `Int32 totalWeight`

- `Int32 limitWeight`

- `Int32 overWeight`

- `Single weightProgress`

- `Single limitWeightScale`

- `Single overWeightScale`

- `String safeDesc`

- `String limitDesc`

- `String overWeightDesc`

- `Boolean troopCarryNotBest`

- `String m_limitDescConstDesc`

- `Int32 focusSequence`

- `RoguelikeFragmentDialogListType listType`

- `String topicId`

- `RoguelikeFragmentDialogMode mode`

- `Int32 weightCharCount`

- `Boolean m_hasUsedFood`

- `Int32 m_detailFocusIndex`

- `Int32 m_summaryFocusIndex`


## Properties

- `Int32 focusIndex`


## Methods

- `Int32 get_focusIndex()`

- `Void LoadData(String, RoguelikeFragmentDialogMode, RoguelikeFragmentDialogListType)`

- `Void RefreshPlayerData()`

- `Void TryFocusItem(Int32)`

- `Int32 _TryFocusItem(Int32, List`1)`

- `Void _LoadWeightCharData(CurrentData, Fragment)`

- `Void _LoadFragmentData(Fragment)`

- `Void _GenerateFragmentGroup()`

- `Void _GenerateFragmentGroup(List`1, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentViewModel : IHotfixable
{
	public const Int32 DEFAULT_FOCUS_INDEX; // 0x0
	public FragmentBagStatus status; // 0x10
	public Int32 totalWeight; // 0x14
	public Int32 limitWeight; // 0x18
	public Int32 overWeight; // 0x1c
	public Single weightProgress; // 0x20
	public Single limitWeightScale; // 0x24
	public Single overWeightScale; // 0x28
	public String safeDesc; // 0x30
	public String limitDesc; // 0x38
	public String overWeightDesc; // 0x40
	public Boolean troopCarryNotBest; // 0x48
	private String m_limitDescConstDesc; // 0x50
	public Int32 focusSequence; // 0x58
	public List`1 weightCharList; // 0x60
	public RoguelikeFragmentDialogListType listType; // 0x68
	public String topicId; // 0x70
	public List`1 fragmentList; // 0x78
	public RoguelikeFragmentDialogMode mode; // 0x80
	public Int32 weightCharCount; // 0x84
	private ListDict`2 m_fragmentList; // 0x88
	private List`1 m_detailGroupList; // 0x90
	private List`1 m_summaryGroupList; // 0x98
	private Boolean m_hasUsedFood; // 0xa0
	private Int32 m_detailFocusIndex; // 0xa4
	private Int32 m_summaryFocusIndex; // 0xa8
	private static DelegateBridge __Hotfix0_get_focusIndex; // 0x0
	private static DelegateBridge __Hotfix0_get_fragmentGroupList; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x18
	private static DelegateBridge __Hotfix0_TryFocusItem; // 0x20
	private static DelegateBridge __Hotfix0__TryFocusItem; // 0x28
	private static DelegateBridge __Hotfix0__LoadWeightCharData; // 0x30
	private static DelegateBridge __Hotfix0__LoadFragmentData; // 0x38
	private static DelegateBridge __Hotfix0__GenerateFragmentGroup; // 0x40
	private static DelegateBridge __Hotfix1__GenerateFragmentGroup; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 focusIndex { get; }
	public List`1 fragmentGroupList { get; }

	// RVA: 0x2b26214 VA: 0x759513e214
	public Int32 get_focusIndex() { }
	// RVA: 0x2b26198 VA: 0x759513e198
	public List`1 get_fragmentGroupList() { }
	// RVA: 0x2b23ea0 VA: 0x759513bea0
	public Void LoadData(String topicId, RoguelikeFragmentDialogMode panelMode, RoguelikeFragmentDialogListType listType) { }
	// RVA: 0x2b244b8 VA: 0x759513c4b8
	public Void RefreshPlayerData() { }
	// RVA: 0x2b24780 VA: 0x759513c780
	public Void TryFocusItem(Int32 itemIndex) { }
	// RVA: 0x2b28548 VA: 0x7595140548
	private Int32 _TryFocusItem(Int32 itemIndex, List`1 groupViewModel) { }
	// RVA: 0x2b27a1c VA: 0x759513fa1c
	private Void _LoadWeightCharData(CurrentData playerData, Fragment playerFragment) { }
	// RVA: 0x2b27ddc VA: 0x759513fddc
	private Void _LoadFragmentData(Fragment playerFragment) { }
	// RVA: 0x2b2838c VA: 0x759514038c
	private Void _GenerateFragmentGroup() { }
	// RVA: 0x2b28744 VA: 0x7595140744
	private Void _GenerateFragmentGroup(List`1 groupList, Int32 itemCountPerRow) { }
	// RVA: 0x2b28b28 VA: 0x7595140b28
	public Void .ctor() { }
}
```