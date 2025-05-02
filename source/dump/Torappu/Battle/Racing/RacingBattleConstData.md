# RacingBattleConstData

**Namespace:** `Torappu.Battle.Racing`


## Fields

- `FP RACING_HP_FACTOR`

- `FP RACING_SPEED_FACTOR`

- `FP RACING_ACCELERATION_FACTOR`

- `FP RECOVER_MOVE_SPEED`

- `FP RECOVER_HP_FACTOR`

- `FP BLEEDING_FACTOR`

- `FP MAX_STEERING_FACTOR`

- `FP STEERING_MASS_LEVEL_FACTOR`

- `FP STEERING_MOVE_SPEED_FACTOR`

- `Single COLLISION_SAFE_ANGLE_COS`

- `Int32 COLLISION_SAFE_FORCE_LEVEL`

- `FP TILE_COLLISION_FACTOR`

- `FP AUTO_USE_ITEM_TIME_MIN`

- `FP AUTO_USE_ITEM_TIME_MAX`

- `FP RECOVER_ACCELERATION`


## Methods

- `Void InitData(RacingInput)`

- `Int32 GetCollisionForceConfig(Single)`

- `Void GetCollisionResultConfig(Int32, Boolean, out, out)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Racing
public class RacingBattleConstData : SingletonInScene`1, IDisposable
{
	public const String RACING_ENEMY_ITEM_1; // 0x0
	public FP RACING_HP_FACTOR; // 0x18
	public FP RACING_SPEED_FACTOR; // 0x20
	public FP RACING_ACCELERATION_FACTOR; // 0x28
	public FP RECOVER_MOVE_SPEED; // 0x30
	public FP RECOVER_HP_FACTOR; // 0x38
	public FP BLEEDING_FACTOR; // 0x40
	public FP MAX_STEERING_FACTOR; // 0x48
	public FP STEERING_MASS_LEVEL_FACTOR; // 0x50
	public FP STEERING_MOVE_SPEED_FACTOR; // 0x58
	public Single COLLISION_SAFE_ANGLE_COS; // 0x60
	public Int32 COLLISION_SAFE_FORCE_LEVEL; // 0x64
	public FP TILE_COLLISION_FACTOR; // 0x68
	public FP AUTO_USE_ITEM_TIME_MIN; // 0x70
	public FP AUTO_USE_ITEM_TIME_MAX; // 0x78
	public FP RECOVER_ACCELERATION; // 0x80
	public Dictionary`2 racingItemInfos; // 0x88
	public List`1 collisionConfigDatas; // 0x90
	public List`1 collisionResultDatas; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_GetCollisionForceConfig; // 0x10
	private static DelegateBridge __Hotfix0_GetCollisionResultConfig; // 0x18
	private static DelegateBridge __Hotfix0_Dispose; // 0x20


	// RVA: 0x1d57ec8 VA: 0x759436fec8
	private Void .ctor() { }
	// RVA: 0x1d57f80 VA: 0x759436ff80
	public Void InitData(RacingInput input) { }
	// RVA: 0x1d58a54 VA: 0x7594370a54
	public Int32 GetCollisionForceConfig(Single collisionForce) { }
	// RVA: 0x1d58b6c VA: 0x7594370b6c
	public Void GetCollisionResultConfig(Int32 realForceIndex, Boolean hitTile, out FP speedLoss, out FP hpLoss) { }
	// RVA: 0x1d58d14 VA: 0x7594370d14
	public Void Dispose() { }
}
```