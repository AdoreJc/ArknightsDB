# ItemRepoStateBean

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemCardGroupViewProperty _itemCardGroupProperty`

- `UIItemDescViewProperty _itemDescProperty`

- `ResourceBarViewProperty _resourceProperty`

- `Int32 clickPosition`


## Methods

- `Void ChangeClassify(ClassifyFilter)`

- `Void RefreshData()`

- `Void LoadData()`

- `Void LoadItemDesc(Int32)`

- `Void UnLoadItemDesc()`

- `UIItemViewModel GetItemViewModel()`

- `Void _AddNonInventoryItems(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private ItemCardGroupViewProperty _itemCardGroupProperty; // 0x18
	private UIItemDescViewProperty _itemDescProperty; // 0x20
	private ResourceBarViewProperty _resourceProperty; // 0x28
	public Int32 clickPosition; // 0x30
	private static DelegateBridge __Hotfix0_ChangeClassify; // 0x0
	private static DelegateBridge __Hotfix0_GetCurrentItemList; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_LoadItemDesc; // 0x20
	private static DelegateBridge __Hotfix0_UnLoadItemDesc; // 0x28
	private static DelegateBridge __Hotfix0_GetItemViewModel; // 0x30
	private static DelegateBridge __Hotfix0__AddNonInventoryItems; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d299a8 VA: 0x75953419a8
	public Void ChangeClassify(ClassifyFilter filter) { }
	// RVA: 0x2d2da5c VA: 0x7595345a5c
	public List`1 GetCurrentItemList() { }
	// RVA: 0x2d28b5c VA: 0x7595340b5c
	public Void RefreshData() { }
	// RVA: 0x2d29b84 VA: 0x7595341b84
	public Void LoadData() { }
	// RVA: 0x2d29330 VA: 0x7595341330
	public Void LoadItemDesc(Int32 itemIndex) { }
	// RVA: 0x2d294a8 VA: 0x75953414a8
	public Void UnLoadItemDesc() { }
	// RVA: 0x2d287fc VA: 0x75953407fc
	public UIItemViewModel GetItemViewModel() { }
	// RVA: 0x2d2de30 VA: 0x7595345e30
	private Void _AddNonInventoryItems(List`1 itemList) { }
	// RVA: 0x2d2e050 VA: 0x7595346050
	public Void .ctor() { }
}
```