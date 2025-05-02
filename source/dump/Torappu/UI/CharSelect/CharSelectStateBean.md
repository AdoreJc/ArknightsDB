# CharSelectStateBean

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `CharacterCardSortTypeViewProperty cardSortTypeProperty`

- `CharAttrViewProperty attrProperty`

- `CardGroupViewProperty cardGroupProperty`

- `Output outputParam`

- `Int32 maxSelectNum`

- `BoolProperty starMarkSelectedProperty`

- `Input m_inputParam`

- `SpriteHub m_professionIconHub`

- `IPlugin <statePlugin>k__BackingField`


## Properties

- `Boolean isSingleMode`

- `Boolean isSkillSelectablePredefined`

- `IPlugin statePlugin`

- `Boolean starMarkTopState`

- `Boolean filterPanelShow`


## Methods

- `CharSelectInputParam DefaultSelectInputParam(Input, Int32)`

- `Boolean get_isSingleMode()`

- `Boolean get_isSkillSelectablePredefined()`

- `IPlugin get_statePlugin()`

- `Void set_statePlugin(IPlugin)`

- `Void SetData(Input)`

- `Void ReloadData()`

- `String GetSelectedSkillId(Int32)`

- `String GetSelectedBranchId(Int32)`

- `Void SwitchSortType(CharacterSortType)`

- `Void ChangeFilter(CharacterFilterViewModel)`

- `Void ToggleStarMarkTopSelected()`

- `Boolean get_starMarkTopState()`

- `Void set_starMarkTopState(Boolean)`

- `Boolean get_filterPanelShow()`

- `Void set_filterPanelShow(Boolean)`

- `Void ClearSquad()`

- `Void ConfirmOutputData()`

- `Void SelectSkill(String)`

- `Void SelectBranch(String)`

- `Void ClearStatePlugin()`

- `IPlugin _GenerateStatePlugin(Input)`

