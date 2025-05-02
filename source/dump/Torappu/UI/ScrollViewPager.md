# ScrollViewPager

**Namespace:** `Torappu.UI`


## Fields

- `Scrollbar _scrollbar`

- `Single _animationDuration`

- `Boolean m_enableDrag`

- `Int32 m_pageCount`

- `Int32 m_currentPage`

- `Single m_lastUpdateTime`

- `Boolean m_isDragging`

- `PointerEventData m_lastActiveDrag`

- `Int32 m_fromPage`

- `Int32 m_toPage`

- `Single m_tweenStartTime`

- `Single m_tweenStartValue`

- `Single m_tweenTargetValue`

- `Boolean m_tweenScrollDirty`

- `Boolean m_isTweening`


## Properties

- `Boolean _enableDrag`

- `Single scrollState`

- `Boolean isUpdating`

- `Int32 pageCount`

- `Int32 currentPage`


## Methods

- `Boolean get__enableDrag()`

- `Void set__enableDrag(Boolean)`

- `Single get_scrollState()`

- `Boolean get_isUpdating()`

- `Int32 get_pageCount()`

- `Void set_pageCount(Int32)`

- `Int32 get_currentPage()`

- `Void set_currentPage(Int32)`

- `Void SetEnableDragFlag(Boolean)`

