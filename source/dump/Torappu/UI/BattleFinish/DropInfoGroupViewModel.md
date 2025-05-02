# DropInfoGroupViewModel

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `StageDiffGroup difficulty`

- `PlayerBattleRank rank`

- `Single goldRate`

- `Single expRate`

- `Boolean isContinuousBattle`


## Methods

- `Void LoadData(CommonFinishBattleResponse)`

- `Void LoadData(PryResult)`

- `Void _BatchServiceItems(List`1, List`1, StageDropType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class DropInfoGroupViewModel
{
	public StageDiffGroup difficulty; // 0x10
	public List`1 dropItems; // 0x18
	public PlayerBattleRank rank; // 0x20
	public Single goldRate; // 0x24
	public Single expRate; // 0x28
	public Boolean isContinuousBattle; // 0x2c


	// RVA: 0x2e8ae64 VA: 0x75954a2e64
	public Void LoadData(CommonFinishBattleResponse response) { }
	// RVA: 0x2e8b0e8 VA: 0x75954a30e8
	public Void LoadData(PryResult dropResult) { }
	// RVA: 0x2e8b97c VA: 0x75954a397c
	private Void _BatchServiceItems(List`1 serviceItems, List`1 resultList, StageDropType dropTypeInput) { }
	// RVA: 0x2e8addc VA: 0x75954a2ddc
	public Void .ctor() { }
}
```