- `Void _InitSpriteHubIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectStateBean : PageComponent, IStateBean, IHotfixable, IDataBindWrapper
{
	public CharacterCardSortTypeViewProperty cardSortTypeProperty; // 0x20
	public CharAttrViewProperty attrProperty; // 0x28
	public CardGroupViewProperty cardGroupProperty; // 0x30
	public Output outputParam; // 0x38
	public Int32 maxSelectNum; // 0x90
	public BoolProperty starMarkSelectedProperty; // 0x98
	private Input m_inputParam; // 0xa0
	private SpriteHub m_professionIconHub; // 0xe0
	private IPlugin <statePlugin>k__BackingField; // 0xe8
	private static DelegateBridge __Hotfix0_DefaultSelectInputParam; // 0x0
	private static DelegateBridge __Hotfix0_get_isSingleMode; // 0x8
	private static DelegateBridge __Hotfix0_get_isSkillSelectablePredefined; // 0x10
	private static DelegateBridge __Hotfix0_get_statePlugin; // 0x18
	private static DelegateBridge __Hotfix0_set_statePlugin; // 0x20
	private static DelegateBridge __Hotfix0_SetData; // 0x28
	private static DelegateBridge __Hotfix0_ReloadData; // 0x30
	private static DelegateBridge __Hotfix0_GetSelectedSkillId; // 0x38
	private static DelegateBridge __Hotfix0_GetSelectedBranchId; // 0x40
	private static DelegateBridge __Hotfix0_SwitchSortType; // 0x48
	private static DelegateBridge __Hotfix0_ChangeFilter; // 0x50
	private static DelegateBridge __Hotfix0_ToggleStarMarkTopSelected; // 0x58
	private static DelegateBridge __Hotfix0_get_starMarkTopState; // 0x60
	private static DelegateBridge __Hotfix0_set_starMarkTopState; // 0x68
	private static DelegateBridge __Hotfix0_get_filterPanelShow; // 0x70
	private static DelegateBridge __Hotfix0_set_filterPanelShow; // 0x78
	private static DelegateBridge __Hotfix0_ClearSquad; // 0x80
	private static DelegateBridge __Hotfix0_ConfirmOutputData; // 0x88
	private static DelegateBridge __Hotfix0_SelectSkill; // 0x90
	private static DelegateBridge __Hotfix0_SelectBranch; // 0x98
	private static DelegateBridge __Hotfix0_ClearStatePlugin; // 0xa0
	private static DelegateBridge __Hotfix0__GenerateStatePlugin; // 0xa8
	private static DelegateBridge __Hotfix0__InitSpriteHubIfNot; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateSelectedSkillDuringReload; // 0xb8
	private static DelegateBridge __Hotfix0__UpdateSelectedBranchDuringReload; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public Boolean isSingleMode { get; }
	public Boolean isSkillSelectablePredefined { get; }
	public IPlugin statePlugin { get; set; }
	public Boolean starMarkTopState { get; set; }
	public Boolean filterPanelShow { get; set; }

	// RVA: 0x2cf0c38 VA: 0x7595308c38
	public CharSelectInputParam DefaultSelectInputParam(Input input, Int32 squadIndex) { }
	// RVA: 0x2cf0d24 VA: 0x7595308d24
	public Boolean get_isSingleMode() { }
	// RVA: 0x2cf0d8c VA: 0x7595308d8c
	public Boolean get_isSkillSelectablePredefined() { }
	// RVA: 0x2cf0df4 VA: 0x7595308df4
	public IPlugin get_statePlugin() { }
	// RVA: 0x2cf0e5c VA: 0x7595308e5c
	private Void set_statePlugin(IPlugin value) { }
	// RVA: 0x2cf0ee0 VA: 0x7595308ee0
	public Void SetData(Input input) { }
	// RVA: 0x2cf1f1c VA: 0x7595309f1c
	public Void ReloadData() { }
	// RVA: 0x2ced3f0 VA: 0x75953053f0
	public String GetSelectedSkillId(Int32 charInstId) { }
	// RVA: 0x2cf1b6c VA: 0x7595309b6c
	public String GetSelectedBranchId(Int32 charInstId) { }
	// RVA: 0x2cee01c VA: 0x759530601c
	public Void SwitchSortType(CharacterSortType sortType) { }
	// RVA: 0x2cee158 VA: 0x7595306158
	public Void ChangeFilter(CharacterFilterViewModel filter) { }
	// RVA: 0x2cf280c VA: 0x759530a80c
	public Void ToggleStarMarkTopSelected() { }
	// RVA: 0x2cf2884 VA: 0x759530a884
	public Boolean get_starMarkTopState() { }
	// RVA: 0x2cf1ce8 VA: 0x7595309ce8
	public Void set_starMarkTopState(Boolean value) { }
	// RVA: 0x2cf2904 VA: 0x759530a904
	public Boolean get_filterPanelShow() { }
	// RVA: 0x2cf1e34 VA: 0x7595309e34
	public Void set_filterPanelShow(Boolean value) { }
	// RVA: 0x2cf299c VA: 0x759530a99c
	public Void ClearSquad() { }
	// RVA: 0x2cf2aa8 VA: 0x759530aaa8
	public Void ConfirmOutputData() { }
	// RVA: 0x2cf2c94 VA: 0x759530ac94
	public Void SelectSkill(String skillId) { }
	// RVA: 0x2cf2ebc VA: 0x759530aebc
	public Void SelectBranch(String equipId) { }
	// RVA: 0x2cf3088 VA: 0x759530b088
	public Void ClearStatePlugin() { }
	// RVA: 0x2cf1940 VA: 0x7595309940
	private IPlugin _GenerateStatePlugin(Input input) { }
	// RVA: 0x2cf1aac VA: 0x7595309aac
	private Void _InitSpriteHubIfNot() { }
	// RVA: 0x2cf264c VA: 0x759530a64c
	private static String _UpdateSelectedSkillDuringReload(Int32 instId, String prevSkillId) { }
	// RVA: 0x2cf2728 VA: 0x759530a728
	private static String _UpdateSelectedBranchDuringReload(Int32 instId, String prevEquipId) { }
	// RVA: 0x2cf3184 VA: 0x759530b184
	public Void .ctor() { }
}
```