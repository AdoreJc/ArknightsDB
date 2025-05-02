# Act42D0RewardViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String selectedAreaId`

- `Int32 ratingMaxCount`

- `String actId`

- `String itemId`

- `String iconId`

- `String itemName`


## Methods

- `Void LoadData(String)`

- `Void UpdatePlayerData(String)`

- `Act42D0RewardAreaViewModel GetSelectedAreaViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardViewModel : IHotfixable
{
	public ListDict`2 areas; // 0x10
	public String selectedAreaId; // 0x18
	public Int32 ratingMaxCount; // 0x20
	public String actId; // 0x28
	public String itemId; // 0x30
	public String iconId; // 0x38
	public String itemName; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x8
	private static DelegateBridge __Hotfix0_GetSelectedAreaViewModel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x321fda4 VA: 0x7595837da4
	public Void LoadData(String activityId) { }
	// RVA: 0x3220a98 VA: 0x7595838a98
	public Void UpdatePlayerData(String actId) { }
	// RVA: 0x3221b40 VA: 0x7595839b40
	public Act42D0RewardAreaViewModel GetSelectedAreaViewModel() { }
	// RVA: 0x322244c VA: 0x759583a44c
	public Void .ctor() { }
}
```