# ItemRepoOptionalVoucherStateBean

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoOptionalVoucherViewProperty voucherViewProperty`

- `UIItemViewModel voucherItemViewModel`

- `String selectChooseItemId`

- `String requireItemId`

- `Int64 requireItemCount`


## Properties

- `Boolean inChooseState`


## Methods

- `Boolean get_inChooseState()`

- `Void LoadData(UIItemViewModel, OptionalVoucherInfo)`

- `Void AddItem(String)`

- `Void MinusItem(String)`

- `Void UpdateChooseState(Boolean)`

- `UIItemViewModel GetDetailChooseItemViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoOptionalVoucherStateBean : IStateBean, IHotfixable
{
	public ItemRepoOptionalVoucherViewProperty voucherViewProperty; // 0x10
	public UIItemViewModel voucherItemViewModel; // 0x18
	public String selectChooseItemId; // 0x20
	public String requireItemId; // 0x28
	public Int64 requireItemCount; // 0x30
	private static DelegateBridge __Hotfix0_get_inChooseState; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_AddItem; // 0x10
	private static DelegateBridge __Hotfix0_MinusItem; // 0x18
	private static DelegateBridge __Hotfix0_UpdateChooseState; // 0x20
	private static DelegateBridge __Hotfix0_GetOptionalChoiceItemList; // 0x28
	private static DelegateBridge __Hotfix0_GetDetailChooseItemViewModel; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean inChooseState { get; }

	// RVA: 0x2d20964 VA: 0x7595338964
	public Boolean get_inChooseState() { }
	// RVA: 0x2d20a50 VA: 0x7595338a50
	public Void LoadData(UIItemViewModel voucherItemModel, OptionalVoucherInfo optionalVoucherInfo) { }
	// RVA: 0x2d211b8 VA: 0x75953391b8
	public Void AddItem(String itemId) { }
	// RVA: 0x2d21650 VA: 0x7595339650
	public Void MinusItem(String itemId) { }
	// RVA: 0x2d2181c VA: 0x759533981c
	public Void UpdateChooseState(Boolean inChoose) { }
	// RVA: 0x2d21bb8 VA: 0x7595339bb8
	public List`1 GetOptionalChoiceItemList() { }
	// RVA: 0x2d21df4 VA: 0x7595339df4
	public UIItemViewModel GetDetailChooseItemViewModel() { }
	// RVA: 0x2d21e94 VA: 0x7595339e94
	public Void .ctor() { }
}
```