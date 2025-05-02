# InertiaScrollViewPager

**Namespace:** `Torappu.UI`


## Fields

- `UIWrappedScrollRect _scrollRect`

- `Single _animationDuration`

- `Single _endScrollSpd`

- `Boolean m_enableDrag`

- `Int32 m_currentPage`

- `State m_state`

- `IScrollHandler m_scrollHandler`

- `ScrollEffectTrigger m_effectTrigger`

- `BlockerManager m_blockers`

- `DragContext m_dragContext`

- `ScrollOptions m_scrollOptions`

- `Int32 m_fromPage`

- `Int32 m_toPage`

- `Single m_tweenStartTime`

- `Single m_tweenStartValue`

- `Single m_tweenTargetValue`

- `Boolean m_isInited`

- `Int32 <pageCount>k__BackingField`


## Properties

- `Boolean _enableDrag`

- `Boolean isUpdating`

- `Int32 pageCount`

- `Int32 currentPage`

- `Single currentScrollIndex`


## Methods

- `Boolean get__enableDrag()`

- `Void _InitIfNot()`

- `Boolean get_isUpdating()`

- `Int32 get_pageCount()`

- `Void set_pageCount(Int32)`

- `Void SetPageCount(Int32, IList`1)`

- `Int32 get_currentPage()`

- `Void set_currentPage(Int32)`

- `Single get_currentScrollIndex()`

- `Void SetScrollOptions(ScrollOptions)`

- `Void SetScrollEffect(ScrollEffectConfig)`

- `Void UpdateTime(Single)`

- `Void MoveToPage(Int32)`

- `Void Awake()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Single _ScrollValue2PageIndex(Single)`

- `Single _PageIndex2ScrollValue(Single)`

- `Int32 _ScrollValueAlignToPage(Single)`

- `Void _SwitchToPage(Int32, Boolean)`

- `Void _AutoAlign()`

- `Void _OnStateChanged(State, State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class InertiaScrollViewPager : MonoBehaviour, ITimeWatcher, IHotfixable
{
	private UIWrappedScrollRect _scrollRect; // 0x18
	private Single _animationDuration; // 0x20
	private Single _endScrollSpd; // 0x24
	private Boolean m_enableDrag; // 0x28
	private Int32 m_currentPage; // 0x2c
	private State m_state; // 0x30
	private IScrollHandler m_scrollHandler; // 0x38
	private ScrollEffectTrigger m_effectTrigger; // 0x40
	private BlockerManager m_blockers; // 0x48
	private DragContext m_dragContext; // 0x50
	private ScrollOptions m_scrollOptions; // 0x58
	private Int32 m_fromPage; // 0x70
	private Int32 m_toPage; // 0x74
	private Single m_tweenStartTime; // 0x78
	private Single m_tweenStartValue; // 0x7c
	private Single m_tweenTargetValue; // 0x80
	private Boolean m_isInited; // 0x84
	private Int32 <pageCount>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get__enableDrag; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_get_isUpdating; // 0x10
	private static DelegateBridge __Hotfix0_get_pageCount; // 0x18
	private static DelegateBridge __Hotfix0_set_pageCount; // 0x20
	private static DelegateBridge __Hotfix0_SetPageCount; // 0x28
	private static DelegateBridge __Hotfix0_get_currentPage; // 0x30
	private static DelegateBridge __Hotfix0_set_currentPage; // 0x38
	private static DelegateBridge __Hotfix0_get_currentScrollIndex; // 0x40
	private static DelegateBridge __Hotfix0_SetScrollOptions; // 0x48
	private static DelegateBridge __Hotfix0_SetScrollEffect; // 0x50
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x58
	private static DelegateBridge __Hotfix0_MoveToPage; // 0x60
	private static DelegateBridge __Hotfix0_Awake; // 0x68
	private static DelegateBridge __Hotfix0_OnEnable; // 0x70
	private static DelegateBridge __Hotfix0_OnDisable; // 0x78
	private static DelegateBridge __Hotfix0_IsScrollStableState; // 0x80
	private static DelegateBridge __Hotfix0__ScrollValue2PageIndex; // 0x88
	private static DelegateBridge __Hotfix0__PageIndex2ScrollValue; // 0x90
	private static DelegateBridge __Hotfix0__ScrollValueAlignToPage; // 0x98
	private static DelegateBridge __Hotfix0__SwitchToPage; // 0xa0
	private static DelegateBridge __Hotfix0__AutoAlign; // 0xa8
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	private Boolean _enableDrag { get; }
	public Boolean isUpdating { get; }
	public Int32 pageCount { get; set; }
	public Int32 currentPage { get; set; }
	public Single currentScrollIndex { get; }

	// RVA: 0x22204b8 VA: 0x75948384b8
	private Boolean get__enableDrag() { }
	// RVA: 0x2220520 VA: 0x7594838520
	private Void _InitIfNot() { }
	// RVA: 0x22206d0 VA: 0x75948386d0
	public Boolean get_isUpdating() { }
	// RVA: 0x2220740 VA: 0x7594838740
	public Int32 get_pageCount() { }
	// RVA: 0x22207a8 VA: 0x75948387a8
	private Void set_pageCount(Int32 value) { }
	// RVA: 0x2220824 VA: 0x7594838824
	public Void SetPageCount(Int32 pageCount, IList`1 segmentFrames) { }
	// RVA: 0x2220b58 VA: 0x7594838b58
	public Int32 get_currentPage() { }
	// RVA: 0x2220bc0 VA: 0x7594838bc0
	public Void set_currentPage(Int32 value) { }
	// RVA: 0x2220f40 VA: 0x7594838f40
	public Single get_currentScrollIndex() { }
	// RVA: 0x22210c4 VA: 0x75948390c4
	public Void SetScrollOptions(ScrollOptions options) { }
	// RVA: 0x2221174 VA: 0x7594839174
	public Void SetScrollEffect(ScrollEffectConfig config) { }
	// RVA: 0x2221284 VA: 0x7594839284
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x2221e68 VA: 0x7594839e68
	public Void MoveToPage(Int32 pageIndex) { }
	// RVA: 0x2221f18 VA: 0x7594839f18
	private Void Awake() { }
	// RVA: 0x2221f80 VA: 0x7594839f80
	private Void OnEnable() { }
	// RVA: 0x2222018 VA: 0x759483a018
	private Void OnDisable() { }
	// RVA: 0x2222088 VA: 0x759483a088
	public static Boolean IsScrollStableState(State state) { }
	// RVA: 0x2221024 VA: 0x7594839024
	private Single _ScrollValue2PageIndex(Single value) { }
	// RVA: 0x2221bec VA: 0x7594839bec
	private Single _PageIndex2ScrollValue(Single index) { }
	// RVA: 0x22220f4 VA: 0x759483a0f4
	private Int32 _ScrollValueAlignToPage(Single value) { }
	// RVA: 0x2220c44 VA: 0x7594838c44
	private Void _SwitchToPage(Int32 targetIndex, Boolean useTween) { }
	// RVA: 0x2221c8c VA: 0x7594839c8c
	private Void _AutoAlign() { }
	// RVA: 0x2221d80 VA: 0x7594839d80
	private Void _OnStateChanged(State from, State to) { }
	// RVA: 0x22221b8 VA: 0x759483a1b8
	public Void .ctor() { }
}
```