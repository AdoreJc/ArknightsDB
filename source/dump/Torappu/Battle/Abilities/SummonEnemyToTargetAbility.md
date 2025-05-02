# SummonEnemyToTargetAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetSelector _sourceSelector`

- `String _enemyKey`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _waitTime`

- `Single _offset`

- `Boolean _noEndPosition`

- `Boolean _selectTargetAsSource`

- `Boolean _loadValueFromBB`

- `Boolean _finishSummonedWhenOwnerFinish`

- `String m_enemyKey`


## Methods

- `Void FinishAllSummonedEnemy(Object)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SummonEnemyToTargetAbility : AbstractAnimatedAbility
{
	private TargetSelector _sourceSelector; // 0x1c0
	private String _enemyKey; // 0x1c8
	private MotionMode _motionMode; // 0x1d0
	private Boolean _unharmful; // 0x1d4
	private Boolean _alwaysCountAsKilled; // 0x1d5
	private Single _waitTime; // 0x1d8
	private Single _offset; // 0x1dc
	private Boolean _noEndPosition; // 0x1e0
	private Boolean _selectTargetAsSource; // 0x1e1
	private BuffData[] _buffsToEnemy; // 0x1e8
	private Boolean _loadValueFromBB; // 0x1f0
	private Boolean _finishSummonedWhenOwnerFinish; // 0x1f1
	private List`1 m_summonedEnemy; // 0x1f8
	private String m_enemyKey; // 0x200
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x0
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0_DoSetData; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0_FinishAllSummonedEnemy; // 0x28
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1e2bd60 VA: 0x7594443d60
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e2bdd8 VA: 0x7594443dd8
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e2be58 VA: 0x7594443e58
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e2bf08 VA: 0x7594443f08
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e2c0e0 VA: 0x75944440e0
	protected override Void Reset() { }
	// RVA: 0x1e2c214 VA: 0x7594444214
	public Void FinishAllSummonedEnemy(Object arg) { }
	// RVA: 0x1e2c478 VA: 0x7594444478
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e2c9c0 VA: 0x75944449c0
	public Void .ctor() { }
	// RVA: 0x1e2cac0 VA: 0x7594444ac0
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e2cac8 VA: 0x7594444ac8
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e2caf0 VA: 0x7594444af0
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e2caf8 VA: 0x7594444af8
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
}
```