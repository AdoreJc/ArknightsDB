# SwitchableWhenContainsBuff

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _hookEffect`


## Methods

- `Void GatherEffects(List`1)`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SwitchableWhenContainsBuff : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private List`1 _buffKeys; // 0x20
	private String _hookEffect; // 0x28
	private ObjectPtr`1 m_hookEffect; // 0x30
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2011c80 VA: 0x7594629c80
	public override Void OnPlay() { }
	// RVA: 0x2011ea0 VA: 0x7594629ea0
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x2011fb4 VA: 0x7594629fb4
	public override Void OnFinish() { }
	// RVA: 0x20120b8 VA: 0x759462a0b8
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x2012130 VA: 0x759462a130
	public Void .ctor() { }
	// RVA: 0x20121a0 VA: 0x759462a1a0
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x20121a8 VA: 0x759462a1a8
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```