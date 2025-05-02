# RacingCollisionModifier

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _speedLossScaler`

- `Boolean _isCollisionWithTile`

- `FP m_speedLossScaler`


## Methods

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnRacingEvent(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RacingCollisionModifier : RacingBaseEventListener
{
	private Single _speedLossScaler; // 0x30
	private Boolean _isCollisionWithTile; // 0x34
	private FP m_speedLossScaler; // 0x38
	private static DelegateBridge __Hotfix0_get_racingEvent; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_OnRacingEvent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override RacingEvent racingEvent { get; }

	// RVA: 0x1ed884c VA: 0x75944f084c
	protected override RacingEvent get_racingEvent() { }
	// RVA: 0x1ed88c0 VA: 0x75944f08c0
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed89b8 VA: 0x75944f09b8
	protected override Void OnRacingEvent(Object arg) { }
	// RVA: 0x1ed8ac0 VA: 0x75944f0ac0
	public Void .ctor() { }
	// RVA: 0x1ed8b34 VA: 0x75944f0b34
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed8b38 VA: 0x75944f0b38
	private Void <>xLuaBaseProxy_OnRacingEvent(Object P0) { }
}
```