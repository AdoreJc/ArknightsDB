# ScrollController

**Namespace:** ` `


## Fields

- `SiracusaMapBigMapView m_closure`

- `Tween m_scrollActions`

- `UIWrappedScrollRect m_scrollRect`

- `RectTransform m_viewport`

- `RectTransform m_scrollContent`

- `Vector2 m_viewportSize`

- `Boolean m_isLayoutReady`

- `FocusPos m_cacheStart`


## Properties

- `Vector2 normalizedPos`


## Methods

- `Void _SampleLayoutInfo()`

- `Vector2 get_normalizedPos()`

- `Void set_normalizedPos(Vector2)`

- `Void _DoScrollWheLayoutReady()`

- `Void NotifyLayoutReady()`

- `Void ScrollActions(FocusPos, FocusAction[])`

- `Vector2 CalcRectPosition(RectTransform)`

- `Vector2 Tick()`

- `Void InterruptScroll()`

- `Void _ScrollActionsImpl(FocusPos, FocusAction[])`

- `Vector2 _TweenGetNormPos()`

- `Void _TweenSetNormPos(Vector2)`

- `Void _ClearScrollActions()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ScrollController : IHotfixable
{
	private SiracusaMapBigMapView m_closure; // 0x10
	private Tween m_scrollActions; // 0x18
	private UIWrappedScrollRect m_scrollRect; // 0x20
	private RectTransform m_viewport; // 0x28
	private RectTransform m_scrollContent; // 0x30
	private Vector2 m_viewportSize; // 0x38
	private Boolean m_isLayoutReady; // 0x40
	private FocusPos m_cacheStart; // 0x44
	private FocusAction[] m_cacheActions; // 0x58
	private static DelegateBridge __Hotfix0__SampleLayoutInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_normalizedPos; // 0x8
	private static DelegateBridge __Hotfix0_set_normalizedPos; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0__DoScrollWheLayoutReady; // 0x20
	private static DelegateBridge __Hotfix0_NotifyLayoutReady; // 0x28
	private static DelegateBridge __Hotfix0_ScrollActions; // 0x30
	private static DelegateBridge __Hotfix0_CalcRectPosition; // 0x38
	private static DelegateBridge __Hotfix0_Tick; // 0x40
	private static DelegateBridge __Hotfix0_InterruptScroll; // 0x48
	private static DelegateBridge __Hotfix0__ScrollActionsImpl; // 0x50
	private static DelegateBridge __Hotfix0__ConvertToNormPos; // 0x58
	private static DelegateBridge __Hotfix0__ConvertFromNormPosToFocusPos; // 0x60
	private static DelegateBridge __Hotfix0__TweenGetNormPos; // 0x68
	private static DelegateBridge __Hotfix0__TweenSetNormPos; // 0x70
	private static DelegateBridge __Hotfix0__ClearScrollActions; // 0x78

	public Vector2 normalizedPos { get; set; }

	// RVA: 0x24102cc VA: 0x7594a282cc
	private Void _SampleLayoutInfo() { }
	// RVA: 0x24103a0 VA: 0x7594a283a0
	public Vector2 get_normalizedPos() { }
	// RVA: 0x2410488 VA: 0x7594a28488
	private Void set_normalizedPos(Vector2 value) { }
	// RVA: 0x240f324 VA: 0x7594a27324
	public Void .ctor(SiracusaMapBigMapView closure) { }
	// RVA: 0x241056c VA: 0x7594a2856c
	private Void _DoScrollWheLayoutReady() { }
	// RVA: 0x2410a10 VA: 0x7594a28a10
	public Void NotifyLayoutReady() { }
	// RVA: 0x240fbc4 VA: 0x7594a27bc4
	public Void ScrollActions(FocusPos start, FocusAction[] actions) { }
	// RVA: 0x240fd24 VA: 0x7594a27d24
	public Vector2 CalcRectPosition(RectTransform target) { }
	// RVA: 0x240ebd4 VA: 0x7594a26bd4
	public Vector2 Tick() { }
	// RVA: 0x240f014 VA: 0x7594a27014
	public Void InterruptScroll() { }
	// RVA: 0x24105e0 VA: 0x7594a285e0
	private Void _ScrollActionsImpl(FocusPos focusStart, FocusAction[] actions) { }
	// RVA: 0x2410cb0 VA: 0x7594a28cb0
	private static Vector2 _ConvertToNormPos(Vector2 position, Vector2 viewSize, Vector2 scrollRange, Boolean useLeftBias) { }
	// RVA: 0x2410a88 VA: 0x7594a28a88
	public static Vector2 _ConvertFromNormPosToFocusPos(Vector2 normPos, Vector2 viewSize, Vector2 scrollRange, Boolean useLeftBias) { }
	// RVA: 0x2410e6c VA: 0x7594a28e6c
	private Vector2 _TweenGetNormPos() { }
	// RVA: 0x2410ed4 VA: 0x7594a28ed4
	private Void _TweenSetNormPos(Vector2 val) { }
	// RVA: 0x2410c20 VA: 0x7594a28c20
	private Void _ClearScrollActions() { }
}
```