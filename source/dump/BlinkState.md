# BlinkState

**Namespace:** ` `


## Fields

- `CoroutineId m_coroutine`


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

- `IEnumerator _PlayAnimation()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BlinkState : BasicState, IAttributesModifier
{
	private const Single BLINK_BEGIN_TIME; // 0x0
	private const Single BLINK_END_TIME; // 0x0
	private CoroutineId m_coroutine; // 0x18
	private static DelegateBridge __Hotfix0_get_attributeMask; // 0x0
	private static DelegateBridge __Hotfix0_get_abnormalFlagMask; // 0x8
	private static DelegateBridge __Hotfix0_get_abnormalImmuneMask; // 0x10
	private static DelegateBridge __Hotfix0_get_abnormalAntiMask; // 0x18
	private static DelegateBridge __Hotfix0_get_abnormalComboMask; // 0x20
	private static DelegateBridge __Hotfix0_get_abnormalComboImmuneMask; // 0x28
	private static DelegateBridge __Hotfix0_GetValue; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x48
	private static DelegateBridge __Hotfix0__PlayAnimation; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }

	// RVA: 0x1c12e34 VA: 0x759422ae34
	public Int64 get_attributeMask() { }
	// RVA: 0x1c12e98 VA: 0x759422ae98
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x1c12f00 VA: 0x759422af00
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x1c12f64 VA: 0x759422af64
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x1c12fc8 VA: 0x759422afc8
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x1c1302c VA: 0x759422b02c
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x1c13090 VA: 0x759422b090
	public Boolean GetValue(AttributeType attribute, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x1c13184 VA: 0x759422b184
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c13370 VA: 0x759422b370
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c13528 VA: 0x759422b528
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1c132c4 VA: 0x759422b2c4
	private IEnumerator _PlayAnimation() { }
	// RVA: 0x1c09e2c VA: 0x7594221e2c
	public Void .ctor() { }
}
```