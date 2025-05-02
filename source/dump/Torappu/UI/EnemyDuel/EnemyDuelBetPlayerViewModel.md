# EnemyDuelBetPlayerViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String playerId`

- `String playerNickname`

- `String playerAvatarId`

- `PlayerAvatarType playerAvatarType`

- `EnemyDuelChoiceSide playerSideType`

- `Int32 winStreakCount`

- `Boolean isExBet`

- `Int64 lastUpdateTime`

- `Boolean isNpc`

- `Boolean isSelf`

- `Boolean isSurvive`

- `Int32 curMoney`

- `Int32 curRank`

- `Int32 index`

- `Int32 minWinStreakCount`


## Methods

- `Void LoadData(EnemyDuelPlayerData)`

- `Int32 CompareTo(EnemyDuelBetPlayerViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetPlayerViewModel : IHotfixable, IComparable`1
{
	public String playerId; // 0x10
	public String playerNickname; // 0x18
	public String playerAvatarId; // 0x20
	public PlayerAvatarType playerAvatarType; // 0x28
	public EnemyDuelChoiceSide playerSideType; // 0x2c
	public Int32 winStreakCount; // 0x30
	public Boolean isExBet; // 0x34
	public Int64 lastUpdateTime; // 0x38
	public Boolean isNpc; // 0x40
	public Boolean isSelf; // 0x41
	public Boolean isSurvive; // 0x42
	public Int32 curMoney; // 0x44
	public Int32 curRank; // 0x48
	public Int32 index; // 0x4c
	public Int32 minWinStreakCount; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2982700 VA: 0x7594f9a700
	public Void LoadData(EnemyDuelPlayerData playerData) { }
	// RVA: 0x2982820 VA: 0x7594f9a820
	public Int32 CompareTo(EnemyDuelBetPlayerViewModel other) { }
	// RVA: 0x2982918 VA: 0x7594f9a918
	public Void .ctor() { }
}
```