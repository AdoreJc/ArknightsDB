# SandboxV2CharRepoModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `ProfessionCategory m_filteredProfession`

- `Boolean m_isProfessionFilterShow`

- `SandboxV2CharFilter m_filteredStatus`

- `Boolean m_isStatusFilterShow`


## Properties

- `Boolean isProfessionFilterShow`

- `Boolean isStatusFilterShow`

- `ProfessionCategory filteredProfession`

- `SandboxV2CharFilter filteredStatus`


## Methods

- `Boolean get_isProfessionFilterShow()`

- `Void set_isProfessionFilterShow(Boolean)`

- `Boolean get_isStatusFilterShow()`

- `Void set_isStatusFilterShow(Boolean)`

- `ProfessionCategory get_filteredProfession()`

- `SandboxV2CharFilter get_filteredStatus()`

- `Void Init(String)`

- `Void UpdateCharListPlayerData()`

- `Boolean TryGetCharModelByInstId(Int32, out)`

- `Boolean TryFilterProfession(ProfessionCategory)`

- `Boolean TryFilterStatus(SandboxV2CharFilter)`

- `Void _CalcFilterSortList()`

- `Int32 _SortByCustomRule(SandboxV2CharViewModel, SandboxV2CharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharRepoModel : IHotfixable
{
	private List`1 m_charList; // 0x10
	private List`1 m_filterSortList; // 0x18
	private ProfessionCategory m_filteredProfession; // 0x20
	private Boolean m_isProfessionFilterShow; // 0x24
	private SandboxV2CharFilter m_filteredStatus; // 0x28
	private Boolean m_isStatusFilterShow; // 0x2c
	private static DelegateBridge __Hotfix0_get_isProfessionFilterShow; // 0x0
	private static DelegateBridge __Hotfix0_set_isProfessionFilterShow; // 0x8
	private static DelegateBridge __Hotfix0_get_isStatusFilterShow; // 0x10
	private static DelegateBridge __Hotfix0_set_isStatusFilterShow; // 0x18
	private static DelegateBridge __Hotfix0_get_filteredProfession; // 0x20
	private static DelegateBridge __Hotfix0_get_filteredStatus; // 0x28
	private static DelegateBridge __Hotfix0_get_displayList; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0_UpdateCharListPlayerData; // 0x40
	private static DelegateBridge __Hotfix0_TryGetCharModelByInstId; // 0x48
	private static DelegateBridge __Hotfix0_TryFilterProfession; // 0x50
	private static DelegateBridge __Hotfix0_TryFilterStatus; // 0x58
	private static DelegateBridge __Hotfix0__CalcFilterSortList; // 0x60
	private static DelegateBridge __Hotfix0__SortByCustomRule; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean isProfessionFilterShow { get; set; }
	public Boolean isStatusFilterShow { get; set; }
	public ProfessionCategory filteredProfession { get; }
	public SandboxV2CharFilter filteredStatus { get; }
	public List`1 displayList { get; }

	// RVA: 0x260c484 VA: 0x7594c24484
	public Boolean get_isProfessionFilterShow() { }
	// RVA: 0x260c4ec VA: 0x7594c244ec
	public Void set_isProfessionFilterShow(Boolean value) { }
	// RVA: 0x260c56c VA: 0x7594c2456c
	public Boolean get_isStatusFilterShow() { }
	// RVA: 0x260c5d4 VA: 0x7594c245d4
	public Void set_isStatusFilterShow(Boolean value) { }
	// RVA: 0x260c654 VA: 0x7594c24654
	public ProfessionCategory get_filteredProfession() { }
	// RVA: 0x260c6bc VA: 0x7594c246bc
	public SandboxV2CharFilter get_filteredStatus() { }
	// RVA: 0x260c724 VA: 0x7594c24724
	public List`1 get_displayList() { }
	// RVA: 0x260c78c VA: 0x7594c2478c
	public Void Init(String topicId) { }
	// RVA: 0x260cd18 VA: 0x7594c24d18
	public Void UpdateCharListPlayerData() { }
	// RVA: 0x260ce0c VA: 0x7594c24e0c
	public Boolean TryGetCharModelByInstId(Int32 charInstId, out SandboxV2CharViewModel result) { }
	// RVA: 0x260cf44 VA: 0x7594c24f44
	public Boolean TryFilterProfession(ProfessionCategory profession) { }
	// RVA: 0x260cfe0 VA: 0x7594c24fe0
	public Boolean TryFilterStatus(SandboxV2CharFilter charStatus) { }
	// RVA: 0x260ca88 VA: 0x7594c24a88
	private Void _CalcFilterSortList() { }
	// RVA: 0x260d07c VA: 0x7594c2507c
	private Int32 _SortByCustomRule(SandboxV2CharViewModel x, SandboxV2CharViewModel y) { }
	// RVA: 0x260d110 VA: 0x7594c25110
	public Void .ctor() { }
}
```