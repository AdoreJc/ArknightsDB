# UniEquipArchiveCharacterViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveCharacterSortViewModel m_sortModel`

- `FilterParam m_profFilterParam`

- `FilterParam m_equipFilterParam`


## Properties

- `UniEquipArchiveCharacterSortViewModel sortModel`


## Methods

- `UniEquipArchiveCharacterSortViewModel get_sortModel()`

- `Void LoadData(ref, out)`

- `Int32 _SortViewModel(UniEquipArchiveCharacterItemViewModel, UniEquipArchiveCharacterItemViewModel)`

- `Void ApplySortType(CharacterSortType)`

- `Void ApplySortStarMark(Boolean)`

- `Void ApplyProfFilterParam(FilterParam)`

- `Void ApplyEquipFilterParam(FilterParam)`

- `Void ApplySortFilter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveCharacterViewModel : IHotfixable
{
	private List`1 m_charCards; // 0x10
	private List`1 m_sortFilteredCharCards; // 0x18
	private UniEquipArchiveCharacterSortViewModel m_sortModel; // 0x20
	private FilterParam m_profFilterParam; // 0x28
	private FilterParam m_equipFilterParam; // 0x30
	private static DelegateBridge __Hotfix0_get_charCards; // 0x0
	private static DelegateBridge __Hotfix0_get_sortModel; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0__SortViewModel; // 0x18
	private static DelegateBridge __Hotfix0_ApplySortType; // 0x20
	private static DelegateBridge __Hotfix0_ApplySortStarMark; // 0x28
	private static DelegateBridge __Hotfix0_ApplyProfFilterParam; // 0x30
	private static DelegateBridge __Hotfix0_ApplyEquipFilterParam; // 0x38
	private static DelegateBridge __Hotfix0_ApplySortFilter; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public List`1 charCards { get; }
	public UniEquipArchiveCharacterSortViewModel sortModel { get; }

	// RVA: 0x22f2224 VA: 0x759490a224
	public List`1 get_charCards() { }
	// RVA: 0x22f228c VA: 0x759490a28c
	public UniEquipArchiveCharacterSortViewModel get_sortModel() { }
	// RVA: 0x22f22f4 VA: 0x759490a2f4
	public Void LoadData(ref HashSet`1 invalidSubProfIds, out Int32 trackNum) { }
	// RVA: 0x22f2c74 VA: 0x759490ac74
	private Int32 _SortViewModel(UniEquipArchiveCharacterItemViewModel lhs, UniEquipArchiveCharacterItemViewModel rhs) { }
	// RVA: 0x22f2e48 VA: 0x759490ae48
	public Void ApplySortType(CharacterSortType sortType) { }
	// RVA: 0x22f3228 VA: 0x759490b228
	public Void ApplySortStarMark(Boolean hasStarMark) { }
	// RVA: 0x22f32b8 VA: 0x759490b2b8
	public Void ApplyProfFilterParam(FilterParam filterParam) { }
	// RVA: 0x22f3344 VA: 0x759490b344
	public Void ApplyEquipFilterParam(FilterParam filterParam) { }
	// RVA: 0x22f2ed4 VA: 0x759490aed4
	public Void ApplySortFilter() { }
	// RVA: 0x22f33d0 VA: 0x759490b3d0
	public Void .ctor() { }
}
```