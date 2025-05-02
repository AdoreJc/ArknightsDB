# Act24sideMealViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String mealId`

- `String mealName`

- `String mealDesc`

- `String mealEffect`

- `Int32 mealSortId`

- `Int32 mealCost`

- `ItemBundle mealRewardItemInfo`

- `Int32 mealRewardApCount`


## Methods

- `Void LoadData(String, MealData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMealViewModel : IHotfixable
{
	public String mealId; // 0x10
	public String mealName; // 0x18
	public String mealDesc; // 0x20
	public String mealEffect; // 0x28
	public Int32 mealSortId; // 0x30
	public Int32 mealCost; // 0x34
	public ItemBundle mealRewardItemInfo; // 0x38
	public Int32 mealRewardApCount; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x329c4f0 VA: 0x75958b44f0
	public Void LoadData(String mealId, MealData mealData) { }
	// RVA: 0x329c5e0 VA: 0x75958b45e0
	public Void .ctor() { }
}
```