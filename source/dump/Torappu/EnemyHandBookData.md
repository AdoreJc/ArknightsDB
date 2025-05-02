# EnemyHandBookData

**Namespace:** `Torappu`


## Fields

- `String enemyId`

- `String enemyIndex`

- `Int32 sortId`

- `String name`

- `EnemyLevelType enemyLevel`

- `String description`

- `String attackType`

- `String ability`

- `Boolean isInvalidKilled`

- `Boolean hideInHandbook`

- `Boolean hideInStage`

- `Boolean invisibleDetail`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class EnemyHandBookData
{
	public String enemyId; // 0x10
	public String enemyIndex; // 0x18
	public String[] enemyTags; // 0x20
	public Int32 sortId; // 0x28
	public String name; // 0x30
	public EnemyLevelType enemyLevel; // 0x38
	public String description; // 0x40
	public String attackType; // 0x48
	public String ability; // 0x50
	public Boolean isInvalidKilled; // 0x58
	public Dictionary`2 overrideKillCntInfos; // 0x60
	public Boolean hideInHandbook; // 0x68
	public Boolean hideInStage; // 0x69
	public List`1 abilityList; // 0x70
	public List`1 linkEnemies; // 0x78
	public List`1 damageType; // 0x80
	public Boolean invisibleDetail; // 0x88


	// RVA: 0x34a0690 VA: 0x7595ab8690
	public Void .ctor() { }
}
```