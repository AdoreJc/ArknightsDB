# GyroInput

**Namespace:** `Torappu.Gyro`


## Fields

- `Single _updateInterval`

- `Vector2 m_simpleAttitude`

- `Double m_rotateX`

- `Double m_rotateY`

- `Boolean m_gyroSupported`


## Properties

- `Vector2 simpleAttitude`

- `Boolean gyroSupported`


## Methods

- `Vector2 get_simpleAttitude()`

- `Boolean get_gyroSupported()`

- `Void Start()`

- `Void FixedUpdate()`

- `Boolean SetOriginRotation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gyro
public class GyroInput : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private const Double BOUNCE_BACK_SPEED; // 0x0
	private const Single MIN_ROTATE_SPEED; // 0x0
	private Single _updateInterval; // 0x18
	private Vector2 m_simpleAttitude; // 0x1c
	private Double m_rotateX; // 0x28
	private Double m_rotateY; // 0x30
	private Boolean m_gyroSupported; // 0x38
	private static DelegateBridge __Hotfix0_get_simpleAttitude; // 0x0
	private static DelegateBridge __Hotfix0_get_gyroSupported; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x28
	private static DelegateBridge __Hotfix0_SetOriginRotation; // 0x30
	private static DelegateBridge __Hotfix0__GetNormalized; // 0x38
	private static DelegateBridge __Hotfix0__GetInverse; // 0x40
	private static DelegateBridge __Hotfix0__IsValidQuaternion; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Vector2 simpleAttitude { get; }
	public Boolean gyroSupported { get; }

	// RVA: 0x372c150 VA: 0x7595d44150
	public Vector2 get_simpleAttitude() { }
	// RVA: 0x372ca84 VA: 0x7595d44a84
	public Boolean get_gyroSupported() { }
	// RVA: 0x372caec VA: 0x7595d44aec
	protected override Void OnDestroy() { }
	// RVA: 0x372cb9c VA: 0x7595d44b9c
	protected override Void OnInit() { }
	// RVA: 0x372cc70 VA: 0x7595d44c70
	private Void Start() { }
	// RVA: 0x372cd58 VA: 0x7595d44d58
	private Void FixedUpdate() { }
	// RVA: 0x372ccec VA: 0x7595d44cec
	public Boolean SetOriginRotation() { }
	// RVA: 0x372cffc VA: 0x7595d44ffc
	private static Quaternion _GetNormalized(Quaternion q) { }
	// RVA: 0x372d0b4 VA: 0x7595d450b4
	private static Quaternion _GetInverse(Quaternion q) { }
	// RVA: 0x372d15c VA: 0x7595d4515c
	private static Boolean _IsValidQuaternion(Quaternion q) { }
	// RVA: 0x372d320 VA: 0x7595d45320
	public Void .ctor() { }
}
```