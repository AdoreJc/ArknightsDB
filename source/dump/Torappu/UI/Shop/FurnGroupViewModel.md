# FurnGroupViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Int32 maxGroup`

- `Int32 currentGroup`

- `Int32 totalDiamondPrice`

- `Int32 totalCoinPrice`

- `Int32 allDiamondPrice`

- `Int32 allCoinPrice`

- `Int32 totalAtmos`

- `Group groupData`


## Methods

- `Void RefreshPlayerData()`

- `Void InitData(Group, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class FurnGroupViewModel
{
	private const Int32 INITGROUPMAX; // 0x0
	public Int32 maxGroup; // 0x10
	public Int32 currentGroup; // 0x14
	public Int32 totalDiamondPrice; // 0x18
	public Int32 totalCoinPrice; // 0x1c
	public Int32 allDiamondPrice; // 0x20
	public Int32 allCoinPrice; // 0x24
	public Int32 totalAtmos; // 0x28
	public Dictionary`2 goodList; // 0x30
	public Group groupData; // 0x38


	// RVA: 0x243e020 VA: 0x7594a56020
	public Void RefreshPlayerData() { }
	// RVA: 0x243e68c VA: 0x7594a5668c
	public Void InitData(Group iGroupData, List`1 goodList) { }
	// RVA: 0x243f23c VA: 0x7594a5723c
	public Void .ctor() { }
}
```