# MultiMeleeHeal

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _additionalTimes`

- `Single _triggerDelta`


## Methods

- `Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32)`

- `Void <>xLuaBaseProxy_DoEmitAudioSignalForSpellOn()`

- `IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiMeleeHeal : Heal
{
	private Int32 _additionalTimes; // 0x1f0
	private Single _triggerDelta; // 0x1f4
	private static DelegateBridge __Hotfix0_CheckAnotherSpell; // 0x0
	private static DelegateBridge __Hotfix0_DoEmitAudioSignalForSpellOn; // 0x8
	private static DelegateBridge __Hotfix0_OnWaitForTriggerDelta; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e1f67c VA: 0x759443767c
	protected override Boolean CheckAnotherSpell(Int32 spellCnt) { }
	// RVA: 0x1e1f700 VA: 0x7594437700
	protected override Void DoEmitAudioSignalForSpellOn() { }
	// RVA: 0x1e1f89c VA: 0x759443789c
	protected override IEnumerator OnWaitForTriggerDelta() { }
	// RVA: 0x1e1f970 VA: 0x7594437970
	public Void .ctor() { }
	// RVA: 0x1e1f9e4 VA: 0x75944379e4
	private Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32 P0) { }
	// RVA: 0x1e1f9ec VA: 0x75944379ec
	private Void <>xLuaBaseProxy_DoEmitAudioSignalForSpellOn() { }
	// RVA: 0x1e1f9f4 VA: 0x75944379f4
	private IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta() { }
}
```