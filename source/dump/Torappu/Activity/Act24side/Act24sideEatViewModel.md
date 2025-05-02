# Act24sideEatViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String actId`

- `Boolean haveMealChanceToday`

- `Boolean currMealUsed`

- `String currMealId`

- `String selectedMealId`

- `Int64 playerGold`

- `Int64 actStartTime`

- `Int64 actEndTime`

- `Int64 nextRefreshTimestamp`

- `Boolean isLastDay`

- `Int32 sequenceNum`


## Methods

- `Void LoadData(String, Boolean)`

- `Act24sideMealViewModel GetSelectedItem()`

- `Boolean SetSelectedItem(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEatViewModel : IHotfixable
{
	public String actId; // 0x10
	public ListDict`2 mealList; // 0x18
	public Boolean haveMealChanceToday; // 0x20
	public Boolean currMealUsed; // 0x21
	public String currMealId; // 0x28
	public String selectedMealId; // 0x30
	public Int64 playerGold; // 0x38
	public Int64 actStartTime; // 0x40
	public Int64 actEndTime; // 0x48
	public Int64 nextRefreshTimestamp; // 0x50
	public Boolean isLastDay; // 0x58
	public Int32 sequenceNum; // 0x5c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetSelectedItem; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedItem; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x329c650 VA: 0x75958b4650
	public Void LoadData(String actId, Boolean isInit) { }
	// RVA: 0x329cbd8 VA: 0x75958b4bd8
	public Act24sideMealViewModel GetSelectedItem() { }
	// RVA: 0x329cc60 VA: 0x75958b4c60
	public Boolean SetSelectedItem(String mealId) { }
	// RVA: 0x329cd94 VA: 0x75958b4d94
	public Void .ctor() { }
}
```