# RacingOnModeSwitchTrigger

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `RacingMode _mode`


## Methods

- `Void GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnRacingEvent(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RacingOnModeSwitchTrigger : RacingBaseEventListener, IBuffSource
{
	private BuffData[] _buffs; // 0x30
	private RacingMode _mode; // 0x38
	private static DelegateBridge __Hotfix0_get_racingEvent; // 0x0
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x8
	private static DelegateBridge __Hotfix0_OnRacingEvent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override RacingEvent racingEvent { get; }

	// RVA: 0x1ed8fd0 VA: 0x75944f0fd0
	protected override RacingEvent get_racingEvent() { }
	// RVA: 0x1ed9034 VA: 0x75944f1034
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ed90e0 VA: 0x75944f10e0
	protected override Void OnRacingEvent(Object arg) { }
	// RVA: 0x1ed925c VA: 0x75944f125c
	public Void .ctor() { }
	// RVA: 0x1ed9304 VA: 0x75944f1304
	private Void <>xLuaBaseProxy_OnRacingEvent(Object P0) { }
}
```