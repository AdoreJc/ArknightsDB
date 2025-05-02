# AdvancedToggleSkill

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _useOnSkillFinishSignal`


## Methods

- `Boolean <>xLuaBaseProxy_IsDiscardable()`

- `Boolean <>xLuaBaseProxy_get_canSkipReduceSp()`

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `FP <>xLuaBaseProxy_get_remainingProgress()`

- `Void <>xLuaBaseProxy_PlayBeginAudio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedToggleSkill : ToggleSkillWithEndAnimation
{
	private Boolean _useOnSkillFinishSignal; // 0x123
	private static DelegateBridge __Hotfix0_IsDiscardable; // 0x0
	private static DelegateBridge __Hotfix0_get_canSkipReduceSp; // 0x8
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x10
	private static DelegateBridge __Hotfix0_get_remainingProgress; // 0x18
	private static DelegateBridge __Hotfix0_PlayBeginAudio; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override Boolean canSkipReduceSp { get; }
	public override Boolean isAffecting { get; }
	public override FP remainingProgress { get; }

	// RVA: 0x40e5d30 VA: 0x75966fdd30
	public override Boolean IsDiscardable() { }
	// RVA: 0x40e5e70 VA: 0x75966fde70
	protected override Boolean get_canSkipReduceSp() { }
	// RVA: 0x40e5ee8 VA: 0x75966fdee8
	public override Boolean get_isAffecting() { }
	// RVA: 0x40e5f54 VA: 0x75966fdf54
	public override FP get_remainingProgress() { }
	// RVA: 0x40e619c VA: 0x75966fe19c
	public override Void PlayBeginAudio() { }
	// RVA: 0x40e6460 VA: 0x75966fe460
	public Void .ctor() { }
	// RVA: 0x40e64d0 VA: 0x75966fe4d0
	private Boolean <>xLuaBaseProxy_IsDiscardable() { }
	// RVA: 0x40e6538 VA: 0x75966fe538
	private Boolean <>xLuaBaseProxy_get_canSkipReduceSp() { }
	// RVA: 0x40e65a0 VA: 0x75966fe5a0
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x40e6624 VA: 0x75966fe624
	private FP <>xLuaBaseProxy_get_remainingProgress() { }
	// RVA: 0x40e6628 VA: 0x75966fe628
	private Void <>xLuaBaseProxy_PlayBeginAudio() { }
}
```