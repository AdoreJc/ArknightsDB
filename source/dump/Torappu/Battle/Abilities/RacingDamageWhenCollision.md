# RacingDamageWhenCollision

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `DamageType _damageType`

- `Boolean _scaleByForce`

- `FP m_damageValue`

- `FP m_damageScale`


## Methods

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnRacingEvent(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RacingDamageWhenCollision : RacingBaseEventListener
{
	private DamageType _damageType; // 0x30
	private Boolean _scaleByForce; // 0x34
	private FP m_damageValue; // 0x38
	private FP m_damageScale; // 0x40
	private static DelegateBridge __Hotfix0_get_racingEvent; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_OnRacingEvent; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override RacingEvent racingEvent { get; }

	// RVA: 0x1ed8b3c VA: 0x75944f0b3c
	protected override RacingEvent get_racingEvent() { }
	// RVA: 0x1ed8ba4 VA: 0x75944f0ba4
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed8cfc VA: 0x75944f0cfc
	protected override Void OnRacingEvent(Object arg) { }
	// RVA: 0x1ed8f28 VA: 0x75944f0f28
	public Void .ctor() { }
	// RVA: 0x1ed8fc8 VA: 0x75944f0fc8
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed8fcc VA: 0x75944f0fcc
	private Void <>xLuaBaseProxy_OnRacingEvent(Object P0) { }
}
```