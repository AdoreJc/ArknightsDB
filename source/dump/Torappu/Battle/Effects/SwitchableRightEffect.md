# SwitchableRightEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _rightEffect`

- `Boolean _onlyCheckOnPlay`

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
public class SwitchableRightEffect : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _rightEffect; // 0x20
	private Boolean _onlyCheckOnPlay; // 0x28
	private ObjectPtr`1 m_rightEffect; // 0x30
	private Boolean m_cachedIsRight; // 0x40
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateFace; // 0x20
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2010cd4 VA: 0x7594628cd4
	public override Void OnPlay() { }
	// RVA: 0x2010fa8 VA: 0x7594628fa8
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x20110bc VA: 0x75946290bc
	public override Void OnFinish() { }
	// RVA: 0x20111c0 VA: 0x75946291c0
	private Void Update() { }
	// RVA: 0x2010d4c VA: 0x7594628d4c
	private Void _UpdateFace(Boolean force) { }
	// RVA: 0x2011250 VA: 0x7594629250
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x20112c8 VA: 0x75946292c8
	public Void .ctor() { }
	// RVA: 0x2011338 VA: 0x7594629338
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2011340 VA: 0x7594629340
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```