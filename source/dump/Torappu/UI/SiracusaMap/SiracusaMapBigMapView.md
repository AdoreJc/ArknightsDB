# SiracusaMapBigMapView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIWrappedScrollRect _scrollRect`

- `UILayoutDimensionListener _mapLayoutListener`

- `SiracusaBigMapLineView _lineView`

- `Vector2 _nodeAnchorBias`

- `RectMask2D _mapMask`

- `SiracusaBigMapTaskArrow _taskArrowPrefab`

- `RectTransform _taskArrowContainer`

- `UIAnimationLocation _showAnim`

- `ScreenEffectHolder _particleOnContent`

- `Boolean m_hasInited`

- `Boolean m_hasValueChangedInited`

- `Boolean m_cachedIsBigMapMode`

- `AnimationSwitchTween m_showSwitchTween`

- `String m_groupId`

- `ScrollController m_scrollCtrl`

- `TaskArrowController m_taskCtrl`

- `ParticleShapeController m_particleCtrl`

- `UIPageListener m_pageListener`

- `Boolean m_hasMapEnabled`

- `SiracusaMapFocusPolicy m_focusPolicy`

- `Vector2 m_lastScrollPos`

- `Action <onBlankClicked>k__BackingField`

- `Action <onFogClicked>k__BackingField`

- `AutoPackSpriteHub <taskCharAvatarHub>k__BackingField`


## Properties

- `Action onBlankClicked`

- `Action onFogClicked`

- `AutoPackSpriteHub taskCharAvatarHub`


## Methods

