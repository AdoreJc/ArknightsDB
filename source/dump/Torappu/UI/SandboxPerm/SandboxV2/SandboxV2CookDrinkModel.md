# SandboxV2CookDrinkModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 <bottleRequiredCount>k__BackingField`

- `Int32 <drinkBottleLimit>k__BackingField`

- `Int32 <bottleStock>k__BackingField`

- `Int32 <inheritedDrinkCount>k__BackingField`

- `SelectMode <selectMode>k__BackingField`

- `Int32 <selectedDrinkCount>k__BackingField`

- `Boolean <initialRender>k__BackingField`


## Properties

- `Int32 bottleRequiredCount`

- `Int32 drinkBottleLimit`

- `Int32 bottleStock`

- `Int32 inheritedDrinkCount`

- `SelectMode selectMode`

- `Int32 selectedDrinkCount`

- `Int32 bottleCount`

- `Boolean initialRender`


## Methods

- `Int32 get_bottleRequiredCount()`

- `Void set_bottleRequiredCount(Int32)`

- `Int32 get_drinkBottleLimit()`

- `Void set_drinkBottleLimit(Int32)`

- `Int32 get_bottleStock()`

- `Void set_bottleStock(Int32)`

- `Int32 get_inheritedDrinkCount()`

- `Void set_inheritedDrinkCount(Int32)`

- `SelectMode get_selectMode()`

- `Void set_selectMode(SelectMode)`

- `Int32 get_selectedDrinkCount()`

- `Void set_selectedDrinkCount(Int32)`

- `Int32 get_bottleCount()`

- `Boolean get_initialRender()`

- `Void set_initialRender(Boolean)`

- `Void LoadData(SandboxV2Data, PlayerSandboxV2)`

- `Void SwitchSelectMode(SelectMode)`

- `Boolean SelectItem(Int32, Int32)`

- `Void ClearSelected()`

