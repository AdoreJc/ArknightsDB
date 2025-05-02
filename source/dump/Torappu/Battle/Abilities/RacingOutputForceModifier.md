# RacingOutputForceModifier

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _forceLevelAddition`

- `Int32 m_forceLevelAdd`


## Methods

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnRacingEvent(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RacingOutputForceModifier : RacingBaseEventListener
{
	private Int32 _forceLevelAddition; // 0x30
	private Int32 m_forceLevelAdd; // 0x34
	private static DelegateBridge __Hotfix0_get_racingEvent; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_OnRacingEvent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override RacingEvent racingEvent { get; }

	// RVA: 0x1ed9308 VA: 0x75944f1308
	protected override RacingEvent get_racingEvent() { }
	// RVA: 0x1ed9370 VA: 0x75944f1370
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed9428 VA: 0x75944f1428
	protected override Void OnRacingEvent(Object arg) { }
	// RVA: 0x1ed9500 VA: 0x75944f1500
	public Void .ctor() { }
	// RVA: 0x1ed956c VA: 0x75944f156c
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed9570 VA: 0x75944f1570
	private Void <>xLuaBaseProxy_OnRacingEvent(Object P0) { }
}
```