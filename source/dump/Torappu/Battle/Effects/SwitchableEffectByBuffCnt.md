# SwitchableEffectByBuffCnt

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffKey`

- `Single _updateInterval`

- `Int32 m_lastCnt`

- `Single m_updateInterval`


## Methods

- `Void GatherEffects(List`1)`

- `Void Update()`

- `Void _UpdateEffectWithBuffCnt()`

- `Void _FinishLastEffect()`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SwitchableEffectByBuffCnt : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _buffKey; // 0x20
	private String[] _effects; // 0x28
	private Single _updateInterval; // 0x30
	private Int32 m_lastCnt; // 0x34
	private Single m_updateInterval; // 0x38
	private ObjectPtr`1 m_lastEff; // 0x40
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateEffectWithBuffCnt; // 0x20
	private static DelegateBridge __Hotfix0__FinishLastEffect; // 0x28
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x200efc8 VA: 0x7594626fc8
	public override Void OnPlay() { }
	// RVA: 0x200f054 VA: 0x7594627054
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x200f128 VA: 0x7594627128
	public override Void OnFinish() { }
	// RVA: 0x200f2f4 VA: 0x75946272f4
	private Void Update() { }
	// RVA: 0x200f3b4 VA: 0x75946273b4
	private Void _UpdateEffectWithBuffCnt() { }
	// RVA: 0x200f19c VA: 0x759462719c
	private Void _FinishLastEffect() { }
	// RVA: 0x200f5b4 VA: 0x75946275b4
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x200f62c VA: 0x759462762c
	public Void .ctor() { }
	// RVA: 0x200f6f0 VA: 0x75946276f0
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x200f6f8 VA: 0x75946276f8
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```