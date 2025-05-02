# ChannelingMeleeAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _triggerDelta`

- `Single _postDelayChecker`

- `Boolean _onlyTrigAudioSignalForFirstSpell`

- `FP m_duration`

- `FP m_castTime`


## Methods

- `FP <>xLuaBaseProxy_get_cooldown()`

- `Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstSpell()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32)`

- `IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta()`

- `FP <>xLuaBaseProxy_GetDuration()`

- `Void <>xLuaBaseProxy_OnCastStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ChannelingMeleeAttack : MeleeAttack
{
	private Single _triggerDelta; // 0x20c
	private Single _postDelayChecker; // 0x210
	private Boolean _onlyTrigAudioSignalForFirstSpell; // 0x214
	private FP m_duration; // 0x218
	private FP m_castTime; // 0x220
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_onlyTrigAudioSignalForFirstSpell; // 0x8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x10
	private static DelegateBridge __Hotfix0_CheckAnotherSpell; // 0x18
	private static DelegateBridge __Hotfix0_OnWaitForTriggerDelta; // 0x20
	private static DelegateBridge __Hotfix0_GetDuration; // 0x28
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override FP cooldown { get; }
	protected override Boolean onlyTrigAudioSignalForFirstSpell { get; }

	// RVA: 0x1e045e4 VA: 0x759441c5e4
	public override FP get_cooldown() { }
	// RVA: 0x1e0464c VA: 0x759441c64c
	protected override Boolean get_onlyTrigAudioSignalForFirstSpell() { }
	// RVA: 0x1e046b4 VA: 0x759441c6b4
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e048d0 VA: 0x759441c8d0
	protected override Boolean CheckAnotherSpell(Int32 spellCnt) { }
	// RVA: 0x1e04a08 VA: 0x759441ca08
	protected override IEnumerator OnWaitForTriggerDelta() { }
	// RVA: 0x1e04adc VA: 0x759441cadc
	protected override FP GetDuration() { }
	// RVA: 0x1e04b44 VA: 0x759441cb44
	protected override Void OnCastStart() { }
	// RVA: 0x1e04bdc VA: 0x759441cbdc
	public Void .ctor() { }
	// RVA: 0x1e04cc4 VA: 0x759441ccc4
	private FP <>xLuaBaseProxy_get_cooldown() { }
	// RVA: 0x1e04ccc VA: 0x759441cccc
	private Boolean <>xLuaBaseProxy_get_onlyTrigAudioSignalForFirstSpell() { }
	// RVA: 0x1e04cd4 VA: 0x759441ccd4
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e04cf8 VA: 0x759441ccf8
	private Boolean <>xLuaBaseProxy_CheckAnotherSpell(Int32 P0) { }
	// RVA: 0x1e04d00 VA: 0x759441cd00
	private IEnumerator <>xLuaBaseProxy_OnWaitForTriggerDelta() { }
	// RVA: 0x1e04d08 VA: 0x759441cd08
	private FP <>xLuaBaseProxy_GetDuration() { }
	// RVA: 0x1e04d10 VA: 0x759441cd10
	private Void <>xLuaBaseProxy_OnCastStart() { }
}
```