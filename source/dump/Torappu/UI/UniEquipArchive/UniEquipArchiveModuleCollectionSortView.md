# UniEquipArchiveModuleCollectionSortView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveSortItem _levelSort`

- `UniEquipArchiveSortItem _updateTimeSort`

- `Text _txtFilterType`

- `Image _imgFilterType`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(UniEquipSortType, String, String)`

- `Void _OnSortTypeClick(UniEquipSortType)`

- `Void OnLevelDownClick()`

- `Void OnLevelUpClick()`

- `Void OnUpdateTimeDownClick()`

- `Void OnUpdateTimeUpClick()`

- `Void OnTypeFilterClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveModuleCollectionSortView : MonoBehaviour, IHotfixable
{
	private UniEquipArchiveSortItem _levelSort; // 0x18
	private UniEquipArchiveSortItem _updateTimeSort; // 0x20
	private Text _txtFilterType; // 0x28
	private Image _imgFilterType; // 0x30
	private Boolean m_isInited; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnSortTypeClick; // 0x10
	private static DelegateBridge __Hotfix0_OnLevelDownClick; // 0x18
	private static DelegateBridge __Hotfix0_OnLevelUpClick; // 0x20
	private static DelegateBridge __Hotfix0_OnUpdateTimeDownClick; // 0x28
	private static DelegateBridge __Hotfix0_OnUpdateTimeUpClick; // 0x30
	private static DelegateBridge __Hotfix0_OnTypeFilterClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x22f1358 VA: 0x7594909358
	private Void _InitIfNot() { }
	// RVA: 0x22f1484 VA: 0x7594909484
	public Void Render(UniEquipSortType sortType, String filterTypeName, String filterTypeBriefName) { }
	// RVA: 0x22f16bc VA: 0x75949096bc
	private Void _OnSortTypeClick(UniEquipSortType sortType) { }
	// RVA: 0x22f17c8 VA: 0x75949097c8
	public Void OnLevelDownClick() { }
	// RVA: 0x22f1834 VA: 0x7594909834
	public Void OnLevelUpClick() { }
	// RVA: 0x22f18a0 VA: 0x75949098a0
	public Void OnUpdateTimeDownClick() { }
	// RVA: 0x22f190c VA: 0x759490990c
	public Void OnUpdateTimeUpClick() { }
	// RVA: 0x22f1978 VA: 0x7594909978
	public Void OnTypeFilterClick() { }
	// RVA: 0x22f1a2c VA: 0x7594909a2c
	public Void .ctor() { }
}
```