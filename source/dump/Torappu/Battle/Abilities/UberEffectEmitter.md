# UberEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _convertCastEndToAttachFinish`

- `Boolean _recalculatePlaybackSpeed`

- `Single _preDelayFactor`


## Properties

- `Boolean recalculatePlaybackSpeed`


## Methods

- `Boolean get_recalculatePlaybackSpeed()`

- `Void _GatherEffects(List`1, T[])`

- `Single <>xLuaBaseProxy_get_playbackSpeed()`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UberEffectEmitter : AbstractEffectEmitter
{
	private HitEffectOptions[] _hitEffects; // 0x20
	private CastEffectOptions[] _castEffects; // 0x28
	private AttachEffectOptions[] _attachEffects; // 0x30
	private InputTargetEffectOptions[] _inputTargetEffects; // 0x38
	private CastTargetEffectOptions[] _castTargetEffects; // 0x40
	private Boolean _convertCastEndToAttachFinish; // 0x48
	private Boolean _recalculatePlaybackSpeed; // 0x49
	private Single _preDelayFactor; // 0x4c
	protected List`1 m_allEffects; // 0x50
	private static DelegateBridge __Hotfix0_get_recalculatePlaybackSpeed; // 0x0
	private static DelegateBridge __Hotfix0_get_playbackSpeed; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x18
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x20
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x28
	private static DelegateBridge __Hotfix0_OnEvent; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x38
	private static DelegateBridge __Hotfix0__GatherEffects; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Boolean recalculatePlaybackSpeed { get; }
	protected override Single playbackSpeed { get; }

	// RVA: 0x1ecb434 VA: 0x75944e3434
	private Boolean get_recalculatePlaybackSpeed() { }
	// RVA: 0x1ecb49c VA: 0x75944e349c
	protected override Single get_playbackSpeed() { }
	// RVA: 0x1ec61f0 VA: 0x75944de1f0
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ec668c VA: 0x75944de68c
	public override Void OnCastStart() { }
	// RVA: 0x1ec68f0 VA: 0x75944de8f0
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ec6b30 VA: 0x75944deb30
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ec7104 VA: 0x75944df104
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec751c VA: 0x75944df51c
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x VA: 0x0
	protected Void _GatherEffects(List`1 effects, T[] options) { }
	// RVA: 0x1ec77bc VA: 0x75944df7bc
	public Void .ctor() { }
	// RVA: 0x1ecb618 VA: 0x75944e3618
	private Single <>xLuaBaseProxy_get_playbackSpeed() { }
	// RVA: 0x1ecb620 VA: 0x75944e3620
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ecb628 VA: 0x75944e3628
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ecb630 VA: 0x75944e3630
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ecb638 VA: 0x75944e3638
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1ecb640 VA: 0x75944e3640
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```