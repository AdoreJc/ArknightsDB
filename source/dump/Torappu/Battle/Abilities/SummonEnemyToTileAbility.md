# SummonEnemyToTileAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetSelector _sourceSelector`

- `String _enemyKey`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _waitTime`

- `Single _offset`

- `String _summonTileEffect`

- `Boolean _noEndPosition`

- `Boolean _rootTileAsCenter`

- `Boolean _summonToAllTile`

- `Boolean _randomEnemy`

- `Boolean _onlySelectMe`

- `Boolean _summonOnCastStart`

- `Boolean _loadValueFromBB`

- `Boolean _dynamicEnemyKey`

- `Boolean _finishSummonedWhenOwnerFinish`

- `Int32 m_maxSummonedCount`

- `String m_enemyKey`

- `Single m_offset`

- `Boolean m_useTileSelector`


## Properties

- `Boolean unharmful`

- `Boolean isSummonNotFull`


## Methods

- `Boolean get_unharmful()`

- `Void FinishAllSummonedEnemy(Object)`

- `Boolean get_isSummonNotFull()`

- `Void _DoSummonEnemy()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`

- `Boolean <>xLuaBaseProxy_get_isReady()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SummonEnemyToTileAbility : AbstractAnimatedAbility
{
	private TargetSelector _sourceSelector; // 0x1c0
	private String _enemyKey; // 0x1c8
	private MotionMode _motionMode; // 0x1d0
	private Boolean _unharmful; // 0x1d4
	private Boolean _alwaysCountAsKilled; // 0x1d5
	private Single _waitTime; // 0x1d8
	private Single _offset; // 0x1dc
	private String _summonTileEffect; // 0x1e0
	private Boolean _noEndPosition; // 0x1e8
	private Boolean _rootTileAsCenter; // 0x1e9
	private Boolean _summonToAllTile; // 0x1ea
	private Boolean _randomEnemy; // 0x1eb
	private String[] _randomEnemys; // 0x1f0
	private Boolean _onlySelectMe; // 0x1f8
	private BuffData[] _buffsToEnemy; // 0x200
	private Boolean _summonOnCastStart; // 0x208
	private Boolean _loadValueFromBB; // 0x209
	private Boolean _dynamicEnemyKey; // 0x20a
	private Boolean _finishSummonedWhenOwnerFinish; // 0x20b
	private ObjectPtr`1 m_routeSource; // 0x210
	protected List`1 m_targetTile; // 0x220
	private ObjectPtr`1 m_summonEffect; // 0x228
	private List`1 m_summonedEnemy; // 0x238
	private List`1 m_randomEnemys; // 0x240
	private Int32 m_maxSummonedCount; // 0x248
	protected String m_enemyKey; // 0x250
	protected Single m_offset; // 0x258
	private Boolean m_useTileSelector; // 0x25c
	private static DelegateBridge __Hotfix0_get_unharmful; // 0x0
	private static DelegateBridge __Hotfix0_get_notSpawnWhenCastEnd; // 0x8
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x10
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x20
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x28
	private static DelegateBridge __Hotfix0_DoSetData; // 0x30
	private static DelegateBridge __Hotfix0_Reset; // 0x38
	private static DelegateBridge __Hotfix0_FinishAllSummonedEnemy; // 0x40
	private static DelegateBridge __Hotfix0_get_isReady; // 0x48
	private static DelegateBridge __Hotfix0_get_isSummonNotFull; // 0x50
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x58
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x60
	private static DelegateBridge __Hotfix0__DoSummonEnemy; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	protected Boolean unharmful { get; }
	protected virtual Boolean notSpawnWhenCastEnd { get; }
	public override Boolean isReady { get; }
	private Boolean isSummonNotFull { get; }

	// RVA: 0x1e2af10 VA: 0x7594442f10
	protected Boolean get_unharmful() { }
	// RVA: 0x1e2b190 VA: 0x7594443190
	protected virtual Boolean get_notSpawnWhenCastEnd() { }
	// RVA: 0x1e2cb00 VA: 0x7594444b00
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e2cb78 VA: 0x7594444b78
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e2cbf8 VA: 0x7594444bf8
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e2cd1c VA: 0x7594444d1c
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e2cdcc VA: 0x7594444dcc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e2d0d0 VA: 0x75944450d0
	protected override Void Reset() { }
	// RVA: 0x1e2d2ac VA: 0x75944452ac
	public Void FinishAllSummonedEnemy(Object arg) { }
	// RVA: 0x1e2d510 VA: 0x7594445510
	public override Boolean get_isReady() { }
	// RVA: 0x1e2d598 VA: 0x7594445598
	private Boolean get_isSummonNotFull() { }
	// RVA: 0x1e2d630 VA: 0x7594445630
	protected override Void OnCastStart() { }
	// RVA: 0x1e2e898 VA: 0x7594446898
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e2e1dc VA: 0x75944461dc
	private Void _DoSummonEnemy() { }
	// RVA: 0x1e2afe4 VA: 0x7594442fe4
	public Void .ctor() { }
	// RVA: 0x1e2eb00 VA: 0x7594446b00
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1e2eb08 VA: 0x7594446b08
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e2eb10 VA: 0x7594446b10
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e2eb38 VA: 0x7594446b38
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e2eb40 VA: 0x7594446b40
	private Boolean <>xLuaBaseProxy_get_isReady() { }
	// RVA: 0x1e2eb48 VA: 0x7594446b48
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e2eb50 VA: 0x7594446b50
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
}
```