# RandomFinishEmitter

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Int32 _count`

- `String _effect`

- `Vector3 _randomRangeFrom`

- `Vector3 _randomRangeTo`


## Methods

- `Void GatherEffects(List`1)`

- `Void _DoEmit()`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class RandomFinishEmitter : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private Int32 _count; // 0x20
	private String _effect; // 0x28
	private Vector3 _randomRangeFrom; // 0x30
	private Vector3 _randomRangeTo; // 0x3c
	private static DelegateBridge __Hotfix0_OnFinish; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0__DoEmit; // 0x10
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2008664 VA: 0x7594620664
	public override Void OnFinish() { }
	// RVA: 0x2008870 VA: 0x7594620870
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x20086cc VA: 0x75946206cc
	private Void _DoEmit() { }
	// RVA: 0x2008984 VA: 0x7594620984
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x20089fc VA: 0x75946209fc
	public Void .ctor() { }
	// RVA: 0x2008a74 VA: 0x7594620a74
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```