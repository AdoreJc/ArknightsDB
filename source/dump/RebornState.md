# RebornState

**Namespace:** ` `


## Fields

- `FP m_remainingTime`

- `RebornData m_data`

- `ITweenHandler m_tween`

- `Boolean m_rebornAfterWave`

- `Int32 m_rebornAfterWaveCnt`

- `Int32 m_currentWaveCnt`

- `FP m_recoverStartHp`


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

- `Void _CheckRemainingTime(FP)`

- `Single _PlayAnimation()`

- `Void <_PlayAnimation>b__26_0(FP)`

- `Single <_PlayAnimation>b__26_1()`

- `Void <_PlayAnimation>b__26_2(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RebornState : BasicState, IAttributesModifier
{
	private FP m_remainingTime; // 0x18
	private RebornData m_data; // 0x20
	private ITweenHandler m_tween; // 0x68
	private Boolean m_rebornAfterWave; // 0x70
	private Int32 m_rebornAfterWaveCnt; // 0x74
	private Int32 m_currentWaveCnt; // 0x78
	private List`1 m_effectList; // 0x80
	private FP m_recoverStartHp; // 0x88
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
	private static DelegateBridge __Hotfix0__CheckRemainingTime; // 0x58
	private static DelegateBridge __Hotfix0__PlayAnimation; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }

	// RVA: 0x1c13ad4 VA: 0x759422bad4
	public Int64 get_attributeMask() { }
	// RVA: 0x1c13b38 VA: 0x759422bb38
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x1c13ba0 VA: 0x759422bba0
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x1c13c04 VA: 0x759422bc04
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x1c13c68 VA: 0x759422bc68
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x1c13ccc VA: 0x759422bccc
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x1c13d30 VA: 0x759422bd30
	public Boolean GetValue(AttributeType attribute, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x1c13e24 VA: 0x759422be24
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c14780 VA: 0x759422c780
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c149d0 VA: 0x759422c9d0
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x1c14bdc VA: 0x759422cbdc
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1c14860 VA: 0x759422c860
	private Void _CheckRemainingTime(FP deltaTime) { }
	// RVA: 0x1c142d4 VA: 0x759422c2d4
	private Single _PlayAnimation() { }
	// RVA: 0x1c09bf0 VA: 0x7594221bf0
	public Void .ctor() { }
	// RVA: 0x1c14d08 VA: 0x759422cd08
	private Void <_PlayAnimation>b__26_0(FP val) { }
	// RVA: 0x1c14de0 VA: 0x759422cde0
	private Single <_PlayAnimation>b__26_1() { }
	// RVA: 0x1c14e3c VA: 0x759422ce3c
	private Void <_PlayAnimation>b__26_2(Single val) { }
}
```