# LineEffectEmitter

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _startEffect`

- `String _midEffect`

- `String _endEffect`

- `LineRenderer m_lineRenderer`

- `Vector3 m_startPosition`

- `Vector3 m_endPosition`


## Properties

- `Boolean hasStartEffect`

- `Boolean hasMidEffect`

- `Boolean hasEndEffect`

- `Effect startEffect`

- `Effect endEffect`


## Methods

- `Boolean get_hasStartEffect()`

- `Boolean get_hasMidEffect()`

- `Boolean get_hasEndEffect()`

- `Effect get_startEffect()`

- `Effect get_endEffect()`

- `Void Update()`

- `Void _TryUpdateEffects()`

- `Void _RefreshMidPositions()`

- `Void GatherEffects(List`1)`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class LineEffectEmitter : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _startEffect; // 0x20
	private String _midEffect; // 0x28
	private String _endEffect; // 0x30
	private LineRenderer m_lineRenderer; // 0x38
	private ObjectPtr`1 m_startEffect; // 0x40
	private ObjectPtr`1 m_endEffect; // 0x50
	private List`1 m_midEffects; // 0x60
	private Vector3 m_startPosition; // 0x68
	private Vector3 m_endPosition; // 0x74
	private List`1 m_midPositions; // 0x80
	private static DelegateBridge __Hotfix0_get_hasStartEffect; // 0x0
	private static DelegateBridge __Hotfix0_get_hasMidEffect; // 0x8
	private static DelegateBridge __Hotfix0_get_hasEndEffect; // 0x10
	private static DelegateBridge __Hotfix0_get_startEffect; // 0x18
	private static DelegateBridge __Hotfix0_get_endEffect; // 0x20
	private static DelegateBridge __Hotfix0_OnPlay; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0__TryUpdateEffects; // 0x38
	private static DelegateBridge __Hotfix0__RefreshMidPositions; // 0x40
	private static DelegateBridge __Hotfix0_OnFinish; // 0x48
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x50
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Boolean hasStartEffect { get; }
	private Boolean hasMidEffect { get; }
	private Boolean hasEndEffect { get; }
	private Effect startEffect { get; }
	private Effect endEffect { get; }

	// RVA: 0x1ffdb50 VA: 0x7594615b50
	private Boolean get_hasStartEffect() { }
	// RVA: 0x1ffdbc8 VA: 0x7594615bc8
	private Boolean get_hasMidEffect() { }
	// RVA: 0x1ffdc40 VA: 0x7594615c40
	private Boolean get_hasEndEffect() { }
	// RVA: 0x1ffdcb8 VA: 0x7594615cb8
	private Effect get_startEffect() { }
	// RVA: 0x1ffddd0 VA: 0x7594615dd0
	private Effect get_endEffect() { }
	// RVA: 0x1ffdee8 VA: 0x7594615ee8
	public override Void OnPlay() { }
	// RVA: 0x1ffe148 VA: 0x7594616148
	private Void Update() { }
	// RVA: 0x1ffe1b0 VA: 0x75946161b0
	private Void _TryUpdateEffects() { }
	// RVA: 0x1ffe8c4 VA: 0x75946168c4
	private Void _RefreshMidPositions() { }
	// RVA: 0x1ffec7c VA: 0x7594616c7c
	public override Void OnFinish() { }
	// RVA: 0x1ffeda4 VA: 0x7594616da4
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ffef8c VA: 0x7594616f8c
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x1fff004 VA: 0x7594617004
	public Void .ctor() { }
	// RVA: 0x1fff0d8 VA: 0x75946170d8
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1fff0dc VA: 0x75946170dc
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```