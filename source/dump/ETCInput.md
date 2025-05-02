# ETCInput

**Namespace:** ` `


## Methods

- `Void RegisterControl(ETCBase)`

- `Void UnRegisterControl(ETCBase)`

- `Void Create()`

- `Void RegisterAxis(ETCAxis)`

- `Void UnRegisterAxis(ETCAxis)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ETCInput : MonoBehaviour
{
	public static ETCInput _instance; // 0x0
	private Dictionary`2 axes; // 0x18
	private Dictionary`2 controls; // 0x20
	private static ETCBase control; // 0x8
	private static ETCAxis axis; // 0x10

	public static ETCInput instance { get; }

	// RVA: 0x1b2dbdc VA: 0x7594145bdc
	public static ETCInput get_instance() { }
	// RVA: 0x1b2de00 VA: 0x7594145e00
	public Void RegisterControl(ETCBase ctrl) { }
	// RVA: 0x1b2e468 VA: 0x7594146468
	public Void UnRegisterControl(ETCBase ctrl) { }
	// RVA: 0x1b30c50 VA: 0x7594148c50
	public Void Create() { }
	// RVA: 0x1b30c54 VA: 0x7594148c54
	public static Void Register(ETCBase ctrl) { }
	// RVA: 0x1b30c74 VA: 0x7594148c74
	public static Void UnRegister(ETCBase ctrl) { }
	// RVA: 0x1b30c94 VA: 0x7594148c94
	public static Void SetControlVisible(String ctrlName, Boolean value) { }
	// RVA: 0x1b30dd4 VA: 0x7594148dd4
	public static Boolean GetControlVisible(String ctrlName) { }
	// RVA: 0x1b30ef0 VA: 0x7594148ef0
	public static Void SetControlActivated(String ctrlName, Boolean value) { }
	// RVA: 0x1b3102c VA: 0x759414902c
	public static Boolean GetControlActivated(String ctrlName) { }
	// RVA: 0x1b31148 VA: 0x7594149148
	public static Void SetControlSwipeIn(String ctrlName, Boolean value) { }
	// RVA: 0x1b31264 VA: 0x7594149264
	public static Boolean GetControlSwipeIn(String ctrlName) { }
	// RVA: 0x1b31380 VA: 0x7594149380
	public static Void SetControlSwipeOut(String ctrlName, Boolean value) { }
	// RVA: 0x1b3149c VA: 0x759414949c
	public static Boolean GetControlSwipeOut(String ctrlName, Boolean value) { }
	// RVA: 0x1b315b8 VA: 0x75941495b8
	public static Void SetDPadAxesCount(String ctrlName, DPadAxis value) { }
	// RVA: 0x1b316d0 VA: 0x75941496d0
	public static DPadAxis GetDPadAxesCount(String ctrlName) { }
	// RVA: 0x1b317e4 VA: 0x75941497e4
	public static ETCJoystick GetControlJoystick(String ctrlName) { }
	// RVA: 0x1b31944 VA: 0x7594149944
	public static ETCDPad GetControlDPad(String ctrlName) { }
	// RVA: 0x1b31aa4 VA: 0x7594149aa4
	public static ETCTouchPad GetControlTouchPad(String ctrlName) { }
	// RVA: 0x1b31c04 VA: 0x7594149c04
	public static ETCButton GetControlButton(String ctrlName) { }
	// RVA: 0x1b31d64 VA: 0x7594149d64
	public static Void SetControlSprite(String ctrlName, Sprite spr, Color color) { }
	// RVA: 0x1b31ebc VA: 0x7594149ebc
	public static Void SetJoystickThumbSprite(String ctrlName, Sprite spr, Color color) { }
	// RVA: 0x1b32110 VA: 0x759414a110
	public static Void SetButtonSprite(String ctrlName, Sprite sprNormal, Sprite sprPress, Color color) { }
	// RVA: 0x1b32268 VA: 0x759414a268
	public static Void SetAxisSpeed(String axisName, Single speed) { }
	// RVA: 0x1b3238c VA: 0x759414a38c
	public static Void SetAxisGravity(String axisName, Single gravity) { }
	// RVA: 0x1b324b0 VA: 0x759414a4b0
	public static Void SetTurnMoveSpeed(String ctrlName, Single speed) { }
	// RVA: 0x1b32538 VA: 0x759414a538
	public static Void ResetAxis(String axisName) { }
	// RVA: 0x1b3264c VA: 0x759414a64c
	public static Void SetAxisEnabled(String axisName, Boolean value) { }
	// RVA: 0x1b32768 VA: 0x759414a768
	public static Boolean GetAxisEnabled(String axisName) { }
	// RVA: 0x1b32884 VA: 0x759414a884
	public static Void SetAxisInverted(String axisName, Boolean value) { }
	// RVA: 0x1b329a0 VA: 0x759414a9a0
	public static Boolean GetAxisInverted(String axisName) { }
	// RVA: 0x1b32abc VA: 0x759414aabc
	public static Void SetAxisDeadValue(String axisName, Single value) { }
	// RVA: 0x1b32be0 VA: 0x759414abe0
	public static Single GetAxisDeadValue(String axisName) { }
	// RVA: 0x1b32cf4 VA: 0x759414acf4
	public static Void SetAxisSensitivity(String axisName, Single value) { }
	// RVA: 0x1b32e18 VA: 0x759414ae18
	public static Single GetAxisSensitivity(String axisName) { }
	// RVA: 0x1b32f2c VA: 0x759414af2c
	public static Void SetAxisThreshold(String axisName, Single value) { }
	// RVA: 0x1b33050 VA: 0x759414b050
	public static Single GetAxisThreshold(String axisName) { }
	// RVA: 0x1b33164 VA: 0x759414b164
	public static Void SetAxisInertia(String axisName, Boolean value) { }
	// RVA: 0x1b33280 VA: 0x759414b280
	public static Boolean GetAxisInertia(String axisName) { }
	// RVA: 0x1b3339c VA: 0x759414b39c
	public static Void SetAxisInertiaSpeed(String axisName, Single value) { }
	// RVA: 0x1b334c0 VA: 0x759414b4c0
	public static Single GetAxisInertiaSpeed(String axisName) { }
	// RVA: 0x1b335d4 VA: 0x759414b5d4
	public static Void SetAxisInertiaThreshold(String axisName, Single value) { }
	// RVA: 0x1b336f8 VA: 0x759414b6f8
	public static Single GetAxisInertiaThreshold(String axisName) { }
	// RVA: 0x1b3380c VA: 0x759414b80c
	public static Void SetAxisAutoStabilization(String axisName, Boolean value) { }
	// RVA: 0x1b33928 VA: 0x759414b928
	public static Boolean GetAxisAutoStabilization(String axisName) { }
	// RVA: 0x1b33a44 VA: 0x759414ba44
	public static Void SetAxisAutoStabilizationSpeed(String axisName, Single value) { }
	// RVA: 0x1b33b68 VA: 0x759414bb68
	public static Single GetAxisAutoStabilizationSpeed(String axisName) { }
	// RVA: 0x1b33c7c VA: 0x759414bc7c
	public static Void SetAxisAutoStabilizationThreshold(String axisName, Single value) { }
	// RVA: 0x1b33da0 VA: 0x759414bda0
	public static Single GetAxisAutoStabilizationThreshold(String axisName) { }
	// RVA: 0x1b33eb4 VA: 0x759414beb4
	public static Void SetAxisClampRotation(String axisName, Boolean value) { }
	// RVA: 0x1b33fd0 VA: 0x759414bfd0
	public static Boolean GetAxisClampRotation(String axisName) { }
	// RVA: 0x1b340ec VA: 0x759414c0ec
	public static Void SetAxisClampRotationValue(String axisName, Single min, Single max) { }
	// RVA: 0x1b34214 VA: 0x759414c214
	public static Void SetAxisClampRotationMinValue(String axisName, Single value) { }
	// RVA: 0x1b34338 VA: 0x759414c338
	public static Void SetAxisClampRotationMaxValue(String axisName, Single value) { }
	// RVA: 0x1b3445c VA: 0x759414c45c
	public static Single GetAxisClampRotationMinValue(String axisName) { }
	// RVA: 0x1b34570 VA: 0x759414c570
	public static Single GetAxisClampRotationMaxValue(String axisName) { }
	// RVA: 0x1b2b7a4 VA: 0x75941437a4
	public static Void SetAxisDirecTransform(String axisName, Transform value) { }
	// RVA: 0x1b34684 VA: 0x759414c684
	public static Transform GetAxisDirectTransform(String axisName) { }
	// RVA: 0x1b34798 VA: 0x759414c798
	public static Void SetAxisDirectAction(String axisName, DirectAction value) { }
	// RVA: 0x1b348b0 VA: 0x759414c8b0
	public static DirectAction GetAxisDirectAction(String axisName) { }
	// RVA: 0x1b349c4 VA: 0x759414c9c4
	public static Void SetAxisAffectedAxis(String axisName, AxisInfluenced value) { }
	// RVA: 0x1b34adc VA: 0x759414cadc
	public static AxisInfluenced GetAxisAffectedAxis(String axisName) { }
	// RVA: 0x1b34bf0 VA: 0x759414cbf0
	public static Void SetAxisOverTime(String axisName, Boolean value) { }
	// RVA: 0x1b34d0c VA: 0x759414cd0c
	public static Boolean GetAxisOverTime(String axisName) { }
	// RVA: 0x1b34e28 VA: 0x759414ce28
	public static Void SetAxisOverTimeStep(String axisName, Single value) { }
	// RVA: 0x1b34f4c VA: 0x759414cf4c
	public static Single GetAxisOverTimeStep(String axisName) { }
	// RVA: 0x1b35060 VA: 0x759414d060
	public static Void SetAxisOverTimeMaxValue(String axisName, Single value) { }
	// RVA: 0x1b35184 VA: 0x759414d184
	public static Single GetAxisOverTimeMaxValue(String axisName) { }
	// RVA: 0x1b35298 VA: 0x759414d298
	public static Single GetAxis(String axisName) { }
	// RVA: 0x1b353ac VA: 0x759414d3ac
	public static Single GetAxisSpeed(String axisName) { }
	// RVA: 0x1b354a8 VA: 0x759414d4a8
	public static Boolean GetAxisDownUp(String axisName) { }
	// RVA: 0x1b355ac VA: 0x759414d5ac
	public static Boolean GetAxisDownDown(String axisName) { }
	// RVA: 0x1b356b0 VA: 0x759414d6b0
	public static Boolean GetAxisDownRight(String axisName) { }
	// RVA: 0x1b357b4 VA: 0x759414d7b4
	public static Boolean GetAxisDownLeft(String axisName) { }
	// RVA: 0x1b358b8 VA: 0x759414d8b8
	public static Boolean GetAxisPressedUp(String axisName) { }
	// RVA: 0x1b359bc VA: 0x759414d9bc
	public static Boolean GetAxisPressedDown(String axisName) { }
	// RVA: 0x1b35ac0 VA: 0x759414dac0
	public static Boolean GetAxisPressedRight(String axisName) { }
	// RVA: 0x1b35bc4 VA: 0x759414dbc4
	public static Boolean GetAxisPressedLeft(String axisName) { }
	// RVA: 0x1b35cc8 VA: 0x759414dcc8
	public static Boolean GetButtonDown(String buttonName) { }
	// RVA: 0x1b35dcc VA: 0x759414ddcc
	public static Boolean GetButton(String buttonName) { }
	// RVA: 0x1b35ee0 VA: 0x759414dee0
	public static Boolean GetButtonUp(String buttonName) { }
	// RVA: 0x1b35fe4 VA: 0x759414dfe4
	public static Single GetButtonValue(String buttonName) { }
	// RVA: 0x1b30aa4 VA: 0x7594148aa4
	private Void RegisterAxis(ETCAxis axis) { }
	// RVA: 0x1b30bb4 VA: 0x7594148bb4
	private Void UnRegisterAxis(ETCAxis axis) { }
	// RVA: 0x1b360e0 VA: 0x759414e0e0
	private Void OnDestroy() { }
	// RVA: 0x1b361a8 VA: 0x759414e1a8
	public Void .ctor() { }
}
```