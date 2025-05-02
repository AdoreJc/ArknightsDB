# ClimbTowerSquadSingleEditModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 m_selectCardId`

- `Int64 gameStartTs`


## Properties

- `Int32 selectCardId`


## Methods

- `Int32 get_selectCardId()`

- `Void set_selectCardId(Int32)`

- `ClimbTowerSquadItemModel FindCharModel(Int32)`

- `Void LoadData(UIPage, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadSingleEditModel
{
	private List`1 m_squadItemList; // 0x10
	private Int32 m_selectCardId; // 0x18
	public Int64 gameStartTs; // 0x20

	public Int32 selectCardId { get; set; }
	public List`1 squadItemList { get; }

	// RVA: 0x2ccc938 VA: 0x75952e4938
	public Int32 get_selectCardId() { }
	// RVA: 0x2ccc940 VA: 0x75952e4940
	public Void set_selectCardId(Int32 value) { }
	// RVA: 0x2ccc948 VA: 0x75952e4948
	public List`1 get_squadItemList() { }
	// RVA: 0x2ccb030 VA: 0x75952e3030
	public ClimbTowerSquadItemModel FindCharModel(Int32 cardId) { }
	// RVA: 0x2ccc634 VA: 0x75952e4634
	public Void LoadData(UIPage page, Int32 cardId) { }
	// RVA: 0x2ccc950 VA: 0x75952e4950
	public Void .ctor() { }
}
```