# ETCJoystick

**Namespace:** ` `


## Fields

- `OnMoveStartHandler onMoveStart`

- `OnMoveHandler onMove`

- `OnMoveSpeedHandler onMoveSpeed`

- `OnMoveEndHandler onMoveEnd`

- `OnTouchStartHandler onTouchStart`

- `OnTouchUpHandler onTouchUp`

- `OnDownUpHandler OnDownUp`

- `OnDownDownHandler OnDownDown`

- `OnDownLeftHandler OnDownLeft`

- `OnDownRightHandler OnDownRight`

- `OnDownUpHandler OnPressUp`

- `OnDownDownHandler OnPressDown`

- `OnDownLeftHandler OnPressLeft`

- `OnDownRightHandler OnPressRight`

- `JoystickType joystickType`

- `Boolean allowJoystickOverTouchPad`

- `RadiusBase radiusBase`

- `Single radiusBaseValue`

- `ETCAxis axisX`

- `ETCAxis axisY`

- `RectTransform thumb`

- `JoystickArea joystickArea`

- `RectTransform userArea`

- `Boolean isTurnAndMove`

- `Single tmSpeed`

- `Single tmAdditionnalRotation`

- `AnimationCurve tmMoveCurve`

- `Boolean tmLockInJump`

- `Vector3 tmLastMove`

- `Boolean <isStarted>k__BackingField`

- `Vector2 thumbPosition`

- `Boolean isDynamicActif`

- `Vector2 tmpAxis`

- `Vector2 OldTmpAxis`

- `Boolean isOnTouch`

- `Boolean isNoReturnThumb`

- `Vector2 noReturnPosition`

- `Vector2 noReturnOffset`

- `Boolean isNoOffsetThumb`


## Properties

- `Boolean isStarted`

- `Boolean IsNoReturnThumb`

- `Boolean IsNoOffsetThumb`


## Methods

- `Void set_isStarted(Boolean)`

- `Boolean get_isStarted()`

- `Boolean get_IsNoReturnThumb()`

- `Void set_IsNoReturnThumb(Boolean)`

- `Boolean get_IsNoOffsetThumb()`

- `Void set_IsNoOffsetThumb(Boolean)`

- `Void InitCameraLookAt()`

- `Void OnPointerEnter(PointerEventData)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void OnUp(Boolean)`

- `Void UpdateJoystick()`

- `Boolean isTouchOverJoystickArea(ref, ref)`

- `Boolean isScreenPointOverArea(Vector2, ref)`

- `Int32 GetTouchCount()`

- `Single GetRadius()`

- `Void DoTurnAndMove()`

- `Void InitCurve()`

