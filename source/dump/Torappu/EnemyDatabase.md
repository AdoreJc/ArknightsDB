# EnemyDatabase

**Namespace:** `Torappu`


## Methods

- `EnemyData GetEnemyLevelData(String, Int32, out)`

- `EnemyData GetComputedEnemyData(String, Int32)`

- `Boolean IsEnemyExist(String, Int32)`

- `Boolean IsEnemyLevelsExist(String)`

- `EnemyData _FindEnemyLevel(List`1, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class EnemyDatabase
{
	public List`1 enemies; // 0x10


	// RVA: 0x349e0f8 VA: 0x7595ab60f8
	public EnemyData GetEnemyLevelData(String id, Int32 level, out Boolean isDefaultLevel) { }
	// RVA: 0x349e3e4 VA: 0x7595ab63e4
	public static Void OverwriteEnemyData(EnemyData levelData, EnemyData overwrittenData, out Boolean isOverwritten) { }
	// RVA: 0x349e984 VA: 0x7595ab6984
	public EnemyData GetComputedEnemyData(String id, Int32 level) { }
	// RVA: 0x349ee70 VA: 0x7595ab6e70
	public Boolean IsEnemyExist(String id, Int32 level) { }
	// RVA: 0x349eef0 VA: 0x7595ab6ef0
	public Boolean IsEnemyLevelsExist(String id) { }
	// RVA: 0x349e274 VA: 0x7595ab6274
	public KeyValuePair`2 FindEnemyLevelsById(String id) { }
	// RVA: 0x349ec98 VA: 0x7595ab6c98
	public static Void ApplyDefinedData(EnemyData data, EnemyData delta) { }
	// RVA: 0x349ef50 VA: 0x7595ab6f50
	private static Void _ApplyUndefinableData(Object data, Object delta) { }
	// RVA: 0x349f3a8 VA: 0x7595ab73a8
	private static Void _ConvertEnemyAttributes(AttributesData target, AttributesData source) { }
	// RVA: 0x349f990 VA: 0x7595ab7990
	private static Void _ApplyBlackboardData(Blackboard data, Blackboard delta) { }
	// RVA: 0x349fd8c VA: 0x7595ab7d8c
	private static Void _ApplySkillData(List`1 data, IEnumerable`1 delta) { }
	// RVA: 0x349eb04 VA: 0x7595ab6b04
	private EnemyData _FindEnemyLevel(List`1 enemyLevels, Int32 targetLevel) { }
	// RVA: 0x34a04a4 VA: 0x7595ab84a4
	public Void .ctor() { }
}
```