# FocusCameraOnItem

**Namespace:** `BitBenderGames`


## Fields

- `Single transitionDuration`

- `AnimationCurve transitionCurve`

- `MobileTouchCamera <MobileTouchCamera>k__BackingField`

- `Vector3 posTransitionStart`

- `Vector3 posTransitionEnd`

- `Quaternion rotTransitionStart`

- `Quaternion rotTransitionEnd`

- `Single zoomTransitionStart`

- `Single zoomTransitionEnd`

- `Single timeTransitionStart`

- `Boolean isTransitionStarted`


## Properties

- `MobileTouchCamera MobileTouchCamera`

- `Single TransitionDuration`


## Methods

- `MobileTouchCamera get_MobileTouchCamera()`

- `Void set_MobileTouchCamera(MobileTouchCamera)`

- `Single get_TransitionDuration()`

- `Void set_TransitionDuration(Single)`

- `Void Awake()`

- `Void LateUpdate()`

- `Void UpdateTransform()`

- `Void OnPickItem(RaycastHit)`

- `Void OnPickItem2D(RaycastHit2D)`

- `Void OnPickableTransformSelected(Transform)`

- `Void FocusCameraOnTransform(Transform)`

- `Void FocusCameraOnTransform(Vector3)`

- `Void FocusCameraOnTarget(Vector3)`

- `Single GetTiltFromRotation(Quaternion)`

- `Void FocusCameraOnTarget(Vector3, Quaternion, Single)`

- `Void SetTransform(Vector3, Quaternion, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : BitBenderGames
public class FocusCameraOnItem : MonoBehaviourWrapped
{
	private Single transitionDuration; // 0x28
	private AnimationCurve transitionCurve; // 0x30
	private MobileTouchCamera <MobileTouchCamera>k__BackingField; // 0x38
	private Vector3 posTransitionStart; // 0x40
	private Vector3 posTransitionEnd; // 0x4c
	private Quaternion rotTransitionStart; // 0x58
	private Quaternion rotTransitionEnd; // 0x68
	private Single zoomTransitionStart; // 0x78
	private Single zoomTransitionEnd; // 0x7c
	private Single timeTransitionStart; // 0x80
	private Boolean isTransitionStarted; // 0x84

	private MobileTouchCamera MobileTouchCamera { get; set; }
	public Single TransitionDuration { get; set; }

	// RVA: 0x2c2acc4 VA: 0x7595242cc4
	private MobileTouchCamera get_MobileTouchCamera() { }
	// RVA: 0x2c2accc VA: 0x7595242ccc
	private Void set_MobileTouchCamera(MobileTouchCamera value) { }
	// RVA: 0x2c2acd4 VA: 0x7595242cd4
	public Single get_TransitionDuration() { }
	// RVA: 0x2c2acdc VA: 0x7595242cdc
	public Void set_TransitionDuration(Single value) { }
	// RVA: 0x2c2ace4 VA: 0x7595242ce4
	public Void Awake() { }
	// RVA: 0x2c2ad44 VA: 0x7595242d44
	public Void LateUpdate() { }
	// RVA: 0x2c2addc VA: 0x7595242ddc
	private Void UpdateTransform() { }
	// RVA: 0x2c2af6c VA: 0x7595242f6c
	public Void OnPickItem(RaycastHit hitInfo) { }
	// RVA: 0x2c2b028 VA: 0x7595243028
	public Void OnPickItem2D(RaycastHit2D hitInfo2D) { }
	// RVA: 0x2c2b04c VA: 0x759524304c
	public Void OnPickableTransformSelected(Transform pickableTransform) { }
	// RVA: 0x2c2af90 VA: 0x7595242f90
	public Void FocusCameraOnTransform(Transform targetTransform) { }
	// RVA: 0x2c2b0e0 VA: 0x75952430e0
	public Void FocusCameraOnTransform(Vector3 targetPosition) { }
	// RVA: 0x2c2b050 VA: 0x7595243050
	public Void FocusCameraOnTarget(Vector3 targetPosition) { }
	// RVA: 0x2c2b350 VA: 0x7595243350
	private Single GetTiltFromRotation(Quaternion camRotation) { }
	// RVA: 0x2c2b0e4 VA: 0x75952430e4
	private Void FocusCameraOnTarget(Vector3 targetPosition, Quaternion targetRotation, Single targetZoom) { }
	// RVA: 0x2c2aecc VA: 0x7595242ecc
	private Void SetTransform(Vector3 newPosition, Quaternion newRotation, Single newZoom) { }
	// RVA: 0x2c2b59c VA: 0x759524359c
	public Void .ctor() { }
}
```