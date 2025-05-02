# Act1VAutoChessChessShopSkillAndModuleEditCharListView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessChessShopLevelCharGroupItemView _groupItemViewPrefab`

- `UIRecycleHorizonLayoutGroup _recycleLayoutList`

- `RectTransform _viewport`

- `ScrollRect _scrollView`

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

- `Void _InitIfNot()`

- `Void _TryStartScrollCo(FocusParams)`

- `IEnumerator _TryScrollToPos(FocusParams)`

- `Act1VAutoChessChessShopLevelCharGroupItemView <>xLuaBaseProxy_get_groupCharChessItemPrefab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopSkillAndModuleEditCharListView : Act1VAutoChessChessShopBaseCharListView
{
	private Act1VAutoChessChessShopLevelCharGroupItemView _groupItemViewPrefab; // 0x18
	private UIRecycleHorizonLayoutGroup _recycleLayoutList; // 0x20
	private RectTransform _viewport; // 0x28
	private ScrollRect _scrollView; // 0x30
	private Act1VAutoChessChessShopCharListRecycleAdapter m_adapter; // 0x38
	private Boolean m_hasInited; // 0x40
	private Coroutine m_scrollToGroupCoroutine; // 0x48
	private Act1VAutoChessEntryPage m_page; // 0x50
	private Tween m_focusTween; // 0x58
	private Int32 m_cachedRefreshSequenceNum; // 0x60
	private FocusCoreLogic m_focusLogic; // 0x68
	private const Single CHAR_CARD_BOUNDS_MARGIN; // 0x0
	private const Single GROUP_VIEW_HEADER_WIDTH; // 0x0
	private const Single GROUP_VIEW_ELEMENT_WIDTH; // 0x0
	private const Single GROUP_VIEW_ELEMENT_SPACING; // 0x0
	private const Single FOCUS_TWEEN_DUR; // 0x0
	private static DelegateBridge __Hotfix0_get_groupCharChessItemPrefab; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_ResetViewSeqCache; // 0x18
	private static DelegateBridge __Hotfix0_GetLeftMostFocusChessInfo; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__TryStartScrollCo; // 0x30
	private static DelegateBridge __Hotfix0__TryScrollToPos; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override Act1VAutoChessChessShopLevelCharGroupItemView groupCharChessItemPrefab { get; }

	// RVA: 0x3323614 VA: 0x759593b614
	public override Act1VAutoChessChessShopLevelCharGroupItemView get_groupCharChessItemPrefab() { }
	// RVA: 0x332367c VA: 0x759593b67c
	public Void Init(Act1VAutoChessEntryPage page) { }
	// RVA: 0x3323700 VA: 0x759593b700
	public Void Render(Act1VAutoChessChessShopLevelCharGroupListViewModel listViewModel, FocusParams focusParams) { }
	// RVA: 0x3323b04 VA: 0x759593bb04
	public Void ResetViewSeqCache() { }
	// RVA: 0x3323b6c VA: 0x759593bb6c
	public Int32 GetLeftMostFocusChessInfo(out Single columnIndex) { }
	// RVA: 0x33237f8 VA: 0x759593b7f8
	private Void _InitIfNot() { }
	// RVA: 0x3323a00 VA: 0x759593ba00
	private Void _TryStartScrollCo(FocusParams focusParams) { }
	// RVA: 0x3323bf8 VA: 0x759593bbf8
	private IEnumerator _TryScrollToPos(FocusParams focusParams) { }
	// RVA: 0x3323d08 VA: 0x759593bd08
	public Void .ctor() { }
	// RVA: 0x3323db8 VA: 0x759593bdb8
	private Act1VAutoChessChessShopLevelCharGroupItemView <>xLuaBaseProxy_get_groupCharChessItemPrefab() { }
}
```