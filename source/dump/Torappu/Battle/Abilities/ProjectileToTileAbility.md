# ProjectileToTileAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _projectileKey`

- `MountPointType _mountPointType`

- `DamageType _damageType`

- `Single _atkScale`

- `String _atkScaleKey`

- `ElementType _elementDamageType`

- `Single _epDamageRatio`

- `Boolean _finishProjectileWhenCastStart`

- `Boolean _waitForProjectileInvalid`

- `Boolean _fireAttackFinishWhenProjectileInvalid`

- `Single _minPostDelayWhenProjectileInvalid`

- `SourceAttackType _attackType`

- `FP m_epDamageRatio`

- `FP m_atkScale`


## Properties

- `Boolean waitForProjectileInvalid`

- `Boolean hasEpDamage`


## Methods

- `Boolean get_waitForProjectileInvalid()`

- `Boolean get_hasEpDamage()`

- `Void CreateAndReplaceDamageNode(Single, IList`1)`

- `Boolean _CheckProjectileValid()`

- `IEnumerator <>n__0()`

- `SourceApplyWay <>xLuaBaseProxy_get_applyWay()`

- `SourceAttackType <>xLuaBaseProxy_get_attackType()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastOnTile(Tile, IList`1, IList`1, IList`1)`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Boolean <>xLuaBaseProxy_CheckIsDamageOrHealSource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ProjectileToTileAbility : CastOnTileAbility
{
	private String _projectileKey; // 0x1f8
	private MountPointType _mountPointType; // 0x200
	private DamageType _damageType; // 0x204
	private Single _atkScale; // 0x208
	private String _atkScaleKey; // 0x210
	private ElementType _elementDamageType; // 0x218
	private Single _epDamageRatio; // 0x21c
	private Boolean _finishProjectileWhenCastStart; // 0x220
	private Boolean _waitForProjectileInvalid; // 0x221
	private Boolean _fireAttackFinishWhenProjectileInvalid; // 0x222
	private Single _minPostDelayWhenProjectileInvalid; // 0x224
	private SourceAttackType _attackType; // 0x228
	private List`1 m_projectiles; // 0x230
	private FP m_epDamageRatio; // 0x238
	protected FP m_atkScale; // 0x240
	protected List`1 m_actions; // 0x248
	private static DelegateBridge __Hotfix0_get_waitForProjectileInvalid; // 0x0
	private static DelegateBridge __Hotfix0_get_hasEpDamage; // 0x8
	private static DelegateBridge __Hotfix0_get_applyWay; // 0x10
	private static DelegateBridge __Hotfix0_get_attackType; // 0x18
	private static DelegateBridge __Hotfix0_DoSetData; // 0x20
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x28
	private static DelegateBridge __Hotfix0_CreateAndReplaceDamageNode; // 0x30
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x38
	private static DelegateBridge __Hotfix0_Reset; // 0x40
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x48
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x50
	private static DelegateBridge __Hotfix0_OnCastOnTile; // 0x58
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x60
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x68
	private static DelegateBridge __Hotfix0_CheckIsDamageOrHealSource; // 0x70
	private static DelegateBridge __Hotfix0__CheckProjectileValid; // 0x78
	private static DelegateBridge __Hotfix0_GetProjectileKey; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Boolean waitForProjectileInvalid { get; }
	public Boolean hasEpDamage { get; }
	public override SourceApplyWay applyWay { get; }
	protected override SourceAttackType attackType { get; }

	// RVA: 0x1e288d4 VA: 0x75944408d4
	public Boolean get_waitForProjectileInvalid() { }
	// RVA: 0x1e2893c VA: 0x759444093c
	public Boolean get_hasEpDamage() { }
	// RVA: 0x1e289ac VA: 0x75944409ac
	public override SourceApplyWay get_applyWay() { }
	// RVA: 0x1e28a14 VA: 0x7594440a14
	protected override SourceAttackType get_attackType() { }
	// RVA: 0x1e264dc VA: 0x759443e4dc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e28a7c VA: 0x7594440a7c
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e28b24 VA: 0x7594440b24
	public Void CreateAndReplaceDamageNode(Single atkScale, IList`1 actionNodes) { }
	// RVA: 0x1e278e8 VA: 0x759443f8e8
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e28f24 VA: 0x7594440f24
	protected override Void Reset() { }
	// RVA: 0x1e28fd8 VA: 0x7594440fd8
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e26e70 VA: 0x759443ee70
	protected override Void OnCastStart() { }
	// RVA: 0x1e29050 VA: 0x7594441050
	protected override Void OnCastOnTile(Tile tile, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e27c6c VA: 0x759443fc6c
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e270ac VA: 0x759443f0ac
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e29324 VA: 0x7594441324
	protected override Boolean CheckIsDamageOrHealSource() { }
	// RVA: 0x1e2938c VA: 0x759444138c
	private Boolean _CheckProjectileValid() { }
	// RVA: 0x1e277a0 VA: 0x759443f7a0
	protected virtual String GetProjectileKey() { }
	// RVA: 0x1e27ac0 VA: 0x759443fac0
	public Void .ctor() { }
	// RVA: 0x1e294e0 VA: 0x75944414e0
	private IEnumerator <>n__0() { }
	// RVA: 0x1e294e8 VA: 0x75944414e8
	private SourceApplyWay <>xLuaBaseProxy_get_applyWay() { }
	// RVA: 0x1e294f0 VA: 0x75944414f0
	private SourceAttackType <>xLuaBaseProxy_get_attackType() { }
	// RVA: 0x1e294f8 VA: 0x75944414f8
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e29520 VA: 0x7594441520
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1e29524 VA: 0x7594441524
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e2952c VA: 0x759444152c
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e29534 VA: 0x7594441534
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e29538 VA: 0x7594441538
	private Void <>xLuaBaseProxy_OnCastOnTile(Tile P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e2953c VA: 0x759444153c
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
	// RVA: 0x1e29544 VA: 0x7594441544
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e29548 VA: 0x7594441548
	private Boolean <>xLuaBaseProxy_CheckIsDamageOrHealSource() { }
}
```