# Whitw2Skill3FunnelRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _useExtraActiveCntAbility`

- `Single _projectileInitRadius`

- `Boolean _clearProjectilesWhenDetached`

- `Int32 m_activeCnt`

- `Int32 m_alreadyAttackCnt`

- `MultiFunnelExtraActiveCntAbility m_extraActiveCntStorage`

- `Single m_projectileAroundRadius`


## Methods

- `Void _DoPlayAttack(Entity)`

- `Void UpdateActiveCntIfAdded()`

- `Void RuntimeApplyAttack(Entity)`

- `Projectile _CreateAroundProjectile(ILocatable, out, Int32)`

- `Void _CalculateProjectilesStartPos(Entity)`

- `Void AttachFunnelProjectileToTarget(Unit, Int32)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class Whitw2Skill3FunnelRangedAttack : RangedAttack
{
	private Boolean _useExtraActiveCntAbility; // 0x25c
	private Single _projectileInitRadius; // 0x260
	private Boolean _clearProjectilesWhenDetached; // 0x264
	private String[] _cruiseProjectileKeys; // 0x268
	private String[] _funnelProjectileKeys; // 0x270
	private Ability[] _funnelActions; // 0x278
	private Int32 m_activeCnt; // 0x280
	private Int32 m_alreadyAttackCnt; // 0x284
	private MultiFunnelExtraActiveCntAbility m_extraActiveCntStorage; // 0x288
	private List`1 m_projectileStartPos; // 0x290
	private Single m_projectileAroundRadius; // 0x298
	private List`1 m_cruiseProjectile; // 0x2a0
	private List`1 m_funnelProjectile; // 0x2a8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x10
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x18
	private static DelegateBridge __Hotfix0__DoPlayAttack; // 0x20
	private static DelegateBridge __Hotfix0_OnDetached; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge __Hotfix0_UpdateActiveCntIfAdded; // 0x38
	private static DelegateBridge __Hotfix0_RuntimeApplyAttack; // 0x40
	private static DelegateBridge __Hotfix0__CreateAroundProjectile; // 0x48
	private static DelegateBridge __Hotfix0__CalculateProjectilesStartPos; // 0x50
	private static DelegateBridge __Hotfix0_AttachFunnelProjectileToTarget; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x1e19e44 VA: 0x7594431e44
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e19fc4 VA: 0x7594431fc4
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e1a384 VA: 0x7594432384
	protected override Void OnCastStart() { }
	// RVA: 0x1e1a4b8 VA: 0x75944324b8
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e1a55c VA: 0x759443255c
	private Void _DoPlayAttack(Entity target) { }
	// RVA: 0x1e1ada0 VA: 0x7594432da0
	protected override Void OnDetached() { }
	// RVA: 0x1e1b110 VA: 0x7594433110
	protected override Void Reset() { }
	// RVA: 0x1e1a25c VA: 0x759443225c
	public Void UpdateActiveCntIfAdded() { }
	// RVA: 0x1e1b1f4 VA: 0x75944331f4
	public Void RuntimeApplyAttack(Entity target) { }
	// RVA: 0x1e1ac40 VA: 0x7594432c40
	private Projectile _CreateAroundProjectile(ILocatable target, out Projectile fakeProjectile, Int32 projectileIndex) { }
	// RVA: 0x1e1a81c VA: 0x759443281c
	private Void _CalculateProjectilesStartPos(Entity target) { }
	// RVA: 0x1e1b348 VA: 0x7594433348
	public Void AttachFunnelProjectileToTarget(Unit target, Int32 projectileIndex) { }
	// RVA: 0x1e1b73c VA: 0x759443373c
	public Void .ctor() { }
	// RVA: 0x1e1b890 VA: 0x7594433890
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e1b8b8 VA: 0x75944338b8
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e1b8c0 VA: 0x75944338c0
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e1b8c4 VA: 0x75944338c4
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e1b8c8 VA: 0x75944338c8
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e1b8d0 VA: 0x75944338d0
	private Void <>xLuaBaseProxy_Reset() { }
}
```