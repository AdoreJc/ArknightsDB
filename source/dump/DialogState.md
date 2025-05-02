# DialogState

**Namespace:** ` `


## Fields

- `FP m_remainingEscapeTime`

- `AnimBundle m_lastPlayedBundle`


## Properties

- `Int64 attributeMask`

- `Int64 abnormalFlagMask`

- `Int64 abnormalImmuneMask`

- `Int64 abnormalAntiMask`

- `Int64 abnormalComboMask`

- `Int64 abnormalComboImmuneMask`

- `Boolean isHanging`


## Methods

- `Int64 get_attributeMask()`

- `Int64 get_abnormalFlagMask()`

- `Int64 get_abnormalImmuneMask()`

- `Int64 get_abnormalAntiMask()`

- `Int64 get_abnormalComboMask()`

- `Int64 get_abnormalComboImmuneMask()`

- `Boolean GetValue(AttributeType, out, out, out, out)`

- `Boolean get_isHanging()`

- `Void set_isHanging(Boolean)`

- `Void UpdateMoveAnimation()`

- `Void _PlayAnim(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DialogState : BasicState, IAttributesModifier
{
	private FP m_remainingEscapeTime; // 0x18
	private AnimBundle m_lastPlayedBundle; // 0x20
	private static DelegateBridge __Hotfix0_get_attributeMask; // 0x0
	private static DelegateBridge __Hotfix0_get_abnormalFlagMask; // 0x8
	private static DelegateBridge __Hotfix0_get_abnormalImmuneMask; // 0x10
	private static DelegateBridge __Hotfix0_get_abnormalAntiMask; // 0x18
	private static DelegateBridge __Hotfix0_get_abnormalComboMask; // 0x20
	private static DelegateBridge __Hotfix0_get_abnormalComboImmuneMask; // 0x28
	private static DelegateBridge __Hotfix0_GetValue; // 0x30
	private static DelegateBridge __Hotfix0_get_isHanging; // 0x38
	private static DelegateBridge __Hotfix0_set_isHanging; // 0x40
	private static DelegateBridge __Hotfix0_OnEnter; // 0x48
	private static DelegateBridge __Hotfix0_OnTick; // 0x50
	private static DelegateBridge __Hotfix0_OnExit; // 0x58
	private static DelegateBridge __Hotfix0_UpdateMoveAnimation; // 0x60
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }
	private Boolean isHanging { get; set; }

	// RVA: 0x1c14f20 VA: 0x759422cf20
	public Int64 get_attributeMask() { }
	// RVA: 0x1c14f84 VA: 0x759422cf84
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x1c14fec VA: 0x759422cfec
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x1c15050 VA: 0x759422d050
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x1c150b4 VA: 0x759422d0b4
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x1c15118 VA: 0x759422d118
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x1c1517c VA: 0x759422d17c
	public Boolean GetValue(AttributeType attribute, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x1c15270 VA: 0x759422d270
	private Boolean get_isHanging() { }
	// RVA: 0x1c15300 VA: 0x759422d300
	private Void set_isHanging(Boolean value) { }
	// RVA: 0x1c15508 VA: 0x759422d508
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c15794 VA: 0x759422d794
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c15964 VA: 0x759422d964
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c153dc VA: 0x759422d3dc
	public Void UpdateMoveAnimation() { }
	// RVA: 0x1c15ad0 VA: 0x759422dad0
	private Void _PlayAnim(Object param) { }
	// RVA: 0x1c09f80 VA: 0x7594221f80
	public Void .ctor() { }
}
```