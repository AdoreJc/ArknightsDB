# RandomEmitter

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Int32 _count`

- `String _effect`

- `Single _preDelay`

- `Single _delayPerEffect`

- `Vector3 _randomRangeFrom`

- `Vector3 _randomRangeTo`


## Methods

- `Void GatherEffects(List`1)`

- `IEnumerator _DoEmit()`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class RandomEmitter : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private Int32 _count; // 0x20
	private String _effect; // 0x28
	private Single _preDelay; // 0x30
	private Single _delayPerEffect; // 0x34
	private Vector3 _randomRangeFrom; // 0x38
	private Vector3 _randomRangeTo; // 0x44
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0__DoEmit; // 0x10
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2007040 VA: 0x759461f040
	public override Void OnPlay() { }
	// RVA: 0x2007164 VA: 0x759461f164
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x20070b8 VA: 0x759461f0b8
	private IEnumerator _DoEmit() { }
	// RVA: 0x20072a0 VA: 0x759461f2a0
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x2007318 VA: 0x759461f318
	public Void .ctor() { }
	// RVA: 0x200738c VA: 0x759461f38c
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```