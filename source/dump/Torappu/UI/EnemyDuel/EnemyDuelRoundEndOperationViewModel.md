# EnemyDuelRoundEndOperationViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `EnemyDuelRoundEndBarModel barModel`

- `Boolean m_isOut`


## Methods

- `Void LoadData()`

- `Void _LoadPlayersData(ActivityEnemyDuelData, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndOperationViewModel
{
	public String actId; // 0x10
	public EnemyDuelRoundEndBarModel barModel; // 0x18
	private Boolean m_isOut; // 0x48
	private List`1 m_rankList; // 0x50

	public List`1 rankList { get; }

	// RVA: 0x298eee4 VA: 0x7594fa6ee4
	public List`1 get_rankList() { }
	// RVA: 0x298e548 VA: 0x7594fa6548
	public Void LoadData() { }
	// RVA: 0x298eeec VA: 0x7594fa6eec
	private Void _LoadPlayersData(ActivityEnemyDuelData actData, Dictionary`2 playerDict) { }
	// RVA: 0x298f448 VA: 0x7594fa7448
	public Void .ctor() { }
}
```