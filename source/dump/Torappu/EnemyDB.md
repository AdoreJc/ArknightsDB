# EnemyDB

**Namespace:** `Torappu`


## Methods

- `Boolean TryGet(String, Int32, out)`

- `Boolean TryGet(EnemyDataDbReference, out)`

- `String GetEnemyName(String)`

- `Boolean TryGetHandbookEnemyData(String, Int32, out)`

- `Boolean TryGetHandbookEnemyData(EnemyDataDbReference, out, out)`

- `InternalEnemyHBData _ComputeEnemyHBData(EnemyData, EnemyData, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class EnemyDB : ConstTable`2
{
	public const String ENEMYDB_SINGLE_FILE_PATH; // 0x0
	private static DelegateBridge __Hotfix0_TryGet; // 0x0
	private static DelegateBridge __Hotfix1_TryGet; // 0x8
	private static DelegateBridge __Hotfix0_GetEnemyName; // 0x10
	private static DelegateBridge __Hotfix0_TryGetHandbookEnemyData; // 0x18
	private static DelegateBridge __Hotfix1_TryGetHandbookEnemyData; // 0x20
	private static DelegateBridge __Hotfix0__ComputeEnemyHBData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31ef4ec VA: 0x75958074ec
	public Boolean TryGet(String id, Int32 level, out EnemyData output) { }
	// RVA: 0x31ef5d0 VA: 0x75958075d0
	public Boolean TryGet(EnemyDataDbReference dbRef, out EnemyData output) { }
	// RVA: 0x31ef7d4 VA: 0x75958077d4
	public String GetEnemyName(String enemyId) { }
	// RVA: 0x31ef970 VA: 0x7595807970
	public Boolean TryGetHandbookEnemyData(String id, Int32 level, out InternalEnemyHBData output) { }
	// RVA: 0x31f0864 VA: 0x7595808864
	public Boolean TryGetHandbookEnemyData(EnemyDataDbReference dbRef, out InternalEnemyHBData output, out Boolean isSp) { }
	// RVA: 0x31efac0 VA: 0x7595807ac0
	private InternalEnemyHBData _ComputeEnemyHBData(EnemyData enemyData, EnemyData levelData, out Boolean isOverwritten) { }
	// RVA: 0x31f0ab8 VA: 0x7595808ab8
	public Void .ctor() { }
}
```