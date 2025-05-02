# HomeIllustEditState

**Namespace:** `Torappu.UI.Home`


## Fields

- `CanvasGroup _alphaHandler`

- `Slider _sizeSlider`

- `HomeIllustEditFrame _editFrame`

- `RectTransform _rectCancel`

- `Text _textPos`

- `Text _textSize`

- `Text _textMinSlide`

- `Text _textMaxSlide`

- `Color _colorChanging`

- `Color _colorChanged`

- `IllustHandler m_illustHandler`

- `AdjustConfig m_adjustConfig`

- `UIIllustLayoutInfo m_editingInfo`

- `DragPosStatus m_dragStatus`

- `LayoutTween m_tweenInUpdate`

- `Boolean m_isInited`

- `String m_rawColorPos`

- `String m_rawColorSize`

- `String m_colorChanging`

- `String m_colorChanged`


## Methods

- `Void _InitIfNot()`

- `Void BeginDragFromFrame(PointerEventData)`

- `Void Update()`

- `Void EventOnCancelClicked()`

- `Void EventOnConfirmClicked()`

- `Void EventOnResetClicked()`

- `Void _UpdatePos()`

- `Void _UpdateSize()`

- `Void _SyncStatusToIllust()`

- `Void _SyncStatusToText()`

- `Void _CheckIfPosChanged(out, out)`

- `Boolean _CheckIfSizeChanged()`

- `DragPosStatus _CreateEditStatusFromBeginDrag(PointerEventData)`

- `Void _CancelEditing()`

- `Boolean _IsStateStable()`

- `Void _OnCancel()`

