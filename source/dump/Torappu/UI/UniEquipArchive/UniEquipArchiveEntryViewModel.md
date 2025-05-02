# UniEquipArchiveEntryViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Boolean <showCollectionsTotalInfo>k__BackingField`

- `UniEquipArchiveCollectionInfoViewModel m_collectionInfoViewModel`

- `Int32 m_enterSeq`


## Properties

- `Boolean showCollectionsTotalInfo`

- `Int32 newEditionUniEquipCount`

- `Int32 enterSeq`


## Methods

- `Boolean get_showCollectionsTotalInfo()`

- `Void set_showCollectionsTotalInfo(Boolean)`

- `Int32 get_newEditionUniEquipCount()`

- `Int32 get_enterSeq()`

- `Void LoadData()`

- `Void RefreshData()`

- `Void RefreshShowCollectionsTotalInfo(Boolean)`

- `UniEquipArchiveEntryCollectionNewEditionItemViewModel TryGetNewEditionItemViewModel(String)`

- `Void _LoadBasicInfoItemViewModels()`

- `Void _RefreshBasicInfoItemViewModels()`

- `UniEquipArchiveEntryCollectionInfoData _GenInfoDataByType(UniEquipArchiveCollectionInfoType)`

- `Void _LoadNewEditionItemList()`

- `Void _RefreshNewEditionItemListState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEntryViewModel : IHotfixable
{
	private Boolean <showCollectionsTotalInfo>k__BackingField; // 0x10
	private List`1 m_infoItemViewModelList; // 0x18
	private List`1 m_newEditionItemViewModelList; // 0x20
	private UniEquipArchiveCollectionInfoViewModel m_collectionInfoViewModel; // 0x28
	private Int32 m_enterSeq; // 0x30
	private static DelegateBridge __Hotfix0_get_infoItemViewModels; // 0x0
	private static DelegateBridge __Hotfix0_get_newEditionItemViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_showCollectionsTotalInfo; // 0x10
	private static DelegateBridge __Hotfix0_set_showCollectionsTotalInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_newEditionUniEquipCount; // 0x20
	private static DelegateBridge __Hotfix0_get_enterSeq; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_RefreshData; // 0x38
	private static DelegateBridge __Hotfix0_RefreshShowCollectionsTotalInfo; // 0x40
	private static DelegateBridge __Hotfix0_TryGetNewEditionItemViewModel; // 0x48
	private static DelegateBridge __Hotfix0__LoadBasicInfoItemViewModels; // 0x50
	private static DelegateBridge __Hotfix0__RefreshBasicInfoItemViewModels; // 0x58
	private static DelegateBridge __Hotfix0__GenInfoDataByType; // 0x60
	private static DelegateBridge __Hotfix0__LoadNewEditionItemList; // 0x68
	private static DelegateBridge __Hotfix0__RefreshNewEditionItemListState; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public List`1 infoItemViewModels { get; }
	public List`1 newEditionItemViewModels { get; }
	public Boolean showCollectionsTotalInfo { get; set; }
	public Int32 newEditionUniEquipCount { get; }
	public Int32 enterSeq { get; }

	// RVA: 0x22efce8 VA: 0x7594907ce8
	public List`1 get_infoItemViewModels() { }
	// RVA: 0x22ef720 VA: 0x7594907720
	public List`1 get_newEditionItemViewModels() { }
	// RVA: 0x22f356c VA: 0x759490b56c
	public Boolean get_showCollectionsTotalInfo() { }
	// RVA: 0x22f35d4 VA: 0x759490b5d4
	private Void set_showCollectionsTotalInfo(Boolean value) { }
	// RVA: 0x22ef6a0 VA: 0x75949076a0
	public Int32 get_newEditionUniEquipCount() { }
	// RVA: 0x22ef34c VA: 0x759490734c
	public Int32 get_enterSeq() { }
	// RVA: 0x22f3654 VA: 0x759490b654
	public Void LoadData() { }
	// RVA: 0x22f396c VA: 0x759490b96c
	public Void RefreshData() { }
	// RVA: 0x22f46dc VA: 0x759490c6dc
	public Void RefreshShowCollectionsTotalInfo(Boolean showTotalInfo) { }
	// RVA: 0x22f4864 VA: 0x759490c864
	public UniEquipArchiveEntryCollectionNewEditionItemViewModel TryGetNewEditionItemViewModel(String uniEquipId) { }
	// RVA: 0x22f36d8 VA: 0x759490b6d8
	private Void _LoadBasicInfoItemViewModels() { }
	// RVA: 0x22f3ffc VA: 0x759490bffc
	private Void _RefreshBasicInfoItemViewModels() { }
	// RVA: 0x22f4aec VA: 0x759490caec
	private UniEquipArchiveEntryCollectionInfoData _GenInfoDataByType(UniEquipArchiveCollectionInfoType collectionInfoType) { }
	// RVA: 0x22f40f8 VA: 0x759490c0f8
	private Void _LoadNewEditionItemList() { }
	// RVA: 0x22f4568 VA: 0x759490c568
	private Void _RefreshNewEditionItemListState() { }
	// RVA: 0x22f50dc VA: 0x759490d0dc
	public Void .ctor() { }
}
```