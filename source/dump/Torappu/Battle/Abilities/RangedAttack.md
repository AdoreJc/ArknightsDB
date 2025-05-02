# RangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _projectileKey`

- `MountPointType _mountPointType`

- `Boolean _useMountGroup`

- `MountPointGroup _mountGroup`

- `DamageType _damageType`

- `Boolean _waitForProjectileInvalid`

- `Boolean _fireAttackFinishWhenProjectileInvalid`

- `Single _minPostDelayWhenProjectileInvalid`

- `Boolean _waitForAnimEndWhenProjectileInvalid`

- `ProjectileDestinationType _projectileDestination`

- `DamageType _extraDamageType`

- `Boolean _emitToInputPosWhenTargetIsInvalid`

- `Boolean _emitToInputRootTileWhenTargetIsInvalid`

- `Boolean _useCachedAtkOnly`

- `Boolean _transferSource`

- `Boolean _fireCreateProjectileEvent`

- `Int32 m_mountPointIndex`


## Properties

- `Boolean emitToInputPosWhenTargetIsInvalid`

- `Boolean useCachedAtkOnly`

- `String projectileKey`

- `Boolean useMountGroup`


## Methods

- `Boolean get_emitToInputPosWhenTargetIsInvalid()`

- `Boolean get_useCachedAtkOnly()`

- `String get_projectileKey()`

- `Boolean get_useMountGroup()`

- `Void _ClearMountPointsCache()`

- `MountPoint _GetMountPoint()`

- `Boolean _CheckProjectileValid()`

- `Void OnPrefabUpdated()`

- `IEnumerator <>n__0()`

