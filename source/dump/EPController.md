# EPController

**Namespace:** ` `


## Fields

- `ElementType recoveryType`

- `Entity m_owner`

- `Boolean m_isInBreakRecovery`

- `ITweenHandler m_tween`


## Properties

- `Boolean isInBreakRecovery`

- `Int64 attributeMask`

- `Int64 abnormalFlagMask`

- `Int64 abnormalImmuneMask`

- `Int64 abnormalAntiMask`

- `Int64 abnormalComboMask`

- `Int64 abnormalComboImmuneMask`


## Methods

- `Boolean get_isInBreakRecovery()`

- `Void set_isInBreakRecovery(Boolean)`

- `Void Reset(Entity)`

- `Void OnFinish()`

- `Void _CreateBrokenBuff(EPBreakBuffData)`

- `Void _StartEPRecovery(Single)`

- `Void OnElementBreak(ElementType)`

- `Int64 get_attributeMask()`

- `Int64 get_abnormalFlagMask()`

- `Int64 get_abnormalImmuneMask()`

- `Int64 get_abnormalAntiMask()`

- `Int64 get_abnormalComboMask()`

- `Int64 get_abnormalComboImmuneMask()`

- `Boolean GetValue(AttributeType, out, out, out, out)`

- `Void <_StartEPRecovery>b__10_0(FP)`

- `Void <_StartEPRecovery>b__10_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EPController : IAttributesModifier, IHotfixable
{
	public ElementType recoveryType; // 0x10
	private Entity m_owner; // 0x18
	private Boolean m_isInBreakRecovery; // 0x20
	private ITweenHandler m_tween; // 0x28
	private static DelegateBridge __Hotfix0_get_isInBreakRecovery; // 0x0
	private static DelegateBridge __Hotfix0_set_isInBreakRecovery; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_OnFinish; // 0x18
	private static DelegateBridge __Hotfix0__CreateBrokenBuff; // 0x20
	private static DelegateBridge __Hotfix0__StartEPRecovery; // 0x28
	private static DelegateBridge __Hotfix0_OnElementBreak; // 0x30
	private static DelegateBridge __Hotfix0_get_attributeMask; // 0x38
	private static DelegateBridge __Hotfix0_get_abnormalFlagMask; // 0x40
	private static DelegateBridge __Hotfix0_get_abnormalImmuneMask; // 0x48
	private static DelegateBridge __Hotfix0_get_abnormalAntiMask; // 0x50
	private static DelegateBridge __Hotfix0_get_abnormalComboMask; // 0x58
	private static DelegateBridge __Hotfix0_get_abnormalComboImmuneMask; // 0x60
	private static DelegateBridge __Hotfix0_GetValue; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean isInBreakRecovery { get; set; }
	public Int64 attributeMask { get; }
	public Int64 abnormalFlagMask { get; }
	public Int64 abnormalImmuneMask { get; }
	public Int64 abnormalAntiMask { get; }
	public Int64 abnormalComboMask { get; }
	public Int64 abnormalComboImmuneMask { get; }

	// RVA: 0x3fd2930 VA: 0x75965ea930
	public Boolean get_isInBreakRecovery() { }
	// RVA: 0x3fd2998 VA: 0x75965ea998
	public Void set_isInBreakRecovery(Boolean value) { }
	// RVA: 0x3fd2b58 VA: 0x75965eab58
	public Void Reset(Entity owner) { }
	// RVA: 0x3fd2c80 VA: 0x75965eac80
	public Void OnFinish() { }
	// RVA: 0x3fd2d78 VA: 0x75965ead78
	private Void _CreateBrokenBuff(EPBreakBuffData data) { }
	// RVA: 0x3fd2ef0 VA: 0x75965eaef0
	private Void _StartEPRecovery(Single recoverTime) { }
	// RVA: 0x3fd30ec VA: 0x75965eb0ec
	public Void OnElementBreak(ElementType curEPDamageType) { }
	// RVA: 0x3fd3564 VA: 0x75965eb564
	public Int64 get_attributeMask() { }
	// RVA: 0x3fd35c8 VA: 0x75965eb5c8
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x3fd3630 VA: 0x75965eb630
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x3fd3694 VA: 0x75965eb694
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x3fd36f8 VA: 0x75965eb6f8
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x3fd375c VA: 0x75965eb75c
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x3fd37c0 VA: 0x75965eb7c0
	public Boolean GetValue(AttributeType attribute, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x3fd38b4 VA: 0x75965eb8b4
	public Void .ctor() { }
	// RVA: 0x3fd3924 VA: 0x75965eb924
	private Void <_StartEPRecovery>b__10_0(FP val) { }
	// RVA: 0x3fd39c8 VA: 0x75965eb9c8
	private Void <_StartEPRecovery>b__10_1() { }
}
```