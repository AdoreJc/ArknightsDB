# BsnakeScreenAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _projectileKey`

- `DamageType _damageType`

- `Int32 _borderToPeel`

- `Single _heightOverHighland`


## Methods

- `SourceApplyWay <>xLuaBaseProxy_get_applyWay()`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BsnakeScreenAttack : AbstractBasicAttack
{
	private String _projectileKey; // 0x200
	private DamageType _damageType; // 0x208
	private Int32 _borderToPeel; // 0x20c
	private Single _heightOverHighland; // 0x210
	protected List`1 m_projectiles; // 0x218
	private static DelegateBridge __Hotfix0_get_damageType; // 0x0
	private static DelegateBridge __Hotfix0_get_extraDamageType; // 0x8
	private static DelegateBridge __Hotfix0_get_applyWay; // 0x10
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x18
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x20
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x28
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x30
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x38
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected override DamageType damageType { get; }
	protected override DamageType extraDamageType { get; }
	public override SourceApplyWay applyWay { get; }

	// RVA: 0x1e6cd60 VA: 0x7594484d60
	protected override DamageType get_damageType() { }
	// RVA: 0x1e6cdc8 VA: 0x7594484dc8
	protected override DamageType get_extraDamageType() { }
	// RVA: 0x1e6ce2c VA: 0x7594484e2c
	public override SourceApplyWay get_applyWay() { }
	// RVA: 0x1e6ce94 VA: 0x7594484e94
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e6d178 VA: 0x7594485178
	protected override Void OnCastStart() { }
	// RVA: 0x1e6d22c VA: 0x759448522c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e6d2a4 VA: 0x75944852a4
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e6d34c VA: 0x759448534c
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e6d470 VA: 0x7594485470
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1e6d5d0 VA: 0x75944855d0
	public Void .ctor() { }
	// RVA: 0x1e6d69c VA: 0x759448569c
	private SourceApplyWay <>xLuaBaseProxy_get_applyWay() { }
	// RVA: 0x1e6d6a4 VA: 0x75944856a4
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e6d6ac VA: 0x75944856ac
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e6d6b4 VA: 0x75944856b4
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e6d6bc VA: 0x75944856bc
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
}
```