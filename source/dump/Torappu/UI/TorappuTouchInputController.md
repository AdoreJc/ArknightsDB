# TorappuTouchInputController

**Namespace:** `Torappu.UI`


## Fields

- `Single clickDurationThreshold`

- `Single doubleclickDurationThreshold`

- `Single tiltMoveDotTreshold`

- `Single tiltHorizontalDotThreshold`

- `Single dragStartDistanceThresholdRelative`

- `Boolean longTapStartsDrag`

- `Single lastFingerDownTimeReal`

- `Single lastClickTimeReal`

- `Boolean wasFingerDownLastFrame`

- `Vector3 lastFinger0DownPos`

- `Boolean isDragging`

- `Vector3 dragStartPos`

- `Vector3 dragStartOffset`

- `Single pinchStartDistance`

- `Vector3 pinchRotationVectorStart`

- `Vector3 pinchVectorLastFrame`

- `Single totalFingerMovement`

- `Boolean wasDraggingLastFrame`

- `Boolean wasPinchingLastFrame`

- `Boolean isPinching`

- `Single timeSinceDragStart`

- `Boolean isClickPrevented`

- `Boolean isFingerDown`

- `GameObject _touchCameraContent`

- `GameObject _touchCameraRaycastBlocker`

- `Boolean <AllowDragOrPinch>k__BackingField`


## Properties

- `Boolean LongTapStartsDrag`

- `Boolean AllowDragOrPinch`


## Methods

- `Void set_DragFinalMomentumVector(List`1)`

- `Boolean get_LongTapStartsDrag()`

- `Boolean get_AllowDragOrPinch()`

- `Void set_AllowDragOrPinch(Boolean)`

- `Boolean _CheckTouchLegal(Vector3)`

- `Void _UpdateTouchInfo()`

- `Void _SetBlockerActive(Boolean)`

- `Void Awake()`

- `Void Update()`

- `Void StartPinch()`

- `Void UpdatePinch()`

- `Single GetPinchDistance(Vector3, Vector3)`

- `Void StopPinch()`

- `Void DragStart(Vector3, Boolean, Boolean)`

- `Void DragUpdate(Vector3)`

- `Void DragStop(Vector3)`

- `Void FingerDown(Vector3)`

- `Void FingerUp()`

- `Vector3 GetTouchPositionRelative(Vector3)`

- `Single GetRelativeDragDistance(Vector3, Vector3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TorappuTouchInputController : AbstractTouchInputController
{
	private Single clickDurationThreshold; // 0x70
	private Single doubleclickDurationThreshold; // 0x74
	private Single tiltMoveDotTreshold; // 0x78
	private Single tiltHorizontalDotThreshold; // 0x7c
	private Single dragStartDistanceThresholdRelative; // 0x80
	private Boolean longTapStartsDrag; // 0x84
	private Single lastFingerDownTimeReal; // 0x88
	private Single lastClickTimeReal; // 0x8c
	private Boolean wasFingerDownLastFrame; // 0x90
	private Vector3 lastFinger0DownPos; // 0x94
	private const Single dragDurationThreshold; // 0x0
	private Boolean isDragging; // 0xa0
	private Vector3 dragStartPos; // 0xa4
	private Vector3 dragStartOffset; // 0xb0
	private List`1 <DragFinalMomentumVector>k__BackingField; // 0xc0
	private const Int32 momentumSamplesCount; // 0x0
	private Single pinchStartDistance; // 0xc8
	private List`1 pinchStartPositions; // 0xd0
	private List`1 touchPositionLastFrame; // 0xd8
	private Vector3 pinchRotationVectorStart; // 0xe0
	private Vector3 pinchVectorLastFrame; // 0xec
	private Single totalFingerMovement; // 0xf8
	private Boolean wasDraggingLastFrame; // 0xfc
	private Boolean wasPinchingLastFrame; // 0xfd
	private Boolean isPinching; // 0xfe
	private Single timeSinceDragStart; // 0x100
	private Boolean isClickPrevented; // 0x104
	private Boolean isFingerDown; // 0x105
	private GameObject _touchCameraContent; // 0x108
	private GameObject _touchCameraRaycastBlocker; // 0x110
	private List`1 m_touchIdList; // 0x118
	private List`1 m_endedTouchIds; // 0x120
	private List`1 m_legalTouches; // 0x128
	private Dictionary`2 m_touchLegalInfo; // 0x130
	private List`1 m_raycastResults; // 0x138
	private Boolean <AllowDragOrPinch>k__BackingField; // 0x140

	private List`1 DragFinalMomentumVector { get; set; }
	public Boolean LongTapStartsDrag { get; }
	public Boolean AllowDragOrPinch { get; set; }

	// RVA: 0x21cd430 VA: 0x75947e5430
	private List`1 get_DragFinalMomentumVector() { }
	// RVA: 0x21cd438 VA: 0x75947e5438
	private Void set_DragFinalMomentumVector(List`1 value) { }
	// RVA: 0x21cd440 VA: 0x75947e5440
	public Boolean get_LongTapStartsDrag() { }
	// RVA: 0x21cd448 VA: 0x75947e5448
	public Boolean get_AllowDragOrPinch() { }
	// RVA: 0x21cd450 VA: 0x75947e5450
	public Void set_AllowDragOrPinch(Boolean value) { }
	// RVA: 0x21cd45c VA: 0x75947e545c
	private Boolean _CheckTouchLegal(Vector3 touchPosition) { }
	// RVA: 0x21cd720 VA: 0x75947e5720
	private Void _UpdateTouchInfo() { }
	// RVA: 0x21cde68 VA: 0x75947e5e68
	private Void _SetBlockerActive(Boolean active) { }
	// RVA: 0x21cde78 VA: 0x75947e5e78
	public Void Awake() { }
	// RVA: 0x21ce210 VA: 0x75947e6210
	public Void Update() { }
	// RVA: 0x21ce884 VA: 0x75947e6884
	private Void StartPinch() { }
	// RVA: 0x21ceb84 VA: 0x75947e6b84
	private Void UpdatePinch() { }
	// RVA: 0x21cf960 VA: 0x75947e7960
	private Single GetPinchDistance(Vector3 pos0, Vector3 pos1) { }
	// RVA: 0x21ceb08 VA: 0x75947e6b08
	private Void StopPinch() { }
	// RVA: 0x21cf5f8 VA: 0x75947e75f8
	private Void DragStart(Vector3 pos, Boolean isLongTap, Boolean isInitialDrag) { }
	// RVA: 0x21cf6a8 VA: 0x75947e76a8
	private Void DragUpdate(Vector3 pos) { }
	// RVA: 0x21cf7b4 VA: 0x75947e77b4
	private Void DragStop(Vector3 pos) { }
	// RVA: 0x21cf91c VA: 0x75947e791c
	private Void FingerDown(Vector3 pos) { }
	// RVA: 0x21cf940 VA: 0x75947e7940
	private Void FingerUp() { }
	// RVA: 0x21cf9c0 VA: 0x75947e79c0
	private Vector3 GetTouchPositionRelative(Vector3 touchPosScreen) { }
	// RVA: 0x21cf560 VA: 0x75947e7560
	private Single GetRelativeDragDistance(Vector3 pos0, Vector3 pos1) { }
	// RVA: 0x21cfa10 VA: 0x75947e7a10
	public Void .ctor() { }
}
```