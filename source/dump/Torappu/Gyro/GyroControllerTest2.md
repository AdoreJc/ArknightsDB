# GyroControllerTest2

**Namespace:** `Torappu.Gyro`


## Fields

- `Transform targetCamera`

- `Transform cameraAim`

- `Vector2 cameraOffset`

- `Vector2 aimOffset`

- `Single maxSpeedFactor`

- `Single minSpeedFactor`

- `Single maxSpeedDistance`

- `Single minSpeedDistance`

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
public class GyroControllerTest2 : MonoBehaviour
{
	public Transform targetCamera; // 0x18
	public Transform cameraAim; // 0x20
	public Vector2 cameraOffset; // 0x28
	public Vector2 aimOffset; // 0x30
	public Single maxSpeedFactor; // 0x38
	public Single minSpeedFactor; // 0x3c
	public Single maxSpeedDistance; // 0x40
	public Single minSpeedDistance; // 0x44
	private Vector3 m_oriCameraPosition; // 0x48
	private Vector3 m_oriAimPosition; // 0x54


	// RVA: 0x372c664 VA: 0x7595d44664
	private Void Start() { }
	// RVA: 0x372c6a8 VA: 0x7595d446a8
	private Void Update() { }
	// RVA: 0x372ca4c VA: 0x7595d44a4c
	private Single _GetOffset(Single maxOffset, Single v, EaseType easeType) { }
	// RVA: 0x372ca70 VA: 0x7595d44a70
	public Void .ctor() { }
}
```