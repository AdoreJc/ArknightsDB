# SwitchableLREffectVarDir

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _rightEffect`

- `Boolean m_cachedIsRight`


## Methods

- `Void GatherEffects(List`1)`

- `Void Update()`

- `Void _UpdateFace(Boolean)`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SwitchableLREffectVarDir : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _rightEffect; // 0x20
	private ObjectPtr`1 m_rightEffect; // 0x28
	private Boolean m_cachedIsRight; // 0x38
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateFace; // 0x20
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2010654 VA: 0x7594628654
	public override Void OnPlay() { }
	// RVA: 0x201093c VA: 0x759462893c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x2010a50 VA: 0x7594628a50
	public override Void OnFinish() { }
	// RVA: 0x2010b54 VA: 0x7594628b54
	private Void Update() { }
	// RVA: 0x20106cc VA: 0x75946286cc
	private Void _UpdateFace(Boolean force) { }
	// RVA: 0x2010bdc VA: 0x7594628bdc
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x2010c54 VA: 0x7594628c54
	public Void .ctor() { }
	// RVA: 0x2010cc4 VA: 0x7594628cc4
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2010ccc VA: 0x7594628ccc
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```