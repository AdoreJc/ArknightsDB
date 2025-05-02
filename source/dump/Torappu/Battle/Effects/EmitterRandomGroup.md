# EmitterRandomGroup

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _selfExcluded`

- `Boolean _dontCheckOwner`

- `Boolean _finishEffectWhenSelfFinish`

- `Boolean _useMainEffectPos`


## Methods

- `Void GatherEffects(List`1)`

- `Void _PickOneEmitter()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class EmitterRandomGroup : Behaviour, IEffectSource
{
	private String[] _effectPickFrom; // 0x20
	private Boolean _selfExcluded; // 0x28
	private Boolean _dontCheckOwner; // 0x29
	private Boolean _finishEffectWhenSelfFinish; // 0x2a
	private Boolean _useMainEffectPos; // 0x2b
	private List`1 m_effects; // 0x30
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0__PickOneEmitter; // 0x10
	private static DelegateBridge __Hotfix0_OnFinish; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ff9fb0 VA: 0x7594611fb0
	public override Void OnPlay() { }
	// RVA: 0x1ffa49c VA: 0x759461249c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ffa05c VA: 0x759461205c
	private Void _PickOneEmitter() { }
	// RVA: 0x1ffa570 VA: 0x7594612570
	public override Void OnFinish() { }
	// RVA: 0x1ffa794 VA: 0x7594612794
	public Void .ctor() { }
	// RVA: 0x1ffa854 VA: 0x7594612854
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ffa858 VA: 0x7594612858
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```