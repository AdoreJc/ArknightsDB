# MobilePickingController

**Namespace:** `BitBenderGames`


## Fields

- `Boolean snapToGrid`

- `Single snapUnitSize`

- `Vector2 snapOffset`

- `SnapAngle snapAngle`

- `Boolean isMultiSelectionEnabled`

- `Boolean requireLongTapForMove`

- `UnityEventWithTransform OnPickableTransformSelected`

- `UnityEventWithPickableSelected OnPickableTransformSelectedExtended`

- `UnityEventWithTransform OnPickableTransformDeselected`

- `UnityEventWithTransform OnPickableTransformMoveStarted`

- `UnityEventWithTransform OnPickableTransformMoved`

- `UnityEventWithPositionAndTransform OnPickableTransformMoveEnded`

- `Boolean expertModeEnabled`

- `Boolean deselectPreviousColliderOnClick`

- `Boolean repeatEventSelectedOnClick`

- `Boolean useLegacyTransformMovedEventOrder`

- `TouchInputController touchInputController`

- `MobileTouchCamera mobileTouchCam`

- `Boolean isSelectedViaLongTap`

- `MobileTouchPickable <CurrentlyDraggedPickable>k__BackingField`

- `Vector3 draggedTransformOffset`

- `Vector3 draggedTransformHeightOffset`

- `Vector3 draggedItemCustomOffset`

- `Vector3 currentlyDraggedTransformPosition`

- `Vector3 currentDragStartPos`

- `Boolean invokeMoveStartedOnDrag`

- `Boolean invokeMoveEndedOnDrag`

- `Vector3 itemInitialDragOffsetWorld`

- `Boolean isManualSelectionRequest`


## Properties

- `Component SelectedCollider`

- `MobileTouchPickable CurrentlyDraggedPickable`

- `Transform CurrentlyDraggedTransform`

- `Boolean SnapToGrid`

- `SnapAngle SnapAngle`

- `Single SnapUnitSize`

- `Vector2 SnapOffset`

- `Boolean IsMultiSelectionEnabled`


## Methods

- `Component get_SelectedCollider()`

- `Void set_SelectedColliders(List`1)`

- `MobileTouchPickable get_CurrentlyDraggedPickable()`

- `Void set_CurrentlyDraggedPickable(MobileTouchPickable)`

- `Transform get_CurrentlyDraggedTransform()`

- `Boolean get_SnapToGrid()`

- `Void set_SnapToGrid(Boolean)`

- `SnapAngle get_SnapAngle()`

- `Void set_SnapAngle(SnapAngle)`

- `Single get_SnapUnitSize()`

- `Void set_SnapUnitSize(Single)`

- `Vector2 get_SnapOffset()`

- `Void set_SnapOffset(Vector2)`

- `Boolean get_IsMultiSelectionEnabled()`

- `Void set_IsMultiSelectionEnabled(Boolean)`

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Void LateUpdate()`

- `Void SelectCollider(Component)`

- `Void DeselectSelectedCollider()`

- `Boolean Deselect(Component)`

- `Int32 DeselectAll()`

- `Component GetClosestColliderAtScreenPoint(Vector3, out)`

- `Void RequestDragPickable(Component)`

- `Vector3 GetFinger0PosWorld()`

- `Void SelectColliderInternal(Component, Boolean, Boolean)`

- `Void InputControllerOnInputClick(Vector3, Boolean, Boolean)`

- `Void RequestDragPickable(Vector3)`

- `Void RequestDragPickable(Component, Vector2, Vector3)`

- `Void InputControllerOnFingerDown(Vector3)`

- `Void InputControllerOnFingerUp()`

- `Vector3 ComputeDragPosition(Vector3, Boolean)`

- `Void InputControllerOnDragStart(Vector3, Boolean)`

- `Void InputControllerOnDragUpdate(Vector3, Vector3, Vector3)`

- `Void InvokePickableMoveStart()`

- `Single ComputeDistance2d(Single, Single, Single, Single)`

- `Void InputControllerOnDragStop(Vector3, Vector3)`

- `Void EndPickableTransformMove()`

- `Vector3 ClampDragPosition(MobileTouchPickable, Vector3)`

- `Void RotateVector2(ref, ref, Single)`

- `Single GetPositionSnapped(Single, Single)`

- `Void OnSelectedColliderChanged(SelectionAction, MobileTouchPickable)`

- `Void OnSelectedColliderChangedExtended(SelectionAction, MobileTouchPickable, Boolean, Boolean)`

- `Void InvokeTransformActionSafe(UnityEventWithTransform, Transform)`

- `Void InvokeGenericActionSafe(T1, T2)`

