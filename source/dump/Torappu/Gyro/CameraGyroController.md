# CameraGyroController

**Namespace:** `Torappu.Gyro`


## Fields

- `Transform targetCamera`

- `Transform cameraAim`

- `Vector2 cameraOffset`

- `Vector2 aimOffset`

- `Vector2 maxAttitude`

- `Single maxSpeedFactor`

- `Single minSpeedFactor`

- `Single maxSpeedDistance`

- `Single minSpeedDistance`

- `Vector3 m_oriCameraPosition`

- `Vector3 m_oriAimPosition`

- `Boolean m_autoUpdate`

- `Tweener m_tweener`


## Properties

- `Boolean AutoUpdate`


## Methods

- `Boolean get_AutoUpdate()`

- `Void set_AutoUpdate(Boolean)`

- `Void TweenToOriginalPositions(Single, Action)`

- `Void Start()`

- `Void InitAndStart()`

- `Void Update()`

- `Single _GetOffset(Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gyro
public class CameraGyroController : MonoBehaviour
{
	public Transform targetCamera; // 0x18
	public Transform cameraAim; // 0x20
	public Vector2 cameraOffset; // 0x28
	public Vector2 aimOffset; // 0x30
	public Vector2 maxAttitude; // 0x38
	public Single maxSpeedFactor; // 0x40
	public Single minSpeedFactor; // 0x44
	public Single maxSpeedDistance; // 0x48
	public Single minSpeedDistance; // 0x4c
	private Vector3 m_oriCameraPosition; // 0x50
	private Vector3 m_oriAimPosition; // 0x5c
	private Boolean m_autoUpdate; // 0x68
	private Tweener m_tweener; // 0x70

	public Boolean AutoUpdate { get; set; }

	// RVA: 0x372b950 VA: 0x7595d43950
	public Boolean get_AutoUpdate() { }
	// RVA: 0x372b958 VA: 0x7595d43958
	public Void set_AutoUpdate(Boolean value) { }
	// RVA: 0x372b964 VA: 0x7595d43964
	public Void TweenToOriginalPositions(Single duration, Action tweenFinishCb) { }
	// RVA: 0x372bc00 VA: 0x7595d43c00
	private Void Start() { }
	// RVA: 0x372bc44 VA: 0x7595d43c44
	public Void InitAndStart() { }
	// RVA: 0x372bc50 VA: 0x7595d43c50
	private Void Update() { }
	// RVA: 0x372c1b4 VA: 0x7595d441b4
	private Single _GetOffset(Single maxOffset, Single v) { }
	// RVA: 0x372c1f0 VA: 0x7595d441f0
	private static Single _EaseOutQuart(Single start, Single end, Single value) { }
	// RVA: 0x372c218 VA: 0x7595d44218
	public Void .ctor() { }
}
```