- `Void set_onNodeClick(Action`1)`

- `Action get_onBlankClicked()`

- `Void set_onBlankClicked(Action)`

- `Action get_onFogClicked()`

- `Void set_onFogClicked(Action)`

- `AutoPackSpriteHub get_taskCharAvatarHub()`

- `Void set_taskCharAvatarHub(AutoPackSpriteHub)`

- `Void DoInit()`

- `Void LateUpdate()`

- `Void OnDestroy()`

- `Void EventOnBlankClicked()`

- `Void _OnNodeClick(SiracusaMapMapNodeViewModel)`

- `Void _OnScrollMauallyDragged()`

- `Void _OnBlankSpaceInteracted()`

- `Void _BeforePageClosed(Boolean)`

- `Void _InitIfNot()`

- `Void _InitOnValueChanged()`

- `IEnumerator _WaitForLayoutReadyCoroutine(UIPage)`

- `Void _UpdateScrollLogics(SiracusaMapPanelMapViewModel)`

- `Void _DoScrollWhenNotForceFocus(SiracusaMapPanelMapViewModel)`

- `Void _DoFocusWithFallbacks()`

- `Vector2 _GetScrollPosOfArea(String)`

- `Vector2 _GetScrollPosOfPoint(String)`

- `RectTransform _GetTransformOfPoint(String)`

- `Vector2 _GetAnchorPosOfPoint(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapBigMapView : SiracusaMapViewBase`1
{
	public const Single FOCUS_MOVE_DELAY; // 0x0
	public const Single FOCUS_MOVE_DUR; // 0x0
	private const Single FOCUS_LEFT_BIAS; // 0x0
	private static readonly FocusAction DELAYED_MOVE_ACTION; // 0x0
	private static readonly FocusAction MOVE_ACTION; // 0x1c
	private UIWrappedScrollRect _scrollRect; // 0x88
	private Canvas[] _canvases; // 0x90
	private UILayoutDimensionListener _mapLayoutListener; // 0x98
	private UICommonPageEffectHolder[] _effects; // 0xa0
	private SiracusaBigMapLineView _lineView; // 0xa8
	private Vector2 _nodeAnchorBias; // 0xb0
	private RectMask2D _mapMask; // 0xb8
	private AreaPosInfo[] _areaPositions; // 0xc0
	private SiracusaBigMapTaskArrow _taskArrowPrefab; // 0xc8
	private RectTransform _taskArrowContainer; // 0xd0
	private UIAnimationLocation _showAnim; // 0xd8
	private ScreenEffectHolder _particleOnContent; // 0xe8
	private Boolean m_hasInited; // 0xf0
	private Boolean m_hasValueChangedInited; // 0xf1
	private Boolean m_cachedIsBigMapMode; // 0xf2
	private AnimationSwitchTween m_showSwitchTween; // 0xf8
	private String m_groupId; // 0x100
	private ScrollController m_scrollCtrl; // 0x108
	private TaskArrowController m_taskCtrl; // 0x110
	private ParticleShapeController m_particleCtrl; // 0x118
	private UIPageListener m_pageListener; // 0x120
	private Boolean m_hasMapEnabled; // 0x128
	private SiracusaMapFocusPolicy m_focusPolicy; // 0x130
	private Vector2 m_lastScrollPos; // 0x158
	private Action`1 <onNodeClick>k__BackingField; // 0x160
	private Action <onBlankClicked>k__BackingField; // 0x168
	private Action <onFogClicked>k__BackingField; // 0x170
	private AutoPackSpriteHub <taskCharAvatarHub>k__BackingField; // 0x178
	private static DelegateBridge __Hotfix0_get_onNodeClick; // 0x38
	private static DelegateBridge __Hotfix0_set_onNodeClick; // 0x40
	private static DelegateBridge __Hotfix0_get_onBlankClicked; // 0x48
	private static DelegateBridge __Hotfix0_set_onBlankClicked; // 0x50
	private static DelegateBridge __Hotfix0_get_onFogClicked; // 0x58
	private static DelegateBridge __Hotfix0_set_onFogClicked; // 0x60
	private static DelegateBridge __Hotfix0_get_taskCharAvatarHub; // 0x68
	private static DelegateBridge __Hotfix0_set_taskCharAvatarHub; // 0x70
	private static DelegateBridge __Hotfix0_DoInit; // 0x78
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x80
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x88
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x90
	private static DelegateBridge __Hotfix0_EventOnBlankClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnNodeClick; // 0xa0
	private static DelegateBridge __Hotfix0__OnScrollMauallyDragged; // 0xa8
	private static DelegateBridge __Hotfix0__OnBlankSpaceInteracted; // 0xb0
	private static DelegateBridge __Hotfix0__BeforePageClosed; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0xc0
	private static DelegateBridge __Hotfix0__InitOnValueChanged; // 0xc8
	private static DelegateBridge __Hotfix0__WaitForLayoutReadyCoroutine; // 0xd0
	private static DelegateBridge __Hotfix0__UpdateScrollLogics; // 0xd8
	private static DelegateBridge __Hotfix0__DoScrollWhenNotForceFocus; // 0xe0
	private static DelegateBridge __Hotfix0__DoFocusWithFallbacks; // 0xe8
	private static DelegateBridge __Hotfix0__GetScrollPosOfArea; // 0xf0
	private static DelegateBridge __Hotfix0__GetScrollPosOfPoint; // 0xf8
	private static DelegateBridge __Hotfix0__GetTransformOfPoint; // 0x100
	private static DelegateBridge __Hotfix0__GetAnchorPosOfPoint; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	private Action`1 onNodeClick { get; set; }
	private Action onBlankClicked { get; set; }
	private Action onFogClicked { get; set; }
	private AutoPackSpriteHub taskCharAvatarHub { get; set; }

	// RVA: 0x240d090 VA: 0x7594a25090
	private Action`1 get_onNodeClick() { }
	// RVA: 0x240d108 VA: 0x7594a25108
	public Void set_onNodeClick(Action`1 value) { }
	// RVA: 0x240d19c VA: 0x7594a2519c
	private Action get_onBlankClicked() { }
	// RVA: 0x240d214 VA: 0x7594a25214
	public Void set_onBlankClicked(Action value) { }
	// RVA: 0x240d2a8 VA: 0x7594a252a8
	private Action get_onFogClicked() { }
	// RVA: 0x240d320 VA: 0x7594a25320
	public Void set_onFogClicked(Action value) { }
	// RVA: 0x240d3b4 VA: 0x7594a253b4
	private AutoPackSpriteHub get_taskCharAvatarHub() { }
	// RVA: 0x240d42c VA: 0x7594a2542c
	public Void set_taskCharAvatarHub(AutoPackSpriteHub value) { }
	// RVA: 0x240d4c0 VA: 0x7594a254c0
	public Void DoInit() { }
	// RVA: 0x240de80 VA: 0x7594a25e80
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x240e9b4 VA: 0x7594a269b4
	private Void LateUpdate() { }
	// RVA: 0x240ecec VA: 0x7594a26cec
	private Void OnDestroy() { }
	// RVA: 0x240eda4 VA: 0x7594a26da4
	public Void EventOnBlankClicked() { }
	// RVA: 0x240eec8 VA: 0x7594a26ec8
	private Void _OnNodeClick(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x240ef90 VA: 0x7594a26f90
	private Void _OnScrollMauallyDragged() { }
	// RVA: 0x240ee1c VA: 0x7594a26e1c
	private Void _OnBlankSpaceInteracted() { }
	// RVA: 0x240f07c VA: 0x7594a2707c
	private Void _BeforePageClosed(Boolean isIntoStack) { }
	// RVA: 0x240d538 VA: 0x7594a25538
	private Void _InitIfNot() { }
	// RVA: 0x240e2b4 VA: 0x7594a262b4
	private Void _InitOnValueChanged() { }
	// RVA: 0x240f4a4 VA: 0x7594a274a4
	private IEnumerator _WaitForLayoutReadyCoroutine(UIPage page) { }
	// RVA: 0x240e358 VA: 0x7594a26358
	private Void _UpdateScrollLogics(SiracusaMapPanelMapViewModel viewModel) { }
	// RVA: 0x240f584 VA: 0x7594a27584
	private Void _DoScrollWhenNotForceFocus(SiracusaMapPanelMapViewModel viewModel) { }
	// RVA: 0x240f744 VA: 0x7594a27744
	private Void _DoFocusWithFallbacks() { }
	// RVA: 0x240f9f4 VA: 0x7594a279f4
	private Vector2 _GetScrollPosOfArea(String areaId) { }
	// RVA: 0x240f8b0 VA: 0x7594a278b0
	private Vector2 _GetScrollPosOfPoint(String pointId) { }
	// RVA: 0x240fea8 VA: 0x7594a27ea8
	private RectTransform _GetTransformOfPoint(String pointId) { }
	// RVA: 0x240ffb4 VA: 0x7594a27fb4
	private Vector2 _GetAnchorPosOfPoint(String pointId) { }
	// RVA: 0x24100fc VA: 0x7594a280fc
	public Void .ctor() { }
	// RVA: 0x24101e0 VA: 0x7594a281e0
	private static Void .cctor() { }
}
```