- `Void AddUpdatingListener(Action`1)`

- `Void RemoveUpdatingListener(Action`1)`

- `Void AddPageIndexListener(Action`1)`

- `Void RemovePageIndexListener(Action`1)`

- `Void AddPageIndexChangedListener(Action`1)`

- `Void RemovePageIndexChangedListener(Action`1)`

- `Void UpdateTime(Single)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void MoveToPage(Int32)`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void _ReleaseDragWhenDisabled()`

- `Single _PageIndex2ScrollValue(Single)`

- `Void _SwitchToPage(Int32, Boolean)`

- `Void _AutoAlign()`

- `Boolean _CheckPageDirtyElastical(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ScrollViewPager : MonoBehaviour, IBeginDragHandler, IEventSystemHandler, IEndDragHandler, IDragHandler, ITimeWatcher, IHotfixable
{
	private Scrollbar _scrollbar; // 0x18
	private Single _animationDuration; // 0x20
	private Boolean m_enableDrag; // 0x24
	protected Int32 m_pageCount; // 0x28
	protected Int32 m_currentPage; // 0x2c
	private Single m_lastUpdateTime; // 0x30
	protected Boolean m_isDragging; // 0x34
	private PointerEventData m_lastActiveDrag; // 0x38
	private Int32 m_fromPage; // 0x40
	private Int32 m_toPage; // 0x44
	private Single m_tweenStartTime; // 0x48
	private Single m_tweenStartValue; // 0x4c
	private Single m_tweenTargetValue; // 0x50
	private Boolean m_tweenScrollDirty; // 0x54
	protected Boolean m_isTweening; // 0x55
	private Action`1 m_updatingListeners; // 0x58
	private Action`1 m_pageChangedListeners; // 0x60
	private Action`1 m_pageChangeFinishListeners; // 0x68
	private static DelegateBridge __Hotfix0_get__enableDrag; // 0x0
	private static DelegateBridge __Hotfix0_set__enableDrag; // 0x8
	private static DelegateBridge __Hotfix0_get_scrollState; // 0x10
	private static DelegateBridge __Hotfix0_get_isUpdating; // 0x18
	private static DelegateBridge __Hotfix0_get_pageCount; // 0x20
	private static DelegateBridge __Hotfix0_set_pageCount; // 0x28
	private static DelegateBridge __Hotfix0_get_currentPage; // 0x30
	private static DelegateBridge __Hotfix0_set_currentPage; // 0x38
	private static DelegateBridge __Hotfix0_SetEnableDragFlag; // 0x40
	private static DelegateBridge __Hotfix0_AddUpdatingListener; // 0x48
	private static DelegateBridge __Hotfix0_RemoveUpdatingListener; // 0x50
	private static DelegateBridge __Hotfix0_AddPageIndexListener; // 0x58
	private static DelegateBridge __Hotfix0_RemovePageIndexListener; // 0x60
	private static DelegateBridge __Hotfix0_AddPageIndexChangedListener; // 0x68
	private static DelegateBridge __Hotfix0_RemovePageIndexChangedListener; // 0x70
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x78
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x80
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x88
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x90
	private static DelegateBridge __Hotfix0__OnEndDrag; // 0x98
	private static DelegateBridge __Hotfix0_OnDrag; // 0xa0
	private static DelegateBridge __Hotfix0_MoveToPage; // 0xa8
	private static DelegateBridge __Hotfix0_OnEnable; // 0xb0
	private static DelegateBridge __Hotfix0_OnDisable; // 0xb8
	private static DelegateBridge __Hotfix0__ReleaseDragWhenDisabled; // 0xc0
	private static DelegateBridge __Hotfix0__ScrollValue2PageIndex; // 0xc8
	private static DelegateBridge __Hotfix0__PageIndex2ScrollValue; // 0xd0
	private static DelegateBridge __Hotfix0__SwitchToPage; // 0xd8
	private static DelegateBridge __Hotfix0__AutoAlign; // 0xe0
	private static DelegateBridge __Hotfix0__CheckPageDirtyElastical; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	protected Boolean _enableDrag { get; set; }
	public Single scrollState { get; }
	public Boolean isUpdating { get; }
	public Int32 pageCount { get; set; }
	public Int32 currentPage { get; set; }

	// RVA: 0x223a624 VA: 0x7594852624
	protected Boolean get__enableDrag() { }
	// RVA: 0x223ade8 VA: 0x7594852de8
	protected Void set__enableDrag(Boolean value) { }
	// RVA: 0x223aeec VA: 0x7594852eec
	public Single get_scrollState() { }
	// RVA: 0x223af7c VA: 0x7594852f7c
	public Boolean get_isUpdating() { }
	// RVA: 0x223a804 VA: 0x7594852804
	public Int32 get_pageCount() { }
	// RVA: 0x223affc VA: 0x7594852ffc
	public Void set_pageCount(Int32 value) { }
	// RVA: 0x223b078 VA: 0x7594853078
	public Int32 get_currentPage() { }
	// RVA: 0x223b0e0 VA: 0x75948530e0
	public Void set_currentPage(Int32 value) { }
	// RVA: 0x223b164 VA: 0x7594853164
	public Void SetEnableDragFlag(Boolean flag) { }
	// RVA: 0x223b278 VA: 0x7594853278
	public Void AddUpdatingListener(Action`1 listener) { }
	// RVA: 0x223b3c0 VA: 0x75948533c0
	public Void RemoveUpdatingListener(Action`1 listener) { }
	// RVA: 0x223b4a8 VA: 0x75948534a8
	public Void AddPageIndexListener(Action`1 listener) { }
	// RVA: 0x223b5f0 VA: 0x75948535f0
	public Void RemovePageIndexListener(Action`1 listener) { }
	// RVA: 0x223b6d8 VA: 0x75948536d8
	public Void AddPageIndexChangedListener(Action`1 listener) { }
	// RVA: 0x223b820 VA: 0x7594853820
	public Void RemovePageIndexChangedListener(Action`1 listener) { }
	// RVA: 0x223b908 VA: 0x7594853908
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x223bc98 VA: 0x7594853c98
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x223ac00 VA: 0x7594852c00
	protected virtual Void _OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x223bd40 VA: 0x7594853d40
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x223aca4 VA: 0x7594852ca4
	protected virtual Void _OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x223bdc8 VA: 0x7594853dc8
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x223be6c VA: 0x7594853e6c
	public Void MoveToPage(Int32 pageIndex) { }
	// RVA: 0x223bef0 VA: 0x7594853ef0
	private Void OnEnable() { }
	// RVA: 0x223bf7c VA: 0x7594853f7c
	private Void OnDisable() { }
	// RVA: 0x223bff4 VA: 0x7594853ff4
	private Void _ReleaseDragWhenDisabled() { }
	// RVA: 0x223ad54 VA: 0x7594852d54
	protected virtual Single _ScrollValue2PageIndex(Single value) { }
	// RVA: 0x223bc04 VA: 0x7594853c04
	private Single _PageIndex2ScrollValue(Single index) { }
	// RVA: 0x223a86c VA: 0x759485286c
	protected Void _SwitchToPage(Int32 targetIndex, Boolean useTween) { }
	// RVA: 0x223a9d4 VA: 0x75948529d4
	protected Void _AutoAlign() { }
	// RVA: 0x223baec VA: 0x7594853aec
	private Boolean _CheckPageDirtyElastical(Int32 pageIndex) { }
	// RVA: 0x223ab78 VA: 0x7594852b78
	public Void .ctor() { }
}
```