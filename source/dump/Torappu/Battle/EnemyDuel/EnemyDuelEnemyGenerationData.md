# EnemyDuelEnemyGenerationData

**Namespace:** `Torappu.Battle.EnemyDuel`


## Fields

- `String enemyId`

- `Single value`

- `Single increment`

- `Int32 priority`

- `Int32 count`


## Methods

- `EnemyDuelEnemyGenerationData Duplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.EnemyDuel
public class EnemyDuelEnemyGenerationData : IHotfixable
{
	public String enemyId; // 0x10
	public Single value; // 0x18
	public Single increment; // 0x1c
	public Int32 priority; // 0x20
	public Int32 count; // 0x24
	private static DelegateBridge __Hotfix0_Duplicate; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x1c62ee4 VA: 0x759427aee4
	public EnemyDuelEnemyGenerationData Duplicate() { }
	// RVA: 0x1c62f7c VA: 0x759427af7c
	public Void .ctor() { }
}
```