# Act1VAutoChessChessShopCharListView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessChessShopLevelCharGroupItemView _groupItemViewPrefab`

- `UIRecycleHorizonLayoutGroup _recycleLayoutList`

- `RectTransform _viewport`

- `ScrollRect _scrollView`

- `UILayoutDimensionListener _dimensionListener`

- `Act1VAutoChessChessShopCharListRecycleAdapter m_adapter`

- `Boolean m_hasInited`

- `Coroutine m_scrollToGroupCoroutine`

- `Act1VAutoChessEntryPage m_page`

- `Tween m_focusTween`

- `Int32 m_cachedRefreshSequenceNum`

- `FocusCoreLogic m_focusLogic`


## Methods

- `Void Init(Act1VAutoChessEntryPage)`

- `Void Render(Act1VAutoChessChessShopLevelCharGroupListViewModel, FocusParams)`

- `Void ResetViewSeqCache()`

- `Int32 GetLeftMostFocusChessInfo(out)`

- `IEnumerator WaitForLayoutReady()`

- `Void TutorialOnly_RegisterTutorialGo()`

- `Void TutorialOnly_RegisterTutorialGoLevelFiveDiyCharItem()`

- `Void _InitIfNot()`

- `Void _TryStartScrollCo(FocusParams)`

- `IEnumerator _TryScrollToPos(FocusParams)`

- `Act1VAutoChessChessShopLevelCharGroupItemView <>xLuaBaseProxy_get_groupCharChessItemPrefab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopCharListView : Act1VAutoChessChessShopBaseCharListView
{
	private Act1VAutoChessChessShopLevelCharGroupItemView _groupItemViewPrefab; // 0x18
	private UIRecycleHorizonLayoutGroup _recycleLayoutList; // 0x20
	private RectTransform _viewport; // 0x28
	private ScrollRect _scrollView; // 0x30
	private UILayoutDimensionListener _dimensionListener; // 0x38
	private Act1VAutoChessChessShopCharListRecycleAdapter m_adapter; // 0x40
	private Boolean m_hasInited; // 0x48
	private Coroutine m_scrollToGroupCoroutine; // 0x50
	private Act1VAutoChessEntryPage m_page; // 0x58
	private Tween m_focusTween; // 0x60
	private Int32 m_cachedRefreshSequenceNum; // 0x68
	private FocusCoreLogic m_focusLogic; // 0x70
	private const Single CHAR_CARD_BOUNDS_MARGIN; // 0x0
	private const Single GROUP_VIEW_HEADER_WIDTH; // 0x0
	private const Single GROUP_VIEW_ELEMENT_WIDTH; // 0x0
	private const Single GROUP_VIEW_ELEMENT_SPACING; // 0x0
	private const Single FOCUS_TWEEN_DUR; // 0x0
	private const Int32 TUTORIAL_FIRST_GROUP_LEVEL; // 0x0
	private const Int32 TUTORIAL_FIRST_CHAR_CARD_POS; // 0x0
	private static DelegateBridge __Hotfix0_get_groupCharChessItemPrefab; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_ResetViewSeqCache; // 0x18
	private static DelegateBridge __Hotfix0_GetLeftMostFocusChessInfo; // 0x20
	private static DelegateBridge __Hotfix0_WaitForLayoutReady; // 0x28
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterTutorialGo; // 0x30
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterTutorialGoLevelFiveDiyCharItem; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__TryStartScrollCo; // 0x48
	private static DelegateBridge __Hotfix0__TryScrollToPos; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override Act1VAutoChessChessShopLevelCharGroupItemView groupCharChessItemPrefab { get; }

	// RVA: 0x3319c98 VA: 0x7595931c98
	public override Act1VAutoChessChessShopLevelCharGroupItemView get_groupCharChessItemPrefab() { }
	// RVA: 0x3314098 VA: 0x759592c098
	public Void Init(Act1VAutoChessEntryPage page) { }
	// RVA: 0x3314678 VA: 0x759592c678
	public Void Render(Act1VAutoChessChessShopLevelCharGroupListViewModel listViewModel, FocusParams focusParams) { }
	// RVA: 0x331411c VA: 0x759592c11c
	public Void ResetViewSeqCache() { }
	// RVA: 0x3312510 VA: 0x759592a510
	public Int32 GetLeftMostFocusChessInfo(out Single columnIndex) { }
	// RVA: 0x3315230 VA: 0x759592d230
	public IEnumerator WaitForLayoutReady() { }
	// RVA: 0x33152dc VA: 0x759592d2dc
	public Void TutorialOnly_RegisterTutorialGo() { }
	// RVA: 0x3314dc4 VA: 0x759592cdc4
	public Void TutorialOnly_RegisterTutorialGoLevelFiveDiyCharItem() { }
	// RVA: 0x3319d00 VA: 0x7595931d00
	private Void _InitIfNot() { }
	// RVA: 0x3319e9c VA: 0x7595931e9c
	private Void _TryStartScrollCo(FocusParams focusParams) { }
	// RVA: 0x3319fc8 VA: 0x7595931fc8
	private IEnumerator _TryScrollToPos(FocusParams focusParams) { }
	// RVA: 0x331a0d4 VA: 0x75959320d4
	public Void .ctor() { }
	// RVA: 0x331a180 VA: 0x7595932180
	private Act1VAutoChessChessShopLevelCharGroupItemView <>xLuaBaseProxy_get_groupCharChessItemPrefab() { }
}
```