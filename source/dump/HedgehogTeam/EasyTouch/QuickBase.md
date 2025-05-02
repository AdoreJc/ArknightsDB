# QuickBase

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `String quickActionName`

- `Boolean isMultiTouch`

- `Boolean is2Finger`

- `Boolean isOnTouch`

- `Boolean enablePickOverUI`

- `Boolean resetPhysic`

- `DirectAction directAction`

- `AffectedAxesAction axesAction`

- `Single sensibility`

- `CharacterController directCharacterController`

- `Boolean inverseAxisValue`

- `Rigidbody cachedRigidBody`

- `Boolean isKinematic`

- `Rigidbody2D cachedRigidBody2D`

- `Boolean isKinematic2D`

- `GameObjectType realType`

- `Int32 fingerIndex`


## Methods

- `Void Awake()`

- `Vector3 GetInfluencedAxis()`

- `Void DoDirectAction(Single)`

- `Void EnabledQuickComponent(String)`

- `Void DisabledQuickComponent(String)`

- `Void DisabledAllSwipeExcepted(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class QuickBase : MonoBehaviour
{
	public String quickActionName; // 0x18
	public Boolean isMultiTouch; // 0x20
	public Boolean is2Finger; // 0x21
	public Boolean isOnTouch; // 0x22
	public Boolean enablePickOverUI; // 0x23
	public Boolean resetPhysic; // 0x24
	public DirectAction directAction; // 0x28
	public AffectedAxesAction axesAction; // 0x2c
	public Single sensibility; // 0x30
	public CharacterController directCharacterController; // 0x38
	public Boolean inverseAxisValue; // 0x40
	protected Rigidbody cachedRigidBody; // 0x48
	protected Boolean isKinematic; // 0x50
	protected Rigidbody2D cachedRigidBody2D; // 0x58
	protected Boolean isKinematic2D; // 0x60
	protected GameObjectType realType; // 0x64
	protected Int32 fingerIndex; // 0x68


	// RVA: 0x375a7ac VA: 0x7595d727ac
	private Void Awake() { }
	// RVA: 0x375a8d8 VA: 0x7595d728d8
	public virtual Void Start() { }
	// RVA: 0x375b184 VA: 0x7595d73184
	public virtual Void OnEnable() { }
	// RVA: 0x375b188 VA: 0x7595d73188
	public virtual Void OnDisable() { }
	// RVA: 0x375b18c VA: 0x7595d7318c
	protected Vector3 GetInfluencedAxis() { }
	// RVA: 0x375b21c VA: 0x7595d7321c
	protected Void DoDirectAction(Single value) { }
	// RVA: 0x375b474 VA: 0x7595d73474
	public Void EnabledQuickComponent(String quickActionName) { }
	// RVA: 0x375b534 VA: 0x7595d73534
	public Void DisabledQuickComponent(String quickActionName) { }
	// RVA: 0x375b5f4 VA: 0x7595d735f4
	public Void DisabledAllSwipeExcepted(String quickActionName) { }
	// RVA: 0x375b7a0 VA: 0x7595d737a0
	public Void .ctor() { }
}
```