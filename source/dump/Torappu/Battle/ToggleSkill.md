# ToggleSkill

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _switchToMode`

- `Boolean _switchToModeDown`

- `Int32 _downMode`

- `Boolean _switchToState`

- `Boolean _restartFSM`

- `Boolean _skipAudioWhenToggleInternal`

- `Boolean m_toggled`

- `Int32 m_defaultModeIndex`


## Properties

- `Boolean toggled`


## Methods

- `Boolean get_toggled()`

- `Void _SetToggledInternal(Boolean, Boolean)`

- `Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ToggleSkill : BasicSkill
{
	private Int32 _switchToMode; // 0xf8
	private Boolean _switchToModeDown; // 0xfc
	private Int32 _downMode; // 0x100
	private Boolean _switchToState; // 0x104
	private Boolean _restartFSM; // 0x105
	private Boolean _skipAudioWhenToggleInternal; // 0x106
	private Boolean m_toggled; // 0x107
	private Int32 m_defaultModeIndex; // 0x108
	private static DelegateBridge __Hotfix0_IsAvailable; // 0x0
	private static DelegateBridge __Hotfix0_get_toggled; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_DoCast; // 0x18
	private static DelegateBridge __Hotfix0_UseSkill; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0__SetToggledInternal; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean toggled { get; }

	// RVA: 0x1b71da8 VA: 0x7594189da8
	public override Boolean IsAvailable(PlayerSide operationSide) { }
	// RVA: 0x1b71e58 VA: 0x7594189e58
	public Boolean get_toggled() { }
	// RVA: 0x1b71ec0 VA: 0x7594189ec0
	public override Void OnInit() { }
	// RVA: 0x1b72094 VA: 0x759418a094
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x1b72368 VA: 0x759418a368
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x1b72428 VA: 0x759418a428
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x1b71f70 VA: 0x7594189f70
	private Void _SetToggledInternal(Boolean value, Boolean force) { }
	// RVA: 0x1b72544 VA: 0x759418a544
	public Void .ctor() { }
	// RVA: 0x1b725c4 VA: 0x759418a5c4
	private Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide P0) { }
	// RVA: 0x1b725cc VA: 0x759418a5cc
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x1b725d4 VA: 0x759418a5d4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```