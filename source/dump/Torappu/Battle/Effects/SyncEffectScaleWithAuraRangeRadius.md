# SyncEffectScaleWithAuraRangeRadius

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Single _effectOriginRadius`

- `String _abilityName`

- `Boolean _updateWhenTick`

- `Boolean _revertWhenFinish`

- `Boolean _applyMaxScale`

- `Single _maxScale`

- `Boolean m_active`

- `AuraAbility m_aura`

- `Single m_scale`


## Properties

- `Boolean applyMaxScale`


## Methods

- `Boolean get_applyMaxScale()`

- `Void Update()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SyncEffectScaleWithAuraRangeRadius : Behaviour
{
	private Single _effectOriginRadius; // 0x20
	private String _abilityName; // 0x28
	private Boolean _updateWhenTick; // 0x30
	private Boolean _revertWhenFinish; // 0x31
	private Boolean _applyMaxScale; // 0x32
	private Single _maxScale; // 0x34
	private Boolean m_active; // 0x38
	private AuraAbility m_aura; // 0x40
	private Single m_scale; // 0x48
	private static DelegateBridge __Hotfix0_get_applyMaxScale; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean applyMaxScale { get; }

	// RVA: 0x2013898 VA: 0x759462b898
	public Boolean get_applyMaxScale() { }
	// RVA: 0x2013900 VA: 0x759462b900
	public override Void OnPlay() { }
	// RVA: 0x2013b7c VA: 0x759462bb7c
	public override Void OnFinish() { }
	// RVA: 0x2013c68 VA: 0x759462bc68
	private Void Update() { }
	// RVA: 0x2013d80 VA: 0x759462bd80
	public Void .ctor() { }
	// RVA: 0x2013e00 VA: 0x759462be00
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2013e08 VA: 0x759462be08
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```