# ItemRepoIssueVoucherViewModel

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Boolean <needReset>k__BackingField`

- `UIItemViewModel <voucherItemModel>k__BackingField`

- `ItemRepoIssueVoucherItemViewModel <inputItem>k__BackingField`

- `Boolean <isOutputItemsDirty>k__BackingField`

- `Boolean <isChoosing>k__BackingField`

- `Int32 <chooseLimit>k__BackingField`

- `Int32 <chooseCount>k__BackingField`


## Properties

- `Boolean needReset`

- `UIItemViewModel voucherItemModel`

- `ItemRepoIssueVoucherItemViewModel inputItem`

- `Boolean isOutputItemsDirty`

- `Boolean isChoosing`

- `Int32 chooseLimit`

- `Int32 chooseCount`


## Methods

- `Boolean get_needReset()`

- `Void set_needReset(Boolean)`

- `UIItemViewModel get_voucherItemModel()`

- `Void set_voucherItemModel(UIItemViewModel)`

- `Void set_chooseItems(List`1)`

- `ItemRepoIssueVoucherItemViewModel get_inputItem()`

- `Void set_inputItem(ItemRepoIssueVoucherItemViewModel)`

- `Boolean get_isOutputItemsDirty()`

- `Void set_isOutputItemsDirty(Boolean)`

- `Boolean get_isChoosing()`

- `Void set_isChoosing(Boolean)`

- `Int32 get_chooseLimit()`

- `Void set_chooseLimit(Int32)`

- `Int32 get_chooseCount()`

- `Void set_chooseCount(Int32)`

- `Void LoadData(Option)`

- `Void SelectItem(Int32, Int32)`

- `Void _UpdateSelectedItemInOutput(ItemRepoIssueVoucherItemViewModel)`

- `Void _UpdateOutputItemsIfNecessary()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoIssueVoucherViewModel : IHotfixable
{
	private Dictionary`2 m_itemOfOutput; // 0x10
	private List`1 m_outputItems; // 0x18
	private Boolean <needReset>k__BackingField; // 0x20
	private UIItemViewModel <voucherItemModel>k__BackingField; // 0x28
	private List`1 <chooseItems>k__BackingField; // 0x30
	private ItemRepoIssueVoucherItemViewModel <inputItem>k__BackingField; // 0x38
	private Boolean <isOutputItemsDirty>k__BackingField; // 0x40
	private Boolean <isChoosing>k__BackingField; // 0x41
	private Int32 <chooseLimit>k__BackingField; // 0x44
	private Int32 <chooseCount>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_needReset; // 0x0
	private static DelegateBridge __Hotfix0_set_needReset; // 0x8
	private static DelegateBridge __Hotfix0_get_voucherItemModel; // 0x10
	private static DelegateBridge __Hotfix0_set_voucherItemModel; // 0x18
	private static DelegateBridge __Hotfix0_get_chooseItems; // 0x20
	private static DelegateBridge __Hotfix0_set_chooseItems; // 0x28
	private static DelegateBridge __Hotfix0_get_inputItem; // 0x30
	private static DelegateBridge __Hotfix0_set_inputItem; // 0x38
	private static DelegateBridge __Hotfix0_get_outputItems; // 0x40
	private static DelegateBridge __Hotfix0_get_isOutputItemsDirty; // 0x48
	private static DelegateBridge __Hotfix0_set_isOutputItemsDirty; // 0x50
	private static DelegateBridge __Hotfix0_get_isChoosing; // 0x58
	private static DelegateBridge __Hotfix0_set_isChoosing; // 0x60
	private static DelegateBridge __Hotfix0_get_chooseLimit; // 0x68
	private static DelegateBridge __Hotfix0_set_chooseLimit; // 0x70
	private static DelegateBridge __Hotfix0_get_chooseCount; // 0x78
	private static DelegateBridge __Hotfix0_set_chooseCount; // 0x80
	private static DelegateBridge __Hotfix0_LoadData; // 0x88
	private static DelegateBridge __Hotfix0_SelectItem; // 0x90
	private static DelegateBridge __Hotfix0_GetOptionalChoiceItemList; // 0x98
	private static DelegateBridge __Hotfix0__UpdateSelectedItemInOutput; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateOutputItemsIfNecessary; // 0xa8
	private static DelegateBridge __Hotfix0__ItemComparison; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public Boolean needReset { get; set; }
	public UIItemViewModel voucherItemModel { get; set; }
	public List`1 chooseItems { get; set; }
	public ItemRepoIssueVoucherItemViewModel inputItem { get; set; }
	public List`1 outputItems { get; }
	public Boolean isOutputItemsDirty { get; set; }
	public Boolean isChoosing { get; set; }
	public Int32 chooseLimit { get; set; }
	public Int32 chooseCount { get; set; }

	// RVA: 0x2d2c768 VA: 0x7595344768
	public Boolean get_needReset() { }
	// RVA: 0x2d1f130 VA: 0x7595337130
	public Void set_needReset(Boolean value) { }
	// RVA: 0x2d2c7d0 VA: 0x75953447d0
	public UIItemViewModel get_voucherItemModel() { }
	// RVA: 0x2d2c838 VA: 0x7595344838
	private Void set_voucherItemModel(UIItemViewModel value) { }
	// RVA: 0x2d2c8bc VA: 0x75953448bc
	public List`1 get_chooseItems() { }
	// RVA: 0x2d2c924 VA: 0x7595344924
	private Void set_chooseItems(List`1 value) { }
	// RVA: 0x2d2c9a8 VA: 0x75953449a8
	public ItemRepoIssueVoucherItemViewModel get_inputItem() { }
	// RVA: 0x2d2ca10 VA: 0x7595344a10
	private Void set_inputItem(ItemRepoIssueVoucherItemViewModel value) { }
	// RVA: 0x2d2ca94 VA: 0x7595344a94
	public List`1 get_outputItems() { }
	// RVA: 0x2d2cc88 VA: 0x7595344c88
	public Boolean get_isOutputItemsDirty() { }
	// RVA: 0x2d2ccf0 VA: 0x7595344cf0
	private Void set_isOutputItemsDirty(Boolean value) { }
	// RVA: 0x2d1f048 VA: 0x7595337048
	public Boolean get_isChoosing() { }
	// RVA: 0x2d1f0b0 VA: 0x75953370b0
	public Void set_isChoosing(Boolean value) { }
	// RVA: 0x2d2cd70 VA: 0x7595344d70
	public Int32 get_chooseLimit() { }
	// RVA: 0x2d2cdd8 VA: 0x7595344dd8
	private Void set_chooseLimit(Int32 value) { }
	// RVA: 0x2d1f3dc VA: 0x75953373dc
	public Int32 get_chooseCount() { }
	// RVA: 0x2d2ce54 VA: 0x7595344e54
	private Void set_chooseCount(Int32 value) { }
	// RVA: 0x2d1fcd8 VA: 0x7595337cd8
	public Void LoadData(Option option) { }
	// RVA: 0x2d1f6b4 VA: 0x75953376b4
	public Void SelectItem(Int32 index, Int32 count) { }
	// RVA: 0x2d1f1b0 VA: 0x75953371b0
	public List`1 GetOptionalChoiceItemList() { }
	// RVA: 0x2d2ced0 VA: 0x7595344ed0
	private Void _UpdateSelectedItemInOutput(ItemRepoIssueVoucherItemViewModel selectItem) { }
	// RVA: 0x2d2cb04 VA: 0x7595344b04
	private Void _UpdateOutputItemsIfNecessary() { }
	// RVA: 0x2d2d078 VA: 0x7595345078
	private static Int32 _ItemComparison(ItemRepoIssueVoucherItemViewModel x, ItemRepoIssueVoucherItemViewModel y) { }
	// RVA: 0x2d2d19c VA: 0x759534519c
	public Void .ctor() { }
}
```