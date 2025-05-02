# GlobalAuraAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetValidator _targetValidator`

- `SelfOption _selfOption`

- `Boolean _removeBuffWhenAbilityDetached`

- `Boolean _removeBuffIncludeReborning`

- `Boolean _onlyDetactTargetWhenStarted`

- `Boolean _onlyDetectCurrentMapLayer`

- `Boolean _listenUnitRebornEvent`

- `Boolean _forceRemoveAllBuffsByKey`

- `Boolean _forceTick`

- `Boolean _excludeReborningEntity`

- `Single _interval`

- `Boolean _clearBuffsWhenDisappear`

- `PeriodicTicker m_triggerTicker`

- `PeriodicTimer m_tickTimer`


## Properties

- `Boolean removeBuffWhenAbilityDetached`

- `Boolean forceTick`


## Methods

- `Boolean get_removeBuffWhenAbilityDetached()`

- `Boolean get_forceTick()`

- `Void OnDestroy()`

- `Void _ClearBuffs()`

- `Void _OnMapLayerChanged(Object)`

- `Void _OnDisappearChanged(Object)`

- `Void _OnUnitBornOrRallyPointReborn(Object)`

- `Void _OnRallyPointDead(Object)`

- `Void _OnRallyPointLikeSwitch(Object)`

- `Void _ClearEffects()`

- `Void _UpdateTargetMap()`

- `Void _UpdateTargets()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class GlobalAuraAbility : AbilityStandard
{
	private const Int32 TRIGGER_TICK; // 0x0
	private TargetValidator _targetValidator; // 0x108
	protected BuffData[] _buffs; // 0x110
	protected BuffData[] _passiveBuffs; // 0x118
	protected SelfOption _selfOption; // 0x120
	private Boolean _removeBuffWhenAbilityDetached; // 0x124
	private Boolean _removeBuffIncludeReborning; // 0x125
	private Boolean _onlyDetactTargetWhenStarted; // 0x126
	private Boolean _onlyDetectCurrentMapLayer; // 0x127
	private Boolean _listenUnitRebornEvent; // 0x128
	private Boolean _forceRemoveAllBuffsByKey; // 0x129
	private String[] _effects; // 0x130
	private Boolean _forceTick; // 0x138
	private Boolean _excludeReborningEntity; // 0x139
	private Single _interval; // 0x13c
	private Boolean _clearBuffsWhenDisappear; // 0x140
	protected Dictionary`2 m_targetMap; // 0x148
	protected List`1 m_targetList; // 0x150
	private List`1 m_effects; // 0x158
	private PeriodicTicker m_triggerTicker; // 0x160
	private PeriodicTimer m_tickTimer; // 0x168
	private readonly List`1 m_sharedTargetList; // 0x170
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x18
	private static DelegateBridge __Hotfix0_get_removeBuffWhenAbilityDetached; // 0x20
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x28
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x30
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x40
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x48
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x50
	private static DelegateBridge __Hotfix0_get_forceTick; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge __Hotfix0_DoSetData; // 0x68
	private static DelegateBridge __Hotfix0_DoAttach; // 0x70
	private static DelegateBridge __Hotfix0_DoDetach; // 0x78
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x80
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x88
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x90
	private static DelegateBridge __Hotfix0__OnMapLayerChanged; // 0x98
	private static DelegateBridge __Hotfix0__OnDisappearChanged; // 0xa0
	private static DelegateBridge __Hotfix0_DealTarget; // 0xa8
	private static DelegateBridge __Hotfix0__OnUnitBornOrRallyPointReborn; // 0xb0
	private static DelegateBridge __Hotfix0__OnRallyPointDead; // 0xb8
	private static DelegateBridge __Hotfix0__OnRallyPointLikeSwitch; // 0xc0
	private static DelegateBridge __Hotfix0__ClearEffects; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateTargetMap; // 0xd0
	private static DelegateBridge __Hotfix0__UpdateTargets; // 0xd8
	private static DelegateBridge __Hotfix0_VerityTarget; // 0xe0
	private static DelegateBridge __Hotfix0_OnTick; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	private Boolean removeBuffWhenAbilityDetached { get; }
	protected Boolean forceTick { get; }

	// RVA: 0x1e41924 VA: 0x7594459924
	public override FP get_cooldown() { }
	// RVA: 0x1e419b4 VA: 0x75944599b4
	public override Category get_category() { }
	// RVA: 0x1e41a1c VA: 0x7594459a1c
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e41a80 VA: 0x7594459a80
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e41ae4 VA: 0x7594459ae4
	private Boolean get_removeBuffWhenAbilityDetached() { }
	// RVA: 0x1e41b4c VA: 0x7594459b4c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e41bc4 VA: 0x7594459bc4
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e41c44 VA: 0x7594459c44
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e41cac VA: 0x7594459cac
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e41d10 VA: 0x7594459d10
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e41dd4 VA: 0x7594459dd4
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e41e98 VA: 0x7594459e98
	protected Boolean get_forceTick() { }
	// RVA: 0x1e41f00 VA: 0x7594459f00
	private Void OnDestroy() { }
	// RVA: 0x1e41fa8 VA: 0x7594459fa8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e420f4 VA: 0x759445a0f4
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e42844 VA: 0x759445a844
	protected override Void DoDetach() { }
	// RVA: 0x1e43648 VA: 0x759445b648
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e436f8 VA: 0x759445b6f8
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e42c10 VA: 0x759445ac10
	private Void _ClearBuffs() { }
	// RVA: 0x1e437a8 VA: 0x759445b7a8
	private Void _OnMapLayerChanged(Object arg) { }
	// RVA: 0x1e438c8 VA: 0x759445b8c8
	private Void _OnDisappearChanged(Object arg) { }
	// RVA: 0x1e43ef0 VA: 0x759445bef0
	protected virtual Boolean DealTarget(Entity target) { }
	// RVA: 0x1e44204 VA: 0x759445c204
	private Void _OnUnitBornOrRallyPointReborn(Object arg) { }
	// RVA: 0x1e44374 VA: 0x759445c374
	private Void _OnRallyPointDead(Object arg) { }
	// RVA: 0x1e44578 VA: 0x759445c578
	private Void _OnRallyPointLikeSwitch(Object arg) { }
	// RVA: 0x1e426d4 VA: 0x759445a6d4
	private Void _ClearEffects() { }
	// RVA: 0x1e447a8 VA: 0x759445c7a8
	private Void _UpdateTargetMap() { }
	// RVA: 0x1e439a0 VA: 0x759445b9a0
	private Void _UpdateTargets() { }
	// RVA: 0x1e44adc VA: 0x759445cadc
	protected virtual Boolean VerityTarget(Entity target) { }
	// RVA: 0x1e44cb4 VA: 0x759445ccb4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e44e00 VA: 0x759445ce00
	public Void .ctor() { }
	// RVA: 0x1e4504c VA: 0x759445d04c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e45074 VA: 0x759445d074
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e4507c VA: 0x759445d07c
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e45084 VA: 0x759445d084
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1e4508c VA: 0x759445d08c
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e45094 VA: 0x759445d094
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```