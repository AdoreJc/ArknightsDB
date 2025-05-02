# GyroControllerTest

**Namespace:** `Torappu.Gyro`


## Fields

- `Transform targetCamera`

- `Transform cameraAim`

- `Vector2 cameraOffset`

- `Vector2 aimOffset`

- `Single speedFactor`

- `Vector3 m_oriCameraPosition`

- `Vector3 m_oriAimPosition`


## Methods

- `Void Start()`

- `Void Update()`

- `Single _GetOffset(Single, Single, EaseType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gyro
public class GyroControllerTest : MonoBehaviour
{
	public Transform targetCamera; // 0x18
	public Transform cameraAim; // 0x20
	public Vector2 cameraOffset; // 0x28
	public Vector2 aimOffset; // 0x30
	public Single speedFactor; // 0x38
	private Vector3 m_oriCameraPosition; // 0x3c
	private Vector3 m_oriAimPosition; // 0x48


	// RVA: 0x372c3d8 VA: 0x7595d443d8
	private Void Start() { }
	// RVA: 0x372c41c VA: 0x7595d4441c
	private Void Update() { }
	// RVA: 0x372c62c VA: 0x7595d4462c
	private Single _GetOffset(Single maxOffset, Single v, EaseType easeType) { }
	// RVA: 0x372c650 VA: 0x7595d44650
	public Void .ctor() { }
}
```