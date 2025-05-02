# ETCAxis

**Namespace:** ` `


## Fields

- `String name`

- `Boolean autoLinkTagPlayer`

- `String autoTag`

- `GameObject player`

- `Boolean enable`

- `Boolean invertedAxis`

- `Single speed`

- `Single deadValue`

- `AxisValueMethod valueMethod`

- `AnimationCurve curveValue`

- `Boolean isEnertia`

- `Single inertia`

- `Single inertiaThreshold`

- `Boolean isAutoStab`

- `Single autoStabThreshold`

- `Single autoStabSpeed`

- `Single startAngle`

- `Boolean isClampRotation`

- `Single maxAngle`

- `Single minAngle`

- `Boolean isValueOverTime`

- `Single overTimeStep`

- `Single maxOverTimeValue`

- `Single axisValue`

- `Single axisSpeedValue`

- `Single axisThreshold`

- `Boolean isLockinJump`

- `Vector3 lastMove`

- `AxisState axisState`

- `Transform _directTransform`

- `DirectAction directAction`

- `AxisInfluenced axisInfluenced`

- `ActionOn actionOn`

- `CharacterController directCharacterController`

- `Rigidbody directRigidBody`

- `Single gravity`

- `Single currentGravity`

- `Boolean isJump`

- `String unityAxis`

- `Boolean showGeneralInspector`

- `Boolean showDirectInspector`

- `Boolean showInertiaInspector`

- `Boolean showSimulatinInspector`


## Properties

- `Transform directTransform`


## Methods

- `Transform get_directTransform()`

- `Void set_directTransform(Transform)`

- `Void InitAxis()`

- `Void UpdateAxis(Single, Boolean, ControlType, Boolean)`

- `Void UpdateButton()`

- `Void ResetAxis()`

- `Void DoDirectAction()`

- `Void DoGravity()`

- `Void ComputAxisValue(Single, ControlType, Boolean, Boolean)`

- `Vector3 GetInfluencedAxis()`

- `Single GetAngle()`

- `Void DoAutoStabilisation()`

- `Void DoAngleLimitation()`

- `Void InitDeadCurve()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ETCAxis
{
	public String name; // 0x10
	public Boolean autoLinkTagPlayer; // 0x18
	public String autoTag; // 0x20
	public GameObject player; // 0x28
	public Boolean enable; // 0x30
	public Boolean invertedAxis; // 0x31
	public Single speed; // 0x34
	public Single deadValue; // 0x38
	public AxisValueMethod valueMethod; // 0x3c
	public AnimationCurve curveValue; // 0x40
	public Boolean isEnertia; // 0x48
	public Single inertia; // 0x4c
	public Single inertiaThreshold; // 0x50
	public Boolean isAutoStab; // 0x54
	public Single autoStabThreshold; // 0x58
	public Single autoStabSpeed; // 0x5c
	private Single startAngle; // 0x60
	public Boolean isClampRotation; // 0x64
	public Single maxAngle; // 0x68
	public Single minAngle; // 0x6c
	public Boolean isValueOverTime; // 0x70
	public Single overTimeStep; // 0x74
	public Single maxOverTimeValue; // 0x78
	public Single axisValue; // 0x7c
	public Single axisSpeedValue; // 0x80
	public Single axisThreshold; // 0x84
	public Boolean isLockinJump; // 0x88
	private Vector3 lastMove; // 0x8c
	public AxisState axisState; // 0x98
	private Transform _directTransform; // 0xa0
	public DirectAction directAction; // 0xa8
	public AxisInfluenced axisInfluenced; // 0xac
	public ActionOn actionOn; // 0xb0
	public CharacterController directCharacterController; // 0xb8
	public Rigidbody directRigidBody; // 0xc0
	public Single gravity; // 0xc8
	public Single currentGravity; // 0xcc
	public Boolean isJump; // 0xd0
	public String unityAxis; // 0xd8
	public Boolean showGeneralInspector; // 0xe0
	public Boolean showDirectInspector; // 0xe1
	public Boolean showInertiaInspector; // 0xe2
	public Boolean showSimulatinInspector; // 0xe3

	public Transform directTransform { get; set; }

	// RVA: 0x1b2c004 VA: 0x7594144004
	public Transform get_directTransform() { }
	// RVA: 0x1b2c00c VA: 0x759414400c
	public Void set_directTransform(Transform value) { }
	// RVA: 0x1b2c110 VA: 0x7594144110
	public Void .ctor(String axisName) { }
	// RVA: 0x1b2c1f0 VA: 0x75941441f0
	public Void InitAxis() { }
	// RVA: 0x1b2c408 VA: 0x7594144408
	public Void UpdateAxis(Single realValue, Boolean isOnDrag, ControlType type, Boolean deltaTime) { }
	// RVA: 0x1b2ca00 VA: 0x7594144a00
	public Void UpdateButton() { }
	// RVA: 0x1b2d16c VA: 0x759414516c
	public Void ResetAxis() { }
	// RVA: 0x1b2cbd8 VA: 0x7594144bd8
	public Void DoDirectAction() { }
	// RVA: 0x1b2d3e0 VA: 0x75941453e0
	public Void DoGravity() { }
	// RVA: 0x1b2c8e8 VA: 0x75941448e8
	private Void ComputAxisValue(Single realValue, ControlType type, Boolean isOnDrag, Boolean deltaTime) { }
	// RVA: 0x1b2d190 VA: 0x7594145190
	private Vector3 GetInfluencedAxis() { }
	// RVA: 0x1b2c2a8 VA: 0x75941442a8
	private Single GetAngle() { }
	// RVA: 0x1b2c60c VA: 0x759414460c
	private Void DoAutoStabilisation() { }
	// RVA: 0x1b2d2a4 VA: 0x75941452a4
	private Void DoAngleLimitation() { }
	// RVA: 0x1b2d4e0 VA: 0x75941454e0
	public Void InitDeadCurve() { }
}
```