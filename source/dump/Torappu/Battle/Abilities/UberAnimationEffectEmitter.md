# UberAnimationEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _sourceAnimKey`

- `LoopType _loopType`

- `AbstractAnimatedAbility m_animatedAbility`

- `Int32 m_currentIndex`


## Methods

- `Void _CalculatePlayIndex()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UberAnimationEffectEmitter : UberEffectEmitter
{
	private String _sourceAnimKey; // 0x58
	private LoopType _loopType; // 0x60
	private List`1 _replaceGroup; // 0x68
	private AbstractAnimatedAbility m_animatedAbility; // 0x70
	private Int32 m_currentIndex; // 0x78
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x10
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x18
	private static DelegateBridge __Hotfix0_OnEvent; // 0x20
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x28
	private static DelegateBridge __Hotfix0__CalculatePlayIndex; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1eca854 VA: 0x75944e2854
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1eca988 VA: 0x75944e2988
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ecab84 VA: 0x75944e2b84
	public override Void OnCastStart() { }
	// RVA: 0x1ecaeec VA: 0x75944e2eec
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ecb018 VA: 0x75944e3018
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ecb158 VA: 0x75944e3158
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ecadbc VA: 0x75944e2dbc
	private Void _CalculatePlayIndex() { }
	// RVA: 0x1ecb350 VA: 0x75944e3350
	public Void .ctor() { }
	// RVA: 0x1ecb418 VA: 0x75944e3418
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ecb420 VA: 0x75944e3420
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ecb424 VA: 0x75944e3424
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ecb428 VA: 0x75944e3428
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ecb42c VA: 0x75944e342c
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ecb430 VA: 0x75944e3430
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```