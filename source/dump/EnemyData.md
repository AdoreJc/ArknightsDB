# EnemyData

**Namespace:** ` `


## Fields

- `String name`

- `String description`

- `String key`

- `AttributesData attributes`

- `SourceApplyWay applyWay`

- `MotionMode motion`

- `Boolean notCountInTotal`

- `String alias`

- `Int32 lifePointReduce`

- `Single rangeRadius`

- `Int32 numOfExtraDrops`

- `Single viewRadius`

- `EnemyLevelType levelType`

- `Blackboard talentBlackboard`

- `ESpData spData`

- `RuntimeData m_runtimeData`


## Properties

- `String keyInLevel`

- `Boolean isBoss`

- `RuntimeData runtimeData`


## Methods

- `String get_keyInLevel()`

- `Boolean get_isBoss()`

- `RuntimeData get_runtimeData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyData
{
	public String name; // 0x10
	public String description; // 0x18
	public String key; // 0x20
	public AttributesData attributes; // 0x28
	public SourceApplyWay applyWay; // 0x30
	public MotionMode motion; // 0x34
	public String[] enemyTags; // 0x38
	public Boolean notCountInTotal; // 0x40
	public String alias; // 0x48
	public Int32 lifePointReduce; // 0x50
	public Single rangeRadius; // 0x54
	public Int32 numOfExtraDrops; // 0x58
	public Single viewRadius; // 0x5c
	public EnemyLevelType levelType; // 0x60
	public Blackboard talentBlackboard; // 0x68
	public ESkillData[] skills; // 0x70
	public ESpData spData; // 0x78
	private RuntimeData m_runtimeData; // 0x80

	public String keyInLevel { get; }
	public Boolean isBoss { get; }
	public RuntimeData runtimeData { get; }

	// RVA: 0x34a40e8 VA: 0x7595abc0e8
	public String get_keyInLevel() { }
	// RVA: 0x34a4118 VA: 0x7595abc118
	public Boolean get_isBoss() { }
	// RVA: 0x34a4128 VA: 0x7595abc128
	public RuntimeData get_runtimeData() { }
	// RVA: 0x349ebc4 VA: 0x7595ab6bc4
	public Void .ctor() { }
}
```