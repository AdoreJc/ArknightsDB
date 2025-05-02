# NightmSkill_1

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ProjectileOptions _primaryOptions`

- `ProjectileOptions _secondaryOptions`

- `TargetSelector _secondarySelector`


## Methods

- `Void _OnHitPrimaryTarget(Entity)`

- `SourceApplyWay <>xLuaBaseProxy_get_applyWay()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `ActionPurposeMask <>xLuaBaseProxy_GeneratePurposeMask()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class NightmSkill_1 : AbstractBasicAttack
{
	private ProjectileOptions _primaryOptions; // 0x200
	private ProjectileOptions _secondaryOptions; // 0x208
	private TargetSelector _secondarySelector; // 0x210
	private List`1 m_secondaryActions; // 0x218
	private static DelegateBridge __Hotfix0_get_applyWay; // 0x0
	private static DelegateBridge __Hotfix0_get_damageType; // 0x8
	private static DelegateBridge __Hotfix0_get_extraDamageType; // 0x10
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x18
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x20
	private static DelegateBridge __Hotfix0_DoSetData; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x38
	private static DelegateBridge __Hotfix0__OnHitPrimaryTarget; // 0x40
	private static DelegateBridge __Hotfix0_GeneratePurposeMask; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override SourceApplyWay applyWay { get; }
	protected override DamageType damageType { get; }
	protected override DamageType extraDamageType { get; }

	// RVA: 0x1eaef04 VA: 0x75944c6f04
	public override SourceApplyWay get_applyWay() { }
	// RVA: 0x1eaef6c VA: 0x75944c6f6c
	protected override DamageType get_damageType() { }
	// RVA: 0x1eaefe0 VA: 0x75944c6fe0
	protected override DamageType get_extraDamageType() { }
	// RVA: 0x1eaf044 VA: 0x75944c7044
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1eaf0d0 VA: 0x75944c70d0
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1eaf178 VA: 0x75944c7178
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1eaf40c VA: 0x75944c740c
	protected override Void Reset() { }
	// RVA: 0x1eaf4f4 VA: 0x75944c74f4
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1eaf5b4 VA: 0x75944c75b4
	private Void _OnHitPrimaryTarget(Entity primaryTarget) { }
	// RVA: 0x1eaf91c VA: 0x75944c791c
	protected override ActionPurposeMask GeneratePurposeMask() { }
	// RVA: 0x1eaf984 VA: 0x75944c7984
	public Void .ctor() { }
	// RVA: 0x1eafadc VA: 0x75944c7adc
	private SourceApplyWay <>xLuaBaseProxy_get_applyWay() { }
	// RVA: 0x1eafae4 VA: 0x75944c7ae4
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1eafb0c VA: 0x75944c7b0c
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1eafb14 VA: 0x75944c7b14
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1eafb1c VA: 0x75944c7b1c
	private ActionPurposeMask <>xLuaBaseProxy_GeneratePurposeMask() { }
}
```