# AppearSkill

**Namespace:** `Torappu.Battle`


## Fields

- `String _overrideStartEffect`

- `Boolean _switchToState`

- `Boolean _castOnLocate`

- `Boolean _overrideAudioSignalId`

- `Boolean m_available`


## Properties

- `String overrideStartEffect`


## Methods

- `String get_overrideStartEffect()`

- `Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide)`

- `Boolean <>xLuaBaseProxy_get_overrideAudioSignalId()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Void <>xLuaBaseProxy_OnLocate()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AppearSkill : BasicSkill, IEffectSource
{
	private String _overrideStartEffect; // 0xf8
	private Boolean _switchToState; // 0x100
	private Boolean _castOnLocate; // 0x101
	private Boolean _overrideAudioSignalId; // 0x102
	private Boolean m_available; // 0x103
	private static DelegateBridge __Hotfix0_IsAvailable; // 0x0
	private static DelegateBridge __Hotfix0_get_overrideStartEffect; // 0x8
	private static DelegateBridge __Hotfix0_get_overrideAudioSignalId; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_DoCast; // 0x20
	private static DelegateBridge __Hotfix0_UseSkill; // 0x28
	private static DelegateBridge __Hotfix0_OnBorn; // 0x30
	private static DelegateBridge __Hotfix0_OnLocate; // 0x38
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String overrideStartEffect { get; }
	public override Boolean overrideAudioSignalId { get; }

	// RVA: 0x40e6630 VA: 0x75966fe630
	public override Boolean IsAvailable(PlayerSide operationSide) { }
	// RVA: 0x40e66ac VA: 0x75966fe6ac
	public String get_overrideStartEffect() { }
	// RVA: 0x40e6714 VA: 0x75966fe714
	public override Boolean get_overrideAudioSignalId() { }
	// RVA: 0x40e677c VA: 0x75966fe77c
	public override Void OnInit() { }
	// RVA: 0x40e6988 VA: 0x75966fe988
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x40e6a44 VA: 0x75966fea44
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x40e6bd8 VA: 0x75966febd8
	public override Void OnBorn() { }
	// RVA: 0x40e6dd8 VA: 0x75966fedd8
	public override Void OnLocate() { }
	// RVA: 0x40e6ee0 VA: 0x75966feee0
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x40e7240 VA: 0x75966ff240
	public Void .ctor() { }
	// RVA: 0x40e7398 VA: 0x75966ff398
	private Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide P0) { }
	// RVA: 0x40e744c VA: 0x75966ff44c
	private Boolean <>xLuaBaseProxy_get_overrideAudioSignalId() { }
	// RVA: 0x40e74b4 VA: 0x75966ff4b4
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x40e74b8 VA: 0x75966ff4b8
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x40e74bc VA: 0x75966ff4bc
	private Void <>xLuaBaseProxy_OnLocate() { }
	// RVA: 0x40e74c0 VA: 0x75966ff4c0
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```