# MultiMeleeAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _additionalTimes`

- `Single _triggerDelta`

- `Boolean _waitAttackEventForAllAttacks`

- `Boolean _splitDamage`

- `Single _minPostDelay`

- `Boolean _onlyFeedActiveBuffToLastOne`

- `Boolean _onlyFeedActiveBuffToFirstOne`

- `Boolean _addSpellCntToLastSignalId`

- `Boolean _onlyTrigAudioSignalForFirstSpell`

- `Boolean _onlyTrigAudioSignalForFirstHit`

- `Boolean _refreshInputTargetOnCheckSpell`

- `TargetTrigger _refreshInputTargetTrigger`

- `Int32 m_additionalTimes`

- `Single m_triggerDelta`

- `ModifierSplitter m_damageSplitter`

- `MultiEventListener m_multiEventListener`


## Properties

- `Boolean waitAttackEventForAllAttacks`


## Methods

- `Boolean get_waitAttackEventForAllAttacks()`

- `IEnumerator <>n__0()`

- `FP <>xLuaBaseProxy_get_postDelay()`

- `Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstSpell()`

- `Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstHit()`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32)`

- `Void <>xLuaBaseProxy_DoEmitAudioSignalForSpellOn()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_DoApplyActionsOnTarget(Entity, IList`1)`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiMeleeAttack : MeleeAttack
{
	private Int32 _additionalTimes; // 0x20c
	private Single _triggerDelta; // 0x210
	private Boolean _waitAttackEventForAllAttacks; // 0x214
	private Boolean _splitDamage; // 0x215
	private Single _minPostDelay; // 0x218
	private Boolean _onlyFeedActiveBuffToLastOne; // 0x21c
	private Boolean _onlyFeedActiveBuffToFirstOne; // 0x21d
	private Boolean _addSpellCntToLastSignalId; // 0x21e
	private Boolean _onlyTrigAudioSignalForFirstSpell; // 0x21f
	private Boolean _onlyTrigAudioSignalForFirstHit; // 0x220
	private Boolean _refreshInputTargetOnCheckSpell; // 0x221
	private TargetTrigger _refreshInputTargetTrigger; // 0x228
	private Int32 m_additionalTimes; // 0x230
	private Single m_triggerDelta; // 0x234
	private ModifierSplitter m_damageSplitter; // 0x238
	private MultiEventListener m_multiEventListener; // 0x240
	private static DelegateBridge __Hotfix0_get_waitAttackEventForAllAttacks; // 0x0
	private static DelegateBridge __Hotfix0_get_postDelay; // 0x8
	private static DelegateBridge __Hotfix0_get_onlyTrigAudioSignalForFirstSpell; // 0x10
	private static DelegateBridge __Hotfix0_get_onlyTrigAudioSignalForFirstHit; // 0x18
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x20
	private static DelegateBridge __Hotfix0_DoAttach; // 0x28
	private static DelegateBridge __Hotfix0_DoSetData; // 0x30
	private static DelegateBridge __Hotfix0_CheckAnotherSpell; // 0x38
	private static DelegateBridge __Hotfix0_DoEmitAudioSignalForSpellOn; // 0x40
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x48
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x50
	private static DelegateBridge __Hotfix0_DoApplyActionsOnTarget; // 0x58
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x60
	private static DelegateBridge __Hotfix0_OnWaitForTriggerDelta; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean waitAttackEventForAllAttacks { get; }
	protected override FP postDelay { get; }
	protected override Boolean onlyTrigAudioSignalForFirstSpell { get; }
	protected override Boolean onlyTrigAudioSignalForFirstHit { get; }

	// RVA: 0x1e062b0 VA: 0x759441e2b0
	public Boolean get_waitAttackEventForAllAttacks() { }
	// RVA: 0x1e06318 VA: 0x759441e318
	protected override FP get_postDelay() { }
	// RVA: 0x1e06408 VA: 0x759441e408
	protected override Boolean get_onlyTrigAudioSignalForFirstSpell() { }
	// RVA: 0x1e06470 VA: 0x759441e470
	protected override Boolean get_onlyTrigAudioSignalForFirstHit() { }
	// RVA: 0x1e064d8 VA: 0x759441e4d8
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e0658c VA: 0x759441e58c
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e06698 VA: 0x759441e698
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e067e8 VA: 0x759441e7e8
	protected override Boolean CheckAnotherSpell(Int32 spellCnt) { }
	// RVA: 0x1e06a94 VA: 0x759441ea94
	protected override Void DoEmitAudioSignalForSpellOn() { }
	// RVA: 0x1e06c74 VA: 0x759441ec74
	protected override Void OnCastStart() { }
	// RVA: 0x1e06d34 VA: 0x759441ed34
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e06de0 VA: 0x759441ede0
	protected override Void DoApplyActionsOnTarget(Entity target, IList`1 actions) { }
	// RVA: 0x1e06f50 VA: 0x759441ef50
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e07024 VA: 0x759441f024
	protected override IEnumerator OnWaitForTriggerDelta() { }
	// RVA: 0x1e070f8 VA: 0x759441f0f8
	public Void .ctor() { }
	// RVA: 0x1e071ac VA: 0x759441f1ac
	private IEnumerator <>n__0() { }
	// RVA: 0x1e071b4 VA: 0x759441f1b4
	private FP <>xLuaBaseProxy_get_postDelay() { }
	// RVA: 0x1e071bc VA: 0x759441f1bc
	private Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstSpell() { }
	// RVA: 0x1e071c4 VA: 0x759441f1c4
	private Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstHit() { }
	// RVA: 0x1e071cc VA: 0x759441f1cc
	private IList`1 <>xLuaBaseProxy_GetActiveBuffs() { }
	// RVA: 0x1e071d4 VA: 0x759441f1d4
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e071dc VA: 0x759441f1dc
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e07200 VA: 0x759441f200
	private Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32 P0) { }
	// RVA: 0x1e07208 VA: 0x759441f208
	private Void <>xLuaBaseProxy_DoEmitAudioSignalForSpellOn() { }
	// RVA: 0x1e07210 VA: 0x759441f210
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e07214 VA: 0x759441f214
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e07218 VA: 0x759441f218
	private Void <>xLuaBaseProxy_DoApplyActionsOnTarget(Entity P0, IList`1 P1) { }
	// RVA: 0x1e07220 VA: 0x759441f220
	private IEnumerator <>xLuaBaseProxy_OnWaitForPreDelay() { }
	// RVA: 0x1e07228 VA: 0x759441f228
	private IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta() { }
}
```