- `Void InitTurnMoveCurve()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ETCJoystick : ETCBase, IPointerEnterHandler, IEventSystemHandler, IDragHandler, IBeginDragHandler, IPointerDownHandler, IPointerUpHandler
{
	public OnMoveStartHandler onMoveStart; // 0xd8
	public OnMoveHandler onMove; // 0xe0
	public OnMoveSpeedHandler onMoveSpeed; // 0xe8
	public OnMoveEndHandler onMoveEnd; // 0xf0
	public OnTouchStartHandler onTouchStart; // 0xf8
	public OnTouchUpHandler onTouchUp; // 0x100
	public OnDownUpHandler OnDownUp; // 0x108
	public OnDownDownHandler OnDownDown; // 0x110
	public OnDownLeftHandler OnDownLeft; // 0x118
	public OnDownRightHandler OnDownRight; // 0x120
	public OnDownUpHandler OnPressUp; // 0x128
	public OnDownDownHandler OnPressDown; // 0x130
	public OnDownLeftHandler OnPressLeft; // 0x138
	public OnDownRightHandler OnPressRight; // 0x140
	public JoystickType joystickType; // 0x148
	public Boolean allowJoystickOverTouchPad; // 0x14c
	public RadiusBase radiusBase; // 0x150
	public Single radiusBaseValue; // 0x154
	public ETCAxis axisX; // 0x158
	public ETCAxis axisY; // 0x160
	public RectTransform thumb; // 0x168
	public JoystickArea joystickArea; // 0x170
	public RectTransform userArea; // 0x178
	public Boolean isTurnAndMove; // 0x180
	public Single tmSpeed; // 0x184
	public Single tmAdditionnalRotation; // 0x188
	public AnimationCurve tmMoveCurve; // 0x190
	public Boolean tmLockInJump; // 0x198
	private Vector3 tmLastMove; // 0x19c
	private Boolean <isStarted>k__BackingField; // 0x1a8
	private Vector2 thumbPosition; // 0x1ac
	private Boolean isDynamicActif; // 0x1b4
	private Vector2 tmpAxis; // 0x1b8
	private Vector2 OldTmpAxis; // 0x1c0
	private Boolean isOnTouch; // 0x1c8
	private Boolean isNoReturnThumb; // 0x1c9
	private Vector2 noReturnPosition; // 0x1cc
	private Vector2 noReturnOffset; // 0x1d4
	private Boolean isNoOffsetThumb; // 0x1dc

	public Boolean isStarted { get; set; }
	public Boolean IsNoReturnThumb { get; set; }
	public Boolean IsNoOffsetThumb { get; set; }

	// RVA: 0x1b36280 VA: 0x759414e280
	private Void set_isStarted(Boolean value) { }
	// RVA: 0x1b3628c VA: 0x759414e28c
	public Boolean get_isStarted() { }
	// RVA: 0x1b36294 VA: 0x759414e294
	public Boolean get_IsNoReturnThumb() { }
	// RVA: 0x1b3629c VA: 0x759414e29c
	public Void set_IsNoReturnThumb(Boolean value) { }
	// RVA: 0x1b362a8 VA: 0x759414e2a8
	public Boolean get_IsNoOffsetThumb() { }
	// RVA: 0x1b362b0 VA: 0x759414e2b0
	public Void set_IsNoOffsetThumb(Boolean value) { }
	// RVA: 0x1b362bc VA: 0x759414e2bc
	public Void .ctor() { }
	// RVA: 0x1b36400 VA: 0x759414e400
	protected override Void Awake() { }
	// RVA: 0x1b364c8 VA: 0x759414e4c8
	public override Void Start() { }
	// RVA: 0x1b36884 VA: 0x759414e884
	public override Void Update() { }
	// RVA: 0x1b36c18 VA: 0x759414ec18
	public override Void LateUpdate() { }
	// RVA: 0x1b36724 VA: 0x759414e724
	private Void InitCameraLookAt() { }
	// RVA: 0x1b36c90 VA: 0x759414ec90
	protected override Void UpdateControlState() { }
	// RVA: 0x1b3750c VA: 0x759414f50c
	public Void OnPointerEnter(PointerEventData eventData) { }
	// RVA: 0x1b375f8 VA: 0x759414f5f8
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x1b3796c VA: 0x759414f96c
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x1b37650 VA: 0x759414f650
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x1b375c8 VA: 0x759414f5c8
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x1b37370 VA: 0x759414f370
	private Void OnUp(Boolean real) { }
	// RVA: 0x1b379d8 VA: 0x759414f9d8
	protected override Void DoActionBeforeEndOfFrame() { }
	// RVA: 0x1b36cb0 VA: 0x759414ecb0
	private Void UpdateJoystick() { }
	// RVA: 0x1b36ad0 VA: 0x759414ead0
	private Boolean isTouchOverJoystickArea(ref Vector2 localPosition, ref Vector2 screenPosition) { }
	// RVA: 0x1b37d44 VA: 0x759414fd44
	private Boolean isScreenPointOverArea(Vector2 screenPosition, ref Vector2 localPosition) { }
	// RVA: 0x1b36c10 VA: 0x759414ec10
	private Int32 GetTouchCount() { }
	// RVA: 0x1b37970 VA: 0x759414f970
	public Single GetRadius() { }
	// RVA: 0x1b37f24 VA: 0x759414ff24
	protected override Void SetActivated() { }
	// RVA: 0x1b37fa0 VA: 0x759414ffa0
	protected override Void SetVisible(Boolean visible) { }
	// RVA: 0x1b37a00 VA: 0x759414fa00
	private Void DoTurnAndMove() { }
	// RVA: 0x1b38068 VA: 0x7594150068
	public Void InitCurve() { }
	// RVA: 0x1b38098 VA: 0x7594150098
	public Void InitTurnMoveCurve() { }
}
```