# Act24sideMeldingItemViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String itemId`

- `UIItemViewModel itemViewModel`

- `Int32 sortId`

- `Int32 price`

- `MeldingItemRarityType rarity`

- `Boolean showCount`

- `Boolean canItemClick`


## Methods

- `Void LoadData(String, String, Int32, Boolean, Boolean)`

- `Void LoadData(MeldingItemData, Int32, Boolean, Boolean)`

- `Void LoadData(String, UIItemViewModel, Boolean, Boolean)`

- `Int32 GetItemCount()`

- `Void _LoadBasicInfo(String, Int32)`

- `Void _LoadMeldingInfo(MeldingItemData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingItemViewModel : IHotfixable
{
	public String itemId; // 0x10
	public UIItemViewModel itemViewModel; // 0x18
	public Int32 sortId; // 0x20
	public Int32 price; // 0x24
	public MeldingItemRarityType rarity; // 0x28
	public Boolean showCount; // 0x2c
	public Boolean canItemClick; // 0x2d
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix1_LoadData; // 0x8
	private static DelegateBridge __Hotfix2_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_GetItemCount; // 0x18
	private static DelegateBridge __Hotfix0__LoadBasicInfo; // 0x20
	private static DelegateBridge __Hotfix0__LoadMeldingInfo; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32b3ab0 VA: 0x75958cbab0
	public Void LoadData(String actId, String id, Int32 count, Boolean needShowCount, Boolean canClick) { }
	// RVA: 0x32b3c58 VA: 0x75958cbc58
	public Void LoadData(MeldingItemData meldingData, Int32 count, Boolean needShowCount, Boolean canClick) { }
	// RVA: 0x32b3ec0 VA: 0x75958cbec0
	public Void LoadData(String actId, UIItemViewModel item, Boolean needShowCount, Boolean canClick) { }
	// RVA: 0x32b395c VA: 0x75958cb95c
	public Int32 GetItemCount() { }
	// RVA: 0x32b3d58 VA: 0x75958cbd58
	private Void _LoadBasicInfo(String id, Int32 count) { }
	// RVA: 0x32b3e34 VA: 0x75958cbe34
	private Void _LoadMeldingInfo(MeldingItemData meldingItemData) { }
	// RVA: 0x32b407c VA: 0x75958cc07c
	public Void .ctor() { }
}
```