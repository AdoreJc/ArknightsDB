# OnFinishEmitter

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _useFaceVector`

- `Boolean _useEffectPosition`


## Methods

- `Void GatherEffects(List`1)`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class OnFinishEmitter : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String[] _effects; // 0x20
	private Boolean _useFaceVector; // 0x28
	private Boolean _useEffectPosition; // 0x29
	private static DelegateBridge __Hotfix0_OnFinish; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2001dbc VA: 0x7594619dbc
	public override Void OnFinish() { }
	// RVA: 0x2002090 VA: 0x759461a090
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x2002144 VA: 0x759461a144
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x20021bc VA: 0x759461a1bc
	public Void .ctor() { }
	// RVA: 0x2002228 VA: 0x759461a228
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```