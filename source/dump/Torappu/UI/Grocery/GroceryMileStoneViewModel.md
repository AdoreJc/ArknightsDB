# GroceryMileStoneViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Int32 focusIndex`

- `Boolean hasItemCanReceive`

- `String prizeText`

- `Int32 point`


## Methods

- `Void LoadData(String)`

- `Void RefreshData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryMileStoneViewModel : IHotfixable
{
	public List`1 dataSet; // 0x10
	public Dictionary`2 itemStateMap; // 0x18
	public Int32 focusIndex; // 0x20
	public Boolean hasItemCanReceive; // 0x24
	public String prizeText; // 0x28
	public List`1 furniRewards; // 0x30
	public Int32 point; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28a8e54 VA: 0x7594ec0e54
	public Void LoadData(String actId) { }
	// RVA: 0x28a91b0 VA: 0x7594ec11b0
	public Void RefreshData(String actId) { }
	// RVA: 0x28a94fc VA: 0x7594ec14fc
	public Void .ctor() { }
}
```