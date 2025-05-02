# EnemyDuelServiceTeamInfo

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `EnemyDuelTeamStatus teamStatus`

- `String <teamID>k__BackingField`


## Properties

- `String teamID`

- `EnemyDuelTeamState state`

- `Boolean closedTeam`

- `Int32 playerCnt`

- `String hostId`


## Methods

- `String get_teamID()`

- `Void set_teamID(String)`

- `EnemyDuelTeamState get_state()`

- `Boolean get_closedTeam()`

- `Int32 get_playerCnt()`

- `String get_hostId()`

- `Void Fill(String, EnemyDuelTeamStatus)`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceTeamInfo
{
	public EnemyDuelTeamStatus teamStatus; // 0x10
	private String <teamID>k__BackingField; // 0x68

	public String teamID { get; set; }
	public EnemyDuelTeamState state { get; }
	public Boolean closedTeam { get; }
	public List`1 playerStatus { get; }
	public Int32 playerCnt { get; }
	public String hostId { get; }

	// RVA: 0x29a67d0 VA: 0x7594fbe7d0
	public String get_teamID() { }
	// RVA: 0x29a67d8 VA: 0x7594fbe7d8
	private Void set_teamID(String value) { }
	// RVA: 0x29a2490 VA: 0x7594fba490
	public EnemyDuelTeamState get_state() { }
	// RVA: 0x29a5f88 VA: 0x7594fbdf88
	public Boolean get_closedTeam() { }
	// RVA: 0x29a67e0 VA: 0x7594fbe7e0
	public List`1 get_playerStatus() { }
	// RVA: 0x29a67e8 VA: 0x7594fbe7e8
	public Int32 get_playerCnt() { }
	// RVA: 0x29a6830 VA: 0x7594fbe830
	public String get_hostId() { }
	// RVA: 0x29a6838 VA: 0x7594fbe838
	public Void Fill(String teamId, EnemyDuelTeamStatus newStatus) { }
	// RVA: 0x29a6878 VA: 0x7594fbe878
	public Void Clear() { }
	// RVA: 0x29a68d0 VA: 0x7594fbe8d0
	public Void .ctor() { }
}
```