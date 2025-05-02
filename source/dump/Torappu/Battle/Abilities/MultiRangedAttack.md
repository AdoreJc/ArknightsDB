# MultiRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _additionalTimes`

- `Single _triggerDelta`

- `Boolean _waitAttackEventForAllAttacks`

- `String _additionalProjectile`

- `Boolean _useMultiAdditionalProjectiles`

- `Boolean _enableMountPointGroup`

- `Boolean _onlyFeedActionsToFirstOne`

- `Boolean _onlyTrigAudioSignalForFirstOne`

- `Boolean _limitToOneTargetAfterFirstRound`

- `Boolean _splitDamage`

- `Boolean _addSpellCntToSignalId`

- `Boolean _onlyFeedActiveBuffToLastOne`

- `Boolean _onlyFeedActiveBuffToFirstOne`

- `Boolean _refreshTimesOnCastStart`

- `Boolean _castToFirstRoundTargetLocationsAtProjectileBirth`

- `String _hookTheLastProjectile`

- `Single m_triggerDelta`

- `Boolean m_alreadyFeedFirstOne`

- `ModifierSplitter m_damageSplitter`

- `MultiEventListener m_multiEventListener`


## Properties

- `Boolean useMultiAdditionalProjectiles`

- `Boolean enableMountPointGroup`

- `Boolean waitAttackEventForAllAttacks`

- `Boolean isLastSpell`

- `Int32 additionalTimes`


## Methods

- `Boolean get_useMultiAdditionalProjectiles()`

- `Boolean get_enableMountPointGroup()`

- `Boolean get_waitAttackEventForAllAttacks()`

- `Boolean get_isLastSpell()`

- `Int32 get_additionalTimes()`

- `IEnumerator <>n__0()`

- `Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstSpell()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32)`

