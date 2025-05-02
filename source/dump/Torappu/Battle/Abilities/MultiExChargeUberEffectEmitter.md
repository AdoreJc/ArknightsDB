# MultiExChargeUberEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _isExEffectEmitter`

- `Event _chargeEffectStartEvent`

- `ExChargeRangedAttack m_exChargeAbility`


## Properties

- `Boolean isExEffectEmitter`


## Methods

- `Boolean get_isExEffectEmitter()`

- `Void ConsumeChargeTimes(Int32)`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Int32 <>xLuaBaseProxy_GetChargeIndex()`

- `Boolean <>xLuaBaseProxy_IsInChargeAction()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiExChargeUberEffectEmitter : MultiChargeUberEffectEmitter
{
	private Boolean _isExEffectEmitter; // 0x74
	private Event _chargeEffectStartEvent; // 0x78
	private ExChargeRangedAttack m_exChargeAbility; // 0x80
	private static DelegateBridge __Hotfix0_get_isExEffectEmitter; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnEvent; // 0x18
	private static DelegateBridge __Hotfix0_ConsumeChargeTimes; // 0x20
	private static DelegateBridge __Hotfix0_GetChargeIndex; // 0x28
	private static DelegateBridge __Hotfix0_IsInChargeAction; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isExEffectEmitter { get; }

	// RVA: 0x1eca12c VA: 0x75944e212c
	public Boolean get_isExEffectEmitter() { }
	// RVA: 0x1eca194 VA: 0x75944e2194
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1eca2a4 VA: 0x75944e22a4
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1eca358 VA: 0x75944e2358
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1eca558 VA: 0x75944e2558
	public Void ConsumeChargeTimes(Int32 times) { }
	// RVA: 0x1eca694 VA: 0x75944e2694
	protected override Int32 GetChargeIndex() { }
	// RVA: 0x1eca720 VA: 0x75944e2720
	protected override Boolean IsInChargeAction() { }
	// RVA: 0x1eca7d4 VA: 0x75944e27d4
	public Void .ctor() { }
	// RVA: 0x1eca840 VA: 0x75944e2840
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1eca844 VA: 0x75944e2844
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1eca848 VA: 0x75944e2848
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1eca84c VA: 0x75944e284c
	private Int32 <>xLuaBaseProxy_GetChargeIndex() { }
	// RVA: 0x1eca850 VA: 0x75944e2850
	private Boolean <>xLuaBaseProxy_IsInChargeAction() { }
}
```