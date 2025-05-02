# ToggleSkillWithEndAnimation

**Namespace:** `Torappu.Battle`


## Fields

- `String _endAnim`

- `Boolean _playExtraSignalAtSkillBegin`

- `Boolean m_skillBeginAnimAlreadyOn`

- `Boolean m_hasPlayedBeginAnim`


## Methods

- `String <>xLuaBaseProxy_get_beginAnim()`

- `Boolean <>xLuaBaseProxy_get_hasPlayedBeginAnim()`

- `Boolean <>xLuaBaseProxy_IsClickable(PlayerSide)`

- `Void <>xLuaBaseProxy_OnBeforeSkillBeginAnim()`

- `Void <>xLuaBaseProxy_OnEnterSkillState()`

- `Void <>xLuaBaseProxy_OnSkillEnd()`

- `Void <>xLuaBaseProxy_InterruptIfNot()`

- `Boolean <>xLuaBaseProxy_UseSkill(PlayerSide)`

- `Void <>xLuaBaseProxy_PlayBeginEffectAndAudio()`

- `Void <>xLuaBaseProxy_PlayBeginAudio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ToggleSkillWithEndAnimation : ToggleSkill
{
	private String _endAnim; // 0x110
	private String[] _endEffect; // 0x118
	private Boolean _playExtraSignalAtSkillBegin; // 0x120
	private Boolean m_skillBeginAnimAlreadyOn; // 0x121
	private Boolean m_hasPlayedBeginAnim; // 0x122
	private static DelegateBridge __Hotfix0_get_beginAnim; // 0x0
	private static DelegateBridge __Hotfix0_get_beginEffect; // 0x8
	private static DelegateBridge __Hotfix0_get_hasPlayedBeginAnim; // 0x10
	private static DelegateBridge __Hotfix0_IsClickable; // 0x18
	private static DelegateBridge __Hotfix0_OnBeforeSkillBeginAnim; // 0x20
	private static DelegateBridge __Hotfix0_OnEnterSkillState; // 0x28
	private static DelegateBridge __Hotfix0_OnSkillEnd; // 0x30
	private static DelegateBridge __Hotfix0_InterruptIfNot; // 0x38
	private static DelegateBridge __Hotfix0_UseSkill; // 0x40
	private static DelegateBridge __Hotfix0_PlayBeginEffectAndAudio; // 0x48
	private static DelegateBridge __Hotfix0_PlayBeginAudio; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override String beginAnim { get; }
	public override String[] beginEffect { get; }
	public override Boolean hasPlayedBeginAnim { get; }

	// RVA: 0x1b725dc VA: 0x759418a5dc
	public override String get_beginAnim() { }
	// RVA: 0x1b72664 VA: 0x759418a664
	public override String[] get_beginEffect() { }
	// RVA: 0x1b726ec VA: 0x759418a6ec
	public override Boolean get_hasPlayedBeginAnim() { }
	// RVA: 0x1b72754 VA: 0x759418a754
	public override Boolean IsClickable(PlayerSide side) { }
	// RVA: 0x1b727f4 VA: 0x759418a7f4
	public override Void OnBeforeSkillBeginAnim() { }
	// RVA: 0x1b72870 VA: 0x759418a870
	public override Void OnEnterSkillState() { }
	// RVA: 0x1b728e4 VA: 0x759418a8e4
	protected override Void OnSkillEnd() { }
	// RVA: 0x1b7295c VA: 0x759418a95c
	public override Void InterruptIfNot() { }
	// RVA: 0x1b729d0 VA: 0x759418a9d0
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x1b72a58 VA: 0x759418aa58
	public override Void PlayBeginEffectAndAudio() { }
	// RVA: 0x1b72bbc VA: 0x759418abbc
	public override Void PlayBeginAudio() { }
	// RVA: 0x1b72d1c VA: 0x759418ad1c
	public Void .ctor() { }
	// RVA: 0x1b72d88 VA: 0x759418ad88
	private String <>xLuaBaseProxy_get_beginAnim() { }
	// RVA: 0x1b72d90 VA: 0x759418ad90
	private String[] <>xLuaBaseProxy_get_beginEffect() { }
	// RVA: 0x1b72d98 VA: 0x759418ad98
	private Boolean <>xLuaBaseProxy_get_hasPlayedBeginAnim() { }
	// RVA: 0x1b72da0 VA: 0x759418ada0
	private Boolean <>xLuaBaseProxy_IsClickable(PlayerSide P0) { }
	// RVA: 0x1b72da8 VA: 0x759418ada8
	private Void <>xLuaBaseProxy_OnBeforeSkillBeginAnim() { }
	// RVA: 0x1b72db0 VA: 0x759418adb0
	private Void <>xLuaBaseProxy_OnEnterSkillState() { }
	// RVA: 0x1b72db8 VA: 0x759418adb8
	private Void <>xLuaBaseProxy_OnSkillEnd() { }
	// RVA: 0x1b72dc0 VA: 0x759418adc0
	private Void <>xLuaBaseProxy_InterruptIfNot() { }
	// RVA: 0x1b72dc8 VA: 0x759418adc8
	private Boolean <>xLuaBaseProxy_UseSkill(PlayerSide P0) { }
	// RVA: 0x1b72dcc VA: 0x759418adcc
	private Void <>xLuaBaseProxy_PlayBeginEffectAndAudio() { }
	// RVA: 0x1b72dd4 VA: 0x759418add4
	private Void <>xLuaBaseProxy_PlayBeginAudio() { }
}
```