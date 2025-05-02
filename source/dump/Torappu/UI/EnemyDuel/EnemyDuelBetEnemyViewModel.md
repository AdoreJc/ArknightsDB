# EnemyDuelBetEnemyViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String enemyId`

- `String enemyIconId`

- `Int32 enemyCount`

- `String enemyName`

- `String enemyDesc`


## Methods

- `Void LoadData(EnemyDuelEnemyGenerationData, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetEnemyViewModel : IHotfixable
{
	public String enemyId; // 0x10
	public String enemyIconId; // 0x18
	public Int32 enemyCount; // 0x20
	public String enemyName; // 0x28
	public String enemyDesc; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2982530 VA: 0x7594f9a530
	public Void LoadData(EnemyDuelEnemyGenerationData enemyData, Dictionary`2 enemyTable) { }
	// RVA: 0x2982690 VA: 0x7594f9a690
	public Void .ctor() { }
}
```