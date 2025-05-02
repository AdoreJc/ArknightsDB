# DemoController

**Namespace:** `BitBenderGames`


## Fields

- `Text textInfo`

- `Text textDetail`

- `TouchInputController touchInputController`

- `MobileTouchCamera mobileTouchCamera`

- `MobilePickingController mobilePickingController`

- `Camera cam`

- `Coroutine coroutineHideInfoText`

- `Transform selectedPickableTransform`

- `Single introTextOnScreenTime`


## Methods

- `Void Awake()`

- `Void OnPickItem(RaycastHit)`

- `Void OnPickItem2D(RaycastHit2D)`

- `Void OnPickableTransformSelected(Transform)`

- `Void OnPickableTransformSelectedExtended(PickableSelectedData)`

- `Void OnPickableTransformDeselected(Transform)`

- `Void OnPickableTransformMoveStarted(Transform)`

- `Void OnPickableTransformMoved(Transform)`

- `Void OnPickableTransformMoveEnded(Vector3, Transform)`

- `Void SetItemColor(Transform, Color)`

- `Void RevertToOriginalItemColor(Transform)`

- `Boolean GetTransformPositionValid(Transform)`

- `IEnumerator AnimateScaleForSelection(Transform)`

- `Void SetCameraModeOrtho()`

- `Void SetCameraModePerspective()`

- `Void SetCameraModePerspectiveTranslation()`

- `Void ResetCamPosition(Single)`

- `Void SetSnapAngleStraight()`

- `Void SetSnapAngleDiagonal()`

- `Void SetSnappingEnabled(Boolean)`

- `Void SetRotationEnabled(Boolean)`

- `Void SetTiltEnabled(Boolean)`

- `Void ToggleGameObjectActive(GameObject)`

- `Void ToggleCamAngle(Boolean)`

- `Void SetInputOnLockedArea()`

- `Void ShowInfoText(String, Single)`

- `IEnumerator HideInfoText(Single)`

- `Void SetTextDetail(String)`

- `Void OnInputClick(Vector3, Boolean, Boolean)`

- `Void OnPinchUpdate(PinchUpdateData)`

- `Void OnPinchStop()`

- `Void OnPinchStart(Vector3, Single)`

- `Void OnFingerDown(Vector3)`

- `Void OnDragUpdate(Vector3, Vector3, Vector3)`

- `Void OnDragStop(Vector3, Vector3)`

