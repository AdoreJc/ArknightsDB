# CastSkillWithSuspendable

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _isOverloadSkill`

- `Boolean _checkFinishedBuffWhenStopAffect`

- `Int32 _suspendableLimitedTimes`


## Methods

- `Void TriggerSpecialAudioSignal()`

- `Boolean <>xLuaBaseProxy_get_isOverloadSkill()`

- `Boolean <>xLuaBaseProxy_IsDiscardable()`

- `Boolean <>xLuaBaseProxy_UseSkill(PlayerSide)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CastSkillWithSuspendable : CastSkill
{
	private Boolean _isOverloadSkill; // 0x11c
	private Boolean _checkFinishedBuffWhenStopAffect; // 0x11d
	private Int32 _suspendableLimitedTimes; // 0x120
	private static DelegateBridge __Hotfix0_get_isOverloadSkill; // 0x0
	private static DelegateBridge __Hotfix0_IsDiscardable; // 0x8
	private static DelegateBridge __Hotfix0_UseSkill; // 0x10
	private static DelegateBridge __Hotfix0_TriggerSpecialAudioSignal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Boolean isOverloadSkill { get; }

	// RVA: 0x40f43fc VA: 0x759670c3fc
	public override Boolean get_isOverloadSkill() { }
	// RVA: 0x40f4464 VA: 0x759670c464
	public override Boolean IsDiscardable() { }
	// RVA: 0x40f4518 VA: 0x759670c518
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x40f4628 VA: 0x759670c628
	protected Void TriggerSpecialAudioSignal() { }
	// RVA: 0x40f4748 VA: 0x759670c748
	public Void .ctor() { }
	// RVA: 0x40f47e0 VA: 0x759670c7e0
	private Boolean <>xLuaBaseProxy_get_isOverloadSkill() { }
	// RVA: 0x40f47e4 VA: 0x759670c7e4
	private Boolean <>xLuaBaseProxy_IsDiscardable() { }
	// RVA: 0x40f47e8 VA: 0x759670c7e8
	private Boolean <>xLuaBaseProxy_UseSkill(PlayerSide P0) { }
}
```