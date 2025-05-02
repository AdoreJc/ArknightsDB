# EnemyDuelRoundEndViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelModeType duelMode`

- `EnemyDuelRoundResult roundResult`

- `EnemyDuelChoiceSide playerSide`

- `EnemyDuelChoiceType playerChoiceType`

- `PlayerInfo playerInfo`

- `Boolean isPlayerWin`

- `Boolean isPlayerOut`

- `Boolean useSheild`

- `Int32 prevMoney`

- `Int32 currMoney`

- `Boolean m_inited`


## Methods

- `Void LoadData()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndViewModel
{
	public EnemyDuelModeType duelMode; // 0x10
	public EnemyDuelRoundResult roundResult; // 0x14
	public EnemyDuelChoiceSide playerSide; // 0x18
	public EnemyDuelChoiceType playerChoiceType; // 0x1c
	public PlayerInfo playerInfo; // 0x20
	public Boolean isPlayerWin; // 0x38
	public Boolean isPlayerOut; // 0x39
	public Boolean useSheild; // 0x3a
	public Int32 prevMoney; // 0x3c
	public Int32 currMoney; // 0x40
	private Boolean m_inited; // 0x44


	// RVA: 0x2991850 VA: 0x7594fa9850
	public Void LoadData() { }
	// RVA: 0x2992734 VA: 0x7594faa734
	private Void _InitIfNot() { }
	// RVA: 0x29927ec VA: 0x7594faa7ec
	public Void .ctor() { }
}
```