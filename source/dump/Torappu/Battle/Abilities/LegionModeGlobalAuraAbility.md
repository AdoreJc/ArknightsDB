# LegionModeGlobalAuraAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetValidator _targetValidator`

- `SelfOption _selfOption`

- `Boolean _removeBuffWhenAbilityDetached`

- `Boolean _removeBuffIncludeReborning`

- `Boolean _onlyDetectTargetWhenStarted`

- `Boolean _onlyDetectCurrentMapLayer`


## Properties

- `Boolean removeBuffWhenAbilityDetached`


## Methods

- `Boolean get_removeBuffWhenAbilityDetached()`

- `Void _ClearBuffs()`

- `Void _OnMapLayerChanged(Object)`

- `Boolean _DealTarget(Entity)`

- `Void _OnUnitBornOrRallyPointReborn(Object)`

- `Void _OnRallyPointDead(Object)`

- `Void _OnRallyPointLikeSwitch(Object)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_UpdateBlackboard()`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_RefreshLegionBuff()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class LegionModeGlobalAuraAbility : LegionModeAbility
{
	private TargetValidator _targetValidator; // 0x130
	private SelfOption _selfOption; // 0x138
	private Boolean _removeBuffWhenAbilityDetached; // 0x13c
	private Boolean _removeBuffIncludeReborning; // 0x13d
	private Boolean _onlyDetectTargetWhenStarted; // 0x13e
	private Boolean _onlyDetectCurrentMapLayer; // 0x13f
	private Dictionary`2 m_targetMap; // 0x140
	private List`1 m_targetList; // 0x148
	private static DelegateBridge __Hotfix0_get_removeBuffWhenAbilityDetached; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_UpdateBlackboard; // 0x18
	private static DelegateBridge __Hotfix0_DoDetach; // 0x20
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x28
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x30
	private static DelegateBridge __Hotfix0__OnMapLayerChanged; // 0x38
	private static DelegateBridge __Hotfix0_RefreshLegionBuff; // 0x40
	private static DelegateBridge __Hotfix0__GetBuffs; // 0x48
	private static DelegateBridge __Hotfix0__DealTarget; // 0x50
	private static DelegateBridge __Hotfix0__OnUnitBornOrRallyPointReborn; // 0x58
	private static DelegateBridge __Hotfix0__OnRallyPointDead; // 0x60
	private static DelegateBridge __Hotfix0__OnRallyPointLikeSwitch; // 0x68
	private static DelegateBridge __Hotfix0_VerityTarget; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private Boolean removeBuffWhenAbilityDetached { get; }

	// RVA: 0x1e7905c VA: 0x759449105c
	private Boolean get_removeBuffWhenAbilityDetached() { }
	// RVA: 0x1e790c4 VA: 0x75944910c4
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e7919c VA: 0x759449119c
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e79848 VA: 0x7594491848
	protected override Void UpdateBlackboard() { }
	// RVA: 0x1e79cb4 VA: 0x7594491cb4
	protected override Void DoDetach() { }
	// RVA: 0x1e7a2cc VA: 0x75944922cc
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e79fa8 VA: 0x7594491fa8
	private Void _ClearBuffs() { }
	// RVA: 0x1e7a498 VA: 0x7594492498
	private Void _OnMapLayerChanged(Object arg) { }
	// RVA: 0x1e7a5ac VA: 0x75944925ac
	public override Void RefreshLegionBuff() { }
	// RVA: 0x1e7a6cc VA: 0x75944926cc
	private IList`1 _GetBuffs() { }
	// RVA: 0x1e7952c VA: 0x759449152c
	private Boolean _DealTarget(Entity target) { }
	// RVA: 0x1e7a8c8 VA: 0x75944928c8
	private Void _OnUnitBornOrRallyPointReborn(Object arg) { }
	// RVA: 0x1e7aa2c VA: 0x7594492a2c
	private Void _OnRallyPointDead(Object arg) { }
	// RVA: 0x1e7ac30 VA: 0x7594492c30
	private Void _OnRallyPointLikeSwitch(Object arg) { }
	// RVA: 0x1e7ae48 VA: 0x7594492e48
	protected virtual Boolean VerityTarget(Entity target) { }
	// RVA: 0x1e7af1c VA: 0x7594492f1c
	public Void .ctor() { }
	// RVA: 0x1e7b064 VA: 0x7594493064
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e7b08c VA: 0x759449308c
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e7b094 VA: 0x7594493094
	private Void <>xLuaBaseProxy_UpdateBlackboard() { }
	// RVA: 0x1e7b098 VA: 0x7594493098
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e7b0a0 VA: 0x75944930a0
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e7b0a8 VA: 0x75944930a8
	private Void <>xLuaBaseProxy_RefreshLegionBuff() { }
}
```