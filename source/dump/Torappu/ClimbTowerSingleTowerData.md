# ClimbTowerSingleTowerData

**Namespace:** `Torappu`


## Fields

- `String id`

- `Int32 sortId`

- `Int32 stageNum`

- `String name`

- `String subName`

- `String desc`

- `ClimbTowerTowerType towerType`

- `String preTowerId`

- `String medalId`

- `String hiddenMedalId`

- `String hardModeMedalId`

- `String bossId`

- `String cardId`

- `String dangerDesc`

- `String hardModeDesc`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ClimbTowerSingleTowerData
{
	public String id; // 0x10
	public Int32 sortId; // 0x18
	public Int32 stageNum; // 0x1c
	public String name; // 0x20
	public String subName; // 0x28
	public String desc; // 0x30
	public ClimbTowerTowerType towerType; // 0x38
	public String[] levels; // 0x40
	public String[] hardLevels; // 0x48
	public List`1 taskInfo; // 0x50
	public String preTowerId; // 0x58
	public String medalId; // 0x60
	public String hiddenMedalId; // 0x68
	public String hardModeMedalId; // 0x70
	public String bossId; // 0x78
	public String cardId; // 0x80
	public List`1 curseCardIds; // 0x88
	public String dangerDesc; // 0x90
	public String hardModeDesc; // 0x98


	// RVA: 0x349be90 VA: 0x7595ab3e90
	public Void .ctor() { }
}
```