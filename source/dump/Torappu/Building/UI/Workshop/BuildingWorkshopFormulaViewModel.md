# BuildingWorkshopFormulaViewModel

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `BuildingWorkshopFilterIndex currentFilterIndex`

- `WorkshopSortingOption currentSortingOption`

- `SortingMethod currentSortingMethod`

- `Boolean showRarityFilterPanel`

- `Int32 rarityFilterIndex`

- `IWorkshopSession m_currentSession`


## Methods

- `Void LoadData(IWorkshopSession)`

- `Void ResetCurSelectRarityInfo()`

- `WorkshopRarityInfo _LoadCurrentRarityInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopFormulaViewModel : IHotfixable
{
	public const BuildingWorkshopFilterIndex INDEX_NOT_NEED_FILTER; // 0x0
	public BuildingWorkshopFilterIndex currentFilterIndex; // 0x10
	public WorkshopSortingOption currentSortingOption; // 0x14
	public SortingMethod currentSortingMethod; // 0x18
	public Boolean showRarityFilterPanel; // 0x1c
	public Int32 rarityFilterIndex; // 0x20
	private IWorkshopSession m_currentSession; // 0x28
	private List`1 m_workshopRarityInfos; // 0x30
	private static DelegateBridge __Hotfix0_get_workshopRarityInfos; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_ResetCurSelectRarityInfo; // 0x10
	private static DelegateBridge __Hotfix0_LoadFormulasWithFilter; // 0x18
	private static DelegateBridge __Hotfix0__LoadCurrentRarityInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public List`1 workshopRarityInfos { get; }

	// RVA: 0x3d5ef88 VA: 0x7596376f88
	public List`1 get_workshopRarityInfos() { }
	// RVA: 0x3d5eff0 VA: 0x7596376ff0
	public Void LoadData(IWorkshopSession currentSession) { }
	// RVA: 0x3d5f0bc VA: 0x75963770bc
	public Void ResetCurSelectRarityInfo() { }
	// RVA: 0x3d5f128 VA: 0x7596377128
	public List`1 LoadFormulasWithFilter() { }
	// RVA: 0x3d5f764 VA: 0x7596377764
	private WorkshopRarityInfo _LoadCurrentRarityInfo() { }
	// RVA: 0x3d5f840 VA: 0x7596377840
	public Void .ctor() { }
}
```