# UpdateableBuffTile

**Namespace:** `Torappu.Battle`


## Fields

- `PeriodicTicker m_triggerTicker`


## Methods

- `Void OnFixedUpdate(FP)`

- `Void _UpdateEnemy()`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`

- `Void <>xLuaBaseProxy_OnInvalidEnemyEnter(Enemy)`

- `Void <>xLuaBaseProxy_OnEnemyLeave(Enemy)`

- `Void <>xLuaBaseProxy_OnEnemyValid(Enemy)`

- `Void <>xLuaBaseProxy_OnEnemyInvalid(Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UpdateableBuffTile : BuffTile, IUpdateable
{
	private ListSet`1 m_invalidEnemy; // 0x198
	private ListSet`1 m_validEnemy; // 0x1a0
	private const Int32 TRIGGER_TICK; // 0x0
	private PeriodicTicker m_triggerTicker; // 0x1a8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x8
	private static DelegateBridge __Hotfix0__UpdateEnemy; // 0x10
	private static DelegateBridge __Hotfix0_OnInvalidEnemyEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnEnemyLeave; // 0x20
	private static DelegateBridge __Hotfix0_OnEnemyValid; // 0x28
	private static DelegateBridge __Hotfix0_OnEnemyInvalid; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x4099ba8 VA: 0x75966b1ba8
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x4099c4c VA: 0x75966b1c4c
	public Void OnFixedUpdate(FP fixedDeltaTime) { }
	// RVA: 0x4099d00 VA: 0x75966b1d00
	private Void _UpdateEnemy() { }
	// RVA: 0x409a1cc VA: 0x75966b21cc
	public override Void OnInvalidEnemyEnter(Enemy enemy) { }
	// RVA: 0x409a2a8 VA: 0x75966b22a8
	protected override Void OnEnemyLeave(Enemy enemy) { }
	// RVA: 0x409a384 VA: 0x75966b2384
	public override Void OnEnemyValid(Enemy enemy) { }
	// RVA: 0x409a4a4 VA: 0x75966b24a4
	public override Void OnEnemyInvalid(Enemy enemy) { }
	// RVA: 0x409a580 VA: 0x75966b2580
	public Void .ctor() { }
	// RVA: 0x409a6dc VA: 0x75966b26dc
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
	// RVA: 0x409a6e0 VA: 0x75966b26e0
	private Void <>xLuaBaseProxy_OnInvalidEnemyEnter(Enemy P0) { }
	// RVA: 0x409a6e4 VA: 0x75966b26e4
	private Void <>xLuaBaseProxy_OnEnemyLeave(Enemy P0) { }
	// RVA: 0x409a6e8 VA: 0x75966b26e8
	private Void <>xLuaBaseProxy_OnEnemyValid(Enemy P0) { }
	// RVA: 0x409a6ec VA: 0x75966b26ec
	private Void <>xLuaBaseProxy_OnEnemyInvalid(Enemy P0) { }
}
```