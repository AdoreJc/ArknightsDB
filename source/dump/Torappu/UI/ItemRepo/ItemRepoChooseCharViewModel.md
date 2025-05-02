# ItemRepoChooseCharViewModel

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `VoucherDisplayType m_displayType`


## Properties

- `VoucherDisplayType displayType`


## Methods

- `VoucherDisplayType get_displayType()`

- `Void LoadData(List`1, VoucherDisplayType, Boolean)`

- `Void _SortCharList(List`1)`

- `Void _GenerateSortedItems()`

- `Void _LoadItem(String, CharacterData, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharViewModel : IHotfixable
{
	private List`1 m_itemList; // 0x10
	private List`1 m_ownedStandardCharList; // 0x18
	private List`1 m_ownedClassicCharList; // 0x20
	private List`1 m_notOwnedStandardCharList; // 0x28
	private List`1 m_notOwnedClassicCharList; // 0x30
	private VoucherDisplayType m_displayType; // 0x38
	private static DelegateBridge __Hotfix0_get_itemList; // 0x0
	private static DelegateBridge __Hotfix0_get_ownedStandardItemList; // 0x8
	private static DelegateBridge __Hotfix0_get_ownedClassicItemList; // 0x10
	private static DelegateBridge __Hotfix0_get_notOwnedStandardItemList; // 0x18
	private static DelegateBridge __Hotfix0_get_notOwnedClassicItemList; // 0x20
	private static DelegateBridge __Hotfix0_get_displayType; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0__SortCharList; // 0x38
	private static DelegateBridge __Hotfix0__GenerateSortedItems; // 0x40
	private static DelegateBridge __Hotfix0__LoadItem; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public List`1 itemList { get; }
	public List`1 ownedStandardItemList { get; }
	public List`1 ownedClassicItemList { get; }
	public List`1 notOwnedStandardItemList { get; }
	public List`1 notOwnedClassicItemList { get; }
	public VoucherDisplayType displayType { get; }

	// RVA: 0x2d1e030 VA: 0x7595336030
	public List`1 get_itemList() { }
	// RVA: 0x2d2b76c VA: 0x759534376c
	public List`1 get_ownedStandardItemList() { }
	// RVA: 0x2d2b7d4 VA: 0x75953437d4
	public List`1 get_ownedClassicItemList() { }
	// RVA: 0x2d2b83c VA: 0x759534383c
	public List`1 get_notOwnedStandardItemList() { }
	// RVA: 0x2d2b8a4 VA: 0x75953438a4
	public List`1 get_notOwnedClassicItemList() { }
	// RVA: 0x2d2b90c VA: 0x759534390c
	public VoucherDisplayType get_displayType() { }
	// RVA: 0x2d1dcc4 VA: 0x7595335cc4
	public Void LoadData(List`1 itemBundles, VoucherDisplayType displayType, Boolean generateSortedItemList) { }
	// RVA: 0x2d2bbc4 VA: 0x7595343bc4
	private Void _SortCharList(List`1 charItems) { }
	// RVA: 0x2d2bd0c VA: 0x7595343d0c
	private Void _GenerateSortedItems() { }
	// RVA: 0x2d2b974 VA: 0x7595343974
	private Void _LoadItem(String charId, CharacterData charData, Boolean classicItemDistinguishable) { }
	// RVA: 0x2d1dc54 VA: 0x7595335c54
	public Void .ctor() { }
}
```