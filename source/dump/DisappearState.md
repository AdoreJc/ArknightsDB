# DisappearState

**Namespace:** ` `


## Fields

- `CoroutineId m_coroutine`

- `Boolean m_originalColliderEnable`

- `Tween m_disappearTween`


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

- `IEnumerator _DoDisappear()`

- `Void _DoAppear()`

- `Void _InterruptDisappearTweenIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DisappearState : BasicState, IAttributesModifier
{
	private const Single DISAPPEAR_TIME; // 0x0
	private const Single APPEAR_TIME; // 0x0
	private CoroutineId m_coroutine; // 0x18
	private Boolean m_originalColliderEnable; // 0x28
	private Tween m_disappearTween; // 0x30
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
	private static DelegateBridge __Hotfix0__DoDisappear; // 0x50
	private static DelegateBridge __Hotfix0__DoAppear; // 0x58
	private static DelegateBridge __Hotfix0__InterruptDisappearTweenIfNot; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }

	// RVA: 0x1c11864 VA: 0x7594229864
	public Int64 get_attributeMask() { }
	// RVA: 0x1c118c8 VA: 0x75942298c8
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x1c11930 VA: 0x7594229930
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x1c11994 VA: 0x7594229994
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x1c119f8 VA: 0x75942299f8
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x1c11a5c VA: 0x7594229a5c
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x1c11ac0 VA: 0x7594229ac0
	public Boolean GetValue(AttributeType attribute, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x1c11bb4 VA: 0x7594229bb4
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c11e54 VA: 0x7594229e54
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c124a0 VA: 0x759422a4a0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c11da8 VA: 0x7594229da8
	private IEnumerator _DoDisappear() { }
	// RVA: 0x1c12070 VA: 0x759422a070
	private Void _DoAppear() { }
	// RVA: 0x1c125cc VA: 0x759422a5cc
	private Void _InterruptDisappearTweenIfNot() { }
	// RVA: 0x1c09db8 VA: 0x7594221db8
	public Void .ctor() { }
}
```