# FreezeState

**Namespace:** ` `


## Fields

- `CurrentAniState m_animatorState`


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


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FreezeState : BasicState, IAttributesModifier
{
	private CurrentAniState m_animatorState; // 0x18
	private static DelegateBridge __Hotfix0_get_attributeMask; // 0x0
	private static DelegateBridge __Hotfix0_get_abnormalFlagMask; // 0x8
	private static DelegateBridge __Hotfix0_get_abnormalImmuneMask; // 0x10
	private static DelegateBridge __Hotfix0_get_abnormalAntiMask; // 0x18
	private static DelegateBridge __Hotfix0_get_abnormalComboMask; // 0x20
	private static DelegateBridge __Hotfix0_get_abnormalComboImmuneMask; // 0x28
	private static DelegateBridge __Hotfix0_GetValue; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_OnExit; // 0x48
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }

	// RVA: 0x1c0e638 VA: 0x7594226638
	public Int64 get_attributeMask() { }
	// RVA: 0x1c0e69c VA: 0x759422669c
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x1c0e704 VA: 0x7594226704
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x1c0e768 VA: 0x7594226768
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x1c0e7cc VA: 0x75942267cc
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x1c0e830 VA: 0x7594226830
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x1c0e894 VA: 0x7594226894
	public Boolean GetValue(AttributeType attributeType, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x1c0e988 VA: 0x7594226988
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c0eb2c VA: 0x7594226b2c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c0ec5c VA: 0x7594226c5c
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c0edb8 VA: 0x7594226db8
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1c09e98 VA: 0x7594221e98
	public Void .ctor() { }
}
```