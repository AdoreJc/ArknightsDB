# EnemyDuelServiceBattleInfo

**Namespace:** `Torappu.UI.EnemyDuel.Service`


## Fields

- `Boolean started`

- `String stageId`

- `Int32 randomSeed`

- `String <sceneID>k__BackingField`

- `EnemyDuelBattleStatus <status>k__BackingField`


## Properties

- `String sceneID`

- `Boolean valid`

- `EnemyDuelBattleStatus status`


## Methods

- `String get_sceneID()`

- `Void set_sceneID(String)`

- `Boolean get_valid()`

- `EnemyDuelBattleStatus get_status()`

- `Void set_status(EnemyDuelBattleStatus)`

- `Void Fill(EnemyDuelServiceSceneJoinData, String)`

- `Void FillBattleStatus(EnemyDuelBattleStatus)`

- `Void Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service
public class EnemyDuelServiceBattleInfo
{
	public Boolean started; // 0x10
	public String stageId; // 0x18
	public Int32 randomSeed; // 0x20
	public List`1 players; // 0x28
	public List`1 npcIds; // 0x30
	private String <sceneID>k__BackingField; // 0x38
	private EnemyDuelBattleStatus <status>k__BackingField; // 0x40

	public String sceneID { get; set; }
	public Boolean valid { get; }
	public EnemyDuelBattleStatus status { get; set; }

	// RVA: 0x29a68d8 VA: 0x7594fbe8d8
	public String get_sceneID() { }
	// RVA: 0x29a68e0 VA: 0x7594fbe8e0
	private Void set_sceneID(String value) { }
	// RVA: 0x29a5f68 VA: 0x7594fbdf68
	public Boolean get_valid() { }
	// RVA: 0x29a68e8 VA: 0x7594fbe8e8
	public EnemyDuelBattleStatus get_status() { }
	// RVA: 0x29a68fc VA: 0x7594fbe8fc
	private Void set_status(EnemyDuelBattleStatus value) { }
	// RVA: 0x29a691c VA: 0x7594fbe91c
	public Void Fill(EnemyDuelServiceSceneJoinData data, String sceneId) { }
	// RVA: 0x29a6a60 VA: 0x7594fbea60
	public Void FillBattleStatus(EnemyDuelBattleStatus battleStatus) { }
	// RVA: 0x29a6a80 VA: 0x7594fbea80
	public Void Reset() { }
	// RVA: 0x29a6b88 VA: 0x7594fbeb88
	public Void .ctor() { }
}
```