# UniEquipArchiveModuleCollectionViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `FilterParam m_equipOwnFilterParam`

- `FilterParam m_equipTypeFilterParam`

- `UniEquipSortType m_sortType`


## Properties

- `UniEquipSortType sortType`

- `UniEquipArchiveModuleTYpeFilterItemInfoData selectedFilterItemData`


## Methods

- `UniEquipSortType get_sortType()`

- `UniEquipArchiveModuleTYpeFilterItemInfoData get_selectedFilterItemData()`

- `Void LoadData()`

- `Void RefreshData()`

- `UniEquipArchiveModuleCollectionItemViewModel TryGetCollectionItemViewModel(String)`

- `Void ApplyEquipOwnFilterParam(FilterParam)`

- `Void ApplyEquipTypeFilterParam(FilterParam)`

- `Void ApplySortType(UniEquipSortType)`

- `Void ApplySortFilter()`

- `Int32 _SortViewModel(UniEquipArchiveModuleCollectionItemViewModel, UniEquipArchiveModuleCollectionItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveModuleCollectionViewModel : IHotfixable
{
	private List`1 m_equipItemViewModels; // 0x10
	private List`1 m_sortedEquipItemViewModels; // 0x18
	private FilterParam m_equipOwnFilterParam; // 0x20
	private FilterParam m_equipTypeFilterParam; // 0x28
	private UniEquipSortType m_sortType; // 0x30
	private static DelegateBridge __Hotfix0_get_sortedEquipItemViewModels; // 0x0
	private static DelegateBridge __Hotfix0_get_sortType; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedFilterItemData; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_RefreshData; // 0x20
	private static DelegateBridge __Hotfix0_TryGetCollectionItemViewModel; // 0x28
	private static DelegateBridge __Hotfix0_ApplyEquipOwnFilterParam; // 0x30
	private static DelegateBridge __Hotfix0_ApplyEquipTypeFilterParam; // 0x38
	private static DelegateBridge __Hotfix0_ApplySortType; // 0x40
	private static DelegateBridge __Hotfix0_ApplySortFilter; // 0x48
	private static DelegateBridge __Hotfix0__SortViewModel; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public List`1 sortedEquipItemViewModels { get; }
	public UniEquipSortType sortType { get; }
	public UniEquipArchiveModuleTYpeFilterItemInfoData selectedFilterItemData { get; }

	// RVA: 0x22f1c7c VA: 0x7594909c7c
	public List`1 get_sortedEquipItemViewModels() { }
	// RVA: 0x22f1ce4 VA: 0x7594909ce4
	public UniEquipSortType get_sortType() { }
	// RVA: 0x22f1d4c VA: 0x7594909d4c
	public UniEquipArchiveModuleTYpeFilterItemInfoData get_selectedFilterItemData() { }
	// RVA: 0x22f6f88 VA: 0x759490ef88
	public Void LoadData() { }
	// RVA: 0x22f7338 VA: 0x759490f338
	public Void RefreshData() { }
	// RVA: 0x22f7544 VA: 0x759490f544
	public UniEquipArchiveModuleCollectionItemViewModel TryGetCollectionItemViewModel(String uniEquipId) { }
	// RVA: 0x22f7668 VA: 0x759490f668
	public Void ApplyEquipOwnFilterParam(FilterParam filterParam) { }
	// RVA: 0x22f795c VA: 0x759490f95c
	public Void ApplyEquipTypeFilterParam(FilterParam filterParam) { }
	// RVA: 0x22f79e8 VA: 0x759490f9e8
	public Void ApplySortType(UniEquipSortType type) { }
	// RVA: 0x22f76f4 VA: 0x759490f6f4
	public Void ApplySortFilter() { }
	// RVA: 0x22f7b38 VA: 0x759490fb38
	private Int32 _SortViewModel(UniEquipArchiveModuleCollectionItemViewModel a, UniEquipArchiveModuleCollectionItemViewModel b) { }
	// RVA: 0x22f7c3c VA: 0x759490fc3c
	public Void .ctor() { }
}
```