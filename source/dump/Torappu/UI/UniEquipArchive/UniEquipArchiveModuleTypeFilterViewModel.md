# UniEquipArchiveModuleTypeFilterViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveModuleTYpeFilterItemInfoData m_selectedTypeInfoData`

- `Boolean m_isFilterViewShowing`


## Properties

- `UniEquipArchiveModuleTYpeFilterItemInfoData selectedTypeInfoData`

- `Boolean isFilterViewShowing`


## Methods

- `UniEquipArchiveModuleTYpeFilterItemInfoData get_selectedTypeInfoData()`

- `Boolean get_isFilterViewShowing()`

- `Void InitData()`

- `Void SetSelectedFilterType(String)`

- `Void SetFilterViewShowing(Boolean)`

- `Void _InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveModuleTypeFilterViewModel : IHotfixable
{
	private UniEquipArchiveModuleTYpeFilterItemInfoData m_selectedTypeInfoData; // 0x10
	private List`1 m_filterItemInfoDataList; // 0x28
	private Boolean m_isFilterViewShowing; // 0x30
	public const String ALL_TYPE; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedTypeInfoData; // 0x0
	private static DelegateBridge __Hotfix0_get_filterItemInfoDataList; // 0x8
	private static DelegateBridge __Hotfix0_get_isFilterViewShowing; // 0x10
	private static DelegateBridge __Hotfix0_InitData; // 0x18
	private static DelegateBridge __Hotfix0_SetSelectedFilterType; // 0x20
	private static DelegateBridge __Hotfix0_SetFilterViewShowing; // 0x28
	private static DelegateBridge __Hotfix0__InitData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public UniEquipArchiveModuleTYpeFilterItemInfoData selectedTypeInfoData { get; }
	public List`1 filterItemInfoDataList { get; }
	public Boolean isFilterViewShowing { get; }

	// RVA: 0x22e3540 VA: 0x75948fb540
	public UniEquipArchiveModuleTYpeFilterItemInfoData get_selectedTypeInfoData() { }
	// RVA: 0x22e40f0 VA: 0x75948fc0f0
	public List`1 get_filterItemInfoDataList() { }
	// RVA: 0x22e3e40 VA: 0x75948fbe40
	public Boolean get_isFilterViewShowing() { }
	// RVA: 0x22e2fe0 VA: 0x75948fafe0
	public Void InitData() { }
	// RVA: 0x22e3390 VA: 0x75948fb390
	public Void SetSelectedFilterType(String type) { }
	// RVA: 0x22e3108 VA: 0x75948fb108
	public Void SetFilterViewShowing(Boolean isShowing) { }
	// RVA: 0x22e57a4 VA: 0x75948fd7a4
	private Void _InitData() { }
	// RVA: 0x22e5ba8 VA: 0x75948fdba8
	public Void .ctor() { }
}
```