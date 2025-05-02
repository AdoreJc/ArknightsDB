# AdvancedCompoundToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _isInitToggled`

- `Boolean _disableWhenAttack`

- `Boolean _disableWhenBlocked`

- `Boolean _disableWhenInAttackState`

- `Boolean _disableWhenInCombatState`

- `Boolean _disableWhenOutputHeal`

- `Boolean _disableWhenTakeDamage`

- `Boolean _disableWhenAppliedModifier`

- `Boolean _disableWhenAppliedDamageModifier`

- `Boolean _disableWhenMoving`

- `Single _restoreDelay`

- `Single m_restoreDelay`


## Properties

- `Boolean disableWhenAppliedModifier`


## Methods

- `Boolean get_disableWhenAppliedModifier()`

- `Void _OnOutputDamage(Object)`

- `Void _OnOutputHeal(Object)`

- `Void _OnTakeDamage(Object)`

- `Void _OnAppliedModifier(Object)`

- `Single <>xLuaBaseProxy_get_restoreDelay()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AdvancedCompoundToggleChecker : Checker
{
	private Boolean _isInitToggled; // 0x20
	private Boolean _disableWhenAttack; // 0x21
	private Boolean _disableWhenBlocked; // 0x22
	private Boolean _disableWhenInAttackState; // 0x23
	private Boolean _disableWhenInCombatState; // 0x24
	private Boolean _disableWhenOutputHeal; // 0x25
	private Boolean _disableWhenTakeDamage; // 0x26
	private Boolean _disableWhenAppliedModifier; // 0x27
	private Boolean _disableWhenAppliedDamageModifier; // 0x28
	private Boolean _disableWhenMoving; // 0x29
	private Single _restoreDelay; // 0x2c
	private Single m_restoreDelay; // 0x30
	private static DelegateBridge __Hotfix0_get_disableWhenAppliedModifier; // 0x0
	private static DelegateBridge __Hotfix0_get_restoreDelay; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_OnAttached; // 0x18
	private static DelegateBridge __Hotfix0_OnDetached; // 0x20
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x28
	private static DelegateBridge __Hotfix0_OnTick; // 0x30
	private static DelegateBridge __Hotfix0__OnOutputDamage; // 0x38
	private static DelegateBridge __Hotfix0__OnOutputHeal; // 0x40
	private static DelegateBridge __Hotfix0__OnTakeDamage; // 0x48
	private static DelegateBridge __Hotfix0__OnAppliedModifier; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean disableWhenAppliedModifier { get; }
	public override Single restoreDelay { get; }

	// RVA: 0x1e5810c VA: 0x759447010c
	public Boolean get_disableWhenAppliedModifier() { }
	// RVA: 0x1e58174 VA: 0x7594470174
	public override Single get_restoreDelay() { }
	// RVA: 0x1e581dc VA: 0x75944701dc
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e58290 VA: 0x7594470290
	public override Void OnAttached() { }
	// RVA: 0x1e584c8 VA: 0x75944704c8
	public override Void OnDetached() { }
	// RVA: 0x1e58700 VA: 0x7594470700
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e58768 VA: 0x7594470768
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e58d30 VA: 0x7594470d30
	private Void _OnOutputDamage(Object arg) { }
	// RVA: 0x1e58dfc VA: 0x7594470dfc
	private Void _OnOutputHeal(Object arg) { }
	// RVA: 0x1e58f3c VA: 0x7594470f3c
	private Void _OnTakeDamage(Object arg) { }
	// RVA: 0x1e59008 VA: 0x7594471008
	private Void _OnAppliedModifier(Object arg) { }
	// RVA: 0x1e59198 VA: 0x7594471198
	public Void .ctor() { }
	// RVA: 0x1e5920c VA: 0x759447120c
	private Single <>xLuaBaseProxy_get_restoreDelay() { }
	// RVA: 0x1e59278 VA: 0x7594471278
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e5927c VA: 0x759447127c
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e59280 VA: 0x7594471280
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```