- `Void OnDragStart(Vector3, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : BitBenderGames
public class DemoController : MonoBehaviour
{
	private Text textInfo; // 0x18
	private Text textDetail; // 0x20
	private TouchInputController touchInputController; // 0x28
	private MobileTouchCamera mobileTouchCamera; // 0x30
	private MobilePickingController mobilePickingController; // 0x38
	private Camera cam; // 0x40
	private Coroutine coroutineHideInfoText; // 0x48
	private Transform selectedPickableTransform; // 0x50
	private Dictionary`2 originalItemColorCache; // 0x58
	public Single introTextOnScreenTime; // 0x60


	// RVA: 0x2c1ec80 VA: 0x7595236c80
	public Void Awake() { }
	// RVA: 0x2c1fa0c VA: 0x7595237a0c
	public Void OnPickItem(RaycastHit hitInfo) { }
	// RVA: 0x2c1fb14 VA: 0x7595237b14
	public Void OnPickItem2D(RaycastHit2D hitInfo2D) { }
	// RVA: 0x2c1fc1c VA: 0x7595237c1c
	public Void OnPickableTransformSelected(Transform pickableTransform) { }
	// RVA: 0x2c20060 VA: 0x7595238060
	public Void OnPickableTransformSelectedExtended(PickableSelectedData data) { }
	// RVA: 0x2c20174 VA: 0x7595238174
	public Void OnPickableTransformDeselected(Transform pickableTransform) { }
	// RVA: 0x2c20428 VA: 0x7595238428
	public Void OnPickableTransformMoveStarted(Transform pickableTransform) { }
	// RVA: 0x2c2043c VA: 0x759523843c
	public Void OnPickableTransformMoved(Transform pickableTransform) { }
	// RVA: 0x2c204e0 VA: 0x75952384e0
	public Void OnPickableTransformMoveEnded(Vector3 startPos, Transform pickableTransform) { }
	// RVA: 0x2c1fdc4 VA: 0x7595237dc4
	private Void SetItemColor(Transform itemTransform, Color color) { }
	// RVA: 0x2c2028c VA: 0x759523828c
	private Void RevertToOriginalItemColor(Transform itemTransform) { }
	// RVA: 0x2c2056c VA: 0x759523856c
	private Boolean GetTransformPositionValid(Transform pickableTransform) { }
	// RVA: 0x2c1fd50 VA: 0x7595237d50
	private IEnumerator AnimateScaleForSelection(Transform pickableTransform) { }
	// RVA: 0x2c20a98 VA: 0x7595238a98
	public Void SetCameraModeOrtho() { }
	// RVA: 0x2c20c98 VA: 0x7595238c98
	public Void SetCameraModePerspective() { }
	// RVA: 0x2c20d04 VA: 0x7595238d04
	public Void SetCameraModePerspectiveTranslation() { }
	// RVA: 0x2c20c28 VA: 0x7595238c28
	private Void ResetCamPosition(Single distance) { }
	// RVA: 0x2c20e20 VA: 0x7595238e20
	public Void SetSnapAngleStraight() { }
	// RVA: 0x2c20e3c VA: 0x7595238e3c
	public Void SetSnapAngleDiagonal() { }
	// RVA: 0x2c20e5c VA: 0x7595238e5c
	public Void SetSnappingEnabled(Boolean flag) { }
	// RVA: 0x2c20e7c VA: 0x7595238e7c
	public Void SetRotationEnabled(Boolean flag) { }
	// RVA: 0x2c20e9c VA: 0x7595238e9c
	public Void SetTiltEnabled(Boolean flag) { }
	// RVA: 0x2c20ebc VA: 0x7595238ebc
	public Void ToggleGameObjectActive(GameObject go) { }
	// RVA: 0x2c20ef0 VA: 0x7595238ef0
	public Void ToggleCamAngle(Boolean angle) { }
	// RVA: 0x2c20f14 VA: 0x7595238f14
	public Void SetInputOnLockedArea() { }
	// RVA: 0x2c1f904 VA: 0x7595237904
	private Void ShowInfoText(String message, Single onScreenTime) { }
	// RVA: 0x2c20f34 VA: 0x7595238f34
	private IEnumerator HideInfoText(Single delay) { }
	// RVA: 0x2c20fe0 VA: 0x7595238fe0
	private Void SetTextDetail(String message) { }
	// RVA: 0x2c21080 VA: 0x7595239080
	private Void OnInputClick(Vector3 clickScreenPosition, Boolean isDoubleClick, Boolean isLongTap) { }
	// RVA: 0x2c21600 VA: 0x7595239600
	private Void OnPinchUpdate(PinchUpdateData pinchUpdateData) { }
	// RVA: 0x2c218e8 VA: 0x75952398e8
	private Void OnPinchStop() { }
	// RVA: 0x2c21930 VA: 0x7595239930
	private Void OnPinchStart(Vector3 pinchCenter, Single pinchDistance) { }
	// RVA: 0x2c21b88 VA: 0x7595239b88
	private Void OnFingerDown(Vector3 screenPosition) { }
	// RVA: 0x2c21c40 VA: 0x7595239c40
	private Void OnDragUpdate(Vector3 dragPosStart, Vector3 dragPosCurrent, Vector3 correctionOffset) { }
	// RVA: 0x2c21eb0 VA: 0x7595239eb0
	private Void OnDragStop(Vector3 dragStopPos, Vector3 dragFinalMomentum) { }
	// RVA: 0x2c22120 VA: 0x759523a120
	private Void OnDragStart(Vector3 pos, Boolean isLongTap) { }
	// RVA: 0x2c223a0 VA: 0x759523a3a0
	public Void .ctor() { }
}
```