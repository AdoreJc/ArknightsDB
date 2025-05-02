# DsdevrMarkTileAuraAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _maxTarget`

- `String _tileEffect`

- `String _markEnemyKey`

- `Int32 m_maxTarget`

- `CoroutineId m_coroutine`


## Properties

- `Boolean hasEffect`


## Methods

- `Boolean get_hasEffect()`

- `Void _clearAll()`

- `Void _UpdateEffects()`

- `Void _OnUnitBorn(Object)`

- `IEnumerator _DelayUpdateTargets()`

- `Void _FilterTiles()`

- `Void _CreateMarkEnemy()`

- `IEnumerator _DelayCreateEnemy(GridPosition, FP)`

- `Int32 _Comparer(TargetTileBundle, TargetTileBundle)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class DsdevrMarkTileAuraAbility : AbilityStandard
{
	private static readonly FP CREATE_MARK_INTERVAL; // 0x0
	private static readonly Single MARK_ENEMY_WAIT_TIME; // 0x8
	private Int32 _maxTarget; // 0x108
	private String _tileEffect; // 0x110
	private String _markEnemyKey; // 0x118
	private Int32 m_maxTarget; // 0x120
	private CoroutineId m_coroutine; // 0x128
	private List`1 m_targetTileBundles; // 0x138
	private static DelegateBridge __Hotfix0_get_hasEffect; // 0x10
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x18
	private static DelegateBridge __Hotfix0_get_category; // 0x20
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x28
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x30
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x38
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x40
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x48
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x50
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x58
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x60
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x68
	private static DelegateBridge __Hotfix0_DoSetData; // 0x70
	private static DelegateBridge __Hotfix0_DoAttach; // 0x78
	private static DelegateBridge __Hotfix0_DoDetach; // 0x80
	private static DelegateBridge __Hotfix0__clearAll; // 0x88
	private static DelegateBridge __Hotfix0__UpdateEffects; // 0x90
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x98
	private static DelegateBridge __Hotfix0__DelayUpdateTargets; // 0xa0
	private static DelegateBridge __Hotfix0__FilterTiles; // 0xa8
	private static DelegateBridge __Hotfix0__CreateMarkEnemy; // 0xb0
	private static DelegateBridge __Hotfix0__DelayCreateEnemy; // 0xb8
	private static DelegateBridge __Hotfix0__Comparer; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	private Boolean hasEffect { get; }
	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e46278 VA: 0x759445e278
	private Boolean get_hasEffect() { }
	// RVA: 0x1e46300 VA: 0x759445e300
	public override FP get_cooldown() { }
	// RVA: 0x1e463a0 VA: 0x759445e3a0
	public override Category get_category() { }
	// RVA: 0x1e46418 VA: 0x759445e418
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e4648c VA: 0x759445e48c
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e46500 VA: 0x759445e500
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e46588 VA: 0x759445e588
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e46618 VA: 0x759445e618
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e4668c VA: 0x759445e68c
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e46700 VA: 0x759445e700
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e467d4 VA: 0x759445e7d4
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e468a8 VA: 0x759445e8a8
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e469bc VA: 0x759445e9bc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e46ac8 VA: 0x759445eac8
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e46c04 VA: 0x759445ec04
	protected override Void DoDetach() { }
	// RVA: 0x1e46fd4 VA: 0x759445efd4
	private Void _clearAll() { }
	// RVA: 0x1e4720c VA: 0x759445f20c
	private Void _UpdateEffects() { }
	// RVA: 0x1e473f0 VA: 0x759445f3f0
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x1e47528 VA: 0x759445f528
	private IEnumerator _DelayUpdateTargets() { }
	// RVA: 0x1e4760c VA: 0x759445f60c
	private Void _FilterTiles() { }
	// RVA: 0x1e46d38 VA: 0x759445ed38
	private Void _CreateMarkEnemy() { }
	// RVA: 0x1e47790 VA: 0x759445f790
	private IEnumerator _DelayCreateEnemy(GridPosition position, FP delay) { }
	// RVA: 0x1e47898 VA: 0x759445f898
	private Int32 _Comparer(TargetTileBundle a, TargetTileBundle b) { }
	// RVA: 0x1e47afc VA: 0x759445fafc
	public Void .ctor() { }
	// RVA: 0x1e47bd0 VA: 0x759445fbd0
	private static Void .cctor() { }
	// RVA: 0x1e47c60 VA: 0x759445fc60
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1e47c68 VA: 0x759445fc68
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e47c90 VA: 0x759445fc90
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e47c98 VA: 0x759445fc98
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```