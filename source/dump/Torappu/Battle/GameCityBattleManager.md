# GameCityBattleManager

**Namespace:** `Torappu.Battle`


## Fields

- `Single _carBuffInterval`

- `String _enemyId`

- `GameCityGameMode m_gameMode`

- `FP m_carBuffInterval`

- `String m_enemyId`

- `EnemyData m_enemyData`

- `PeriodicTimer m_timer`


## Methods

- `Void _UpdateCarBuff(FP)`

- `Void _SpawnTokenRandom()`

- `Boolean _CheckTileValid(Tile)`

- `Boolean <_SpawnTokenRandom>b__11_0(Tile)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GameCityBattleManager : EnvManager
{
	private Single _carBuffInterval; // 0x28
	private String _enemyId; // 0x30
	private GameCityGameMode m_gameMode; // 0x38
	private FP m_carBuffInterval; // 0x40
	private String m_enemyId; // 0x48
	private EnemyData m_enemyData; // 0x50
	private PeriodicTimer m_timer; // 0x58
	private List`1 m_tiles; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__UpdateCarBuff; // 0x10
	private static DelegateBridge __Hotfix0__SpawnTokenRandom; // 0x18
	private static DelegateBridge __Hotfix0__CheckTileValid; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x404bbe0 VA: 0x7596663be0
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x404bf28 VA: 0x7596663f28
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x404bfd4 VA: 0x7596663fd4
	private Void _UpdateCarBuff(FP deltaTime) { }
	// RVA: 0x404c0a8 VA: 0x75966640a8
	private Void _SpawnTokenRandom() { }
	// RVA: 0x404c37c VA: 0x759666437c
	private Boolean _CheckTileValid(Tile tile) { }
	// RVA: 0x404c7c4 VA: 0x75966647c4
	public Void .ctor() { }
	// RVA: 0x404c8f0 VA: 0x75966648f0
	private Boolean <_SpawnTokenRandom>b__11_0(Tile tile) { }
	// RVA: 0x404c8f4 VA: 0x75966648f4
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x404c8fc VA: 0x75966648fc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```