- `Void Select(Component, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : BitBenderGames
public class MobilePickingController : MonoBehaviour
{
	private Boolean snapToGrid; // 0x18
	private Single snapUnitSize; // 0x1c
	private Vector2 snapOffset; // 0x20
	private SnapAngle snapAngle; // 0x28
	private Boolean isMultiSelectionEnabled; // 0x2c
	private Boolean requireLongTapForMove; // 0x2d
	private UnityEventWithTransform OnPickableTransformSelected; // 0x30
	private UnityEventWithPickableSelected OnPickableTransformSelectedExtended; // 0x38
	private UnityEventWithTransform OnPickableTransformDeselected; // 0x40
	private UnityEventWithTransform OnPickableTransformMoveStarted; // 0x48
	private UnityEventWithTransform OnPickableTransformMoved; // 0x50
	private UnityEventWithPositionAndTransform OnPickableTransformMoveEnded; // 0x58
	private Boolean expertModeEnabled; // 0x60
	private Boolean deselectPreviousColliderOnClick; // 0x61
	private Boolean repeatEventSelectedOnClick; // 0x62
	private Boolean useLegacyTransformMovedEventOrder; // 0x63
	private TouchInputController touchInputController; // 0x68
	private MobileTouchCamera mobileTouchCam; // 0x70
	private List`1 <SelectedColliders>k__BackingField; // 0x78
	private Boolean isSelectedViaLongTap; // 0x80
	private MobileTouchPickable <CurrentlyDraggedPickable>k__BackingField; // 0x88
	private Vector3 draggedTransformOffset; // 0x90
	private Vector3 draggedTransformHeightOffset; // 0x9c
	private Vector3 draggedItemCustomOffset; // 0xa8
	public const Single snapAngleDiagonal; // 0x0
	private Vector3 currentlyDraggedTransformPosition; // 0xb4
	private const Single transformMovedDistanceThreshold; // 0x0
	private Vector3 currentDragStartPos; // 0xc0
	private Boolean invokeMoveStartedOnDrag; // 0xcc
	private Boolean invokeMoveEndedOnDrag; // 0xcd
	private Vector3 itemInitialDragOffsetWorld; // 0xd0
	private Boolean isManualSelectionRequest; // 0xdc
	private Dictionary`2 selectionPositionOffsets; // 0xe0

	private Component SelectedCollider { get; }
	public List`1 SelectedColliders { get; set; }
	public MobileTouchPickable CurrentlyDraggedPickable { get; set; }
	private Transform CurrentlyDraggedTransform { get; }
	public Boolean SnapToGrid { get; set; }
	public SnapAngle SnapAngle { get; set; }
	public Single SnapUnitSize { get; set; }
	public Vector2 SnapOffset { get; set; }
	public Boolean IsMultiSelectionEnabled { get; set; }

	// RVA: 0x2c227c4 VA: 0x759523a7c4
	private Component get_SelectedCollider() { }
	// RVA: 0x2c2283c VA: 0x759523a83c
	public List`1 get_SelectedColliders() { }
	// RVA: 0x2c22844 VA: 0x759523a844
	private Void set_SelectedColliders(List`1 value) { }
	// RVA: 0x2c2284c VA: 0x759523a84c
	public MobileTouchPickable get_CurrentlyDraggedPickable() { }
	// RVA: 0x2c22854 VA: 0x759523a854
	private Void set_CurrentlyDraggedPickable(MobileTouchPickable value) { }
	// RVA: 0x2c2285c VA: 0x759523a85c
	private Transform get_CurrentlyDraggedTransform() { }
	// RVA: 0x2c228dc VA: 0x759523a8dc
	public Boolean get_SnapToGrid() { }
	// RVA: 0x2c228e4 VA: 0x759523a8e4
	public Void set_SnapToGrid(Boolean value) { }
	// RVA: 0x2c228f0 VA: 0x759523a8f0
	public SnapAngle get_SnapAngle() { }
	// RVA: 0x2c228f8 VA: 0x759523a8f8
	public Void set_SnapAngle(SnapAngle value) { }
	// RVA: 0x2c22900 VA: 0x759523a900
	public Single get_SnapUnitSize() { }
	// RVA: 0x2c22908 VA: 0x759523a908
	public Void set_SnapUnitSize(Single value) { }
	// RVA: 0x2c22910 VA: 0x759523a910
	public Vector2 get_SnapOffset() { }
	// RVA: 0x2c22918 VA: 0x759523a918
	public Void set_SnapOffset(Vector2 value) { }
	// RVA: 0x2c22920 VA: 0x759523a920
	public Boolean get_IsMultiSelectionEnabled() { }
	// RVA: 0x2c22928 VA: 0x759523a928
	public Void set_IsMultiSelectionEnabled(Boolean value) { }
	// RVA: 0x2c22bc4 VA: 0x759523abc4
	public Void Awake() { }
	// RVA: 0x2c22d90 VA: 0x759523ad90
	public Void Start() { }
	// RVA: 0x2c23174 VA: 0x759523b174
	public Void OnDestroy() { }
	// RVA: 0x2c23558 VA: 0x759523b558
	public Void LateUpdate() { }
	// RVA: 0x2c23588 VA: 0x759523b588
	public Void SelectCollider(Component collider) { }
	// RVA: 0x2c23910 VA: 0x759523b910
	public Void DeselectSelectedCollider() { }
	// RVA: 0x2c2392c VA: 0x759523b92c
	private Boolean Deselect(Component colliderComponent) { }
	// RVA: 0x2c2293c VA: 0x759523a93c
	public Int32 DeselectAll() { }
	// RVA: 0x2c23a7c VA: 0x759523ba7c
	public Component GetClosestColliderAtScreenPoint(Vector3 screenPoint, out Vector3 intersectionPoint) { }
	// RVA: 0x2c23cb0 VA: 0x759523bcb0
	public Void RequestDragPickable(Component colliderComponent) { }
	// RVA: 0x2c245d4 VA: 0x759523c5d4
	public Vector3 GetFinger0PosWorld() { }
	// RVA: 0x2c23740 VA: 0x759523b740
	private Void SelectColliderInternal(Component colliderComponent, Boolean isDoubleClick, Boolean isLongTap) { }
	// RVA: 0x2c246d0 VA: 0x759523c6d0
	private Void InputControllerOnInputClick(Vector3 clickPosition, Boolean isDoubleClick, Boolean isLongTap) { }
	// RVA: 0x2c24718 VA: 0x759523c718
	private Void RequestDragPickable(Vector3 fingerDownPos) { }
	// RVA: 0x2c24070 VA: 0x759523c070
	private Void RequestDragPickable(Component colliderComponent, Vector2 fingerDownPos, Vector3 intersectionPoint) { }
	// RVA: 0x2c24a38 VA: 0x759523ca38
	private Void InputControllerOnFingerDown(Vector3 fingerDownPos) { }
	// RVA: 0x2c24a50 VA: 0x759523ca50
	private Void InputControllerOnFingerUp() { }
	// RVA: 0x2c248a4 VA: 0x759523c8a4
	private Vector3 ComputeDragPosition(Vector3 dragPosCurrent, Boolean clampToGrid) { }
	// RVA: 0x2c24c64 VA: 0x759523cc64
	private Void InputControllerOnDragStart(Vector3 clickPosition, Boolean isLongTap) { }
	// RVA: 0x2c24de8 VA: 0x759523cde8
	private Void InputControllerOnDragUpdate(Vector3 dragPosStart, Vector3 dragPosCurrent, Vector3 correctionOffset) { }
	// RVA: 0x2c2525c VA: 0x759523d25c
	private Void InvokePickableMoveStart() { }
	// RVA: 0x2c25290 VA: 0x759523d290
	private Single ComputeDistance2d(Single x0, Single y0, Single x1, Single y1) { }
	// RVA: 0x2c2530c VA: 0x759523d30c
	private Void InputControllerOnDragStop(Vector3 dragStopPos, Vector3 dragFinalMomentum) { }
	// RVA: 0x2c24a54 VA: 0x759523ca54
	private Void EndPickableTransformMove() { }
	// RVA: 0x2c24b3c VA: 0x759523cb3c
	private Vector3 ClampDragPosition(MobileTouchPickable draggedPickable, Vector3 position) { }
	// RVA: 0x2c25310 VA: 0x759523d310
	private Void RotateVector2(ref Single x, ref Single y, Single degrees) { }
	// RVA: 0x2c253e4 VA: 0x759523d3e4
	private Single GetPositionSnapped(Single position, Single snapOffset) { }
	// RVA: 0x2c239d0 VA: 0x759523b9d0
	private Void OnSelectedColliderChanged(SelectionAction selectionAction, MobileTouchPickable mobileTouchPickable) { }
	// RVA: 0x2c25500 VA: 0x759523d500
	private Void OnSelectedColliderChangedExtended(SelectionAction selectionAction, MobileTouchPickable mobileTouchPickable, Boolean isDoubleClick, Boolean isLongTap) { }
	// RVA: 0x2c252ac VA: 0x759523d2ac
	private Void InvokeTransformActionSafe(UnityEventWithTransform eventAction, Transform selectionTransform) { }
	// RVA: 0x VA: 0x0
	private Void InvokeGenericActionSafe(T1 eventAction, T2 eventArgs) { }
	// RVA: 0x2c235cc VA: 0x759523b5cc
	private Void Select(Component colliderComponent, Boolean isDoubleClick, Boolean isLongTap) { }
	// RVA: 0x2c2561c VA: 0x759523d61c
	public Void .ctor() { }
}
```