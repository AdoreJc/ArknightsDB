# InteractableBounceEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `BounceEnemyPhysicalFeatureTalent _phyTalent`

- `FilterType _triggerForceFilterType`

- `Boolean _disableIdleAnimation`

- `ActionArray _actionsToSelfWhenCollide`

- `ActionArray _actionsToTargetWhenCollide`

- `FP m_triggerTotalDmg`

- `FP m_bounceFrictionFactor`

- `FP m_attenuation`

- `FP m_kickBackDefaultForce`

- `Tile m_cacheRootTile`

- `ForceInfo m_cachedForceInfo`

- `UIForceInfo m_cachedForceInfoUI`

- `ForceInfo m_descriteForceInfo`


## Properties

- `ForceInfo baseTypeCachedForceInfo`

- `UIForceInfo baseTypeCachedForceInfoUI`

- `ForceInfo baseTypeDescriteForceInfo`


## Methods

- `ForceInfo get_baseTypeCachedForceInfo()`

- `UIForceInfo get_baseTypeCachedForceInfoUI()`

- `ForceInfo get_baseTypeDescriteForceInfo()`

- `Void _FindSurroundingTiles()`

- `Void OnCollisionEnter2D(Collision2D)`

- `Boolean <>xLuaBaseProxy_get_disableUIUnitHud()`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`

- `Void <>xLuaBaseProxy_PlayUnbalanceAnimation()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class InteractableBounceEnemy : BounceEnemy
{
	protected BounceEnemyPhysicalFeatureTalent _phyTalent; // 0x4c0
	protected FilterType _triggerForceFilterType; // 0x4c8
	protected Boolean _disableIdleAnimation; // 0x4cc
	protected ActionArray _actionsToSelfWhenCollide; // 0x4d0
	protected ActionArray _actionsToTargetWhenCollide; // 0x4d8
	protected readonly String MOVE_LEFT_KEY; // 0x4e0
	protected readonly String MOVE_RIGHT_KEY; // 0x4e8
	protected FP m_triggerTotalDmg; // 0x4f0
	protected FP m_bounceFrictionFactor; // 0x4f8
	protected FP m_attenuation; // 0x500
	protected FP m_kickBackDefaultForce; // 0x508
	protected Tile m_cacheRootTile; // 0x510
	protected readonly HashSet`1 m_surroundTiles; // 0x518
	protected ForceInfo m_cachedForceInfo; // 0x520
	protected UIForceInfo m_cachedForceInfoUI; // 0x528
	protected ForceInfo m_descriteForceInfo; // 0x530
	private static DelegateBridge __Hotfix0_get_disableUIUnitHud; // 0x0
	private static DelegateBridge __Hotfix0_get_baseTypeCachedForceInfo; // 0x8
	private static DelegateBridge __Hotfix0_get_baseTypeCachedForceInfoUI; // 0x10
	private static DelegateBridge __Hotfix0_get_baseTypeDescriteForceInfo; // 0x18
	private static DelegateBridge __Hotfix0_UpdatePhysicalParams; // 0x20
	private static DelegateBridge __Hotfix0_ApplyForce; // 0x28
	private static DelegateBridge __Hotfix0__ShouldApplyFinalForce; // 0x30
	private static DelegateBridge __Hotfix0__ApplyFinalForce; // 0x38
	private static DelegateBridge __Hotfix0_GetForceScaler; // 0x40
	private static DelegateBridge __Hotfix0__FindSurroundingTiles; // 0x48
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x50
	private static DelegateBridge __Hotfix0__RunActionsOnTargetWhenCollide; // 0x58
	private static DelegateBridge __Hotfix0__RunActionsOnSelfWhenCollide; // 0x60
	private static DelegateBridge __Hotfix0__UpdateAnimation; // 0x68
	private static DelegateBridge __Hotfix0_PlayUnbalanceAnimation; // 0x70
	private static DelegateBridge __Hotfix0__UpdateUnbalanceAnimation; // 0x78
	private static DelegateBridge __Hotfix0_OnTick; // 0x80
	private static DelegateBridge __Hotfix0_OnCollisionEnter2D; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public override Boolean disableUIUnitHud { get; }
	protected ForceInfo baseTypeCachedForceInfo { get; }
	protected UIForceInfo baseTypeCachedForceInfoUI { get; }
	public ForceInfo baseTypeDescriteForceInfo { get; }

	// RVA: 0x1c21f4c VA: 0x7594239f4c
	public override Boolean get_disableUIUnitHud() { }
	// RVA: 0x1c21fb0 VA: 0x7594239fb0
	protected ForceInfo get_baseTypeCachedForceInfo() { }
	// RVA: 0x1c220d0 VA: 0x759423a0d0
	protected UIForceInfo get_baseTypeCachedForceInfoUI() { }
	// RVA: 0x1c221f0 VA: 0x759423a1f0
	public ForceInfo get_baseTypeDescriteForceInfo() { }
	// RVA: 0x1c222a0 VA: 0x759423a2a0
	public virtual Void UpdatePhysicalParams(IPhysicalParams pparams) { }
	// RVA: 0x1c22480 VA: 0x759423a480
	public virtual Void ApplyForce(Entity forceSource, IForceInfo forceInfo) { }
	// RVA: 0x1c227e8 VA: 0x759423a7e8
	protected virtual Boolean _ShouldApplyFinalForce(IForceInfo cachedForceInfo) { }
	// RVA: 0x1c22904 VA: 0x759423a904
	protected virtual Void _ApplyFinalForce(IForceInfo finalForceInfo) { }
	// RVA: 0x1c22c74 VA: 0x759423ac74
	public virtual FP GetForceScaler(Entity forceSource) { }
	// RVA: 0x1c22e28 VA: 0x759423ae28
	protected Void _FindSurroundingTiles() { }
	// RVA: 0x1c22fc4 VA: 0x759423afc4
	public override Void GatherActionNodes(List`1 actions) { }
	// RVA: 0x1c23184 VA: 0x759423b184
	protected virtual Void _RunActionsOnTargetWhenCollide(Entity target) { }
	// RVA: 0x1c23434 VA: 0x759423b434
	protected virtual Void _RunActionsOnSelfWhenCollide(Entity target) { }
	// RVA: 0x1c236e4 VA: 0x759423b6e4
	protected virtual Void _UpdateAnimation(FP deltaTime) { }
	// RVA: 0x1c23868 VA: 0x759423b868
	public override Void PlayUnbalanceAnimation() { }
	// RVA: 0x1c238dc VA: 0x759423b8dc
	protected virtual Void _UpdateUnbalanceAnimation() { }
	// RVA: 0x1c239dc VA: 0x759423b9dc
	public override Void OnTick(FP fixedDeltaTime) { }
	// RVA: 0x1c23a78 VA: 0x759423ba78
	private Void OnCollisionEnter2D(Collision2D other) { }
	// RVA: 0x1c23c80 VA: 0x759423bc80
	public Void .ctor() { }
	// RVA: 0x1c23e48 VA: 0x759423be48
	private Boolean <>xLuaBaseProxy_get_disableUIUnitHud() { }
	// RVA: 0x1c23e50 VA: 0x759423be50
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
	// RVA: 0x1c23e54 VA: 0x759423be54
	private Void <>xLuaBaseProxy_PlayUnbalanceAnimation() { }
	// RVA: 0x1c23e5c VA: 0x759423be5c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```