- `Boolean <>xLuaBaseProxy_UpdateTargets(Boolean)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_DoApplyActionsOnTarget(Entity, IList`1)`

- `Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable, out)`

- `Void <>xLuaBaseProxy_Reset()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta()`

- `String <>xLuaBaseProxy_GetProjectileKey()`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_CheckProjectileNameOnApplied(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiRangedAttack : RangedAttack
{
	private Int32 _additionalTimes; // 0x25c
	private Single _triggerDelta; // 0x260
	private Boolean _waitAttackEventForAllAttacks; // 0x264
	private String _additionalProjectile; // 0x268
	private Boolean _useMultiAdditionalProjectiles; // 0x270
	private String[] _additionalProjectiles; // 0x278
	private Boolean _enableMountPointGroup; // 0x280
	private MountPointType[] _mountPointGroup; // 0x288
	private Boolean _onlyFeedActionsToFirstOne; // 0x290
	private Boolean _onlyTrigAudioSignalForFirstOne; // 0x291
	private Boolean _limitToOneTargetAfterFirstRound; // 0x292
	private Boolean _splitDamage; // 0x293
	private Boolean _addSpellCntToSignalId; // 0x294
	private Boolean _onlyFeedActiveBuffToLastOne; // 0x295
	private Boolean _onlyFeedActiveBuffToFirstOne; // 0x296
	private Boolean _refreshTimesOnCastStart; // 0x297
	private Boolean _castToFirstRoundTargetLocationsAtProjectileBirth; // 0x298
	private String _hookTheLastProjectile; // 0x2a0
	private Single m_triggerDelta; // 0x2a8
	private Boolean m_alreadyFeedFirstOne; // 0x2ac
	private ModifierSplitter m_damageSplitter; // 0x2b0
	private MultiEventListener m_multiEventListener; // 0x2b8
	private List`1 m_locationsFirstSpellCastTo; // 0x2c0
	private static DelegateBridge __Hotfix0_get_useMultiAdditionalProjectiles; // 0x0
	private static DelegateBridge __Hotfix0_get_enableMountPointGroup; // 0x8
	private static DelegateBridge __Hotfix0_get_waitAttackEventForAllAttacks; // 0x10
	private static DelegateBridge __Hotfix0_get_isLastSpell; // 0x18
	private static DelegateBridge __Hotfix0_get_onlyTrigAudioSignalForFirstSpell; // 0x20
	private static DelegateBridge __Hotfix0_get_additionalTimes; // 0x28
	private static DelegateBridge __Hotfix0_DoSetData; // 0x30
	private static DelegateBridge __Hotfix0_DoAttach; // 0x38
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x40
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x48
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x50
	private static DelegateBridge __Hotfix0_CheckAnotherSpell; // 0x58
	private static DelegateBridge __Hotfix0_UpdateTargets; // 0x60
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x68
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x70
	private static DelegateBridge __Hotfix0_DoApplyActionsOnTarget; // 0x78
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x80
	private static DelegateBridge __Hotfix0_Reset; // 0x88
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x90
	private static DelegateBridge __Hotfix0_OnWaitForTriggerDelta; // 0x98
	private static DelegateBridge __Hotfix0_GetProjectileKey; // 0xa0
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0xa8
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0xb0
	private static DelegateBridge __Hotfix0_CheckProjectileNameOnApplied; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	private Boolean useMultiAdditionalProjectiles { get; }
	private Boolean enableMountPointGroup { get; }
	public Boolean waitAttackEventForAllAttacks { get; }
	public Boolean isLastSpell { get; }
	protected override Boolean onlyTrigAudioSignalForFirstSpell { get; }
	protected Int32 additionalTimes { get; }

	// RVA: 0x1e14b60 VA: 0x759442cb60
	private Boolean get_useMultiAdditionalProjectiles() { }
	// RVA: 0x1e14bc8 VA: 0x759442cbc8
	private Boolean get_enableMountPointGroup() { }
	// RVA: 0x1e14c30 VA: 0x759442cc30
	public Boolean get_waitAttackEventForAllAttacks() { }
	// RVA: 0x1e14c98 VA: 0x759442cc98
	public Boolean get_isLastSpell() { }
	// RVA: 0x1e14d1c VA: 0x759442cd1c
	protected override Boolean get_onlyTrigAudioSignalForFirstSpell() { }
	// RVA: 0x1e11abc VA: 0x7594429abc
	protected Int32 get_additionalTimes() { }
	// RVA: 0x1e11970 VA: 0x7594429970
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e14d84 VA: 0x759442cd84
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e14e90 VA: 0x759442ce90
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e104c4 VA: 0x75944284c4
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e14ff0 VA: 0x759442cff0
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e11bd4 VA: 0x7594429bd4
	protected override Boolean CheckAnotherSpell(Int32 spellCnt) { }
	// RVA: 0x1e11f34 VA: 0x7594429f34
	protected override Boolean UpdateTargets(Boolean updateInputPos) { }
	// RVA: 0x1e0f87c VA: 0x759442787c
	protected override Void OnCastStart() { }
	// RVA: 0x1e1534c VA: 0x759442d34c
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e153f8 VA: 0x759442d3f8
	protected override Void DoApplyActionsOnTarget(Entity target, IList`1 actions) { }
	// RVA: 0x1e107bc VA: 0x75944287bc
	protected override Projectile CreateProjectile(ILocatable target, out Projectile fakeProjectile) { }
	// RVA: 0x1e15568 VA: 0x759442d568
	protected override Void Reset() { }
	// RVA: 0x1e155f8 VA: 0x759442d5f8
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e156cc VA: 0x759442d6cc
	protected override IEnumerator OnWaitForTriggerDelta() { }
	// RVA: 0x1e157a0 VA: 0x759442d7a0
	protected override String GetProjectileKey() { }
	// RVA: 0x1e15940 VA: 0x759442d940
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e15b1c VA: 0x759442db1c
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e15bd0 VA: 0x759442dbd0
	protected override Void CheckProjectileNameOnApplied(String projectileKey) { }
	// RVA: 0x1e10378 VA: 0x7594428378
	public Void .ctor() { }
	// RVA: 0x1e15dbc VA: 0x759442ddbc
	private IEnumerator <>n__0() { }
	// RVA: 0x1e15dc4 VA: 0x759442ddc4
	private Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstSpell() { }
	// RVA: 0x1e15dcc VA: 0x759442ddcc
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e15df4 VA: 0x759442ddf4
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e15dfc VA: 0x759442ddfc
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1e15e00 VA: 0x759442de00
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e15e04 VA: 0x759442de04
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e15e08 VA: 0x759442de08
	private Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32 P0) { }
	// RVA: 0x1e15e10 VA: 0x759442de10
	private Boolean <>xLuaBaseProxy_UpdateTargets(Boolean P0) { }
	// RVA: 0x1e15e18 VA: 0x759442de18
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e15e1c VA: 0x759442de1c
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e15e20 VA: 0x759442de20
	private Void <>xLuaBaseProxy_DoApplyActionsOnTarget(Entity P0, IList`1 P1) { }
	// RVA: 0x1e15e28 VA: 0x759442de28
	private Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable P0, out Projectile P1) { }
	// RVA: 0x1e15e2c VA: 0x759442de2c
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e15e30 VA: 0x759442de30
	private IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay() { }
	// RVA: 0x1e15e38 VA: 0x759442de38
	private IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta() { }
	// RVA: 0x1e15e40 VA: 0x759442de40
	private String <>xLuaBaseProxy_GetProjectileKey() { }
	// RVA: 0x1e15e44 VA: 0x759442de44
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e15e48 VA: 0x759442de48
	private IList`1 <>xLuaBaseProxy_GetActiveBuffs() { }
	// RVA: 0x1e15e50 VA: 0x759442de50
	private Void <>xLuaBaseProxy_CheckProjectileNameOnApplied(String P0) { }
}
```