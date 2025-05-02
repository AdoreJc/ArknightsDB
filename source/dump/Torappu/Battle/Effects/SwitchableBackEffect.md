# SwitchableBackEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _backEffect`

- `Boolean _forceCheckInUpdate`

- `Boolean _oneShot`

- `Boolean _useBehaviourPause`

- `Boolean m_cachedIsBack`


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
public class SwitchableBackEffect : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _backEffect; // 0x20
	private Boolean _forceCheckInUpdate; // 0x28
	private Boolean _oneShot; // 0x29
	private Boolean _useBehaviourPause; // 0x2a
	private ObjectPtr`1 m_backEffect; // 0x30
	private Boolean m_cachedIsBack; // 0x40
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateFace; // 0x20
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x200dc24 VA: 0x7594625c24
	public override Void OnPlay() { }
	// RVA: 0x200df74 VA: 0x7594625f74
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x200e088 VA: 0x7594626088
	public override Void OnFinish() { }
	// RVA: 0x200e194 VA: 0x7594626194
	private Void Update() { }
	// RVA: 0x200dc9c VA: 0x7594625c9c
	private Void _UpdateFace(Boolean force) { }
	// RVA: 0x200e224 VA: 0x7594626224
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x200e29c VA: 0x759462629c
	public Void .ctor() { }
	// RVA: 0x200e30c VA: 0x759462630c
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x200e314 VA: 0x7594626314
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```