# ReadyEnemySkillEffect

**Namespace:** `Torappu.Battle`


## Fields

- `String _effect`

- `Boolean _stopBeforeCast`


## Methods

- `Void GatherEffects(List`1)`

- `Void _ClearEffect()`

- `Void <>xLuaBaseProxy_OnAttach()`

- `Void <>xLuaBaseProxy_OnDetach()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ReadyEnemySkillEffect : Behaviour, IEffectSource
{
	private String _effect; // 0x20
	private Boolean _stopBeforeCast; // 0x28
	private ObjectPtr`1 m_effectPtr; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x0
	private static DelegateBridge __Hotfix0_OnAttach; // 0x8
	private static DelegateBridge __Hotfix0_OnDetach; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x20
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x28
	private static DelegateBridge __Hotfix0__ClearEffect; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3fba720 VA: 0x75965d2720
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x3fba834 VA: 0x75965d2834
	public override Void OnAttach() { }
	// RVA: 0x3fbaa00 VA: 0x75965d2a00
	public override Void OnDetach() { }
	// RVA: 0x3fbaad4 VA: 0x75965d2ad4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x3fbada8 VA: 0x75965d2da8
	public override Void OnCastStart() { }
	// RVA: 0x3fbae90 VA: 0x75965d2e90
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x3fba908 VA: 0x75965d2908
	private Void _ClearEffect() { }
	// RVA: 0x3fbaf90 VA: 0x75965d2f90
	public Void .ctor() { }
	// RVA: 0x3fbb0b0 VA: 0x75965d30b0
	private Void <>xLuaBaseProxy_OnAttach() { }
	// RVA: 0x3fbb0b4 VA: 0x75965d30b4
	private Void <>xLuaBaseProxy_OnDetach() { }
	// RVA: 0x3fbb0b8 VA: 0x75965d30b8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x3fbb0bc VA: 0x75965d30bc
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x3fbb0c0 VA: 0x75965d30c0
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
}
```