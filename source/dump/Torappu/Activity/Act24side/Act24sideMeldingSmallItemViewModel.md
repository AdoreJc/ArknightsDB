# Act24sideMeldingSmallItemViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMeldingItemViewModel baseViewModel`

- `ACT24SIDE_MELDING_SMALL_ITEM_BG_TYPE bgType`


## Methods

- `Void LoadData(String, String, ACT24SIDE_MELDING_SMALL_ITEM_BG_TYPE, Int32, Boolean, Boolean)`

- `Void LoadData(MeldingItemData, ACT24SIDE_MELDING_SMALL_ITEM_BG_TYPE, Int32, Boolean, Boolean)`

- `Void SetCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingSmallItemViewModel : IHotfixable
{
	public Act24sideMeldingItemViewModel baseViewModel; // 0x10
	public ACT24SIDE_MELDING_SMALL_ITEM_BG_TYPE bgType; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix1_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetCount; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32b40ec VA: 0x75958cc0ec
	public Void LoadData(String actId, String id, ACT24SIDE_MELDING_SMALL_ITEM_BG_TYPE bgType, Int32 count, Boolean needShowCount, Boolean canClick) { }
	// RVA: 0x32b4200 VA: 0x75958cc200
	public Void LoadData(MeldingItemData meldingData, ACT24SIDE_MELDING_SMALL_ITEM_BG_TYPE bgType, Int32 count, Boolean needShowCount, Boolean canClick) { }
	// RVA: 0x32b4310 VA: 0x75958cc310
	public Void SetCount(Int32 count) { }
	// RVA: 0x32b43a4 VA: 0x75958cc3a4
	public Void .ctor() { }
}
```