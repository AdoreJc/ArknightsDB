# EnemyDuelBattleCharItemViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String id`

- `Boolean isNpc`

- `Boolean isSelf`

- `String avatarId`

- `PlayerAvatarType avatarType`

- `Int32 round`

- `EnemyDuelChoiceSide choiceSide`

- `EnemyDuelChoiceType choiceType`


## Methods

- `Void LoadData(EnemyDuelPlayerData)`

- `Int32 CompareTo(EnemyDuelBattleCharItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattleCharItemViewModel : IComparable`1, IHotfixable
{
	public String id; // 0x10
	public Boolean isNpc; // 0x18
	public Boolean isSelf; // 0x19
	public String avatarId; // 0x20
	public PlayerAvatarType avatarType; // 0x28
	public Int32 round; // 0x2c
	public EnemyDuelChoiceSide choiceSide; // 0x30
	public EnemyDuelChoiceType choiceType; // 0x34
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x298b924 VA: 0x7594fa3924
	public Void LoadData(EnemyDuelPlayerData playerData) { }
	// RVA: 0x298ba08 VA: 0x7594fa3a08
	public Int32 CompareTo(EnemyDuelBattleCharItemViewModel other) { }
	// RVA: 0x298bacc VA: 0x7594fa3acc
	public Void .ctor() { }
}
```