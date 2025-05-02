# YuS3EffectBehaviour

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _effectEachGrid`

- `Boolean m_inited`


## Methods

- `Void GatherEffects(List`1)`

- `Void ChangeEffectsExt(String)`

- `String _ReplaceEffectName(String, String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class YuS3EffectBehaviour : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _effectEachGrid; // 0x20
	private Boolean m_inited; // 0x28
	private List`1 m_effects; // 0x30
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_OnFinish; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x18
	private static DelegateBridge __Hotfix0__ReplaceEffectName; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x200a8d0 VA: 0x75946228d0
	public override Void OnPlay() { }
	// RVA: 0x200adc4 VA: 0x7594622dc4
	public override Void OnFinish() { }
	// RVA: 0x200afc0 VA: 0x7594622fc0
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x200b0b4 VA: 0x75946230b4
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x200b138 VA: 0x7594623138
	private String _ReplaceEffectName(String effectName, String ext) { }
	// RVA: 0x200b1d8 VA: 0x75946231d8
	public Void .ctor() { }
	// RVA: 0x200b29c VA: 0x759462329c
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x200b2a4 VA: 0x75946232a4
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```