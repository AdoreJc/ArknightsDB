# SwitchableEffectByBlackboardValue

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffKey`

- `String _blackboardKey`

- `Single _updateInterval`

- `Int32 m_lastValue`

- `Single m_updateInterval`


## Methods

- `Void GatherEffects(List`1)`

- `Void Update()`

- `Void _UpdateEffect()`

- `Void _FinishAllEffects()`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SwitchableEffectByBlackboardValue : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _buffKey; // 0x20
	private String _blackboardKey; // 0x28
	private String[] _effects; // 0x30
	private Single _updateInterval; // 0x38
	private Int32 m_lastValue; // 0x3c
	private Single m_updateInterval; // 0x40
	private ListDict`2 m_cachedEffects; // 0x48
	private ObjectPtr`1 m_holdBuff; // 0x50
	private static DelegateBridge __Hotfix0_get_holdBuff; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_OnFinish; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0__UpdateEffect; // 0x28
	private static DelegateBridge __Hotfix0__FinishAllEffects; // 0x30
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private ObjectPtr`1 holdBuff { get; }

	// RVA: 0x200e31c VA: 0x759462631c
	private ObjectPtr`1 get_holdBuff() { }
	// RVA: 0x200e46c VA: 0x759462646c
	public override Void OnPlay() { }
	// RVA: 0x200e9e8 VA: 0x75946269e8
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x200eabc VA: 0x7594626abc
	public override Void OnFinish() { }
	// RVA: 0x200ed6c VA: 0x7594626d6c
	private Void Update() { }
	// RVA: 0x200e548 VA: 0x7594626548
	private Void _UpdateEffect() { }
	// RVA: 0x200eb30 VA: 0x7594626b30
	private Void _FinishAllEffects() { }
	// RVA: 0x200ee2c VA: 0x7594626e2c
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x200eea4 VA: 0x7594626ea4
	public Void .ctor() { }
	// RVA: 0x200efb8 VA: 0x7594626fb8
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x200efc0 VA: 0x7594626fc0
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```