- `Boolean SelectMaterialsToFillOneBottle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookDrinkModel : IHotfixable
{
	private readonly List`1 m_foodmatItems; // 0x10
	private readonly List`1 m_foodItems; // 0x18
	private Int32 <bottleRequiredCount>k__BackingField; // 0x20
	private Int32 <drinkBottleLimit>k__BackingField; // 0x24
	private Int32 <bottleStock>k__BackingField; // 0x28
	private Int32 <inheritedDrinkCount>k__BackingField; // 0x2c
	private SelectMode <selectMode>k__BackingField; // 0x30
	private Int32 <selectedDrinkCount>k__BackingField; // 0x34
	private Boolean <initialRender>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_bottleRequiredCount; // 0x0
	private static DelegateBridge __Hotfix0_set_bottleRequiredCount; // 0x8
	private static DelegateBridge __Hotfix0_get_drinkBottleLimit; // 0x10
	private static DelegateBridge __Hotfix0_set_drinkBottleLimit; // 0x18
	private static DelegateBridge __Hotfix0_get_bottleStock; // 0x20
	private static DelegateBridge __Hotfix0_set_bottleStock; // 0x28
	private static DelegateBridge __Hotfix0_get_inheritedDrinkCount; // 0x30
	private static DelegateBridge __Hotfix0_set_inheritedDrinkCount; // 0x38
	private static DelegateBridge __Hotfix0_get_foodMatItems; // 0x40
	private static DelegateBridge __Hotfix0_get_foodItems; // 0x48
	private static DelegateBridge __Hotfix0_get_selectMode; // 0x50
	private static DelegateBridge __Hotfix0_set_selectMode; // 0x58
	private static DelegateBridge __Hotfix0_get_selectedDrinkCount; // 0x60
	private static DelegateBridge __Hotfix0_set_selectedDrinkCount; // 0x68
	private static DelegateBridge __Hotfix0_get_bottleCount; // 0x70
	private static DelegateBridge __Hotfix0_get_initialRender; // 0x78
	private static DelegateBridge __Hotfix0_set_initialRender; // 0x80
	private static DelegateBridge __Hotfix0_LoadData; // 0x88
	private static DelegateBridge __Hotfix0_SwitchSelectMode; // 0x90
	private static DelegateBridge __Hotfix0_SelectItem; // 0x98
	private static DelegateBridge __Hotfix0_ClearSelected; // 0xa0
	private static DelegateBridge __Hotfix0_SelectMaterialsToFillOneBottle; // 0xa8
	private static DelegateBridge __Hotfix0__FoodmatComparision; // 0xb0
	private static DelegateBridge __Hotfix0__FoodComparision; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public Int32 bottleRequiredCount { get; set; }
	public Int32 drinkBottleLimit { get; set; }
	public Int32 bottleStock { get; set; }
	public Int32 inheritedDrinkCount { get; set; }
	public List`1 foodMatItems { get; }
	public List`1 foodItems { get; }
	public SelectMode selectMode { get; set; }
	public Int32 selectedDrinkCount { get; set; }
	public Int32 bottleCount { get; }
	public Boolean initialRender { get; set; }

	// RVA: 0x24bb4d0 VA: 0x7594ad34d0
	public Int32 get_bottleRequiredCount() { }
	// RVA: 0x24bb538 VA: 0x7594ad3538
	private Void set_bottleRequiredCount(Int32 value) { }
	// RVA: 0x24bb5b4 VA: 0x7594ad35b4
	public Int32 get_drinkBottleLimit() { }
	// RVA: 0x24bb61c VA: 0x7594ad361c
	private Void set_drinkBottleLimit(Int32 value) { }
	// RVA: 0x24bb698 VA: 0x7594ad3698
	public Int32 get_bottleStock() { }
	// RVA: 0x24bb700 VA: 0x7594ad3700
	private Void set_bottleStock(Int32 value) { }
	// RVA: 0x24bb77c VA: 0x7594ad377c
	public Int32 get_inheritedDrinkCount() { }
	// RVA: 0x24bb7e4 VA: 0x7594ad37e4
	private Void set_inheritedDrinkCount(Int32 value) { }
	// RVA: 0x24bb860 VA: 0x7594ad3860
	public List`1 get_foodMatItems() { }
	// RVA: 0x24bb8c8 VA: 0x7594ad38c8
	public List`1 get_foodItems() { }
	// RVA: 0x24bb930 VA: 0x7594ad3930
	public SelectMode get_selectMode() { }
	// RVA: 0x24bb998 VA: 0x7594ad3998
	public Void set_selectMode(SelectMode value) { }
	// RVA: 0x24bba14 VA: 0x7594ad3a14
	public Int32 get_selectedDrinkCount() { }
	// RVA: 0x24bba7c VA: 0x7594ad3a7c
	private Void set_selectedDrinkCount(Int32 value) { }
	// RVA: 0x24bbaf8 VA: 0x7594ad3af8
	public Int32 get_bottleCount() { }
	// RVA: 0x24bbb90 VA: 0x7594ad3b90
	public Boolean get_initialRender() { }
	// RVA: 0x24bbbf8 VA: 0x7594ad3bf8
	public Void set_initialRender(Boolean value) { }
	// RVA: 0x24bbc78 VA: 0x7594ad3c78
	public Void LoadData(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24bc4a0 VA: 0x7594ad44a0
	public Void SwitchSelectMode(SelectMode mode) { }
	// RVA: 0x24bc7d0 VA: 0x7594ad47d0
	public Boolean SelectItem(Int32 index, Int32 count) { }
	// RVA: 0x24bc548 VA: 0x7594ad4548
	public Void ClearSelected() { }
	// RVA: 0x24bc988 VA: 0x7594ad4988
	public Boolean SelectMaterialsToFillOneBottle() { }
	// RVA: 0x24bcc5c VA: 0x7594ad4c5c
	private static Int32 _FoodmatComparision(SandboxV2CookDrinkItemModel x, SandboxV2CookDrinkItemModel y) { }
	// RVA: 0x24bcd58 VA: 0x7594ad4d58
	private static Int32 _FoodComparision(SandboxV2CookDrinkItemModel x, SandboxV2CookDrinkItemModel y) { }
	// RVA: 0x24bce74 VA: 0x7594ad4e74
	public Void .ctor() { }
}
```