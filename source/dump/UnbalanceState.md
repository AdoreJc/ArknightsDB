# UnbalanceState

**Namespace:** ` `


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

- `Boolean _CheckCollideWithHighLand(Enemy, Single)`

- `Boolean _UpdateFriction(Single)`

- `Boolean _UpdatePullSources()`

- `Void OnPhysicObjectInit()`

- `Void OnAfterPhysicSimulate(Single)`

- `Void OnPhysicObjectRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UnbalanceState : BasicState, IAttributesModifier, IPhysicObject
{
	private static DelegateBridge __Hotfix0_get_attributeMask; // 0x0
	private static DelegateBridge __Hotfix0_get_abnormalFlagMask; // 0x8
	private static DelegateBridge __Hotfix0_get_abnormalImmuneMask; // 0x10
	private static DelegateBridge __Hotfix0_get_abnormalAntiMask; // 0x18
	private static DelegateBridge __Hotfix0_get_abnormalComboMask; // 0x20
	private static DelegateBridge __Hotfix0_get_abnormalComboImmuneMask; // 0x28
	private static DelegateBridge __Hotfix0_GetValue; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0_OnTick; // 0x48
	private static DelegateBridge __Hotfix0__CheckCollideWithHighLand; // 0x50
	private static DelegateBridge __Hotfix0__UpdateFriction; // 0x58
	private static DelegateBridge __Hotfix0__UpdatePullSources; // 0x60
	private static DelegateBridge __Hotfix0_OnPhysicObjectInit; // 0x68
	private static DelegateBridge __Hotfix0_OnAfterPhysicSimulate; // 0x70
	private static DelegateBridge __Hotfix0_OnPhysicObjectRecycle; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }

	// RVA: 0x1c0fa2c VA: 0x7594227a2c
	public Int64 get_attributeMask() { }
	// RVA: 0x1c0fa90 VA: 0x7594227a90
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x1c0faf8 VA: 0x7594227af8
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x1c0fb5c VA: 0x7594227b5c
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x1c0fbc0 VA: 0x7594227bc0
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x1c0fc24 VA: 0x7594227c24
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x1c0fc88 VA: 0x7594227c88
	public Boolean GetValue(AttributeType attribute, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x1c0fd7c VA: 0x7594227d7c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c0ffc0 VA: 0x7594227fc0
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c1058c VA: 0x759422858c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c10100 VA: 0x7594228100
	private Boolean _CheckCollideWithHighLand(Enemy enemy, Single scopeOffset) { }
	// RVA: 0x1c10868 VA: 0x7594228868
	private Boolean _UpdateFriction(Single deltaTime) { }
	// RVA: 0x1c10be8 VA: 0x7594228be8
	private Boolean _UpdatePullSources() { }
	// RVA: 0x1c0ff30 VA: 0x7594227f30
	public Void OnPhysicObjectInit() { }
	// RVA: 0x1c10cb8 VA: 0x7594228cb8
	public Void OnAfterPhysicSimulate(Single deltaTimeAsFloat) { }
	// RVA: 0x1c104fc VA: 0x75942284fc
	public Void OnPhysicObjectRecycle() { }
	// RVA: 0x1c09cc8 VA: 0x7594221cc8
	public Void .ctor() { }
}
```