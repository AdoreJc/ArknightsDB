# Act38sideSwitchableEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _dontCheckOwner`

- `Boolean _finishEffectWhenSelfFinish`

- `Boolean _useMainEffectPos`

- `Boolean _checkCarnivalFinished`

- `String _envSystemKey`

- `Act38SideBattleManager m_envManager`

- `FireworkType m_fireworkType`

- `Int32 m_fireworkLevel`


## Methods

- `Void Update()`

- `Void GatherEffects(List`1)`

- `Void _PickOneEmitter()`

- `String _GetEffectKeyByFireworkType()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class Act38sideSwitchableEffect : Behaviour, IEffectSource
{
	private Boolean _dontCheckOwner; // 0x20
	private Boolean _finishEffectWhenSelfFinish; // 0x21
	private Boolean _useMainEffectPos; // 0x22
	private Boolean _checkCarnivalFinished; // 0x23
	private String _envSystemKey; // 0x28
	private List`1 _effectSettings; // 0x30
	private List`1 m_effects; // 0x38
	private Act38SideBattleManager m_envManager; // 0x40
	private FireworkType m_fireworkType; // 0x48
	private Int32 m_fireworkLevel; // 0x4c
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0__PickOneEmitter; // 0x18
	private static DelegateBridge __Hotfix0__GetEffectKeyByFireworkType; // 0x20
	private static DelegateBridge __Hotfix0_OnFinish; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1ff4cfc VA: 0x759460ccfc
	private Void Update() { }
	// RVA: 0x1ff4ddc VA: 0x759460cddc
	public override Void OnPlay() { }
	// RVA: 0x1ff534c VA: 0x759460d34c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ff4fe0 VA: 0x759460cfe0
	private Void _PickOneEmitter() { }
	// RVA: 0x1ff556c VA: 0x759460d56c
	private String _GetEffectKeyByFireworkType() { }
	// RVA: 0x1ff5704 VA: 0x759460d704
	public override Void OnFinish() { }
	// RVA: 0x1ff5928 VA: 0x759460d928
	public Void .ctor() { }
	// RVA: 0x1ff5a18 VA: 0x759460da18
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ff5a1c VA: 0x759460da1c
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```