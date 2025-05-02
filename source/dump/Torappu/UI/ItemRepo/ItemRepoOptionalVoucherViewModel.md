# ItemRepoOptionalVoucherViewModel

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `UIItemViewModel <voucherItemViewModel>k__BackingField`

- `String <voucherDecPicName>k__BackingField`

- `Int32 <totalCanPickNum>k__BackingField`

- `Int32 <curPickNum>k__BackingField`

- `Boolean <inChooseState>k__BackingField`

- `OptionalVoucherInfo m_voucherInfo`


## Properties

- `UIItemViewModel voucherItemViewModel`

- `String voucherDecPicName`

- `Int32 totalCanPickNum`

- `Int32 curPickNum`

- `Boolean inChooseState`

- `Boolean isChooseComplete`


## Methods

- `UIItemViewModel get_voucherItemViewModel()`

- `Void set_voucherItemViewModel(UIItemViewModel)`

- `String get_voucherDecPicName()`

- `Void set_voucherDecPicName(String)`

- `Int32 get_totalCanPickNum()`

- `Void set_totalCanPickNum(Int32)`

- `Int32 get_curPickNum()`

- `Void set_curPickNum(Int32)`

- `Boolean get_inChooseState()`

- `Void set_inChooseState(Boolean)`

- `Boolean get_isChooseComplete()`

- `Void InitModel(Option)`

- `Boolean CheckIfCanPick()`

- `Boolean AddItem(ItemRepoOptionalVoucherChooseItemViewModel)`

- `Boolean MinusItem(ItemRepoOptionalVoucherChooseItemViewModel)`

- `Boolean CheckIfItemCanAdd(ItemRepoOptionalVoucherChooseItemViewModel)`

- `Void UpdateChooseState(Boolean)`

- `Void UpdateOutputItemList()`

- `ItemRepoOptionalVoucherChooseItemViewModel TryGetItemFromChooseList(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoOptionalVoucherViewModel : IHotfixable
{
	private UIItemViewModel <voucherItemViewModel>k__BackingField; // 0x10
	private String <voucherDecPicName>k__BackingField; // 0x18
	private Int32 <totalCanPickNum>k__BackingField; // 0x20
	private Int32 <curPickNum>k__BackingField; // 0x24
	private Boolean <inChooseState>k__BackingField; // 0x28
	public List`1 chooseItemViewModels; // 0x30
	public List`1 outputItemViewModels; // 0x38
	private OptionalVoucherInfo m_voucherInfo; // 0x40
	private static DelegateBridge __Hotfix0_get_voucherItemViewModel; // 0x0
	private static DelegateBridge __Hotfix0_set_voucherItemViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_voucherDecPicName; // 0x10
	private static DelegateBridge __Hotfix0_set_voucherDecPicName; // 0x18
	private static DelegateBridge __Hotfix0_get_totalCanPickNum; // 0x20
	private static DelegateBridge __Hotfix0_set_totalCanPickNum; // 0x28
	private static DelegateBridge __Hotfix0_get_curPickNum; // 0x30
	private static DelegateBridge __Hotfix0_set_curPickNum; // 0x38
	private static DelegateBridge __Hotfix0_get_inChooseState; // 0x40
	private static DelegateBridge __Hotfix0_set_inChooseState; // 0x48
	private static DelegateBridge __Hotfix0_get_isChooseComplete; // 0x50
	private static DelegateBridge __Hotfix0_InitModel; // 0x58
	private static DelegateBridge __Hotfix0_CheckIfCanPick; // 0x60
	private static DelegateBridge __Hotfix0_AddItem; // 0x68
	private static DelegateBridge __Hotfix0_MinusItem; // 0x70
	private static DelegateBridge __Hotfix0_CheckIfItemCanAdd; // 0x78
	private static DelegateBridge __Hotfix0_UpdateChooseState; // 0x80
	private static DelegateBridge __Hotfix0_UpdateOutputItemList; // 0x88
	private static DelegateBridge __Hotfix0_TryGetItemFromChooseList; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public UIItemViewModel voucherItemViewModel { get; set; }
	public String voucherDecPicName { get; set; }
	public Int32 totalCanPickNum { get; set; }
	public Int32 curPickNum { get; set; }
	public Boolean inChooseState { get; set; }
	public Boolean isChooseComplete { get; }

	// RVA: 0x2d2d484 VA: 0x7595345484
	public UIItemViewModel get_voucherItemViewModel() { }
	// RVA: 0x2d2d4ec VA: 0x75953454ec
	private Void set_voucherItemViewModel(UIItemViewModel value) { }
	// RVA: 0x2d2d570 VA: 0x7595345570
	public String get_voucherDecPicName() { }
	// RVA: 0x2d2d5d8 VA: 0x75953455d8
	private Void set_voucherDecPicName(String value) { }
	// RVA: 0x2d2d65c VA: 0x759534565c
	public Int32 get_totalCanPickNum() { }
	// RVA: 0x2d2d6c4 VA: 0x75953456c4
	private Void set_totalCanPickNum(Int32 value) { }
	// RVA: 0x2d2d740 VA: 0x7595345740
	public Int32 get_curPickNum() { }
	// RVA: 0x2d2d7a8 VA: 0x75953457a8
	private Void set_curPickNum(Int32 value) { }
	// RVA: 0x2d209e8 VA: 0x75953389e8
	public Boolean get_inChooseState() { }
	// RVA: 0x2d2d824 VA: 0x7595345824
	private Void set_inChooseState(Boolean value) { }
	// RVA: 0x2d2d8a4 VA: 0x75953458a4
	public Boolean get_isChooseComplete() { }
	// RVA: 0x2d20c2c VA: 0x7595338c2c
	public Void InitModel(Option option) { }
	// RVA: 0x2d21368 VA: 0x7595339368
	public Boolean CheckIfCanPick() { }
	// RVA: 0x2d21594 VA: 0x7595339594
	public Boolean AddItem(ItemRepoOptionalVoucherChooseItemViewModel chooseItemModel) { }
	// RVA: 0x2d21744 VA: 0x7595339744
	public Boolean MinusItem(ItemRepoOptionalVoucherChooseItemViewModel chooseItemModel) { }
	// RVA: 0x2d21500 VA: 0x7595339500
	public Boolean CheckIfItemCanAdd(ItemRepoOptionalVoucherChooseItemViewModel chooseItemModel) { }
	// RVA: 0x2d21b38 VA: 0x7595339b38
	public Void UpdateChooseState(Boolean inChoose) { }
	// RVA: 0x2d21904 VA: 0x7595339904
	public Void UpdateOutputItemList() { }
	// RVA: 0x2d213e8 VA: 0x75953393e8
	public ItemRepoOptionalVoucherChooseItemViewModel TryGetItemFromChooseList(String itemId) { }
	// RVA: 0x2d20bb4 VA: 0x7595338bb4
	public Void .ctor() { }
}
```