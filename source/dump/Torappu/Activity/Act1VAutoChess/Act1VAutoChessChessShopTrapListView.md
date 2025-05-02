# Act1VAutoChessChessShopTrapListView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessChessShopLevelTrapGroupItemView _groupItemViewPrefab`

- `UIRecycleHorizonLayoutGroup _recycleLayoutList`

- `RectTransform _viewport`

- `ScrollRect _scrollView`

- `Act1VAutoChessChessShopTrapListRecycleAdapter m_adapter`

- `Boolean m_hasInited`

- `Coroutine m_scrollToGroupCoroutine`

- `Act1VAutoChessEntryPage m_page`

- `Tween m_focusTween`

- `Int32 m_cachedEnterSequenceNum`


## Properties

- `Act1VAutoChessChessShopLevelTrapGroupItemView groupTrapChessItemPrefab`


## Methods

- `Act1VAutoChessChessShopLevelTrapGroupItemView get_groupTrapChessItemPrefab()`

- `Void Init(Act1VAutoChessEntryPage)`

- `Void Render(Act1VAutoChessChessShopLevelTrapGroupListViewModel, FocusParams)`

- `Void ResetViewSeqCache()`

- `Void _InitIfNot()`

- `Void _TryStartScrollCo(FocusParams)`

- `IEnumerator _TryScrollToPos(FocusParams)`

- `Single _GetPositionFromViewAndColumnIndex(Int32)`

- `Void _FocusToPos(Single, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopTrapListView : MonoBehaviour, IHotfixable
{
	private Act1VAutoChessChessShopLevelTrapGroupItemView _groupItemViewPrefab; // 0x18
	private UIRecycleHorizonLayoutGroup _recycleLayoutList; // 0x20
	private RectTransform _viewport; // 0x28
	private ScrollRect _scrollView; // 0x30
	private Act1VAutoChessChessShopTrapListRecycleAdapter m_adapter; // 0x38
	private Boolean m_hasInited; // 0x40
	private Coroutine m_scrollToGroupCoroutine; // 0x48
	private Act1VAutoChessEntryPage m_page; // 0x50
	private Tween m_focusTween; // 0x58
	private Int32 m_cachedEnterSequenceNum; // 0x60
	private const Single FOCUS_TWEEN_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_get_groupTrapChessItemPrefab; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_ResetViewSeqCache; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__TryStartScrollCo; // 0x28
	private static DelegateBridge __Hotfix0__TryScrollToPos; // 0x30
	private static DelegateBridge __Hotfix0__GetPositionFromViewAndColumnIndex; // 0x38
	private static DelegateBridge __Hotfix0__FocusToPos; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Act1VAutoChessChessShopLevelTrapGroupItemView groupTrapChessItemPrefab { get; }

	// RVA: 0x332529c VA: 0x759593d29c
	public Act1VAutoChessChessShopLevelTrapGroupItemView get_groupTrapChessItemPrefab() { }
	// RVA: 0x3325660 VA: 0x759593d660
	public Void Init(Act1VAutoChessEntryPage page) { }
	// RVA: 0x33256e4 VA: 0x759593d6e4
	public Void Render(Act1VAutoChessChessShopLevelTrapGroupListViewModel listViewModel, FocusParams focusParams) { }
	// RVA: 0x33259dc VA: 0x759593d9dc
	public Void ResetViewSeqCache() { }
	// RVA: 0x33257b8 VA: 0x759593d7b8
	private Void _InitIfNot() { }
	// RVA: 0x33258f0 VA: 0x759593d8f0
	private Void _TryStartScrollCo(FocusParams focusParams) { }
	// RVA: 0x3325a44 VA: 0x759593da44
	private IEnumerator _TryScrollToPos(FocusParams focusParams) { }
	// RVA: 0x3325b30 VA: 0x759593db30
	private Single _GetPositionFromViewAndColumnIndex(Int32 viewIndex) { }
	// RVA: 0x3325bbc VA: 0x759593dbbc
	private Void _FocusToPos(Single pos, Boolean fastMode) { }
	// RVA: 0x3325e18 VA: 0x759593de18
	public Void .ctor() { }
}
```