# LevitateState

**Namespace:** ` `


## Fields

- `Tween m_tween`

- `Vector3 m_beforePos`


## Properties

- `Int64 attributeMask`

- `Int64 abnormalFlagMask`

- `Int64 abnormalImmuneMask`

- `Int64 abnormalAntiMask`

- `Int64 abnormalComboMask`

- `Int64 abnormalComboImmuneMask`


## Methods

- `Int64 get_attributeMask()`

- `Int64 get_abnormalFlagMask()`

- `Int64 get_abnormalImmuneMask()`

- `Int64 get_abnormalAntiMask()`

- `Int64 get_abnormalComboMask()`

- `Int64 get_abnormalComboImmuneMask()`

- `Boolean GetValue(AttributeType, out, out, out, out)`

- `Void _PlayAnimation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LevitateState : BasicState, IAttributesModifier
{
	private static Single RAISE_HEIGHT_OFFSET; // 0x0
	private static Single RAISE_SHAKE_DEFAULT_TIME; // 0x4
	private static Single SHAKE_DELAY_TIME; // 0x8
	private static Vector3 SHAKE_STRENGTH; // 0xc
	private Tween m_tween; // 0x18
	private Vector3 m_beforePos; // 0x20
	private static DelegateBridge __Hotfix0_get_attributeMask; // 0x18
	private static DelegateBridge __Hotfix0_get_abnormalFlagMask; // 0x20
	private static DelegateBridge __Hotfix0_get_abnormalImmuneMask; // 0x28
	private static DelegateBridge __Hotfix0_get_abnormalAntiMask; // 0x30
	private static DelegateBridge __Hotfix0_get_abnormalComboMask; // 0x38
	private static DelegateBridge __Hotfix0_get_abnormalComboImmuneMask; // 0x40
	private static DelegateBridge __Hotfix0_GetValue; // 0x48
	private static DelegateBridge __Hotfix0_OnEnter; // 0x50
	private static DelegateBridge __Hotfix0_OnTick; // 0x58
	private static DelegateBridge __Hotfix0_OnExit; // 0x60
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x68
	private static DelegateBridge __Hotfix0__PlayAnimation; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }

	// RVA: 0x1c0ee90 VA: 0x7594226e90
	public Int64 get_attributeMask() { }
	// RVA: 0x1c0ef04 VA: 0x7594226f04
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x1c0ef7c VA: 0x7594226f7c
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x1c0eff0 VA: 0x7594226ff0
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x1c0f064 VA: 0x7594227064
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x1c0f0d8 VA: 0x75942270d8
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x1c0f14c VA: 0x759422714c
	public Boolean GetValue(AttributeType attributeType, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x1c0f250 VA: 0x7594227250
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c0f60c VA: 0x759422760c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c0f748 VA: 0x7594227748
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c0f8f8 VA: 0x75942278f8
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1c0f40c VA: 0x759422740c
	private Void _PlayAnimation() { }
	// RVA: 0x1c09f04 VA: 0x7594221f04
	public Void .ctor() { }
	// RVA: 0x1c0f9d0 VA: 0x75942279d0
	private static Void .cctor() { }
}
```