- `Void _CancelDragging()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeIllustEditState : HomeReplaceableState, IDragEvent
{
	private const Single MIN_SIZE; // 0x0
	private const Int32 MIN_SLIDE; // 0x0
	private const Int32 MAX_SLIDE; // 0x0
	private const Single MAX_POS; // 0x0
	private CanvasGroup _alphaHandler; // 0x60
	private Slider _sizeSlider; // 0x68
	private HomeIllustEditFrame _editFrame; // 0x70
	private RectTransform _rectCancel; // 0x78
	private Text _textPos; // 0x80
	private Text _textSize; // 0x88
	private Text _textMinSlide; // 0x90
	private Text _textMaxSlide; // 0x98
	private Color _colorChanging; // 0xa0
	private Color _colorChanged; // 0xb0
	private IllustHandler m_illustHandler; // 0xc0
	private AdjustConfig m_adjustConfig; // 0xc8
	private UIIllustLayoutInfo m_editingInfo; // 0x100
	private DragPosStatus m_dragStatus; // 0x110
	private LayoutTween m_tweenInUpdate; // 0x150
	private Boolean m_isInited; // 0x1a0
	private String m_rawColorPos; // 0x1a8
	private String m_rawColorSize; // 0x1b0
	private String m_colorChanging; // 0x1b8
	private String m_colorChanged; // 0x1c0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_BeginDragFromFrame; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnResetClicked; // 0x40
	private static DelegateBridge __Hotfix0__UpdatePos; // 0x48
	private static DelegateBridge __Hotfix0__UpdateSize; // 0x50
	private static DelegateBridge __Hotfix0__SyncStatusToIllust; // 0x58
	private static DelegateBridge __Hotfix0__SyncStatusToText; // 0x60
	private static DelegateBridge __Hotfix0__CheckIfPosChanged; // 0x68
	private static DelegateBridge __Hotfix0__CheckIfSizeChanged; // 0x70
	private static DelegateBridge __Hotfix0__GenAdjustConfig; // 0x78
	private static DelegateBridge __Hotfix0__CreateEditStatusFromBeginDrag; // 0x80
	private static DelegateBridge __Hotfix0__CancelEditing; // 0x88
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x90
	private static DelegateBridge __Hotfix0__OnCancel; // 0x98
	private static DelegateBridge __Hotfix0__CancelDragging; // 0xa0
	private static DelegateBridge __Hotfix0__ConvertScreenPosToIllust; // 0xa8
	private static DelegateBridge __Hotfix0_HideEffect; // 0xb0
	private static DelegateBridge __Hotfix0_HideFastMode; // 0xb8
	private static DelegateBridge __Hotfix0_ShowEffect; // 0xc0
	private static DelegateBridge __Hotfix0_ShowFastMode; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0


	// RVA: 0x27efaa0 VA: 0x7594e07aa0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27efb04 VA: 0x7594e07b04
	private Void _InitIfNot() { }
	// RVA: 0x27efd14 VA: 0x7594e07d14
	protected override Void OnEnter() { }
	// RVA: 0x27f0628 VA: 0x7594e08628
	protected override Void OnExit() { }
	// RVA: 0x27f06a4 VA: 0x7594e086a4
	public Void BeginDragFromFrame(PointerEventData eventData) { }
	// RVA: 0x27f0aa0 VA: 0x7594e08aa0
	private Void Update() { }
	// RVA: 0x27f1438 VA: 0x7594e09438
	public Void EventOnCancelClicked() { }
	// RVA: 0x27f1674 VA: 0x7594e09674
	public Void EventOnConfirmClicked() { }
	// RVA: 0x27f1894 VA: 0x7594e09894
	public Void EventOnResetClicked() { }
	// RVA: 0x27f0b20 VA: 0x7594e08b20
	private Void _UpdatePos() { }
	// RVA: 0x27f0c48 VA: 0x7594e08c48
	private Void _UpdateSize() { }
	// RVA: 0x27f0e20 VA: 0x7594e08e20
	private Void _SyncStatusToIllust() { }
	// RVA: 0x27f0f04 VA: 0x7594e08f04
	private Void _SyncStatusToText() { }
	// RVA: 0x27f1fa0 VA: 0x7594e09fa0
	private Void _CheckIfPosChanged(out Boolean xChanged, out Boolean yChanged) { }
	// RVA: 0x27f22c8 VA: 0x7594e0a2c8
	private Boolean _CheckIfSizeChanged() { }
	// RVA: 0x27eff54 VA: 0x7594e07f54
	private static AdjustConfig _GenAdjustConfig(IllustHandler handler) { }
	// RVA: 0x27f07e8 VA: 0x7594e087e8
	private DragPosStatus _CreateEditStatusFromBeginDrag(PointerEventData eventData) { }
	// RVA: 0x27f14a0 VA: 0x7594e094a0
	private Void _CancelEditing() { }
	// RVA: 0x27f2450 VA: 0x7594e0a450
	private Boolean _IsStateStable() { }
	// RVA: 0x27f23c4 VA: 0x7594e0a3c4
	private Void _OnCancel() { }
	// RVA: 0x27f17ec VA: 0x7594e097ec
	private Void _CancelDragging() { }
	// RVA: 0x27f1c44 VA: 0x7594e09c44
	private static Vector2 _ConvertScreenPosToIllust(Vector2 sp, RectTransform illustContainer, Camera illustCam) { }
	// RVA: 0x27f2540 VA: 0x7594e0a540
	protected override IEnumerator HideEffect() { }
	// RVA: 0x27f2614 VA: 0x7594e0a614
	protected override Void HideFastMode() { }
	// RVA: 0x27f2694 VA: 0x7594e0a694
	protected override IEnumerator ShowEffect(HomeReplaceableState extractState) { }
	// RVA: 0x27f277c VA: 0x7594e0a77c
	protected override Void ShowFastMode() { }
	// RVA: 0x27f280c VA: 0x7594e0a80c
	public Void .ctor() { }
	// RVA: 0x27f28b0 VA: 0x7594e0a8b0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27f28b8 VA: 0x7594e0a8b8
	private Void <>xLuaBaseProxy_OnExit() { }
}
```