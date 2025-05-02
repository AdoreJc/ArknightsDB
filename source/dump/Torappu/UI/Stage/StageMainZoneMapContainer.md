# StageMainZoneMapContainer

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageClickEvent _stageSelectEvent`

- `Single _dragFactor`

- `AnimationCurve _easeMoveCurve`

- `Single _easeMoveDuration`

- `Single _ineriaFactor`

- `Single _ineriaIteratorPeriod`

- `UIStringEvent _stageFogUnlockEvent`

- `Transform _diffHolderContainer`

- `UIDiffGroupEvent _selectDiffAction`

- `UnityEvent _onDiffSelectDetail`

- `UnityEvent _onAddedReceiveCacheEvent`

- `StageZoneDiffSelectHolder m_diffHolder`

- `UIStringEvent _eventMapNotFound`

- `UIStringEvent _eventMapLoadFinish`

- `RectTransform _mapContainer`

- `RectTransform _focusBound`

- `Vector2 m_dragOrigin`

- `Single m_positionValue`

- `StageMainZoneMap m_mainZoneMap`

- `String m_zoneMapAssetPathCache`

- `Boolean m_pressing`

- `Boolean m_dragging`

- `String m_currentZoneId`

- `StageDiffGroup m_cacheDiffGroup`

- `String m_focusedStageId`

- `Boolean m_focus`

- `Double m_easeMoveBaseTime`

- `Single m_easeMoveVal0`

- `Single m_easeMoveVal1`

- `Single m_extensionOffset`

- `Single m_extensionBaseTime`

- `Single m_extensionOffsetMoveVal0`

- `Single m_lastPositionValue`

- `PositionTween m_posTween`

- `UIPageListener m_pageListener`

- `Action m_onceWorkAfterUpdate`


## Properties

- `StageZoneDiffSelectHolder diffHolder`

- `Single positionValue`

- `Single backgroundImageRefValue`


## Methods

- `StageZoneDiffSelectHolder get_diffHolder()`

- `Void DoOnceAfterUpdate(Action)`

- `Void _OnStageClicked(String)`

- `Void _OnStageFogClicked(String)`

- `Void _OnSpecialStageRewardClicked(String)`

- `Single _UniformPositionValueViaMap(Single)`

- `Void _FocusToStage(String)`

- `Void _FocusToValue(Single)`

- `Void _FocusCancel()`

- `Vector2 _IntertiaProcess(Vector2, Single, Single)`

- `Void _UpdateInertia()`

- `Void _UpdateEaseMove()`

- `Void _UpdatePositionTween()`

- `Void _UpdateExtensionOffsetMove()`

- `Void _ClearCachedMap()`

- `Void _ClearUpdateCache()`

- `Void _Setup(ZoneViewModel)`

- `Void _TweenPositionTo(Single, Single)`

- `Boolean _SetupZoneMapIfNeeded(ZoneViewModel)`

- `Void Update()`

- `Void OnDestroy()`

- `Single get_positionValue()`

- `Single get_backgroundImageRefValue()`

- `UIPage GetPage()`

- `Void OnPointerUp(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnDrag(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMainZoneMapContainer : DataBinder`1, IStageMainZoneMapController, IPointerUpHandler, IEventSystemHandler, IPointerDownHandler, IDragHandler, IEndDragHandler
{
	private const Single POS_TWEEN_SPEED; // 0x0
	private const Single POS_TWEEN_MIN_DUR; // 0x0
	private const Single INIT_POS_TWEEN_MAX_DIS; // 0x0
	private StageClickEvent _stageSelectEvent; // 0x20
	private Single _dragFactor; // 0x28
	private AnimationCurve _easeMoveCurve; // 0x30
	private Single _easeMoveDuration; // 0x38
	private Single _ineriaFactor; // 0x3c
	private Single _ineriaIteratorPeriod; // 0x40
	private UIStringEvent _stageFogUnlockEvent; // 0x48
	private Transform _diffHolderContainer; // 0x50
	private UIDiffGroupEvent _selectDiffAction; // 0x58
	private UnityEvent _onDiffSelectDetail; // 0x60
	private UnityEvent _onAddedReceiveCacheEvent; // 0x68
	private StageZoneDiffSelectHolder m_diffHolder; // 0x70
	private Action`1 _specialStageRewardEvent; // 0x78
	private UIStringEvent _eventMapNotFound; // 0x80
	private UIStringEvent _eventMapLoadFinish; // 0x88
	private RectTransform _mapContainer; // 0x90
	private RectTransform _focusBound; // 0x98
	private Vector2 m_dragOrigin; // 0xa0
	private Single m_positionValue; // 0xa8
	private StageMainZoneMap m_mainZoneMap; // 0xb0
	private String m_zoneMapAssetPathCache; // 0xb8
	private Boolean m_pressing; // 0xc0
	private Boolean m_dragging; // 0xc1
	private String m_currentZoneId; // 0xc8
	private StageDiffGroup m_cacheDiffGroup; // 0xd0
	private String m_focusedStageId; // 0xd8
	private Boolean m_focus; // 0xe0
	private Double m_easeMoveBaseTime; // 0xe8
	private Single m_easeMoveVal0; // 0xf0
	private Single m_easeMoveVal1; // 0xf4
	private Single m_extensionOffset; // 0xf8
	private Single m_extensionBaseTime; // 0xfc
	private Single m_extensionOffsetMoveVal0; // 0x100
	private Single m_lastPositionValue; // 0x104
	private PositionTween m_posTween; // 0x108
	private UIPageListener m_pageListener; // 0x128
	private Action m_onceWorkAfterUpdate; // 0x130
	private static DelegateBridge __Hotfix0_get_diffHolder; // 0x0
	private static DelegateBridge __Hotfix0_DoOnceAfterUpdate; // 0x8
	private static DelegateBridge __Hotfix0__OnStageClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnStageFogClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnSpecialStageRewardClicked; // 0x20
	private static DelegateBridge __Hotfix0__UniformPositionValueViaMap; // 0x28
	private static DelegateBridge __Hotfix0__FocusToStage; // 0x30
	private static DelegateBridge __Hotfix0__FocusToValue; // 0x38
	private static DelegateBridge __Hotfix0__FocusCancel; // 0x40
	private static DelegateBridge __Hotfix0__IntertiaProcess; // 0x48
	private static DelegateBridge __Hotfix0__UpdateInertia; // 0x50
	private static DelegateBridge __Hotfix0__UpdateEaseMove; // 0x58
	private static DelegateBridge __Hotfix0__UpdatePositionTween; // 0x60
	private static DelegateBridge __Hotfix0__UpdateExtensionOffsetMove; // 0x68
	private static DelegateBridge __Hotfix0__ClearCachedMap; // 0x70
	private static DelegateBridge __Hotfix0__ClearUpdateCache; // 0x78
	private static DelegateBridge __Hotfix0__Setup; // 0x80
	private static DelegateBridge __Hotfix0__TweenPositionTo; // 0x88
	private static DelegateBridge __Hotfix0__SetupZoneMapIfNeeded; // 0x90
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x98
	private static DelegateBridge __Hotfix0_Update; // 0xa0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xa8
	private static DelegateBridge __Hotfix0_get_positionValue; // 0xb0
	private static DelegateBridge __Hotfix0_get_backgroundImageRefValue; // 0xb8
	private static DelegateBridge __Hotfix0_GetPage; // 0xc0
	private static DelegateBridge __Hotfix0_OnPointerUp; // 0xc8
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0xd0
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0xd8
	private static DelegateBridge __Hotfix0_OnDrag; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public StageZoneDiffSelectHolder diffHolder { get; }
	public Single positionValue { get; }
	public Single backgroundImageRefValue { get; }

	// RVA: 0x2f964bc VA: 0x75955ae4bc
	public StageZoneDiffSelectHolder get_diffHolder() { }
	// RVA: 0x2f9669c VA: 0x75955ae69c
	public Void DoOnceAfterUpdate(Action work) { }
	// RVA: 0x2f96778 VA: 0x75955ae778
	private Void _OnStageClicked(String stageId) { }
	// RVA: 0x2f96824 VA: 0x75955ae824
	private Void _OnStageFogClicked(String stageId) { }
	// RVA: 0x2f968d0 VA: 0x75955ae8d0
	private Void _OnSpecialStageRewardClicked(String stageId) { }
	// RVA: 0x2f96970 VA: 0x75955ae970
	private Single _UniformPositionValueViaMap(Single positionVal) { }
	// RVA: 0x2f96a20 VA: 0x75955aea20
	private Void _FocusToStage(String stageId) { }
	// RVA: 0x2f96c6c VA: 0x75955aec6c
	private Void _FocusToValue(Single val) { }
	// RVA: 0x2f96d2c VA: 0x75955aed2c
	private Void _FocusCancel() { }
	// RVA: 0x2f96dd4 VA: 0x75955aedd4
	private Vector2 _IntertiaProcess(Vector2 dualHist, Single factor, Single threshold) { }
	// RVA: 0x2f96e90 VA: 0x75955aee90
	private Void _UpdateInertia() { }
	// RVA: 0x2f9700c VA: 0x75955af00c
	private Void _UpdateEaseMove() { }
	// RVA: 0x2f97144 VA: 0x75955af144
	private Void _UpdatePositionTween() { }
	// RVA: 0x2f972a4 VA: 0x75955af2a4
	private Void _UpdateExtensionOffsetMove() { }
	// RVA: 0x2f973a4 VA: 0x75955af3a4
	private Void _ClearCachedMap() { }
	// RVA: 0x2f97420 VA: 0x75955af420
	private Void _ClearUpdateCache() { }
	// RVA: 0x2f974bc VA: 0x75955af4bc
	private Void _Setup(ZoneViewModel model) { }
	// RVA: 0x2f97b44 VA: 0x75955afb44
	private Void _TweenPositionTo(Single targetVal, Single maxTweenDis) { }
	// RVA: 0x2f977e0 VA: 0x75955af7e0
	private Boolean _SetupZoneMapIfNeeded(ZoneViewModel model) { }
	// RVA: 0x2f97e40 VA: 0x75955afe40
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2f980dc VA: 0x75955b00dc
	public Void Update() { }
	// RVA: 0x2f981f0 VA: 0x75955b01f0
	private Void OnDestroy() { }
	// RVA: 0x2f98258 VA: 0x75955b0258
	public Single get_positionValue() { }
	// RVA: 0x2f982cc VA: 0x75955b02cc
	public Single get_backgroundImageRefValue() { }
	// RVA: 0x2f97d30 VA: 0x75955afd30
	public UIPage GetPage() { }
	// RVA: 0x2f98340 VA: 0x75955b0340
	public Void OnPointerUp(PointerEventData data) { }
	// RVA: 0x2f983d4 VA: 0x75955b03d4
	public Void OnEndDrag(PointerEventData data) { }
	// RVA: 0x2f98450 VA: 0x75955b0450
	public Void OnPointerDown(PointerEventData data) { }
	// RVA: 0x2f984e0 VA: 0x75955b04e0
	public Void OnDrag(PointerEventData data) { }
	// RVA: 0x2f9863c VA: 0x75955b063c
	public Void .ctor() { }
}
```