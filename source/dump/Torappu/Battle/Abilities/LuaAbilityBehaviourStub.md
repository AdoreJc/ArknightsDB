# LuaAbilityBehaviourStub

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _luaBehaviourName`

- `LuaBinding m_luaBinding`


## Properties

- `String luaBehaviourName`

- `Boolean isLuaReady`


## Methods

- `String get_luaBehaviourName()`

- `Boolean get_isLuaReady()`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_OnStopAffect()`

- `Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class LuaAbilityBehaviourStub : Behaviour, ILuaCallCSharp, IHotfixable
{
	private String _luaBehaviourName; // 0x20
	private LuaBinding m_luaBinding; // 0x28
	private static DelegateBridge __Hotfix0_get_luaBehaviourName; // 0x0
	private static DelegateBridge __Hotfix0_get_isLuaReady; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_SetData; // 0x18
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x20
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x28
	private static DelegateBridge __Hotfix0_OnEvent; // 0x30
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x38
	private static DelegateBridge __Hotfix0_OnStopAffect; // 0x40
	private static DelegateBridge __Hotfix0_UpdatePlaybackSpeed; // 0x48
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String luaBehaviourName { get; }
	protected Boolean isLuaReady { get; }

	// RVA: 0x1ed012c VA: 0x75944e812c
	public String get_luaBehaviourName() { }
	// RVA: 0x1ed0194 VA: 0x75944e8194
	protected Boolean get_isLuaReady() { }
	// RVA: 0x1ed0204 VA: 0x75944e8204
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ed02c8 VA: 0x75944e82c8
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed03e4 VA: 0x75944e83e4
	public override Void OnCastStart() { }
	// RVA: 0x1ed04e4 VA: 0x75944e84e4
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ed0600 VA: 0x75944e8600
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ed0720 VA: 0x75944e8720
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ed0840 VA: 0x75944e8840
	public override Void OnStopAffect() { }
	// RVA: 0x1ed0940 VA: 0x75944e8940
	public override Boolean UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming timing, out Single playbackSpeed) { }
	// RVA: 0x1ed0a6c VA: 0x75944e8a6c
	private Void OnDestroy() { }
	// RVA: 0x1ed0adc VA: 0x75944e8adc
	public Void .ctor() { }
	// RVA: 0x1ed0b4c VA: 0x75944e8b4c
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ed0b54 VA: 0x75944e8b54
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed0b5c VA: 0x75944e8b5c
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ed0b64 VA: 0x75944e8b64
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ed0b6c VA: 0x75944e8b6c
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ed0b74 VA: 0x75944e8b74
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1ed0b7c VA: 0x75944e8b7c
	private Void <>xLuaBaseProxy_OnStopAffect() { }
	// RVA: 0x1ed0b84 VA: 0x75944e8b84
	private Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming P0, out Single P1) { }
}
```