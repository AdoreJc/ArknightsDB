# MultiProjectileToTileAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _additionalTimes`

- `Single _triggerDelta`

- `Boolean _waitAttackEventForAllAttacks`

- `Boolean _onlyTrigAudioSignalForFirstOne`

- `Boolean _splitDamage`

- `Boolean _onlyFeedActiveBuffToLastOne`

- `Boolean _onlyFeedActiveBuffToFirstOne`

- `Boolean _refreshTimesOnCastStart`

- `Boolean _castToTileOneByOne`

- `Boolean _fireAttackFinishWhenCastToTileOneByOne`

- `Single _minPostDelayWhenCastToTileOneByOne`

- `Single m_triggerDelta`

- `ModifierSplitter m_damageSplitter`

- `MultiEventListener m_multiEventListener`


## Properties

- `Boolean isLastSpell`

- `Int32 additionalTimes`

- `Boolean waitAttackEventForAllAttacks`

- `Boolean castToTileOneByOne`


## Methods

- `Boolean get_isLastSpell()`

- `Int32 get_additionalTimes()`

- `Boolean get_waitAttackEventForAllAttacks()`

- `Boolean get_castToTileOneByOne()`

- `IEnumerator <>n__0()`

- `IEnumerator <>n__1()`

- `Boolean <>xLuaBaseProxy_get_finishStartEffectsOnCastEnd()`

- `Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstSpell()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_DoApplyActionsOnTarget(Entity, IList`1)`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta()`

- `String <>xLuaBaseProxy_GetProjectileKey()`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiProjectileToTileAbility : ProjectileToTileAbility
{
	private Int32 _additionalTimes; // 0x250
	private Single _triggerDelta; // 0x254
	private Boolean _waitAttackEventForAllAttacks; // 0x258
	private Boolean _onlyTrigAudioSignalForFirstOne; // 0x259
	private Boolean _splitDamage; // 0x25a
	private Boolean _onlyFeedActiveBuffToLastOne; // 0x25b
	private Boolean _onlyFeedActiveBuffToFirstOne; // 0x25c
	private Boolean _refreshTimesOnCastStart; // 0x25d
	private Boolean _castToTileOneByOne; // 0x25e
	private String[] _additionalProjectiles; // 0x260
	private Boolean _fireAttackFinishWhenCastToTileOneByOne; // 0x268
	private Single _minPostDelayWhenCastToTileOneByOne; // 0x26c
	private Single m_triggerDelta; // 0x270
	private ModifierSplitter m_damageSplitter; // 0x278
	private MultiEventListener m_multiEventListener; // 0x280
	private List`1 m_cachedCastTiles; // 0x288
	private static DelegateBridge __Hotfix0_get_isLastSpell; // 0x0
	private static DelegateBridge __Hotfix0_get_additionalTimes; // 0x8
	private static DelegateBridge __Hotfix0_get_waitAttackEventForAllAttacks; // 0x10
	private static DelegateBridge __Hotfix0_get_castToTileOneByOne; // 0x18
	private static DelegateBridge __Hotfix0_get_finishStartEffectsOnCastEnd; // 0x20
	private static DelegateBridge __Hotfix0_get_onlyTrigAudioSignalForFirstSpell; // 0x28
	private static DelegateBridge __Hotfix0_DoSetData; // 0x30
	private static DelegateBridge __Hotfix0_DoAttach; // 0x38
	private static DelegateBridge __Hotfix0_CheckAnotherSpell; // 0x40
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x48
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x50
	private static DelegateBridge __Hotfix0_DoApplyActionsOnTarget; // 0x58
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x60
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x68
	private static DelegateBridge __Hotfix0_OnWaitForTriggerDelta; // 0x70
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x78
	private static DelegateBridge __Hotfix0_GetProjectileKey; // 0x80
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Boolean isLastSpell { get; }
	protected Int32 additionalTimes { get; }
	protected Boolean waitAttackEventForAllAttacks { get; }
	protected Boolean castToTileOneByOne { get; }
	protected override Boolean finishStartEffectsOnCastEnd { get; }
	protected override Boolean onlyTrigAudioSignalForFirstSpell { get; }

	// RVA: 0x1e260ec VA: 0x759443e0ec
	public Boolean get_isLastSpell() { }
	// RVA: 0x1e26170 VA: 0x759443e170
	protected Int32 get_additionalTimes() { }
	// RVA: 0x1e261d8 VA: 0x759443e1d8
	protected Boolean get_waitAttackEventForAllAttacks() { }
	// RVA: 0x1e26240 VA: 0x759443e240
	protected Boolean get_castToTileOneByOne() { }
	// RVA: 0x1e262a8 VA: 0x759443e2a8
	protected override Boolean get_finishStartEffectsOnCastEnd() { }
	// RVA: 0x1e2632c VA: 0x759443e32c
	protected override Boolean get_onlyTrigAudioSignalForFirstSpell() { }
	// RVA: 0x1e26394 VA: 0x759443e394
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e268a8 VA: 0x759443e8a8
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e269b4 VA: 0x759443e9b4
	protected override Boolean CheckAnotherSpell(Int32 spellCnt) { }
	// RVA: 0x1e26b74 VA: 0x759443eb74
	protected override Void OnCastStart() { }
	// RVA: 0x1e27000 VA: 0x759443f000
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e27234 VA: 0x759443f234
	protected override Void DoApplyActionsOnTarget(Entity target, IList`1 actions) { }
	// RVA: 0x1e273a4 VA: 0x759443f3a4
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e27478 VA: 0x759443f478
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e2754c VA: 0x759443f54c
	protected override IEnumerator OnWaitForTriggerDelta() { }
	// RVA: 0x1e27620 VA: 0x759443f620
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e276d4 VA: 0x759443f6d4
	protected override String GetProjectileKey() { }
	// RVA: 0x1e27808 VA: 0x759443f808
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e27a0c VA: 0x759443fa0c
	public Void .ctor() { }
	// RVA: 0x1e27c60 VA: 0x759443fc60
	private IEnumerator <>n__0() { }
	// RVA: 0x1e27c68 VA: 0x759443fc68
	private IEnumerator <>n__1() { }
	// RVA: 0x1e27d18 VA: 0x759443fd18
	private Boolean <>xLuaBaseProxy_get_finishStartEffectsOnCastEnd() { }
	// RVA: 0x1e27d1c VA: 0x759443fd1c
	private Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstSpell() { }
	// RVA: 0x1e27d24 VA: 0x759443fd24
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e27d48 VA: 0x759443fd48
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e27d50 VA: 0x759443fd50
	private Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32 P0) { }
	// RVA: 0x1e27d58 VA: 0x759443fd58
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e27d5c VA: 0x759443fd5c
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e27d60 VA: 0x759443fd60
	private Void <>xLuaBaseProxy_DoApplyActionsOnTarget(Entity P0, IList`1 P1) { }
	// RVA: 0x1e27d68 VA: 0x759443fd68
	private IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay() { }
	// RVA: 0x1e27d70 VA: 0x759443fd70
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
	// RVA: 0x1e27d74 VA: 0x759443fd74
	private IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta() { }
	// RVA: 0x1e27d7c VA: 0x759443fd7c
	private IList`1 <>xLuaBaseProxy_GetActiveBuffs() { }
	// RVA: 0x1e27d84 VA: 0x759443fd84
	private String <>xLuaBaseProxy_GetProjectileKey() { }
	// RVA: 0x1e27d88 VA: 0x759443fd88
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
}
```