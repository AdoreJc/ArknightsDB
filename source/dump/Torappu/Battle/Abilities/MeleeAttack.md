# MeleeAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `DamageType _damageType`

- `DamageType _extraDamageType`

- `Boolean _alwaysPutIncludeTargetFirst`

- `Single m_buffProb`


## Methods

- `SourceApplyWay <>xLuaBaseProxy_get_applyWay()`

- `Boolean <>xLuaBaseProxy_CheckActiveBuffs(Entity, IList`1)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_UpdateTargets(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MeleeAttack : AbstractBasicAttack
{
	private DamageType _damageType; // 0x1fc
	private DamageType _extraDamageType; // 0x200
	private Boolean _alwaysPutIncludeTargetFirst; // 0x204
	private Single m_buffProb; // 0x208
	private static DelegateBridge __Hotfix0_get_applyWay; // 0x0
	private static DelegateBridge __Hotfix0_get_damageType; // 0x8
	private static DelegateBridge __Hotfix0_get_extraDamageType; // 0x10
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x18
	private static DelegateBridge __Hotfix0_CheckActiveBuffs; // 0x20
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x28
	private static DelegateBridge __Hotfix0_DoSetData; // 0x30
	private static DelegateBridge __Hotfix0_UpdateTargets; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override SourceApplyWay applyWay { get; }
	protected override DamageType damageType { get; }
	protected override DamageType extraDamageType { get; }

	// RVA: 0x1e04dd0 VA: 0x759441cdd0
	public override SourceApplyWay get_applyWay() { }
	// RVA: 0x1e04e38 VA: 0x759441ce38
	protected override DamageType get_damageType() { }
	// RVA: 0x1e04ea0 VA: 0x759441cea0
	protected override DamageType get_extraDamageType() { }
	// RVA: 0x1e04f08 VA: 0x759441cf08
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e04f94 VA: 0x759441cf94
	protected override Boolean CheckActiveBuffs(Entity target, IList`1 buffs) { }
	// RVA: 0x1e050f4 VA: 0x759441d0f4
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e047e0 VA: 0x759441c7e0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e05174 VA: 0x759441d174
	protected override Boolean UpdateTargets(Boolean updateInputPos) { }
	// RVA: 0x1e04c48 VA: 0x759441cc48
	public Void .ctor() { }
	// RVA: 0x1e053b8 VA: 0x759441d3b8
	private SourceApplyWay <>xLuaBaseProxy_get_applyWay() { }
	// RVA: 0x1e053c0 VA: 0x759441d3c0
	private Boolean <>xLuaBaseProxy_CheckActiveBuffs(Entity P0, IList`1 P1) { }
	// RVA: 0x1e053c8 VA: 0x759441d3c8
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e053ec VA: 0x759441d3ec
	private Boolean <>xLuaBaseProxy_UpdateTargets(Boolean P0) { }
}
```