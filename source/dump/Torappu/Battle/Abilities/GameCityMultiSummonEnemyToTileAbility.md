# GameCityMultiSummonEnemyToTileAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _spawnCnt`

- `Single _delayTime`


## Methods

- `Void _DoSummonEnemies()`

- `Boolean <>xLuaBaseProxy_get_notSpawnWhenCastEnd()`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class GameCityMultiSummonEnemyToTileAbility : SummonEnemyToTileAbility
{
	private Int32 _spawnCnt; // 0x260
	private Single _delayTime; // 0x264
	private static DelegateBridge __Hotfix0_get_notSpawnWhenCastEnd; // 0x0
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x8
	private static DelegateBridge __Hotfix0__DoSummonEnemies; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override Boolean notSpawnWhenCastEnd { get; }

	// RVA: 0x1e2a9cc VA: 0x75944429cc
	protected override Boolean get_notSpawnWhenCastEnd() { }
	// RVA: 0x1e2aa34 VA: 0x7594442a34
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e2aaf0 VA: 0x7594442af0
	private Void _DoSummonEnemies() { }
	// RVA: 0x1e2af78 VA: 0x7594442f78
	public Void .ctor() { }
	// RVA: 0x1e2b18c VA: 0x759444318c
	private Boolean <>xLuaBaseProxy_get_notSpawnWhenCastEnd() { }
	// RVA: 0x1e2b1f8 VA: 0x75944431f8
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
}
```