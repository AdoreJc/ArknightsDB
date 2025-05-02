# TouchInputController

**Namespace:** `BitBenderGames`


## Fields

- `Boolean expertModeEnabled`

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

- `Boolean isInputOnLockedArea`

- `Single timeSinceDragStart`

- `Boolean isClickPrevented`

- `Boolean isFingerDown`


## Properties

- `Boolean LongTapStartsDrag`

- `Boolean IsInputOnLockedArea`


## Methods

- `Void set_DragFinalMomentumVector(List`1)`

- `Boolean get_LongTapStartsDrag()`

- `Boolean get_IsInputOnLockedArea()`

- `Void set_IsInputOnLockedArea(Boolean)`

- `Void Awake()`

- `Void OnEventTriggerPointerDown(BaseEventData)`

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
// Namespace : BitBenderGames
public class TouchInputController : AbstractTouchInputController
{
	private Boolean expertModeEnabled; // 0x70
	private Single clickDurationThreshold; // 0x74
	private Single doubleclickDurationThreshold; // 0x78
	private Single tiltMoveDotTreshold; // 0x7c
	private Single tiltHorizontalDotThreshold; // 0x80
	private Single dragStartDistanceThresholdRelative; // 0x84
	private Boolean longTapStartsDrag; // 0x88
	private Single lastFingerDownTimeReal; // 0x8c
	private Single lastClickTimeReal; // 0x90
	private Boolean wasFingerDownLastFrame; // 0x94
	private Vector3 lastFinger0DownPos; // 0x98
	private const Single dragDurationThreshold; // 0x0
	private Boolean isDragging; // 0xa4
	private Vector3 dragStartPos; // 0xa8
	private Vector3 dragStartOffset; // 0xb4
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
	private Boolean isInputOnLockedArea; // 0xff
	private Single timeSinceDragStart; // 0x100
	private Boolean isClickPrevented; // 0x104
	private Boolean isFingerDown; // 0x105

	private List`1 DragFinalMomentumVector { get; set; }
	public Boolean LongTapStartsDrag { get; }
	public Boolean IsInputOnLockedArea { get; set; }

	// RVA: 0x2c2c128 VA: 0x7595244128
	private List`1 get_DragFinalMomentumVector() { }
	// RVA: 0x2c2c130 VA: 0x7595244130
	private Void set_DragFinalMomentumVector(List`1 value) { }
	// RVA: 0x2c2c138 VA: 0x7595244138
	public Boolean get_LongTapStartsDrag() { }
	// RVA: 0x2c2c140 VA: 0x7595244140
	public Boolean get_IsInputOnLockedArea() { }
	// RVA: 0x2c2c148 VA: 0x7595244148
	public Void set_IsInputOnLockedArea(Boolean value) { }
	// RVA: 0x2c2c154 VA: 0x7595244154
	public Void Awake() { }
	// RVA: 0x2c2c4d8 VA: 0x75952444d8
	public Void OnEventTriggerPointerDown(BaseEventData baseEventData) { }
	// RVA: 0x2c2c4e4 VA: 0x75952444e4
	public Void Update() { }
	// RVA: 0x2c2cab4 VA: 0x7595244ab4
	private Void StartPinch() { }
	// RVA: 0x2c2cda0 VA: 0x7595244da0
	private Void UpdatePinch() { }
	// RVA: 0x2c2db60 VA: 0x7595245b60
	private Single GetPinchDistance(Vector3 pos0, Vector3 pos1) { }
	// RVA: 0x2c2cd28 VA: 0x7595244d28
	private Void StopPinch() { }
	// RVA: 0x2c2d808 VA: 0x7595245808
	private Void DragStart(Vector3 pos, Boolean isLongTap, Boolean isInitialDrag) { }
	// RVA: 0x2c2d8ac VA: 0x75952458ac
	private Void DragUpdate(Vector3 pos) { }
	// RVA: 0x2c2d9b8 VA: 0x75952459b8
	private Void DragStop(Vector3 pos) { }
	// RVA: 0x2c2db18 VA: 0x7595245b18
	private Void FingerDown(Vector3 pos) { }
	// RVA: 0x2c2db3c VA: 0x7595245b3c
	private Void FingerUp() { }
	// RVA: 0x2c2dbc0 VA: 0x7595245bc0
	private Vector3 GetTouchPositionRelative(Vector3 touchPosScreen) { }
	// RVA: 0x2c2d770 VA: 0x7595245770
	private Single GetRelativeDragDistance(Vector3 pos0, Vector3 pos1) { }
	// RVA: 0x2c2dc10 VA: 0x7595245c10
	public Void .ctor() { }
}
```