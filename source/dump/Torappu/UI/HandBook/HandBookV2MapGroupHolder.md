# HandBookV2MapGroupHolder

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Transform _container`

- `UIHandBookCardEvent _clickEvent`

- `Image _backLogo`

- `RectTransform _focusView`

- `UIStringEvent _onForceClick`

- `RectTransform _scrollHolder`

- `UITouchZoom _touchZoom`

- `ScrollRect _scrollRect`

- `HandBookV2MapGroupView defaultGroup`

- `HandBookV2GroupViewModel m_cacheViewModel`

- `HandBookV2GroupViewModel m_pendingData`

- `HandBookV2MapGroupView m_groupView`

- `UIPageListener m_pageBinder`

- `Boolean isLocked`

- `String m_mainForce`

- `Boolean m_isInited`


## Properties

- `RectTransform touchZoomRect`

- `ScrollRect scrollRect`

- `RectTransform scrollRectTrans`


## Methods

- `Void _InitIfNot()`

- `Single GetScale()`

- `Void _OnScaleStart(Single)`

- `Void _OnScaleEnd(Single)`

- `Void _OnScaleChanged(Single)`

- `HandBookV2MapGroupView _GetGroupView()`

- `Void _RenderBackLogo(HandBookV2GroupViewModel)`

- `IEnumerator _OnTransitionGroup(HandBookV2GroupViewModel, HandBookV2GroupViewModel)`

- `IEnumerator _OnTransition(HandBookV2GroupViewModel)`

- `RectTransform get_touchZoomRect()`

- `ScrollRect get_scrollRect()`

- `RectTransform get_scrollRectTrans()`

- `Void _CoroutineWithPage(IEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapGroupHolder : DataBinder`1, IHotfixable
{
	private Transform _container; // 0x20
	private UIHandBookCardEvent _clickEvent; // 0x28
	private Image _backLogo; // 0x30
	private RectTransform _focusView; // 0x38
	private UIStringEvent _onForceClick; // 0x40
	private RectTransform _scrollHolder; // 0x48
	private UITouchZoom _touchZoom; // 0x50
	private ScrollRect _scrollRect; // 0x58
	private HandBookV2MapGroupView defaultGroup; // 0x60
	private HandBookV2GroupViewModel m_cacheViewModel; // 0x68
	private HandBookV2GroupViewModel m_pendingData; // 0x70
	private HandBookV2MapGroupView m_groupView; // 0x78
	private UIPageListener m_pageBinder; // 0x80
	public Boolean isLocked; // 0x88
	private String m_mainForce; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetScale; // 0x8
	private static DelegateBridge __Hotfix0__OnScaleStart; // 0x10
	private static DelegateBridge __Hotfix0__OnScaleEnd; // 0x18
	private static DelegateBridge __Hotfix0__OnScaleChanged; // 0x20
	private static DelegateBridge __Hotfix0__GetGroupView; // 0x28
	private static DelegateBridge __Hotfix0__RenderBackLogo; // 0x30
	private static DelegateBridge __Hotfix0__OnTransitionGroup; // 0x38
	private static DelegateBridge __Hotfix0__OnTransition; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x48
	private static DelegateBridge __Hotfix0_get_touchZoomRect; // 0x50
	private static DelegateBridge __Hotfix0_get_scrollRect; // 0x58
	private static DelegateBridge __Hotfix0_get_scrollRectTrans; // 0x60
	private static DelegateBridge __Hotfix0__CoroutineWithPage; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public RectTransform touchZoomRect { get; }
	public ScrollRect scrollRect { get; }
	public RectTransform scrollRectTrans { get; }

	// RVA: 0x2ed3038 VA: 0x75954eb038
	private Void _InitIfNot() { }
	// RVA: 0x2ed31c0 VA: 0x75954eb1c0
	public Single GetScale() { }
	// RVA: 0x2ed3244 VA: 0x75954eb244
	private Void _OnScaleStart(Single scale) { }
	// RVA: 0x2ed32c8 VA: 0x75954eb2c8
	private Void _OnScaleEnd(Single scale) { }
	// RVA: 0x2ed334c VA: 0x75954eb34c
	private Void _OnScaleChanged(Single scale) { }
	// RVA: 0x2ed3448 VA: 0x75954eb448
	private HandBookV2MapGroupView _GetGroupView() { }
	// RVA: 0x2ed3524 VA: 0x75954eb524
	private Void _RenderBackLogo(HandBookV2GroupViewModel viewModel) { }
	// RVA: 0x2ed3624 VA: 0x75954eb624
	private IEnumerator _OnTransitionGroup(HandBookV2GroupViewModel oldViewModel, HandBookV2GroupViewModel newViewModel) { }
	// RVA: 0x2ed3734 VA: 0x75954eb734
	private IEnumerator _OnTransition(HandBookV2GroupViewModel newViewModel) { }
	// RVA: 0x2ed382c VA: 0x75954eb82c
	public override Void OnValueChanged(HandBookV2GroupProperty property) { }
	// RVA: 0x2ed3a0c VA: 0x75954eba0c
	public RectTransform get_touchZoomRect() { }
	// RVA: 0x2ed3a78 VA: 0x75954eba78
	public ScrollRect get_scrollRect() { }
	// RVA: 0x2ed3ae0 VA: 0x75954ebae0
	public RectTransform get_scrollRectTrans() { }
	// RVA: 0x2ed390c VA: 0x75954eb90c
	private Void _CoroutineWithPage(IEnumerator coroutine) { }
	// RVA: 0x2ed3b4c VA: 0x75954ebb4c
	public Void .ctor() { }
}
```