- `SourceApplyWay <>xLuaBaseProxy_get_applyWay()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Boolean <>xLuaBaseProxy_UpdateTargets(Boolean)`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_Reset()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_ClearProjectile()`

- `ApplyDamage <>xLuaBaseProxy_NewDamageNode(DamageType, FP)`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RangedAttack : AbstractBasicAttack, IOnPrefabUpdated
{
	private String _projectileKey; // 0x200
	private MountPointType _mountPointType; // 0x208
	private Boolean _useMountGroup; // 0x20c
	private MountPointGroup _mountGroup; // 0x210
	private DamageType _damageType; // 0x218
	private Boolean _waitForProjectileInvalid; // 0x21c
	private Boolean _fireAttackFinishWhenProjectileInvalid; // 0x21d
	private Single _minPostDelayWhenProjectileInvalid; // 0x220
	private Boolean _waitForAnimEndWhenProjectileInvalid; // 0x224
	private ProjectileDestinationType _projectileDestination; // 0x228
	private DamageType _extraDamageType; // 0x22c
	private Boolean _emitToInputPosWhenTargetIsInvalid; // 0x230
	private Boolean _emitToInputRootTileWhenTargetIsInvalid; // 0x231
	private Boolean _useCachedAtkOnly; // 0x232
	private Boolean _transferSource; // 0x233
	private String[] _extraProjectileKeys; // 0x238
	private Boolean _fireCreateProjectileEvent; // 0x240
	protected List`1 m_projectiles; // 0x248
	private List`1 m_mountPointsCache; // 0x250
	private Int32 m_mountPointIndex; // 0x258
	private static DelegateBridge __Hotfix0_get_waitForProjectileInvalid; // 0x0
	private static DelegateBridge __Hotfix0_get_emitToInputPosWhenTargetIsInvalid; // 0x8
	private static DelegateBridge __Hotfix0_get_applyWay; // 0x10
	private static DelegateBridge __Hotfix0_get_damageType; // 0x18
	private static DelegateBridge __Hotfix0_get_extraDamageType; // 0x20
	private static DelegateBridge __Hotfix0_get_useCachedAtkOnly; // 0x28
	private static DelegateBridge __Hotfix0_get_projectileKey; // 0x30
	private static DelegateBridge __Hotfix0_get_useMountGroup; // 0x38
	private static DelegateBridge __Hotfix0_get_mountPointCache; // 0x40
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x48
	private static DelegateBridge __Hotfix0_UpdateTargets; // 0x50
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x58
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x60
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x68
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x70
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x78
	private static DelegateBridge __Hotfix0_Reset; // 0x80
	private static DelegateBridge __Hotfix0__ClearMountPointsCache; // 0x88
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x90
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x98
	private static DelegateBridge __Hotfix0_ClearProjectile; // 0xa0
	private static DelegateBridge __Hotfix0_NewDamageNode; // 0xa8
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0xb0
	private static DelegateBridge __Hotfix0__GetMountPoint; // 0xb8
	private static DelegateBridge __Hotfix0_GetProjectileKey; // 0xc0
	private static DelegateBridge __Hotfix0__CheckProjectileValid; // 0xc8
	private static DelegateBridge __Hotfix0_CheckProjectileNameOnApplied; // 0xd0
	private static DelegateBridge __Hotfix0_OnPrefabUpdated; // 0xd8
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public virtual Boolean waitForProjectileInvalid { get; }
	protected Boolean emitToInputPosWhenTargetIsInvalid { get; }
	public override SourceApplyWay applyWay { get; }
	protected override DamageType damageType { get; }
	protected override DamageType extraDamageType { get; }
	protected Boolean useCachedAtkOnly { get; }
	protected String projectileKey { get; }
	private Boolean useMountGroup { get; }
	public List`1 mountPointCache { get; }

	// RVA: 0x1e16e00 VA: 0x759442ee00
	public virtual Boolean get_waitForProjectileInvalid() { }
	// RVA: 0x1e16e68 VA: 0x759442ee68
	protected Boolean get_emitToInputPosWhenTargetIsInvalid() { }
	// RVA: 0x1e16ed0 VA: 0x759442eed0
	public override SourceApplyWay get_applyWay() { }
	// RVA: 0x1e16f38 VA: 0x759442ef38
	protected override DamageType get_damageType() { }
	// RVA: 0x1e16fa0 VA: 0x759442efa0
	protected override DamageType get_extraDamageType() { }
	// RVA: 0x1e17008 VA: 0x759442f008
	protected Boolean get_useCachedAtkOnly() { }
	// RVA: 0x1e11290 VA: 0x7594429290
	protected String get_projectileKey() { }
	// RVA: 0x1e17070 VA: 0x759442f070
	private Boolean get_useMountGroup() { }
	// RVA: 0x1e170d8 VA: 0x759442f0d8
	public List`1 get_mountPointCache() { }
	// RVA: 0x1e128a0 VA: 0x759442a8a0
	protected override Void OnCastStart() { }
	// RVA: 0x1e1514c VA: 0x759442d14c
	protected override Boolean UpdateTargets(Boolean updateInputPos) { }
	// RVA: 0x1e0c2dc VA: 0x75944242dc
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0c828 VA: 0x7594424828
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e17140 VA: 0x759442f140
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e14f48 VA: 0x759442cf48
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e0d0f8 VA: 0x75944250f8
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e0eb24 VA: 0x7594426b24
	protected override Void Reset() { }
	// RVA: 0x1e171b8 VA: 0x759442f1b8
	private Void _ClearMountPointsCache() { }
	// RVA: 0x1e17240 VA: 0x759442f240
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e11690 VA: 0x7594429690
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e17314 VA: 0x759442f314
	public override Void ClearProjectile() { }
	// RVA: 0x1e17480 VA: 0x759442f480
	protected override ApplyDamage NewDamageNode(DamageType damageType, FP atkScale) { }
	// RVA: 0x1e0ce80 VA: 0x7594424e80
	protected virtual Projectile CreateProjectile(ILocatable target, out Projectile fakeProjectile) { }
	// RVA: 0x1e175d8 VA: 0x759442f5d8
	private MountPoint _GetMountPoint() { }
	// RVA: 0x1e158d8 VA: 0x759442d8d8
	protected virtual String GetProjectileKey() { }
	// RVA: 0x1e176e0 VA: 0x759442f6e0
	private Boolean _CheckProjectileValid() { }
	// RVA: 0x1e15cb0 VA: 0x759442dcb0
	protected virtual Void CheckProjectileNameOnApplied(String projectileKey) { }
	// RVA: 0x1e17834 VA: 0x759442f834
	public Void OnPrefabUpdated() { }
	// RVA: 0x1e17898 VA: 0x759442f898
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1e0c204 VA: 0x7594424204
	public Void .ctor() { }
	// RVA: 0x1e179f8 VA: 0x759442f9f8
	private IEnumerator <>n__0() { }
	// RVA: 0x1e17a00 VA: 0x759442fa00
	private SourceApplyWay <>xLuaBaseProxy_get_applyWay() { }
	// RVA: 0x1e17a08 VA: 0x759442fa08
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e17a10 VA: 0x759442fa10
	private Boolean <>xLuaBaseProxy_UpdateTargets(Boolean P0) { }
	// RVA: 0x1e17a1c VA: 0x759442fa1c
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e17a24 VA: 0x759442fa24
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e17a2c VA: 0x759442fa2c
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e17a34 VA: 0x759442fa34
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e17a3c VA: 0x759442fa3c
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
	// RVA: 0x1e17a44 VA: 0x759442fa44
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e17a4c VA: 0x759442fa4c
	private Void <>xLuaBaseProxy_ClearProjectile() { }
	// RVA: 0x1e17a54 VA: 0x759442fa54
	private ApplyDamage <>xLuaBaseProxy_NewDamageNode(DamageType P0, FP P1) { }
	// RVA: 0x1e17a5c VA: 0x759442fa5c
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
}
```