# RacingTakeForceModifier

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
public class RacingTakeForceModifier : RacingBaseEventListener
{
	private Int32 _forceLevelAddition; // 0x30
	private Int32 m_forceLevelAdd; // 0x34
	private static DelegateBridge __Hotfix0_get_racingEvent; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_OnRacingEvent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override RacingEvent racingEvent { get; }

	// RVA: 0x1ed9574 VA: 0x75944f1574
	protected override RacingEvent get_racingEvent() { }
	// RVA: 0x1ed95dc VA: 0x75944f15dc
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed9694 VA: 0x75944f1694
	protected override Void OnRacingEvent(Object arg) { }
	// RVA: 0x1ed976c VA: 0x75944f176c
	public Void .ctor() { }
	// RVA: 0x1ed97d8 VA: 0x75944f17d8
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed97dc VA: 0x75944f17dc
	private Void <>xLuaBaseProxy_OnRacingEvent(Object P0) { }
}
```