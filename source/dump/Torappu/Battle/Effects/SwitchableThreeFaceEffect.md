# SwitchableThreeFaceEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _upEffect`

- `String _downEffect`

- `Boolean _forceCheckInUpdate`

- `FaceDirType m_cachedFaceDir`


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
public class SwitchableThreeFaceEffect : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _upEffect; // 0x20
	private String _downEffect; // 0x28
	private Boolean _forceCheckInUpdate; // 0x30
	private ObjectPtr`1 m_upEffect; // 0x38
	private ObjectPtr`1 m_downEffect; // 0x48
	private FaceDirType m_cachedFaceDir; // 0x58
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateFace; // 0x20
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2011348 VA: 0x7594629348
	public override Void OnPlay() { }
	// RVA: 0x20117d8 VA: 0x75946297d8
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x2011998 VA: 0x7594629998
	public override Void OnFinish() { }
	// RVA: 0x2011af8 VA: 0x7594629af8
	private Void Update() { }
	// RVA: 0x20113c8 VA: 0x75946293c8
	private Void _UpdateFace(Boolean force) { }
	// RVA: 0x2011b80 VA: 0x7594629b80
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x2011bf8 VA: 0x7594629bf8
	public Void .ctor() { }
	// RVA: 0x2011c70 VA: 0x7594629c70
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2011c78 VA: 0x7594629c78
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```